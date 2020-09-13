---
title: Example
description: 'Empower your NuxtJS application with @nuxt/content module.'
position: 2
category: Getting started
version: 0.1
fullscreen: false

items:
  - Item1
  - Item2
  - Item3
---

<alert>

Check out a warning alert with a `codeblock`!

</alert>

<alert type="info">

Check out an info alert with a [link](/themes/docs).

</alert>

<list :items="items"></list>

<code-group>
  <code-block label="Yarn" active>

  ```bash
  yarn add @nuxt/content-theme-docs
  \```

  </code-block>
  <code-block label="NPM">

  ```bash
  npm install @nuxt/content-theme-docs
  \```

  </code-block>
</code-group>
