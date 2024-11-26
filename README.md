# 👋 Hey there, I'm Satyam

🔍 Exploring the world of **Fintech, Consulting,** and **Banking** as a passionate software engineer and a graduate student in **Computer Science** at **Northeastern University**. I’m always learning and building new things—focused on backend development, DevOps, and image processing.

---

## 🔥 GitHub Activity Streak
[![GitHub Streak](https://streak-stats.demolab.com/?user=satyampriyam&theme=radical&hide_border=true)](https://git.io/streak-stats)

## 🧑‍💻 My Technical Toolbox
I work with an array of tools and languages, adding to my skillset every day:

![Java](https://img.shields.io/badge/Code-Java-informational?style=flat-square&logo=java&logoColor=white&color=2bbc8a)
![Python](https://img.shields.io/badge/Code-Python-informational?style=flat-square&logo=python&logoColor=white&color=2bbc8a)
![JavaScript](https://img.shields.io/badge/Code-JavaScript-informational?style=flat-square&logo=javascript&logoColor=white&color=2bbc8a)
![React](https://img.shields.io/badge/Framework-React-informational?style=flat-square&logo=react&logoColor=white&color=2bbc8a)
![Docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat-square&logo=docker&logoColor=white&color=2bbc8a)
![Kafka](https://img.shields.io/badge/Tools-Kafka-informational?style=flat-square&logo=apache-kafka&logoColor=white&color=2bbc8a)
![GitHub Actions](https://img.shields.io/badge/Tools-GitHub_Actions-informational?style=flat-square&logo=github-actions&logoColor=white&color=2bbc8a)

---

## 🚀 Featured Repositories
Here are a few of my top repositories showcasing my experience across projects:

1. **[Snap Project](https://github.com/satryampriyam01/snap)** - MVC-based project on **image processing** with transformations and filters.
2. **[Atom to Byte](https://github.com/satryampriyam01/atom-to-byte)** - Social initiative converting physical resources into digital formats for village children.
3. **[Auto-Hotel Merger](https://github.com/satryampriyam01/auto-hotel-merger)** - Algorithmic project for hotel data matching using **Redis** and **Kafka**.

**Languages Used Across Repos**:  

[![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=satyampriyam&langs_count=8&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

---

## 📊 Dynamic GitHub Stats
[![Satyam's GitHub Stats](https://github-readme-stats.vercel.app/api?username=satyampriyam&show_icons=true&theme=radical&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)

---

## ⏰ Weekly Coding Stats
<!-- This section will auto-update to show hours spent on various programming languages over the past week. -->
<!-- WakaTime Setup Required -->
<!--
[![Satyam's Coding Time](https://github-readme-stats.vercel.app/api/wakatime?username=satyampriyam&theme=radical&hide_border=true)](https://wakatime.com/@username)
-->

---

## 🤖 GitHub Action for Dynamic Updates
Want to keep this README up-to-date automatically? Use the following GitHub Actions workflow to fetch repositories and language usage data daily:

```yaml
name: Update README with Repository Info

on:
  schedule:
    - cron: '0 0 * * *' # Runs daily
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v2

      - name: Fetch Repository Data
        run: |
          echo "Fetching repositories and language stats..."
          # Insert script here to pull repository details, languages, etc.
          
      - name: Commit Changes
        run: |
          git config --local user.email "actions@github.com"
          git config --local user.name "GitHub Actions"
          git add README.md
          git commit -m "Update README with new repo data"
          git push
