---
title: 'undefined'
theme: geist
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-start'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: true
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# undefined

undefined

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Что такое undefined?

undefined

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {}
</style>

---


<div grid="~ cols-4 gap-2" m="m-t-4">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-alert-02.png?raw=true">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/object-object-vk.jpg?raw=true">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-alert.gif?raw=true">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-red.png?raw=true">

</div>


---

<div grid="~ cols-4 gap-2" m="m-t-4">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-meme-01.jpg?raw=true">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-meme-02.jpg?raw=true">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-meme-03.jpg?raw=true">

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/undefined-merch.webp?raw=true">

</div>

---

# Null vs undefined

Null и undefined - это не одно и то же.

### Разница между этими двумя типами данных

|Null | undefined | 
|--------------| ----------------| 
| Lack of( Отсутствие) | Declared        | 
| Empty/void   | Uninitialized   |
| Non-existent | Engine Assigned | 
| User assigned|  
|              |
<!-- https://sli.dev/guide/animations.html#click-animations -->

---

# Зачем?

---

# Зачем?

- зачем? нужен ли NGRX Effects?
- зачем нужна простая архитектура?
- зачем нужна дизайн система?

---

# Зачем? нужен ли NGRX Effects?

<div grid="~ cols-2">
  <img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/state-management-lifecycle.png?raw=true">
</div>

---

# Зачем нужна простая архитектура?

- [v] структура

- [x] масштабируемость и переиспользуемость

- [x] best practices

- [x] принципы и паттерны

---

# Зачем нужна дизайн система?

<img border="rounded" src="https://github.com/ippatev/undefined-page/blob/main/screenshots/design-system.png?raw=true">

---
