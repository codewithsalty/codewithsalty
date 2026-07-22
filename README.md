<div align="center">

<!-- ANIMATED SVG PROFILE BANNER -->
<svg width="100%" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bgGlow" cx="50%" cy="40%" r="60%">
      <stop offset="0%" stop-color="#1a0101" />
      <stop offset="60%" stop-color="#0a0a0a" />
      <stop offset="100%" stop-color="#000000" />
    </radialGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#dc2626" />
      <stop offset="30%" stop-color="#ef4444" />
      <stop offset="60%" stop-color="#f87171" />
      <stop offset="100%" stop-color="#dc2626" />
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="transparent" />
      <stop offset="50%" stop-color="#dc2626" />
      <stop offset="100%" stop-color="transparent" />
    </linearGradient>
    <filter id="glowFilter">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="dotGrid" width="30" height="30" patternUnits="userSpaceOnUse">
      <circle cx="15" cy="15" r="0.8" fill="#dc2626" opacity="0.12" />
    </pattern>
  </defs>

  <rect width="1200" height="320" fill="url(#bgGlow)" />
  <rect width="1200" height="320" fill="url(#dotGrid)" />

  <!-- Decorative lines -->
  <line x1="100" y1="40" x2="500" y2="40" stroke="url(#lineGrad)" stroke-width="1" opacity="0.5">
    <animate attributeName="x1" values="80;120;80" dur="4s" repeatCount="indefinite" />
  </line>
  <line x1="700" y1="40" x2="1100" y2="40" stroke="url(#lineGrad)" stroke-width="1" opacity="0.5">
    <animate attributeName="x2" values="1120;1080;1120" dur="4s" repeatCount="indefinite" />
  </line>

  <!-- Pulsing shield icon -->
  <g transform="translate(600, 60)" filter="url(#glowFilter)">
    <path d="M0 -30 L22 -15 L22 15 Q22 38 0 45 Q-22 38 -22 15 L-22 -15 Z" fill="none" stroke="#dc2626" stroke-width="2">
      <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite" />
    </path>
    <circle cx="0" cy="3" r="6" fill="none" stroke="#dc2626" stroke-width="1.5">
      <animate attributeName="r" values="5;7;5" dur="2s" repeatCount="indefinite" />
    </circle>
    <line x1="0" y1="-2" x2="0" y2="15" stroke="#dc2626" stroke-width="2">
      <animate attributeName="y1" values="-2;2;-2" dur="2s" repeatCount="indefinite" />
    </line>
  </g>

  <!-- Name -->
  <text x="600" y="145" text-anchor="middle" fill="url(#nameGrad)" font-size="56" font-weight="900" font-family="Arial, sans-serif" letter-spacing="6">
    SALMAN KHAN
    <animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite" />
  </text>

  <!-- Title -->
  <text x="600" y="185" text-anchor="middle" fill="#dc2626" font-size="18" font-family="monospace" opacity="0.85" letter-spacing="4">
    AI ENGINEER &amp; FULL STACK DEVELOPER
  </text>

  <!-- Terminal-style tagline -->
  <rect x="350" y="205" width="500" height="28" rx="4" fill="#111" stroke="#dc2626" stroke-width="0.5" opacity="0.6"/>
  <text x="600" y="224" text-anchor="middle" fill="#ef4444" font-size="13" font-family="monospace" opacity="0.9">
    $ █ building production AI that creates real impact
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite" />
  </text>

  <!-- Bottom status bar -->
  <rect x="150" y="270" width="900" height="2" fill="url(#lineGrad)" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="5s" repeatCount="indefinite" />
  </rect>

  <text x="160" y="295" fill="#dc2626" font-size="11" font-family="monospace" opacity="0.5">📍 ISLAMABAD, PAKISTAN</text>
  <text x="450" y="295" fill="#dc2626" font-size="11" font-family="monospace" opacity="0.5">🎓 BS AI @ NUML</text>
  <text x="700" y="295" fill="#dc2626" font-size="11" font-family="monospace" opacity="0.5">🏆 URAAN HACKATHON FINALIST</text>
  <text x="940" y="295" fill="#dc2626" font-size="11" font-family="monospace" opacity="0.5">⚡ OPEN TO WORK</text>

  <!-- Pulsing dot -->
  <circle cx="930" cy="282" r="2.5" fill="#22c55e">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite" />
  </circle>
</svg>

<br/>

