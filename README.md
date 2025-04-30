<!-- Profile README for github.com/guptan404 -->
<h1 align="center">
  Hey, I’m Nikhil Gupta <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"/>
</h1>

<p align="center">
  Founder&nbsp;& CEO&nbsp;@&nbsp;<a href="https://nearkart.in">NearKart</a> • Full-Stack&nbsp;& Mobile Dev • DSA Mentor • Eternal Hacker
</p>

---

## 🚀 What I’m Building
- **NearKart** – real-time marketplace connecting 400 + street vendors to local customers  
  <sub>Built with Flutter (📱), NestJS (🚀), MongoDB (🍃), PostgreSQL (🐘), RabbitMQ (📨), AWS (☁️), Docker (🐳)</sub>
- ⚙️ Micro-services, event-driven backends & CI/CD pipelines that ship faster than designers can say “tweak the padding”
- 📚 Weekends spent teaching Data Structures & Algorithms to college students

## 🛠️ Tech Toolbox
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-e0234e?style=flat&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-e10098?style=flat&logo=graphql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)

> **Current fascination:** LLM-powered chatbots & streaming architectures

## 📈 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=guptan404&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats">
  <br>
  <img src="https://streak-stats.demolab.com?user=guptan404&hide_border=true" alt="GitHub streak">
</p>

## 📝 Latest Blog Posts
<!-- BLOG-POST-LIST:START -->
- [Seamless Flutter to Android: Unveiling GitPod’s Next Chapter](https://medium.com/@guptan404/seamless-flutter-to-android-unveiling-gitpods-next-chapter-ccb22d37a040) _(Aug 14 2023)_
- [Seamless Flutter Development on GitHub Web IDE using GitPod](https://medium.com/@guptan404/seamless-flutter-development-on-github-web-ide-using-gitpod-61bb5d317637) _(Aug 4 2023)_
- [Understanding the Project Structure & Exploring the Dart Code](https://medium.com/@guptan404/understanding-the-project-structure-and-exploring-the-dart-code-getting-started-with-flutter-a793a7d3a4fd) _(Jul 29 2023)_
- [Getting Started with Flutter: Building Your First App](https://medium.com/@guptan404/getting-started-with-flutter-building-your-first-app-introduction-6e64f41e26e6) _(Jul 28 2023)_
<!-- BLOG-POST-LIST:END -->

<details>
<summary><b>Automate this list?</b></summary>

Add a workflow like the snippet below in `.github/workflows/blog.yml` to refresh it every 12 hours:

```yaml
name: Update recent Medium posts
on:
  schedule:
    - cron: '0 */12 * * *'
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: gautamkrishnar/blog-post-workflow@v2
        with:
          feed_list: "https://medium.com/feed/@guptan404"
          max_post_count: 4
