<div align="center">

![ezgif-2-e81342282f](https://github.com/cn-2k/vue-tailwind-lightbox/assets/59366705/f6b3f948-2d8a-4886-bb8d-b8b6c786bab0)


</div>

<h1 align=center>Nuxt Tailwind Lightbox ✨</h1>
<p align=center>A Gallery/Lightbox component styled with TailwindCSS for Nuxt 3 (Typescript included!).</p>
<p align=center>Based on <a href="https://www.frontendmentor.io/challenges/ecommerce-product-page-UPsZ9MJp6" target="_blank">Frontend Mentor E-commerce product page</a> Lightbox.</p>

## Quick Setup

1. Add `nuxt-tailwind-lightbox` dependency to your project

```bash
# Using pnpm
pnpm add -D nuxt-tailwind-lightbox

# Using yarn
yarn add --dev nuxt-tailwind-lightbox

# Using npm
npm install --save-dev nuxt-tailwind-lightbox
```

2. Add `nuxt-tailwind-lightbox` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: [
    'nuxt-tailwind-lightbox'
  ]
})
```

## 📃 Props

| Name       | Type               | Default | Description                        |
| ---------- | ------------------ | ------- | ---------------------------------- |
| `image-list` | `Array`          |   ---   | Array of images to fill the gallery |

That's it! You can now use the ```<NuxtTailwindLightbox :image-list="your_image_list_array" />``` component in your Nuxt app ✨

## Development

```bash
# Install dependencies
npm install

# Generate type stubs
npm run dev:prepare

# Develop with the playground
npm run dev

# Build the playground
npm run dev:build

# Run ESLint
npm run lint

# Run Vitest
npm run test
npm run test:watch

# Release new version
npm run release
```

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/my-module/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/my-module

[npm-downloads-src]: https://img.shields.io/npm/dm/my-module.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/my-module

[license-src]: https://img.shields.io/npm/l/my-module.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/my-module

[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
