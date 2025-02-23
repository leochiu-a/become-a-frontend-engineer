---
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Become a Frontend Engineer
class: text-center
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
theme: seriph
---

# Become a Frontend Engineer

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Let's start <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Outline

- 什麼是前端？
- 我為什麼會成為前端工程師？
- 一瞥前端工程師的工作方式
- 如何學習？

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-left

# the image source
image: /assets/leo.jpeg

transition: slide-up
---

# 大家好，我是 Leo

<br>

- KKday 前端工程師
- Hahow 前端工程師
- 第 13 屆 IT 鐵人佳作 - 從零開始學習 Next.js
- 2021 JSDC - 為什麼許多公司都願意導入 Next.js

<br>

歡迎追蹤 👇

<img src="/assets/threads.png" />

---
transition: slide-up
level: 2
layout: center
---

# 什麼是前端？


---
layout: iframe
url: https://www.awwwards.com/sites/ottografie-2025#creator
title: awwwards
---

---
layout: center
---

# 把設計稿變成網頁
# 然後祈禱它在所有瀏覽器上都能正常顯示

---
layout: center
---

# HTML：網頁的骨架
# CSS：網頁的衣服
# JavaScript：網頁的靈魂，偶爾也會讓它中邪

---
layout: center
---

# 寫 CSS 的時候，你以為自己是藝術家
# 結果發現自己是在解數學題

---
layout: center
---

# 響應式設計：讓網頁在手機、平板、電腦上都能完美顯示，除了 Safari

---
layout: image
image: /assets/FE-ice.png
backgroundSize: contain
title: 前端水很深
---

---
layout: center
---

# 我是如何成為前端的呢？

---
layout: center
title: 六角精神時光屋
---

<img src="/assets/精神時光屋.png" />

---
layout: center
---


# 看到喜歡的公司有職缺

---
layout: center
---

<div class="center">

# 到 Udemy 買了兩堂 300 元的課程

</div>

<div class="flex">

<img src="/assets/udemy1.png" width="50%" />

<img src="/assets/udemy2.png" width="50%" />

</div>

<style>
.center {
  text-align: center;
}

.flex {
  display: flex;
  gap: 20px;
}
</style>

---
layout: center
---

# Offer get

---
layout: center
---

# 前端如何入門


---
layout: center
---

# HTML：網頁的骨架
# CSS：網頁的衣服
# JavaScript：網頁的靈魂，偶爾也會讓它中邪

---

# HTML

- HTML 是一種用來建構網頁的<span v-mark.underline.orange>標籤語言</span>，而非程式語言
- header、section、img、footer 等元素
- 元素會用 `< >` 撰寫

標題

```html
<h1>我是標題</h1>
```

header

```html
<header>我是 header</header>
```

img

```html
<img src="/assets/ice.png" alt="ice"/>
```

---

# CSS

- 跟 HTML 一樣，CSS 既非標準程式語言，也不是標記語言, 而是一種<span v-mark.underline.orange>風格頁面語言（style sheet language）</span>
- 讓 HTML 文件中的元素（element）上套用不同的樣式（style）

例如你想要將段落元素（paragraph elements）裡的文字全部轉換成紅色：

```css
p {
  color: red;
}
```

想要改變圖片的大小：

```css
img {
  width:  200px;
}
```

--- 

# JavaScript

- JavaScript 是一個可以幫你在網站裡加入互動功能的<span v-mark.underline.orange>程式語言</span>
- 舉例來說：
  - 一個頁面可能會在按鈕按下載入資料
  - 輸入帳號密碼後點擊登入

HTML

```html
<button onclick="login()">登入</button>
```

JavaScript

```
function login() {
  // 獲取使用者的帳號密碼，執行登入
}
```

---
layout: center
---

# Live Coding

---

# 學習前端的資源

- 線上課程：Hahow、Udemy
- roadmap.sh
- 文章：Threads、Medium、掘金、Daily Dev
- 作品集：GitHub、CodePen

---
layout: center
---

<div style="text-align: center; margin-bottom: 32px">

# Q&A

</div>

<img src="/assets/qrcode_linktr.ee.png" width="200" />


---
layout: center
---

# Thanks you