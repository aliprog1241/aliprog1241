<h1 align="center">✨ Hello My Friend 🖖🏿✌🏿 ✨</h1>

<div align="center">
  <img src="https://i.pinimg.com/originals/bc/1f/3e/bc1f3e8836f8f4a7e74b1e0ff0ec5b5d.gif" width="400" alt="anime" />
</div>

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aliprog1241&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=codeSTACKr&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=aliprog1241&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=codeSTACKr&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=aliprog1241&radius=16&theme=redical&area=true&order=5" height="300" alt="activity-graph graph"  />
</div>

---
name: "generate-snake-game-from-github-contribution-grid"
description: "Generates a snake game from a github user contributions grid. Output the animation as gif or svg"
author: "platane"

runs:
  using: docker
  image: docker://platane/snk@sha256:96390294299275740e5963058c9784c60c5393b3b8b16082dcf41b240db791f9

inputs:
  github_user_name:
    description: "github user name"
    required: true
  github_token:
    description: "github token used to fetch the contribution calendar. Default to the action token if empty."
    required: false
    default: ${{ github.token }}
  outputs:
    required: false
    description: |
      list of files to generate.
      one file per line. Each output can be customized with options as query string.

       supported query string options:

      - palette:      A preset of color, one of [github, github-dark, github-light]
      - color_snake:  Color of the snake
      - color_dots:   Coma separated list of dots color. 
                      The first one is 0 contribution, then it goes from the low contribution to the highest.
                      Exactly 5 colors are expected.
      example:
        outputs: |
          dark.svg?palette=github-dark&color_snake=blue
          light.svg?color_snake=#7845ab
          ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

<h2 align="left">🛠️ Proficient in:</h2>

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" height="40" alt="pycharm logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
</div>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aliprog1241/aliprog1241/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aliprog1241/aliprog1241/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/aliprog1241/aliprog1241/output/pacman-contribution-graph.svg">
</picture>

---

<h2 align="left">🌐 Find Me:</h2>

<div align="left">
  <a href="https://linkedin.com/in/yourusername" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://twitter.com/yourusername" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="twitter logo"  />
  </a>
  <a href="https://discord.gg/yourlink" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord logo"  />
  </a>
  <a href="https://youtube.com/@yourchannel" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube logo"  />
  </a>
  <a href="https://instagram.com/yourusername" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="52" height="40" alt="instagram logo"  />
  </a>
  <a href="https://t.me/yourusername" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/telegram/default.svg" width="52" height="40" alt="telegram logo"  />
  </a>
  <a href="https://twitch.tv/yourusername" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitch/default.svg" width="52" height="40" alt="twitch logo"  />
  </a>
</div>

---

<div align="center">
  <img height="200" src="https://i.pinimg.com/originals/53/74/3d/53743d0c7f68fbb6f4131ce8c63b9266.gif"  />
</div>