<!-- STATS BADGES -->
<p>
  <img src="https://komarev.com/ghpvc/?username=codewithsalty&label=PROFILE+VIEWS&color=dc2626&style=for-the-badge&labelColor=111" alt="Views"/>
  <img src="https://img.shields.io/github/followers/codewithsalty?label=FOLLOWERS&color=dc2626&style=for-the-badge&logo=github&labelColor=111" alt="Followers"/>
  <img src="https://img.shields.io/github/stars/codewithsalty?label=STARS&color=dc2626&style=for-the-badge&logo=github&labelColor=111" alt="Stars"/>
  <img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20WORK-22c55e?style=for-the-badge&labelColor=111" alt="Status"/>
</p>

<!-- ACHIEVEMENT BADGES -->
<p>
  <img src="https://img.shields.io/badge/🏆%20Uraan%20Pakistan%20Techathon-Finalist-dc2626?style=flat-square&labelColor=111" alt="Techathon"/>
  <img src="https://img.shields.io/badge/🎓%20BS%20AI-CGPA%203.56-dc2626?style=flat-square&labelColor=111" alt="CGPA"/>
  <img src="https://img.shields.io/badge/💼%205%2B-Internships-dc2626?style=flat-square&labelColor=111" alt="Internships"/>
  <img src="https://img.shields.io/badge/🛡️%20CEH%20v13-Certified-dc2626?style=flat-square&labelColor=111" alt="CEH"/>
  <img src="https://img.shields.io/badge/🎯%208%2B-Certifications-dc2626?style=flat-square&labelColor=111" alt="Certs"/>
</p>

<br/>

<!-- TYPING ANIMATION -->
<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=DC143C&center=true&vCenter=true&width=700&lines=Full+Stack+AI+Engineer+%7C+Certified+Ethical+Hacker;Building+Production-Grade+AI+Systems;LLMs+%7C+RAG+%7C+AI+Agents+%7C+NLP;Shipping+Real+Impact%2C+Not+Just+Demos" alt="Typing SVG" />
</p>

</div>

<!-- ANIMATED DIVIDER -->
<svg width="100%" height="30" viewBox="0 0 1200 30" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="d1" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent" />
    <stop offset="50%" stop-color="#dc2626" />
    <stop offset="100%" stop-color="transparent" />
  </linearGradient></defs>
  <line x1="150" y1="15" x2="1050" y2="15" stroke="url(#d1)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite" />
  </line>
  <circle cx="600" cy="15" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite" />
  </circle>
</svg>

<br/>

<!-- SNAKE CONTRIBUTION -->
<div align="center">

## 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake-dark.svg">
</picture>

</div>

<br/>

<!-- ANIMATED DIVIDER -->
<svg width="100%" height="30" viewBox="0 0 1200 30" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="d2" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent" />
    <stop offset="50%" stop-color="#dc2626" />
    <stop offset="100%" stop-color="transparent" />
  </linearGradient></defs>
  <line x1="150" y1="15" x2="1050" y2="15" stroke="url(#d2)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="1s" repeatCount="indefinite" />
  </line>
  <circle cx="600" cy="15" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2s" begin="0.5s" repeatCount="indefinite" />
  </circle>
</svg>

<br/>

## 👨‍💻 About Me

<div align="center">

<svg width="600" height="200" viewBox="0 0 600 200" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="0" width="600" height="200" rx="10" fill="#0a0a0a" stroke="#dc2626" stroke-width="1" opacity="0.8"/>
  <rect x="0" y="0" width="600" height="30" rx="10" fill="#111"/>
  <circle cx="20" cy="15" r="5" fill="#ff5f56"/>
  <circle cx="40" cy="15" r="5" fill="#ffbd2e"/>
  <circle cx="60" cy="15" r="5" fill="#27c93f"/>
  <text x="300" y="20" text-anchor="middle" fill="#888" font-size="11" font-family="monospace">salman-khan-terminal — bash</text>

  <text x="20" y="55" fill="#22c55e" font-size="13" font-family="monospace">$ <tspan fill="#dc2626">cat</tspan> about-salman.json</text>
  <text x="20" y="75" fill="#c9d1d9" font-size="13" font-family="monospace">{</text>
  <text x="35" y="95" fill="#6ba8e8" font-size="13" font-family="monospace">  "role"</text><text x="145" y="95" fill="#c9d1d9" font-size="13" font-family="monospace">: </text><text x="155" y="95" fill="#9ddc8b" font-size="13" font-family="monospace">"Full Stack AI Engineer"</text>
  <text x="35" y="115" fill="#6ba8e8" font-size="13" font-family="monospace">  "education"</text><text x="145" y="115" fill="#c9d1d9" font-size="13" font-family="monospace">: </text><text x="155" y="115" fill="#9ddc8b" font-size="13" font-family="monospace">"BS AI @ NUML, Islamabad"</text>
  <text x="35" y="135" fill="#6ba8e8" font-size="13" font-family="monospace">  "focus"</text><text x="145" y="135" fill="#c9d1d9" font-size="13" font-family="monospace">: </text><text x="155" y="135" fill="#9ddc8b" font-size="13" font-family="monospace">"LLMs, RAG, AI Agents, CV, NLP"</text>
  <text x="20" y="160" fill="#c9d1d9" font-size="13" font-family="monospace">}</text>
  <text x="20" y="185" fill="#dc2626" font-size="11" font-family="monospace" opacity="0.6">▌ Building production AI that creates real impact</text>
