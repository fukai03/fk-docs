---
title: vue面试
nav:
  title: vue
  path: /vue
group:
  path: /interview
---

### 1. v-if 和 v-for 的优先级

- 在 V2 当中，v-for 的优先级更高，而在 V3 当中，则是 v-if 的优先级更高。在 V3 当中，做了 v-if 的提升优化，去除了没有必要的计算，但同时也会带来一个无法取到 v-for 当中遍历的 item 问题，这就需要开发者们采取其他灵活的方式去解决这种问题。

### 2. vue3 的响应式原理
