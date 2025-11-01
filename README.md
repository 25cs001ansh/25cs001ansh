<!-- 💫 GitHub Profile README for Ansh Adodariya -->

<h1 align="center">👋 Hi, I'm <span style="color:#58a6ff;">Ansh Adodariya</span></h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=25&duration=3500&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Full+Stack+Web+Developer;Open+Source+Contributor;React+%7C+Node.js+%7C+MongoDB;Always+Learning+New+Things+🚀" alt="Typing SVG Animation" />
</p>

---

### 🚀 About Me
- 🌱 Currently exploring **Next.js**, **TypeScript**, and **Cloud Computing**  
- 💻 Skilled in **React**, **Node.js**, **Express**, **MongoDB**, and **JavaScript**  
- 🧩 Passionate about **clean code**, **open source**, and **problem solving**  
- 🎯 Goal: To craft scalable web apps and impactful open-source projects  
- ⚡ Fun fact: I debug faster when I’m listening to EDM 🎧  

---

### 🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,express,mongodb,git,github,python,vscode,figma" />
</p>

---

### 📊 GitHub Analytics & Streak

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=anshadodariya&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=anshadodariya&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anshadodariya&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

### 🌐 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/anshadodariya" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://twitter.com/anshadodariya" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
  <a href="https://github.com/anshadodariya" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://anshadodariya.github.io" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio"/>
  </a>
</p>

---

### 🧩 Fun Animation

<p align="center">
  <img src="https://raw.githubusercontent.com/anshadodariya/anshadodariya/main/assets/coding.gif" width="400" alt="Coding Animation">
</p>

---

### 🐍 Contribution Snake Animation

<p align="center">
  <img src="https://raw.githubusercontent.com/anshadodariya/anshadodariya/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: anshadodariya
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

---

### ✨ Quote of the Day
> “The best error message is the one that never shows up.” — Thomas Fuchs

---

⭐ **From [Ansh Adodariya](https://github.com/anshadodariya)**

