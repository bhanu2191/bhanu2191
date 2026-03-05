<!-- =======================
   PREMIUM GITHUB PROFILE README
   Username: bhanu2191
   Repo name MUST be: bhanu2191
   File: README.md
======================= -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=3500&pause=800&color=58A6FF&center=true&vCenter=true&width=820&lines=Hi%2C+I'm+Akila+Abeysinghe;Software+Engineering+Student+%7C+Full+Stack+Developer;Java+%7C+Node.js+%7C+React+%7C+Flutter;Building+clean%2C+scalable+software+solutions" />

<br/>

<img src="https://komarev.com/ghpvc/?username=bhanu2191&style=for-the-badge&color=0e75b6" />
<a href="https://github.com/bhanu2191?tab=followers">
  <img src="https://img.shields.io/github/followers/bhanu2191?label=Followers&style=for-the-badge" />
</a>
<a href="https://github.com/bhanu2191?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-Explore-2ea043?style=for-the-badge" />
</a>

</div>

---

## About Me

- 🎓 Software Engineering student  
- 💻 Full Stack Developer (Web + Backend + Mobile)  
- ⚙️ Interested in scalable systems, clean architecture, and modern UI  
- 🚀 Currently building: **BidSync** (Distributed Online Auction System)

---

## Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,nodejs,php,react,js,tailwind,vite,flutter,android,mysql,sqlite,firebase,docker,git,github,vscode&perline=8" />
</div>

---

## GitHub Analytics

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=bhanu2191&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhanu2191&layout=compact&theme=github_dark&hide_border=true" />
</div>

<div align="center">
  <img height="180" src="https://streak-stats.demolab.com?user=bhanu2191&theme=github-dark-blue&hide_border=true" />
</div>

---

## Achievements

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=bhanu2191&theme=darkhub&no-frame=true&row=1&column=7" />
</div>

---

## Activity Graph (Premium)

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=bhanu2191&theme=github-compact&hide_border=true" />
</div>

---

## Featured Projects

### 🔥 BidSync — Distributed Online Auction System
- Java EE (EJB, JMS), distributed design, real-time bidding + notifications  
- Focus: scalability, reliability, clean architecture

### 🛒 Full Stack E-Commerce Application
- Product management, authentication, responsive UI  
- Full-stack workflow with modern frontend + backend

> Tip: Pin your best 6 repositories on your profile for a premium look.

---

## What I’m Learning Now

- System Design & Architecture  
- Distributed Systems  
- Backend performance + best practices  
- Cloud-native development fundamentals

---

## Contact

<div align="center">

<a href="https://github.com/bhanu2191">
  <img src="https://img.shields.io/badge/GitHub-bhanu2191-black?style=for-the-badge&logo=github" />
</a>

<!-- OPTIONAL: Add LinkedIn + Email (replace placeholders) -->
<!--
<a href="https://www.linkedin.com/in/YOUR_LINKEDIN">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" />
</a>
<a href="mailto:YOUR_EMAIL">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
-->

</div>

---

## Contribution Snake (Animated)

![Snake animation](https://github.com/bhanu2191/bhanu2191/blob/output/github-contribution-grid-snake.svg)

---

# ✅ Enable the Snake Animation (Required)

Create this file in your profile repo:

`.github/workflows/snake.yml`

Paste this EXACTLY:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"  # runs daily
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: bhanu2191
          outputs: |
            dist/github-contribution-grid-snake.svg
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
