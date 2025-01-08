---
theme: default
background: assets/cover.jpeg
title: Intro
info: ""
class: text-left
drawings:
  persist: false
transition: fade-out
mdc: true
colorSchema: 'dark'
---

# **Ollama Bootcamp** <br/><br/>

<v-click>

  <div class="backdrop-blur-md bg-black/30 py-2 px-8 rounded-md bg-gradient-to-r from-pink-500 via-red-500 to-yellow-500 p-1">

  ## **Module 01**
  </div>

</v-click>


<div class="backdrop-blur-md bg-black/10 py-2 rounded-md">

  <v-click>

  <div class="ma-4 px-8">

  ### 1. Working with models locally
  </div>
  </v-click>

  <v-click>

  <div class="ma-4 px-8">

  ### 2. Prompting techniques
  </div>
  </v-click>

  <v-click>

  <div class="ma-4 px-8">

  ### 3. Chain-of-Thought (CoT) Prompting: Guiding Reasoning
  </div>
  </v-click>

</div>

<div @click="$slidev.nav.next" class="mt-12 py-1 text-right" hover:bg="white op-10">
    <carbon:arrow-right />
</div>

---
transition: fade-out
title: Working with models locally
colorSchema: 'dark'
layout: two-cols-header
layoutClass: gap-16
---

# Working with models locally

<div class="pt-12 text-center">
<v-click>

##  2 <span v-mark.red="1">methods to work with the LLM</span>
</v-click>
</div>

::left::

<div class="pt-12 text-center">
<v-click>

##  REPL using terminal

<div class="flex justify-center items-center mt-8">
  <img class="rounded-md w-48" src="./assets/terminal.png" alt="">
</div>

</v-click>
</div>

::right::

<div class="pt-12 text-center">
<v-click>

##  API calls using REST client

<div class="flex justify-center items-center mt-8">
  <img class="rounded-md w-48" src="./assets/postman.png" alt="">
</div>

</v-click>
</div>

<br/>

<!-- API documentation: https://github.com/ollama/ollama/blob/main/docs/api.md -->

---
transition: fade-out
title: Prompting techniques - basics
colorSchema: 'dark'
layout: two-cols-header
---

# Prompting techniques - basics

::left::

<div class="pt-12 text-left">
<v-click>

##  👎 Bad Prompt Example

<div class="flex ma-8 pa-2">

> Write a story for me

</div>


<v-click>

- Story about what? (context)<br>
</v-click>

<v-click>

- How long should the story be? <br>
</v-click>

<v-click>

- Which genre? <br>
</v-click>

</v-click>
</div>

::right::

<div class="pt-12 text-left">
<v-click>

##  👍 Good Prompt Example

<div class="flex ma-8 pa-2">

> <span v-mark.red="6">Acting as an expert storyteller</span>, write a <span v-mark.green="7">500-word</span> <span v-mark.blue="8">fantasy story set in a medieval kingdom</span> where a young blacksmith's apprentice discovers a magical sword that can only be wielded by someone with a pure heart. Include elements of adventure, a quest to save the kingdom from an evil sorcerer, and a <span v-mark.yellow="9">moral lesson about courage and integrity</span>. Use a third-person narrative style and ensure the story has a clear beginning, middle, and end.

</div>


</v-click>
</div>

<br/>

---
transition: fade-out
title: Prompting techniques - best practices
colorSchema: 'dark'
layout: two-cols-header
---

# Prompting techniques - best practices

::left::

<div class="pt-12 text-left">
<v-click>

##  👍 Good Prompt Example

<div class="flex ma-8 pa-2">

> <span v-mark.red="1">Acting as an expert storyteller</span>, write a <span v-mark.green="1">500-word</span> <span v-mark.blue="1">fantasy story set in a medieval kingdom</span> where a young blacksmith's apprentice discovers a magical sword that can only be wielded by someone with a pure heart. Include elements of adventure, a quest to save the kingdom from an evil sorcerer, and a <span v-mark.yellow="1">moral lesson about courage and integrity</span>. Use a third-person narrative style and ensure the story has a clear beginning, middle, and end.

</div>
</v-click>
</div>
<br/>

::right::

<div class="mt-8 px-2">
  <v-click>

  ### 1. **Providing Context** <br><br>
  </v-click>
  <v-click>

  ### 2. **Specifying Role** <br><br>
  </v-click>
  <v-click>

  ### 3. **Defining Task** <br><br>
  </v-click>
  <v-click>

  ### 4. **Detailing Desired Output** <br><br>
  </v-click>
  <v-click>

  ### 5. **Encouraging Creativity** <br><br>
  </v-click>
</div>

---
transition: fade-out
title: Prompting techniques - zero-shot
colorSchema: 'dark'
---

# Prompting techniques - Zero-Shot prompting

<div class="pt-12 text-center">

<v-click>

## title

</v-click>
</div>

<div class="ma-4 px-8">
<br><br>
<v-click>

## sub-title 🎉 <br><br>
</v-click>
<div class="mx-4 px-8">
  <v-click>

  ### 1. point 1 <br><br>
  </v-click>
  <v-click>

  ### 2. point 2 <br><br>
  </v-click>
  <v-click>

  ### 3. point 3
  </v-click>
</div>

</div>
---
transition: fade-out
title: Prompting techniques - one-shot
colorSchema: 'dark'
---

# Prompting techniques - One-shot prompting

<div class="pt-12 text-center">

<v-click>

## title

</v-click>
</div>

<div class="ma-4 px-8">
<br><br>
<v-click>

## sub-title 🎉 <br><br>
</v-click>
<div class="mx-4 px-8">
  <v-click>

  ### 1. point 1 <br><br>
  </v-click>
  <v-click>

  ### 2. point 2 <br><br>
  </v-click>
  <v-click>

  ### 3. point 3
  </v-click>
</div>

</div>

---
transition: fade-out
title: CoT Prompting - guided reasoning
colorSchema: 'dark'
---

# CoT Prompting - guided reasoning

<div class="pt-12 text-center">

<v-click>

## title

</v-click>
</div>

<div class="ma-4 px-8">
<br><br>
<v-click>

## sub-title 🎉 <br><br>
</v-click>
<div class="mx-4 px-8">
  <v-click>

  ### 1. point 1 <br><br>
  </v-click>
  <v-click>

  ### 2. point 2 <br><br>
  </v-click>
  <v-click>

  ### 3. point 3
  </v-click>
</div>

</div>

---
transition: fade-out
colorSchema: 'dark'
title: Thank you
layout: center
---

## Thank you 🙏 🤗