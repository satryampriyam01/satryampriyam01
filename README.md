# 👋 Hello! I'm Satyam

I'm a passionate software engineer with a focus on **backend development**, **DevOps**, and **image processing**. Currently, I'm a graduate student in Computer Science at Northeastern University, exploring new tech every day!

---

## 🔥 GitHub Activity Streak
[![GitHub Streak](https://streak-stats.demolab.com/?user=satyampriyam)](https://git.io/streak-stats)

## 🧑‍💻 Skills & Tools
![Java](https://img.shields.io/badge/Code-Java-informational?style=flat-square&logo=java&logoColor=white&color=2bbc8a)
![Python](https://img.shields.io/badge/Code-Python-informational?style=flat-square&logo=python&logoColor=white&color=2bbc8a)
![JavaScript](https://img.shields.io/badge/Code-JavaScript-informational?style=flat-square&logo=javascript&logoColor=white&color=2bbc8a)
![React](https://img.shields.io/badge/Framework-React-informational?style=flat-square&logo=react&logoColor=white&color=2bbc8a)
![Docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat-square&logo=docker&logoColor=white&color=2bbc8a)
![Kafka](https://img.shields.io/badge/Tools-Kafka-informational?style=flat-square&logo=apache-kafka&logoColor=white&color=2bbc8a)
![GitHub Actions](https://img.shields.io/badge/Tools-GitHub_Actions-informational?style=flat-square&logo=github-actions&logoColor=white&color=2bbc8a)

---

## 📈 Language Usage (Last 30 Days)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=satyampriyam&layout=compact&theme=radical)

---

## 🌱 What I'm Currently Working On
- [Snap Project](link-to-project-repo): An MVC-based project applying image processing techniques.
- **Exploring**: React, state management, and advanced Java programming patterns.

---

## 🤖 GitHub Action to Showcase Daily Activity
Here's a sample GitHub Action workflow you could use to update the README daily with your latest commits and coding streak:

```yaml
name: Update README with Activity

on:
  schedule:
    - cron: '0 0 * * *' # Runs daily

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v2

      - name: Update README
        run: |
          echo "Updating README with recent activity..."
          # Here you could add logic to update the README with any custom script
