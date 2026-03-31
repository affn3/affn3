<div align="center">

<!-- Animated header with typing effect via SVG -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=9CA3AF&center=true&vCenter=true&width=600&lines=Hey+%F0%9F%91%8B+I'm+Nils+Affolter;Software+Developer+%F0%9F%87%A8%F0%9F%87%AD+Basel%2C+CH;Building+clean+%26+reliable+web+apps;Always+learning+%F0%9F%9A%80" alt="Typing SVG" />

<br/>

<!-- Animated wave banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1a1f2e,100:9CA3AF&height=120&section=header&animation=twinkling" width="100%"/>

</div>

<!-- Snake animation (add via GitHub Actions — see bottom of README) -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nilsaffolter/nilsaffolter/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nilsaffolter/nilsaffolter/output/github-contribution-grid-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/nilsaffolter/nilsaffolter/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</div>

---

## `> whoami`

```ts
const nils = {
  location : "Basel, Switzerland 🇨🇭",
  role     : "Software Developer",
  focus    : ["E-Commerce", "Clean Code", "UI/UX"],
  learning : "always",
  motto    : "Ship it. Then make it better.",
};
```

<div align="center">

<img src="https://komarev.com/ghpvc/?username=nilsaffolter&style=for-the-badge&color=0D1117&label=PROFILE+VIEWS&labelColor=1a1f2e" />

</div>

---

## `> tech --list`

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=react,ts,js,html,css,bootstrap&theme=dark&perline=6" />

### Backend

<img src="https://skillicons.dev/icons?i=java,spring,mysql&theme=dark&perline=6" />

### Tools

<img src="https://skillicons.dev/icons?i=vscode,idea,docker,git&theme=dark&perline=6" />

</div>

---

## `> git log --stats`

<div align="center">

<a href="https://github.com/nilsaffolter">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=nilsaffolter&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=9CA3AF&icon_color=6B7280&text_color=E5E7EB&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nilsaffolter&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=9CA3AF&text_color=E5E7EB&langs_count=6" />
</a>

<br/>

<a href="https://github.com/nilsaffolter">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nilsaffolter&theme=github-dark-blue&hide_border=true&background=0D1117&ring=9CA3AF&fire=9CA3AF&currStreakLabel=9CA3AF" />
</a>

</div>

---

## `> activity --graph`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=nilsaffolter&bg_color=0D1117&color=9CA3AF&line=6B7280&point=E5E7EB&area=true&area_color=1a1f2e&hide_border=true&custom_title=Contribution+Graph" />

</div>

---

## `> open --social`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0D1117?style=for-the-badge&logo=linkedin&logoColor=9CA3AF&labelColor=1a1f2e)](https://www.linkedin.com/in/leandro-fragale-53780b34a/)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-0D1117?style=for-the-badge&logo=instagram&logoColor=9CA3AF&labelColor=1a1f2e)](https://www.instagram.com/leandro_fragale/)
[![Basel](https://img.shields.io/badge/📍_Basel,_Switzerland-0D1117?style=for-the-badge&logoColor=9CA3AF&labelColor=1a1f2e)](https://www.google.com/maps/place/Basel)

</div>

---

<div align="center">

<!-- Animated footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9CA3AF,100:0D1117&height=100&section=footer&animation=twinkling" width="100%"/>

<sub>⚡ crafted with precision · Basel, CH · 2025</sub>

</div>

---

<!-- =====================================================
🐍 SNAKE ANIMATION SETUP (einmalig konfigurieren)
=======================================================

Damit die Snake-Animation funktioniert, füge diese GitHub Action hinzu:
Pfad: .github/workflows/snake.yml

name: Generate Snake
on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_token: ${{ secrets.GITHUB_TOKEN }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

Ersetze "nilsaffolter" überall mit deinem echten GitHub-Username!
====================================================== -->
