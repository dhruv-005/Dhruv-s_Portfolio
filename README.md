<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Dhruv%20Sonani&fontSize=60&fontColor=00ff88&animation=fadeIn&fontAlignY=38&desc=Developer%20Portfolio&descAlignY=60&descColor=4d9fff&descSize=22" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=00FF88&center=true&vCenter=true&multiline=false&width=650&height=50&lines=⚡+Full-Stack+Developer;🤖+AI+%26+Automation+Engineer;🚀+Open+Source+Contributor;💡+Built+with+Pure+HTML+CSS+JS;🔗+Live+GitHub+API+Integration" alt="Typing SVG" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=4000&pause=2000&color=4d9fff&center=true&vCenter=true&width=500&lines=No+Frameworks.+No+Build+Tools.+Just+Clean+Code.+✨" alt="Subtitle" />

<br/><br/>

[![Portfolio](https://img.shields.io/badge/🌐%20Live%20Portfolio-Visit%20Now-00ff88?style=for-the-badge&labelColor=0a0a0f&color=00ff88)](https://dhruv-005.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-dhruv--005-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dhruv-005)
[![MIT License](https://img.shields.io/badge/License-MIT-a855f7?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)

<br/>

![Last Commit](https://img.shields.io/github/last-commit/dhruv-005/dhruv-005.github.io?style=flat-square&color=00ff88&label=Last%20Updated&logo=git&logoColor=white)
![Repo Size](https://img.shields.io/github/repo-size/dhruv-005/dhruv-005.github.io?style=flat-square&color=4d9fff&logo=github&logoColor=white)
![Stars](https://img.shields.io/github/stars/dhruv-005/dhruv-005.github.io?style=flat-square&color=f59e0b&logo=github&logoColor=white)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=dhruv-005.dhruv-005.github.io&style=flat-square&color=00ff88)

<br/>

```
◆━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━◆
        ⚡  ZERO DEPENDENCIES  •  LIVE API  •  FULLY RESPONSIVE  ⚡
◆━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━◆
```

</div>

---

<div align="center">

## 🌐 Live Demo

### 👉 [https://dhruv-005.github.io](https://dhruv-005.github.io)

| 🖥️ Desktop | 💻 Laptop | 📱 Mobile | 📟 Tablet |
|:---:|:---:|:---:|:---:|
| ✅ Full Support | ✅ Full Support | ✅ Full Support | ✅ Full Support |

</div>

---

<div align="center">

## ✨ Features

</div>

```
╔══════════════════════════════════════════════════════════════╗
║                      CORE FEATURES                           ║
╠══════════════════════════════════════════════════════════════╣
║  🔴  Live GitHub API     →  Stars, repos, followers always   ║
║                             fresh — fetched every visit      ║
║  🖼️  Smart Avatar         →  Local photo first, GitHub       ║
║                             avatar as automatic fallback     ║
║  🌙  Dark / Light Mode   →  Smooth toggle + localStorage     ║
║  ⌨️  Typing Animation    →  Typewriter effect on hero        ║
║  📊  Animated Counters   →  Stats count up with easing       ║
║  🃏  Repo Cards          →  Auto-generated from GitHub       ║
║  🔍  Detail Modals       →  Stars, forks, issues, dates      ║
║  📱  Fully Responsive    →  All screen sizes supported       ║
║  🔒  CORS Safe           →  Correct API headers, no errors   ║
║  ⚡  Zero Dependencies   →  No npm, no bundler, no framework ║
╚══════════════════════════════════════════════════════════════╝
```

---

<div align="center">

## 🛠️ Built With

</div>

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-264DE4?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub API](https://img.shields.io/badge/GitHub_REST_API_v3-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

</div>

```
┌─────────────────────────────────────────────────────┐
│  Architecture  →  Single File (HTML + CSS + JS)     │
│  Fonts         →  Space Grotesk + Fira Code         │
│  Icons         →  Inline SVG (no external library)  │
│  API           →  GitHub REST API v3                │
│  Hosting       →  GitHub Pages (Free)               │
│  Theme         →  CSS Variables + localStorage      │
│  Animations    →  CSS keyframes + rAF               │
└─────────────────────────────────────────────────────┘
```

---

<div align="center">

## 🔗 How GitHub API Works

</div>

```javascript
// Two API calls on every visit — always live data
GET https://api.github.com/users/dhruv-005
GET https://api.github.com/users/dhruv-005/repos?per_page=100&sort=updated&type=public
```

> ⚠️ **CORS Fix** — Only `Accept` header is used. `Cache-Control` causes preflight CORS errors with GitHub API.

```javascript
// ✅ CORRECT — GitHub allows this header
headers: { 'Accept': 'application/vnd.github.v3+json' }

// ❌ WRONG — Triggers CORS preflight error
headers: { 'Cache-Control': 'no-cache' }
```

```
┌──────────────────────────────────────────────────────────┐
│                  DATA FETCHED LIVE                       │
├─────────────────────┬────────────────────────────────────┤
│  Profile Endpoint   │  Repos Endpoint                    │
├─────────────────────┼────────────────────────────────────┤
│  ✦ Name & Bio       │  ✦ Repo name & description         │
│  ✦ Avatar URL       │  ✦ Star count (always live ⭐)     │
│  ✦ Location         │  ✦ Fork count                      │
│  ✦ Repo count       │  ✦ Watcher count                   │
│  ✦ Followers        │  ✦ Open issues                     │
│  ✦ Following        │  ✦ Primary language                │
│                     │  ✦ Topics / tags                   │
│                     │  ✦ Homepage (live demo link)       │
│                     │  ✦ License info                    │
│                     │  ✦ Created & updated dates         │
└─────────────────────┴────────────────────────────────────┘
```

```javascript
// Repos sorted: most stars first → then most recently updated
repos.sort((a, b) => {
  const starDiff = b.stargazers_count - a.stargazers_count;
  return starDiff !== 0 ? starDiff : new Date(b.updated_at) - new Date(a.updated_at);
});
```

> **Rate Limit:** 60 requests/hour unauthenticated · This portfolio uses **2 requests per visit**

---

<div align="center">

## 📁 Project Structure

</div>

```
dhruv-005.github.io/
│
├── 📄  index.html   ←  Entire portfolio (HTML + CSS + JS)
├── 🖼️  dhruv.png    ←  Profile photo (GitHub avatar fallback)
└── 📖  README.md    ←  You are here
```

---

<div align="center">

## ⚙️ How It Works

</div>

```
Page Load
│
├── 1️⃣  Restore saved theme from localStorage
│
├── 2️⃣  Render all static content immediately
│        ├── Blog cards
│        ├── Research cards
│        ├── Achievements list
│        └── About / Tech Stack / Timeline
│
├── 3️⃣  Start typing animation (hero section)
│
└── 4️⃣  Fetch GitHub API (async, parallel)
         │
         ├── fetchProfile()  →  GET /users/dhruv-005
         ├── fetchRepos()    →  GET /users/dhruv-005/repos
         │
         └── On success ✅
              ├── Animate hero stats with countUp()
              ├── Update terminal with live data
              ├── Set GitHub avatar as fallback
              ├── Render GitHub profile banner
              └── Render all repo cards
```

---

<div align="center">

## 🎨 CSS Architecture

</div>

```
CSS Custom Properties (Design Tokens)
│
├── 🎨  Colors       →  --green  --blue  --purple  --amber  --red
├── 🌑  Backgrounds  →  --bg  --bg2  --bg3  --bg4  --bg5
├── 🃏  Cards        →  --card  --card-h
├── ─── Borders      →  --border  --border-h
├── 📝  Text         →  --text  --text2  --text3
├── 💫  Shadows      →  --shadow  --shadow-lg
├── 📐  Spacing      →  --radius  --radius-lg  --radius-xl  --nav
└── 🔤  Fonts        →  --font (Space Grotesk)  --mono (Fira Code)

Dark / Light Theme = Only CSS variable values swap
Zero JavaScript repaint needed — instant theme switch ⚡
```

---

<div align="center">

## 📱 Responsive Breakpoints

</div>

```
┌─────────────────────────────────────────────────────────┐
│  1280px+   Full desktop layout — all columns visible    │
│  1024px    About grid → single column                   │
│   900px    Nav links hidden → hamburger menu shown      │
│   768px    Hero stats → 2×2 grid, cards → single col    │
│   640px    Reduced padding, compact footer              │
│   380px    Minimum sizes for smallest phones            │
└─────────────────────────────────────────────────────────┘
```

---

<div align="center">

## 🚀 Deploy Your Own

</div>

```bash
# Step 1 — Clone the repo
git clone https://github.com/dhruv-005/dhruv-005.github.io.git
cd dhruv-005.github.io

# Step 2 — Set your GitHub username (in index.html)
const GH = 'your-github-username';

# Step 3 — Replace dhruv.png with your photo

# Step 4 — Create your repo named: yourusername.github.io
# Step 5 — Push your code
git add .
git commit -m "🚀 My portfolio"
git push origin main

# Step 6 — Enable GitHub Pages
# Settings → Pages → Branch: main → /(root) → Save

# Step 7 — Visit 🎉
# https://yourusername.github.io
```

---

<div align="center">

## 🔧 Customisation Guide

</div>

```
To update content — edit these arrays in index.html
│
├── POSTS[]          →  Blog articles
├── ARTICLES{}       →  Full article bodies
├── RESEARCH[]       →  Research papers
├── ACHIEVEMENTS[]   →  Certs, courses, contributions
├── TECH_STACK[]     →  Skills in About page
├── TIMELINE[]       →  Work experience & internships
└── GH = ''          →  Your GitHub username ← most important
```

---

<div align="center">

## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=dhruv-005&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00ff88&icon_color=4d9fff&text_color=e8e8f0&border_radius=12" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhruv-005&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00ff88&text_color=e8e8f0&border_radius=12" width="49%" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=dhruv-005&theme=tokyonight&hide_border=true&background=0d1117&ring=00ff88&fire=4d9fff&currStreakLabel=00ff88&border_radius=12" width="60%" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dhruv-005&theme=react-dark&bg_color=0d1117&color=00ff88&line=4d9fff&point=00ff88&area=true&hide_border=true" width="95%" />

</div>

---

<div align="center">

## 📝 License

MIT License — Free to use, modify, and distribute.

If you use this as a template, please give a ⭐ star — it helps a lot!

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&width=600&lines=No+frameworks.+No+build+tools.+Just+clean+code.+⚡;Star+the+repo+if+you+find+it+useful+⭐;Made+with+%E2%9D%A4%EF%B8%8F+by+Dhruv+Sonani" alt="Footer Typing" />

<br/>

**[dhruv-005](https://github.com/dhruv-005)** · © 2026 · MIT License

</div>