</svg>

</div>

<br/>

## 🚀 Featured Projects

<div align="center">

<table>
  <tr>
    <td width="50%">
      <h3>⚡ SurakshaAI</h3>
      <p><em>Uraan Pakistan Hackathon — Finalist</em></p>
      <p>AI-powered threat intelligence, video surveillance, and border anomaly detection platform for national security.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js" />
        <img src="https://img.shields.io/badge/YOLOv8-00CCFF?style=flat-square&logo=openai" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi" />
      </p>
      <p>
        <a href="https://github.com/codewithsalty/Suraksha-AI">📂 Repo</a> · <a href="https://suraksha-ai-pakistan.netlify.app">🚀 Demo</a>
      </p>
    </td>
    <td width="50%">
      <h3>🧠 NeuroAssist-Ai</h3>
      <p><em>Brain Tumor Detection & Staging</em></p>
      <p>End-to-end deep learning pipeline combining CNN for MRI classification and ANN for glioma gene mutation staging.</p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit" />
      </p>
      <p>
        <a href="https://github.com/codewithsalty/NeuroAssist-Ai">📂 Repo</a> · <a href="https://neuroassistai.vercel.app">🚀 Demo</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📚 Taleem-AI</h3>
      <p><em>AI-Powered Learning Platform</em></p>
      <p>Voice-first bilingual AI tutor with curriculum-grounded RAG, smart study suite, and gamified learning for Pakistani students.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js" />
        <img src="https://img.shields.io/badge/RAG-4285F4?style=flat-square&logo=google" />
        <img src="https://img.shields.io/badge/Voice%20AI-FF6F00?style=flat-square&logo=googleassistant" />
      </p>
      <p>
        <a href="https://github.com/codewithsalty/Taleem-AI">📂 Repo</a>
      </p>
    </td>
    <td width="50%">
      <h3>🌍 AQI Predictor</h3>
      <p><em>Real-time Air Quality Forecasting</em></p>
      <p>Serverless ML pipeline with automated hourly ingestion and daily retraining delivering real-time AQI forecasts.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi" />
        <img src="https://img.shields.io/badge/XGBoost-000?style=flat-square&logo=python" />
        <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js" />
      </p>
      <p>
        <a href="https://github.com/codewithsalty/aqi-predictor">📂 Repo</a> · <a href="https://pearls-aqi.vercel.app">🚀 Demo</a>
      </p>
    </td>
  </tr>
</table>

</div>

<br/>

## 📌 Pinned Repositories

<p align="center">
  <a href="https://github.com/codewithsalty/Suraksha-AI">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=Suraksha-AI&theme=dark&bg_color=0d1117&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=true&border_color=dc2626" />
  </a>
  <a href="https://github.com/codewithsalty/NeuroAssist-Ai">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=NeuroAssist-Ai&theme=dark&bg_color=0d1117&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=true&border_color=dc2626" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/codewithsalty/Taleem-AI">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=Taleem-AI&theme=dark&bg_color=0d1117&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=true&border_color=dc2626" />
  </a>
  <a href="https://github.com/codewithsalty/aqi-predictor">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=aqi-predictor&theme=dark&bg_color=0d1117&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=true&border_color=dc2626" />
  </a>
</p>

