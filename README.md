# <div align="center"> <img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+Mono&size=45&duration=3000&color=6366F1&center=true&vCenter=true&width=500&lines=Hey+I'm+Syafiy;Mobile+Dev+Web3+Builder;Blockchain+Explorer" alt="Typing SVG"/> </div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=syafiyft&color=6366F1&style=flat-square" alt="Profile Views"/>
</div>

---

## About Me

I build mobile apps and explore Web3. Currently preparing for AWS Certified Solutions Architect (Associate) while diving into blockchain, NFTs, and DeFi protocols.

- Mobile development (Flutter & React Native)
- Web3 architecture and smart contracts
- AI agents and conversational systems
- Blockchain, NFTs, DeFi protocols
- Distributed systems and cloud infrastructure

---

## Current Focus

**AWS SAA Preparation** — Understanding cloud architecture, infrastructure design, and AWS services at scale.

**Blockchain & DeFi** — Exploring tokenomics, smart contract patterns, and DeFi protocol design. How do we build financial systems that actually work?

**Mobile at Scale** — Enterprise mobile apps with offline-first sync, clean architecture, and real-time data.

---

## Featured Projects

### [Barakah Vault](https://github.com/syafiyft/barakah-vault)
AI-powered Shariah compliance chatbot with multilingual RAG and Islamic finance scoring.  
**Tech:** JavaScript, LLMs, Arabic NLP | **Event:** AI Fiqh Hackathon 2026

### [For Ummah](https://github.com/syafiyft/for-ummah)
Conversational AI agent exploring agentic patterns.  
**Tech:** Python

### [Wild Watch](https://github.com/syafiyft/wild_watch_v2)
Wildlife discovery platform. Awarded FYP2 Best Project.  
**Tech:** Full-stack

---

## Tech Stack

<div align="center">

**Languages**  
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Mobile**  
![React Native](https://img.shields.io/badge/-React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Frontend**  
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**Backend & Cloud**  
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=black)

**Databases**  
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/-MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white)

**Web3**  
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/-Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)

</div>

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=syafiyft&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=syafiyft&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## What I'm Learning

- Cloud architecture patterns and AWS services
- Smart contract security and DeFi mechanics
- Distributed consensus algorithms
- Enterprise mobile architecture at scale

---

## Let's Connect

<div align="center">

[LinkedIn](https://linkedin.com/in/syafiyft) | [Portfolio](https://github.com/syafiyft/syafiys-portfolio) | Email: [add your email]

---

Made with intent and strong ☕

</div>

<!-- Snake Game - Interactive Element -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/syafiyft/syafiyft/blob/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/syafiyft/syafiyft/blob/output/github-contribution-grid-snake.svg">
  <img alt="github-snake" src="https://github.com/syafiyft/syafiyft/blob/output/github-contribution-grid-snake.svg">
</picture>

---

## Setup Instructions

To use this README with the snake game animation:

1. Replace this content in your `syafiyft/syafiyft` repository README.md
2. Create `.github/workflows/snake.yml` with this content:

```yaml
name: generate animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: generate snake svg
        uses: Platane/snk/svg-only@v3
        with:
          github-user-name: syafiyft
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push snake svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Push the changes. The snake will auto-generate and update based on your contributions.

---

**Customization:**

- Change `6366F1` (indigo) in typing SVG to your preferred color (hex code)
- Update LinkedIn, Portfolio, and Email links
- Replace `syafiyft` with your username in the snake game and stats URLs
- Typing messages: Edit the `lines=` parameter in the typing SVG URL
