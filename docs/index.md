---
layout: home

title: DN Blog
titleTemplate: 学习和记录

hero:
  name: DN Blog
  text: 基于 VitePress 构建的文档站点
  tagline: 通过 GitHub Pages 部署的文档站点
  actions:
    - theme: brand
      text: 命令大全
      link: /articles/常用命令/JavaScript/npm
    - theme: alt
      text: 我也来一个？
      link: /install/vitepress-install
    - theme: alt
      text: 官方教程
      link: https://vitepress.dev/zh/
  image:
      src: /vitepress-logo-large.webp
      alt: VitePress

features:
  - icon: 🧛
    title: 记录常用命令
    details: 好记性不如烂笔头，记录常用命令，方便查阅。有大佬看到问题，不嫌弃的话可以直接 Issue 💌 给我，我会及时回复。
  - icon: 📝
    title: 记录学习笔记
    details: 之前的 Markdown 都存在本地，换电脑后找也不方便。放 Github 上刚刚好，还不用整域名备案（现在备案还真麻烦），嘿嘿🤣
  - icon: 🌻
    title: 记录生活琐事
    details: 后续打算自己写一些文章，记录一下日常。很多事情不去记录，过去了就过去了...🕛
  - icon: 🤡
    title: 我的 CSS 真的很烂
    details: 前端会写，但做不出那种美美的画风😭，拿这个记录日常学习刚刚好。
---
<style>
  <script src="https://unpkg.com/vue-pdf-embed"></script>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>
