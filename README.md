# Svelte Heroicons

<p align="center">
  <img src="https://raw.githubusercontent.com/tailwindlabs/heroicons/master/.github/logo.svg" alt="Heroicons">
</p>

<p align="center">
  An set of 450+ free MIT-licensed high-quality SVG icons for you to use in your web projects. <br>Available as an unofficial <b>Svelte</b> library. Browse the complete set at <a href="https://heroicons.com"><strong>Heroicons.com &rarr;</strong></a>
</p>

## Why this package?

Copying SVG code into your project can become tedious and messy if you don't need to edit the SVG markup. This library simply makes it easier to import each icon and have it scale based on it's inherited font-size.

_Find the original repository for Heroicons on Github: [tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons)_

## Basic Usage

```html
<script>
	import { AcademicCap } from "$lib/outline";
</script>

<style>
	.icon {
		font-size: 40px;
		color: red;
	}
</style>

<div class="icon"><AcademicCap /></div>
```

-   The icon will scale in size so that the height of the icon is the current font-size.
-   The icon will inherit the current text color.

## License

This library is MIT licensed.
