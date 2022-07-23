<p align='center'>
  <img src='https://user-images.githubusercontent.com/11247099/111864893-a457fd00-899e-11eb-9f05-f4b88987541d.png' alt='Vitesse - Opinionated Vite Starter Template' width='600'/>
</p>

<h6 align='center'>
<a href="https://vitesse-lite.netlify.app/">在线 Demo</a>
</h6>

<h5 align='center'>
<b>轻量版的 <a href="https://github.com/antfu/vitesse">Vitesse</a></b>
</h5>

<br>

> 复刻自 [antfu/vitesse-lite](https://github.com/antfu/vitesse-lite)

<p align='center'>
<b>简体中文</b> | <a href="https://github.com/antfu/vitesse-lite/blob/main/README.md">English</a> 
</p>

<br>

## 特性

- ⚡️ [Vue 3](https://github.com/vuejs/core), [Vite 3](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [ESBuild](https://github.com/evanw/esbuild) - 就是快！

- 🗂 [文件即路由](./src/pages)

- 📦 [组件自动加载](./src/components)

- 🎨 [UnoCSS](https://github.com/unocss/unocss) - 原子化 CSS 引擎，高效且灵活

- 😃 [各种图标集为你所用](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- 🔥 使用 [ `<script setup>` 语法](https://github.com/vuejs/rfcs/pull/227)

- ✅ 使用 [Vitest](http://vitest.dev/) 来单元测试或组件测试

- 🦾 TypeScript

- ☁️ 零配置部署 Netlify

<br>

完整特性,请查看 [Vitesse](https://github.com/antfu/vitesse)

## 从 [Vitesse](https://github.com/antfu/vitesse) 中删除了以下特性

- ~~i18n~~
- ~~Layouts~~
- ~~SSG~~
- ~~PWA~~
- ~~Markdown~~

## 预配置

### UI 框架

- [UnoCSS](https://github.com/antfu/unocss) - 原子化 CSS 引擎，高效且灵活

### Icons

- [Iconify](https://iconify.design) - 可用任意图标集，浏览：[🔍Icônes](https://icones.netlify.app/)
- [UnoCSS 中的纯 CSS 图标方案](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### 插件

- [Vue Router](https://github.com/vuejs/vue-router)
  - [`vite-plugin-pages`](https://github.com/hannoeru/vite-plugin-pages) - 以文件系统为基础的路由
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - 自动导入，可直接使用 Composition API 等
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - 自动加载组件
- [VueUse](https://github.com/antfu/vueuse) - 实用的 Composition API 工具合集

## 现在可以试试!

### GitHub 模板

[使用这个模板创建仓库](https://github.com/antfu/vitesse-lite/generate).

### 克隆到本地

欲清除 git 历史记录，请执行此操作

```bash
npx degit antfu/vitesse-lite my-vitesse-app
cd my-vitesse-app
pnpm i # 如果你没装过 pnpm, 可以先运行: npm install -g pnpm
```
