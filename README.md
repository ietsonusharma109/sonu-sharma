
<!-- ======================================================= -->
<!--                 SONU SHARMA | PROFILE                   -->
<!-- ======================================================= -->

<div align="center">

# 👋 Hi, I'm Sonu Sharma

### 💻 Aspiring Full Stack Developer | C++ & DSA Enthusiast

Building my coding skills one problem and one project at a time.

<a href="https://github.com/ietsonusharma109">
  <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github" alt="GitHub Profile" />
</a>
<a href="https://leetcode.com/sonu-sharma/">
  <img src="https://img.shields.io/badge/LeetCode-Practice-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
</a>
<a href="mailto:sonuksharma6203@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<img src="https://komarev.com/ghpvc/?username=ietsonusharma109&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" />

</div>

---

## 🚀 About Me

- 🌱 Currently learning **HTML and Web Development**
- 💡 Practicing **Data Structures and Algorithms using C++**
- 🧠 Solving coding challenges on **LeetCode**
- 🛠️ Interested in building useful and practical projects
- 🎯 Working toward becoming a **Full Stack Developer**
- 📂 Explore my repositories: [GitHub Projects](https://github.com/ietsonusharma109?tab=repositories)
- 📫 Contact me: **sonuksharma6203@gmail.com**

---

## 🧰 Languages & Tools

<div align="center">

<a href="https://isocpp.org/">
  <img src="https://skillicons.dev/icons?i=cpp" width="48" alt="C++" />
</a>
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
  <img src="https://skillicons.dev/icons?i=html" width="48" alt="HTML" />
</a>
<a href="https://git-scm.com/">
  <img src="https://skillicons.dev/icons?i=git" width="48" alt="Git" />
</a>
<a href="https://github.com/">
  <img src="https://skillicons.dev/icons?i=github" width="48" alt="GitHub" />
</a>
<a href="https://www.mongodb.com/">
  <img src="https://skillicons.dev/icons?i=mongodb" width="48" alt="MongoDB" />
</a>
<a href="https://www.mysql.com/">
  <img src="https://skillicons.dev/icons?i=mysql" width="48" alt="MySQL" />
</a>

</div>

<p align="center">
  <i>Learning, practicing, and improving every day.</i>
</p>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=ietsonusharma109&show_icons=true&rank_icon=github&include_all_commits=true&theme=tokyonight&hide_border=true" alt="GitHub statistics" />

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ietsonusharma109&layout=compact&langs_count=6&theme=tokyonight&hide_border=true" alt="Most used programming languages" />

</div>

<div align="center">

<img src="https://img.shields.io/badge/Repositories-Live%20on%20GitHub-2f81f7?style=for-the-badge&logo=github" alt="View repositories" />

<a href="https://github.com/ietsonusharma109?tab=repositories">
  <img src="https://img.shields.io/badge/Explore-All%20Repositories-161b22?style=for-the-badge&logo=github" alt="Explore all repositories" />
</a>

</div>

---

## 🔥 Contribution Streak

<div align="center">

<img src="https://streak-stats.demolab.com/?user=ietsonusharma109&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>

---

## 📈 Contribution Activity Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ietsonusharma109&theme=tokyo-night&hide_border=true&area=true" alt="GitHub contribution activity graph" />

</div>

---


---

## 🐍 Contribution Snake

<div align="center">

<!-- Dark theme -->
<img src="https://raw.githubusercontent.com/ietsonusharma109/ietsonusharma109/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake Animation" />

</div>

## 🌟 Featured Projects

<div align="center">

<a href="https://github.com/ietsonusharma109/sonu-sharma">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ietsonusharma109&repo=sonu-sharma&theme=tokyonight&hide_border=true" alt="Sonu Sharma project repository" />
</a>

</div>

<p align="center">
  🚀 More projects are available in my
  <a href="https://github.com/ietsonusharma109?tab=repositories">repositories</a>.
</p>

---

## 🏆 GitHub Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=ietsonusharma109&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&row=1" alt="GitHub profile trophies" />

</div>

---

## 🤝 Let's Connect

<div align="center">

<a href="https://github.com/ietsonusharma109">
  <img src="https://img.shields.io/badge/GitHub-Follow%20My%20Journey-181717?style=for-the-badge&logo=github" alt="GitHub" />
</a>
<a href="https://leetcode.com/sonu-sharma/">
  <img src="https://img.shields.io/badge/LeetCode-Solve%20Together-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
</a>
<a href="mailto:sonuksharma6203@gmail.com">
  <img src="https://img.shields.io/badge/Email-Let's%20Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

### ⭐ Thanks for visiting my profile!

*Keep learning. Keep building. Keep growing.* 🚀

</div>

name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: ietsonusharma109
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Publish Snake
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./dist
          publish_branch: output
