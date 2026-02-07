# Hello World I'm Jamalul Husnil Mubaraq👋

![Banner](https://drive.google.com/uc?export=view&id=1RaR_-8KADg3Pp-UuT3deZFyD5mP65523)


I’m an Informatics Engineering undergraduate at Universitas Jabal Ghafur Sigli with a strong passion for web development and digital creativity. I enjoy working across the full-stack spectrum while also having a keen interest in UI/UX design, constantly learning and adapting to emerging technologies in the web ecosystem.

I aspire to grow as a proficient bug hunter, focusing on building secure, efficient, and innovative systems while identifying vulnerabilities that help strengthen digital security. From developing scalable applications to tackling ethical hacking challenges, I’m driven by curiosity and problem-solving.

I love transforming ideas into intuitive, engaging digital experiences through clean and maintainable code. Feel free to explore my work, collaborate on exciting projects, and let’s build impactful solutions together. 🚀✨

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/hsnlmbrq_)
[![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@migi.way7)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/jamalul-husnil-mubaraq-284b8638b)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@ppy.)

## 🌐Skills

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=js,html,css,laravel,flutter,py,php,react,java,cpp,figma" />
  </a>
</p>

## 🌏GitHub Stats

<!--
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=haerul920&theme=blue_navy&hide_border=false&include_all_commits=true&count_private=false" width="430" />
  <img src="https://nirzak-streak-stats.vercel.app/?user=haerul920&theme=blue_navy&hide_border=false" width="430" />
</p>-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/haerul920/haerul920/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/haerul920/haerul920/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/haerul920/haerul920/output/pacman-contribution-graph.svg">
</picture>

name: Generate Pacman Contribution Graph

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate pacman graph
        uses: Platane/snk@v3
        with:
          github_user_name: haerul920
          outputs: |
            dist/pacman-contribution-graph.svg
            dist/pacman-contribution-graph-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## 💵Support Me

[![Saweria]()]()
