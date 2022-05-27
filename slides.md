---
theme: seriph # https://sli.dev/themes/gallery.html
title: thanks-kunp-yan-slidev
download: false
lineNumbers: true
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
---

# Thanks kunp-yan

10000leaves

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/10000leaves/thanks-kunp-yan-slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# thanks-kunp-yan-slidev とは?
https://thanks-kunp-yan-slidev.netlify.app/  

watanabeさんの時に味を占めて、また作成しました。

Slidev というスライドツールを使用して作成しています。

<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-square.png"
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-circle.png"
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>
  <div
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Slidev
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }"
>
  <p>今回も、作成するにあたり様々な方からメッセージをいただきました。</p>
  <p>ご協力していただき、ありがとうございました。</p>
</div>
---
layout: intro
class: 'text-center'
---

# 使用した技術

<Decoration />

---

# 技術一覧

<div class="grid grid-cols-[30%,70%]"><div>

- Frontend
  - Slidev
  - Vue
  - Markdown
  - CSS
- Infrastructure
  - Netlify
- Code Management
  - GitHub
- Image editing
  - draw.io
  - undraw

</div><div>
  <img src="/drawio/systemConfiguration.drawio.png"/>
</div></div>

---

# Slidev とは?

公式サイト： https://sli.dev/

Slidev は開発者向けに設計されたスライドツールです。以下の機能で構成されています。

- 📝 **Text-based** - マークダウンを使用し、スタイルを設定出来ます
- 🎨 **Themable** - npm package を使用しテーマをシェア出来ます
- 🧑‍💻 **Developer Friendly** - コードハイライト, オートコンプリートを使用したライブコーディング
- 🤹 **Interactive** - Vue コンポーネントの埋め込みで表現を強化します
- 🎥 **Recording** - ビルトインの録画とカメラビューがあります
- 📤 **Portable** - PDF へのエクスポート, PNG, ホスティング可能な SPA
- 🛠 **Hackable** - Web ページで可能なことは何でも

<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)

---
layout: intro
class: 'text-center'
---

# メッセージ

<Decoration />

---

# ka-horikawa  

<div class="grid grid-cols-[50%,50%]"><div>

メッセージ考え中

</div><div class="text-5xl m-0 animate-spin">
  🔄
</div></div>

---
