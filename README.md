<div align="center">
  <h1>北北博客</h1>
  <h2>由Nuxt 3 Blog构建</h2>
</div>

site style form [antfu.me](https://antfu.me/), But base on [nuxt3](https://nuxt.com/)

> [!IMPORTANT]
> A new [version](https://github.com/chansee97/issue-nuxt-blog) of article management based on Github issues, simpler and more convenient.

## 💡Features

- Nuxt3 technology stack, ssr rendering, more friendly to seo
- Adapt to mobile end layout
- Page loading, dark mode transition animation Simple and elegant
- Use markdown as article format
- Tag Category View Function
- Article search function
- Integrate website configuration to reduce the mental burden of modification
- Comment function based on [Giscus](https://giscus.app/zh-CN)

## 🔎Setup
Make sure to install the dependencies:
```
pnpm install
```
open dev serve

```
pnpm dev
```

## 📖Usage

You should modify the following files

- site.config.ts - base site config
- content - your article folder
- `pages\p\[...post].vue` - comment config, to [Giscus](https://giscus.app/zh-CN)

## Icon
- [icon-park-outline](https://icones.js.org/collection/icon-park-outline)
- [simple-icons](https://icones.js.org/collection/simple-icons)
