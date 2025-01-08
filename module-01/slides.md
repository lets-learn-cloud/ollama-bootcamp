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

<div class="backdrop-blur-md bg-white/30 ma-4 py-2 px-8">

## **Module 01**
</div>

</v-click>

<v-click>

<div class="backdrop-blur-md bg-black/10 py-2">
<div class="ma-4 px-8">
<v-click>

### 1. Working with models locally
</v-click>
</div>


<div class="ma-4 px-8">
<v-click>

### 2. Prompting techniques
</v-click>
</div>

<div class="ma-4 px-8">
<v-click>

### 3. Chain-of-Thought (CoT) Prompting: Guiding Reasoning
</v-click>
</div>
</div>
</v-click>

<div @click="$slidev.nav.next" class="mt-12 py-1 text-right" hover:bg="white op-10">
    <carbon:arrow-right />
</div>

---
transition: fade-out
title: Requirements
colorSchema: 'dark'
---

# Requirements

<div class="pt-12 text-center">
<v-click>

##  Follow along and <span v-mark.red="1">try these exercises yourself</span>
</v-click>

</div>

<br/>
<v-click>

## You need <br><br>
</v-click>
<div class="mx-4 px-8">
  <v-click>

  ### 1. A Windows / Mac / Linux laptop / desktop <br><br>
  </v-click>
  <v-click>

  ### 2. Access to internet <br><br>
  </v-click>
  <v-click>

  ### 3. Permissions to install downloaded software
  </v-click>
</div>
---
transition: fade-out
title: What is Ollama?
colorSchema: 'dark'
---

# What is Ollama?

<div class="pt-12 text-center">

<v-click>

## Open-source framework for running and managing large language models (LLMs) on <span v-mark.undeline.red="1">local computing resources</span>

</v-click>
</div>

<div class="ma-4 px-8">
<br><br>
<v-click>

## Advantages 🎉 <br><br>
</v-click>
<div class="mx-4 px-8">
  <v-click>

  ### 1. Load and deploy large language models on your PC<br><br>
  </v-click>
  <v-click>

  ### 2. Local sandbox for proof-of-concepts <br><br>
  </v-click>
  <v-click>

  ### 3. Run GenAI models offline! No vendor lock-in
  </v-click>
</div>

</div>

<!-- Ollama is still under development, but it looks like a promising tool for people who want to experiment with large language models without needing to rely on the cloud. -->

---
transition: fade-out
title: Environment Setup
layout: image-right
image: assets/slide-4.png
colorSchema: 'dark'
---

# Environment Setup

<div class="pt-12 text-center">

<v-click>

### Similar / same steps for all O.S Windows / Mac / Linux

</v-click>
</div><br><br>

<div class="mx-4 px-8">
  <v-click>

  #### 1. Install ollama<br><br>
  </v-click>
  <v-click>

  #### 2. Test the ollama (CLI)<br><br>
  </v-click>
  <v-click>

  #### 3. Run an LLM offline
  </v-click>
</div>

---
transition: fade-out
title: ollama serve
colorSchema: 'dark'
---

# ollama CLI basics

<div class="pt-12">

<v-click>

```sh
> ollama serve
```

</v-click>
</div><br><br>

<div class="mx-4 px-8">
  <v-click>

  #### - Starts the Ollama Server <br><br>
  </v-click>
  <v-click>

  #### - Serves Downloaded Models<br><br>
  </v-click>
  <v-click>

  <div class="bg-orange-300 text-red-950 pa-4 border-l-4 border-red-600">
    If the Ollama icon is in your taskbar, the server is likely running, and you might not need to execute ollama serve.
  </div>
  </v-click>
</div>

---
transition: fade-out
title: ollama create
colorSchema: 'dark'
---

# ollama CLI basics

<div class="pt-12">

<v-click>

```sh
> ollama create
```

</v-click>
</div><br><br>

<div class="mx-4 px-8">
  <v-click>

  #### - Creates a Custom Model <br><br>
  </v-click>
  <v-click>

  #### - Uses Modelfiles<br><br>
  </v-click>
  <v-click>

  <div class="bg-sky-100 text-stone-950 pa-4 border-l-4 border-sky-600">
    We will use this in the upcoming videos to create our own models on top of base models as blueprints ✨
  </div>
  </v-click>
</div>

---
transition: fade-out
title: ollama show
colorSchema: 'dark'
---

# ollama CLI basics

<div class="pt-12">

<v-click>

```sh
> ollama show
```

</v-click>
</div><br><br>

<div class="mx-4 px-8">
  <v-click>

  #### - Displays Model Information <br><br>
  </v-click>
  <v-click>

  #### - Helps in Model Selection<br><br>
  </v-click>
  <v-click>

  <div class="bg-teal-100 text-stone-950 pa-4 border-l-4 border-teal-600">
    Helps us make informed decisions about which model to pick for a given use case / business problem.
  </div>
  </v-click>
</div>

---
transition: fade-out
title: ollama run
colorSchema: 'dark'
---

# ollama CLI basics

<div class="pt-12">

<v-click>

```sh
> ollama run
```

</v-click>
</div><br><br>

<div class="mx-4 px-8">
  <v-click>

  #### - Executes an LLM <br><br>
  </v-click>
  <v-click>

  #### - Enables Model Interaction<br><br>
  </v-click>
  <v-click>

  <div class="bg-teal-100 text-stone-950 pa-4 border-l-4 border-teal-600">
    Primary way to use Ollama for tasks like text generation, question answering, translation, and more via REPL / API calls.
  </div>
  </v-click>
</div>

---
transition: fade-out
colorSchema: 'dark'
title: Thank you
layout: center
---

## Thank you 🙏 🤗