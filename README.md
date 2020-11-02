# vue-nuxt

> Nuxt + Leaflet

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

---

## Config

- env：
  可以根据当前的环境变量，使用不同的 baseUrl
- mode：
  配置模式，universal 进行 ssr；spa 不进行 ssr

> 在 plugins 中 context 获取 env

## Vue-Meta

在页面级组件当中添加 head 方法，可以配置页面的 title 等标签

---

[Reference](https://xiaozhuanlan.com/topic/3614597820)
