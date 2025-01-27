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

## License

MIT.
