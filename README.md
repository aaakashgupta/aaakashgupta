from pathlib import Path
import pypandoc

md = r"""# Hi 👋, I'm Akash Gupta

<h3 align="center">Full Stack MERN Developer | JavaScript Developer | Open Source Learner</h3>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Poppins&size=28&duration=3500&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Full+Stack+MERN+Developer;React+Developer;Node.js+Backend+Developer;Always+Learning" />
</p>

<p align="center">
<a href="https://www.linkedin.com/in/akash-gupta-0b8725339/"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
<a href="mailto:aaakashgupta2023@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" /></a>
</p>

---

## 🚀 About Me

- 💻 MERN Stack Developer
- 🌱 Learning Backend & DSA with JavaScript
- 🎯 Looking for Software Development Internship
- 📫 aaakashgupta2023@gmail.com

## 🛠 Tech Stack

<p>
<img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,express,mongodb,git,github,vscode,postman" />
</p>

## 📊 GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=aaakashgupta&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aaakashgupta&layout=compact&theme=tokyonight)

## 🔥 Streak

![Streak](https://streak-stats.demolab.com?user=aaakashgupta&theme=tokyonight)

## 📈 Activity Graph

![Graph](https://github-readme-activity-graph.vercel.app/graph?username=aaakashgupta&theme=tokyo-night)

## 🏆 Trophies

![Trophy](https://github-profile-trophy.vercel.app/?username=aaakashgupta&theme=tokyonight&no-frame=true)

## 🚀 Featured Projects

- Portfolio Website
- MERN Task Manager
- E-Commerce Website
- Weather App

## 🐍 Snake Animation

After creating the profile, create this workflow:

`.github/workflows/snake.yml`

and use Platane/snk GitHub Action.

"""

out="/mnt/data/README.md"
pypandoc.convert_text(md,"md",format="md",outputfile=out,extra_args=["--standalone"])
print(out)
