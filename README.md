# Hi there, I'm Soham 👋  

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=25&color=58A6FF&center=true&vCenter=true&width=600&lines=IT+Student+%7C+AI+%26+ML+Enthusiast;React+%7C+Python+%7C+C%2FC%2B%2B;Full+Stack+Developer+In+Progress;Always+Learning+New+Things+🚀" />
</p>

---

## 🚀 About Me  
- 💻 CS student passionate about **AI, Machine Learning, and Full-Stack Development**  
- 🌱 Currently practicing **Data Structures & Algorithms** in C/C++  
- ⚡ Skilled in **React**, **Python (pandas, Django, Rest API, NumPy, scikit-learn)**  
- 📊 Interested in **Data Science, AI/ML, and Scalable Applications**  
- 🔗 Open to collaborating on exciting projects & hackathons  

---

## 🛠️ Tech Stack  

### 💻 Languages & Frameworks  
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### 📊 Databases  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

### ⚙️ Libraries & Tools  
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Spline](https://img.shields.io/badge/Spline-0A0A0A?style=for-the-badge&logo=spline&logoColor=white)

---

## 📈 GitHub Stats  
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sohamkadu17&show_icons=true&theme=tokyonight" height="180em"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sohamkadu17&theme=tokyonight" height="180em"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sohamkadu17&layout=compact&theme=tokyonight" height="180em"/>
</p>

---

## 🐍 Snake Eating My Contributions  
<p align="center">
<!--   <img src="https://raw.githubusercontent.com/sohamkadu17/sohamkadu17/main/github-contribution-grid-snake.svg,dist/github-contribution-grid-snake-dark.svg" alt="snake animation" />
  <br> -->
    <img src="https://raw.githubusercontent.com/sohamkadu17/sohamkadu17/output/github-contribution-grid-snake.svg,dist/github-contribution-grid-snake-dark.svg" alt="snake animation" />

</p>

---

## ⚙️ Snake Workflow Configuration

Here is the GitHub Actions workflow (`.github/workflows/snake.yml`) that generates the contribution snake animation above:

```yaml
name: Generate Snake

on:
  schedule: # Runs every 12 hours
    - cron: "0 */12 * * *"
  workflow_dispatch:

permissions:
  contents: write # Needed for pushing to branches

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      # 1. Checkout with full history
      - name: Checkout repository
        uses: actions/checkout@v3
        with:
          fetch-depth: 0

      # 2. Generate the snake animation
      - name: Generate snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: sohamkadu17
          outputs: dist/github-contribution-grid-snake.svg,dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      # 3. Push to output branch
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

---

## 🌐 Connect with Me  
- [LinkedIn](www.linkedin.com/in/soham-kadu-4b1214359) 
- 📧 Email: sohamkadu24@gmail.com
---

⭐️ *“Code, Learn, Build, Repeat.”*  