<br/>

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
|---|---|
| **🧠 AI/ML** | ![Python](https://img.shields.io/badge/Python-dc2626?style=flat-square&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-dc2626?style=flat-square&logo=tensorflow) ![PyTorch](https://img.shields.io/badge/PyTorch-dc2626?style=flat-square&logo=pytorch) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-dc2626?style=flat-square&logo=scikitlearn) ![OpenCV](https://img.shields.io/badge/OpenCV-dc2626?style=flat-square&logo=opencv) ![LangChain](https://img.shields.io/badge/LangChain-dc2626?style=flat-square&logo=chainlink) ![HuggingFace](https://img.shields.io/badge/HuggingFace-dc2626?style=flat-square&logo=huggingface) |
| **⚡ Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-dc2626?style=flat-square&logo=fastapi) ![Flask](https://img.shields.io/badge/Flask-dc2626?style=flat-square&logo=flask) ![Django](https://img.shields.io/badge/Django-dc2626?style=flat-square&logo=django) ![Node.js](https://img.shields.io/badge/Node.js-dc2626?style=flat-square&logo=nodedotjs) |
| **🎨 Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-dc2626?style=flat-square&logo=nextdotjs) ![React](https://img.shields.io/badge/React-dc2626?style=flat-square&logo=react) ![TypeScript](https://img.shields.io/badge/TypeScript-dc2626?style=flat-square&logo=typescript) ![Tailwind](https://img.shields.io/badge/Tailwind-dc2626?style=flat-square&logo=tailwindcss) ![Framer](https://img.shields.io/badge/Framer-dc2626?style=flat-square&logo=framer) |
| **🗄️ Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-dc2626?style=flat-square&logo=postgresql) ![MongoDB](https://img.shields.io/badge/MongoDB-dc2626?style=flat-square&logo=mongodb) ![Pinecone](https://img.shields.io/badge/Pinecone-dc2626?style=flat-square&logo=pinecone) ![Redis](https://img.shields.io/badge/Redis-dc2626?style=flat-square&logo=redis) |
| **☁️ Cloud/DevOps** | ![AWS](https://img.shields.io/badge/AWS-dc2626?style=flat-square&logo=amazonaws) ![GCP](https://img.shields.io/badge/GCP-dc2626?style=flat-square&logo=googlecloud) ![Docker](https://img.shields.io/badge/Docker-dc2626?style=flat-square&logo=docker) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-dc2626?style=flat-square&logo=githubactions) |
| **🛠️ Tools** | ![VS Code](https://img.shields.io/badge/VS_Code-dc2626?style=flat-square&logo=visualstudiocode) ![Cursor](https://img.shields.io/badge/Cursor-dc2626?style=flat-square&logo=cursor) ![Postman](https://img.shields.io/badge/Postman-dc2626?style=flat-square&logo=postman) ![n8n](https://img.shields.io/badge/n8n-dc2626?style=flat-square&logo=n8n) ![Docker](https://img.shields.io/badge/Docker-dc2626?style=flat-square&logo=docker) |

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=S4lmankhan&show_icons=true&theme=dark&bg_color=0d1117&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=true&count_private=true&include_all_commits=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=S4lmankhan&layout=compact&theme=dark&bg_color=0d1117&title_color=dc2626&text_color=c9d1d9&hide_border=true&langs_count=8&border_color=dc2626" />

<img src="https://github-readme-streak-stats.herokuapp.com?user=S4lmankhan&theme=dark&background=0d1117&ring=dc2626&fire=dc2626&currStreakLabel=dc2626&hide_border=true" />

</div>

### 📈 Contribution Graph

<img src="https://github-readme-activity-graph.vercel.app/graph?username=S4lmankhan&bg_color=0d1117&color=dc2626&line=dc2626&point=dc2626&area=true&hide_border=true&area_color=dc2626" />

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=S4lmankhan&theme=github_dark" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=S4lmankhan&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=S4lmankhan&theme=github_dark" />
</div>

<br/>

<!-- ANIMATED DIVIDER -->
<svg width="100%" height="30" viewBox="0 0 1200 30" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="d3" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent" />
    <stop offset="50%" stop-color="#dc2626" />
    <stop offset="100%" stop-color="transparent" />
  </linearGradient></defs>
  <line x1="150" y1="15" x2="1050" y2="15" stroke="url(#d3)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="2s" repeatCount="indefinite" />
  </line>
</svg>

## 🏆 Achievements

<p align="center">
  <img src="https://github.com/S4lmankhan/S4lmankhan/blob/main/.github/assets/quickdraw.png?raw=true" width="80" alt="Quickdraw"/>
  <img src="https://github.com/S4lmankhan/S4lmankhan/blob/main/.github/assets/pull-shark.png?raw=true" width="80" alt="Pull Shark"/>
  <img src="https://github.com/S4lmankhan/S4lmankhan/blob/main/.github/assets/yolo.png?raw=true" width="80" alt="YOLO"/>
  <img src="https://github.com/S4lmankhan/S4lmankhan/blob/main/.github/assets/starstruck.png?raw=true" width="80" alt="Starstruck"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=S4lmankhan&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=10" />
</p>

<details>
<summary><b>🎖️ Certifications</b></summary>
<br/>
<p align="center">
  <img src="https://img.shields.io/badge/EC--Council%20CEH%20v13-89.6%25-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/Certified%20Ethical%20Hacker-NAVTTC-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/Deep%20Learning-DeepLearning.AI-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Stanford-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/CyberSecurity-Cisco-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/CPEE-Prompt%20Engineering-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/Python%20Full%20Stack-Udemy-dc2626?style=for-the-badge&labelColor=111" />
  <img src="https://img.shields.io/badge/NSCT-89.7th%20Percentile-dc2626?style=for-the-badge&labelColor=111" />
</p>
</details>

<br/>

<!-- QUOTE -->
<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=Ship%20production%20AI%2C%20not%20just%20demos&author=Salman%20Khan&border=true&borderColor=dc2626" />
</p>

<!-- ANIMATED DIVIDER -->
<svg width="100%" height="30" viewBox="0 0 1200 30" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="d4" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent" />
    <stop offset="50%" stop-color="#dc2626" />
    <stop offset="100%" stop-color="transparent" />
  </linearGradient></defs>
  <line x1="150" y1="15" x2="1050" y2="15" stroke="url(#d4)" stroke-width="1.5" opacity="0.6" />
</svg>

## 📫 Connect With Me

<p align="center">
  <a href="mailto:codewithsalty@gmail.com">
    <img src="https://img.shields.io/badge/📧_Email-dc2626?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111" />
  </a>
  <a href="https://linkedin.com/in/s4lmankhan">
    <img src="https://img.shields.io/badge/💼_LinkedIn-dc2626?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=111" />
  </a>
  <a href="https://github.com/S4lmankhan">
    <img src="https://img.shields.io/badge/🐙_GitHub-dc2626?style=for-the-badge&logo=github&logoColor=white&labelColor=111" />
  </a>
  <a href="https://salman-khan.dev">
    <img src="https://img.shields.io/badge/🌐_Portfolio-dc2626?style=for-the-badge&logo=vercel&logoColor=white&labelColor=111" />
  </a>
  <a href="https://kaggle.com/s4lmankhan">
    <img src="https://img.shields.io/badge/📊_Kaggle-dc2626?style=for-the-badge&logo=kaggle&logoColor=white&labelColor=111" />
  </a>
</p>

<p align="center">
  <a href="https://instagram.com/codewithsalty">
    <img src="https://img.shields.io/badge/📸_Instagram-dc2626?style=for-the-badge&logo=instagram&logoColor=white&labelColor=111" />
  </a>
  <a href="https://x.com/codewithsalty">
    <img src="https://img.shields.io/badge/🐦_X/Twitter-dc2626?style=for-the-badge&logo=x&logoColor=white&labelColor=111" />
  </a>
  <a href="https://wa.me/923425646313">
    <img src="https://img.shields.io/badge/💬_WhatsApp-dc2626?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=111" />
  </a>
</p>

<br/>

<!-- ANIMATED FOOTER -->
<div align="center">

<svg width="100%" height="100" viewBox="0 0 1200 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="fGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="transparent" />
      <stop offset="50%" stop-color="#dc2626" />
      <stop offset="100%" stop-color="transparent" />
    </linearGradient>
  </defs>
  <rect x="0" y="0" width="1200" height="100" fill="#050505" rx="8"/>
  <rect x="0" y="0" width="1200" height="100" fill="url(#dotGrid)" rx="8"/>
  <line x1="200" y1="20" x2="1000" y2="20" stroke="url(#fGrad)" stroke-width="1.5" opacity="0.4">
    <animate attributeName="opacity" values="0.1;0.6;0.1" dur="5s" repeatCount="indefinite" />
  </line>
  <text x="600" y="50" text-anchor="middle" fill="#dc2626" font-size="16" font-family="monospace" opacity="0.8" letter-spacing="3">
    $ thanks_for_visiting
  </text>
  <text x="600" y="75" text-anchor="middle" fill="#666" font-size="12" font-family="monospace">
    Let's build something amazing together
  </text>
  <circle cx="550" cy="40" r="2" fill="#dc2626" opacity="0.6">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="650" cy="40" r="2" fill="#dc2626" opacity="0.6">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" begin="1s" repeatCount="indefinite" />
  </circle>
</svg>

<br/>
<sub>✨ Open to collaboration and opportunities ✨</sub>

</div>
