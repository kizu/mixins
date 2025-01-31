# Experimental Native CSS Mixins

> **Warning:**
> **All of this is highly experimental!** You probably don’t want to include this mixin’s code anywhere near your production code. But in a dev environment? Or on CodePen? That’s the best place for experimental tech like that, where you’re the main user.

I am planning to add more mixins to this package. For now, there is only the one: `--preview`.

## The `--preview` Mixin

I wrote [an article](https://kizu.dev/preview-mixin/) about the `--preview` mixin: read it to see the examples and read some of the explanations over how it works.

### Install & Use

```sh
npm install @kizu/mixins
```

Or

```sh
yarn add @kizu/mixins
```

Or use some CDN:

```HTML
<link
	rel="stylesheet"
	type="text/css"
	href="https://unpkg.com/@kizu/mixins@0.1.3/preview.css"
/>
```

Or

```CSS
@import
	url("https://unpkg.com/@kizu/mixins@0.1.3/preview.css");
```

### API

The API docs for the mixin are currently available as a [corresponding section of the article](https://kizu.dev/preview-mixin/preview-mixin/#mixins-api) I wrote about it.

## Changelog

### 0.2.0 — 2025-01-31

#### `--preview` Mixin Extension API

The extension API consists of three custom properties:

- `--preview-cycle-extension` — allows setting up the cycle from the `--preview` custom property in a way similar to how it is already done in the mixin.

- `--preview-reset-extension` — allows adding something to the `counter-reset` value of the mixin.

- `--preview-content-extension` — allows adding something at the end of the mixin's `content` output (but before the `--preview-suffix`).

This API allows extending the `--preview` mixin with new capabilities without touching its existing code, making it easy to prototype new features, or upgrade your usage of it.

## License

MIT.
