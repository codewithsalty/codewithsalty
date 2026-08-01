<div align="center">

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   ANIMATED HEADER BANNER               -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="100%" height="340" viewBox="0 0 900 340" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bg" cx="50%" cy="35%" r="65%">
      <stop offset="0%" stop-color="#1a0000"/>
      <stop offset="55%" stop-color="#0a0000"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7f0000"/>
      <stop offset="35%" stop-color="#dc2626"/>
      <stop offset="65%" stop-color="#ef4444"/>
      <stop offset="100%" stop-color="#7f0000"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="transparent"/>
      <stop offset="50%" stop-color="#dc2626"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="grid" width="28" height="28" patternUnits="userSpaceOnUse">
      <circle cx="14" cy="14" r="0.7" fill="#dc2626" opacity="0.10"/>
    </pattern>
  </defs>

  <rect width="900" height="340" fill="url(#bg)"/>
  <rect width="900" height="340" fill="url(#grid)"/>

  <!-- Animated corner accents -->
  <polyline points="20,60 20,20 60,20" fill="none" stroke="#dc2626" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="4s" repeatCount="indefinite"/>
  </polyline>
  <polyline points="840,20 880,20 880,60" fill="none" stroke="#dc2626" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="4s" begin="0.5s" repeatCount="indefinite"/>
  </polyline>
  <polyline points="20,280 20,320 60,320" fill="none" stroke="#dc2626" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="4s" begin="1s" repeatCount="indefinite"/>
  </polyline>
  <polyline points="840,320 880,320 880,280" fill="none" stroke="#dc2626" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="4s" begin="1.5s" repeatCount="indefinite"/>
  </polyline>

  <!-- Horizontal scan lines -->
  <line x1="60" y1="40" x2="400" y2="40" stroke="url(#lineGrad)" stroke-width="1" opacity="0.5">
    <animate attributeName="x1" values="40;80;40" dur="5s" repeatCount="indefinite"/>
  </line>
  <line x1="500" y1="40" x2="840" y2="40" stroke="url(#lineGrad)" stroke-width="1" opacity="0.5">
    <animate attributeName="x2" values="860;820;860" dur="5s" repeatCount="indefinite"/>
  </line>

  <!-- Glowing shield icon -->
  <g transform="translate(450,75)" filter="url(#glow)">
    <path d="M0,-28 L20,-14 L20,12 Q20,32 0,40 Q-20,32 -20,12 L-20,-14 Z" fill="none" stroke="#dc2626" stroke-width="2">
      <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/>
    </path>
    <text y="8" text-anchor="middle" fill="#dc2626" font-size="14" font-family="monospace">AI</text>
  </g>

  <!-- NAME -->
  <text x="450" y="155" text-anchor="middle" fill="url(#nameGrad)"
        font-size="52" font-weight="900" font-family="'Segoe UI',Arial,sans-serif" letter-spacing="8" filter="url(#glow)">
    SALMAN KHAN
    <animate attributeName="opacity" values="0.85;1;0.85" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- Subtitle -->
  <text x="450" y="193" text-anchor="middle" fill="#ef4444"
        font-size="14" font-family="'Courier New',monospace" letter-spacing="5" opacity="0.9">
    AI ENGINEER  ·  FULL STACK DEVELOPER  ·  FOUNDER
  </text>

  <!-- Terminal tagline box -->
  <rect x="220" y="212" width="460" height="30" rx="5" fill="#0d0000" stroke="#dc2626" stroke-width="0.8" opacity="0.8"/>
  <text x="450" y="231" text-anchor="middle" fill="#ef4444" font-size="12" font-family="'Courier New',monospace">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
    $ ship production AI — not just demos █
  </text>

  <!-- Bottom divider line -->
  <line x1="100" y1="278" x2="800" y2="278" stroke="url(#lineGrad)" stroke-width="1">
    <animate attributeName="opacity" values="0.2;0.7;0.2" dur="5s" repeatCount="indefinite"/>
  </line>

  <!-- Status bar -->
  <circle cx="118" cy="298" r="3" fill="#22c55e">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <text x="128" y="302" fill="#6b7280" font-size="11" font-family="'Courier New',monospace">📍 ISLAMABAD, PK</text>
  <text x="300" y="302" fill="#6b7280" font-size="11" font-family="'Courier New',monospace">🎓 BS AI · NUML</text>
  <text x="445" y="302" fill="#6b7280" font-size="11" font-family="'Courier New',monospace">🏆 URAAN FINALIST</text>
  <text x="610" y="302" fill="#6b7280" font-size="11" font-family="'Courier New',monospace">🛡️ CEH v13 CERTIFIED</text>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                      BADGES ROW                        -->
<!-- ═══════════════════════════════════════════════════════ -->

[![Profile Views](https://komarev.com/ghpvc/?username=S4lmankhan&label=PROFILE+VIEWS&color=dc2626&style=for-the-badge&labelColor=0d0000)](https://github.com/S4lmankhan)
[![Followers](https://img.shields.io/github/followers/S4lmankhan?label=FOLLOWERS&color=dc2626&style=for-the-badge&logo=github&labelColor=0d0000)](https://github.com/S4lmankhan?tab=followers)
[![Stars](https://img.shields.io/github/stars/S4lmankhan?label=STARS&color=dc2626&style=for-the-badge&logo=github&labelColor=0d0000)](https://github.com/S4lmankhan)
[![Status](https://img.shields.io/badge/STATUS-OPEN%20TO%20WORK-22c55e?style=for-the-badge&labelColor=0d0000)](https://linkedin.com/in/s4lmankhan)

<br/>

<!-- Achievement pills -->
[![Techathon](https://img.shields.io/badge/🏆_Uraan_Pakistan_Techathon-Finalist-dc2626?style=flat-square&labelColor=111)](https://github.com/S4lmankhan)
[![CGPA](https://img.shields.io/badge/🎓_BS_AI-CGPA_3.56-dc2626?style=flat-square&labelColor=111)](https://github.com/S4lmankhan)
[![Internships](https://img.shields.io/badge/💼_5%2B-Internships-dc2626?style=flat-square&labelColor=111)](https://github.com/S4lmankhan)
[![CEH](https://img.shields.io/badge/🛡️_CEH_v13-Certified-dc2626?style=flat-square&labelColor=111)](https://github.com/S4lmankhan)
[![Certs](https://img.shields.io/badge/🎯_8%2B-Certifications-dc2626?style=flat-square&labelColor=111)](https://github.com/S4lmankhan)

<br/>

<!-- Typing animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=DC2626&center=true&vCenter=true&width=750&lines=Full+Stack+AI+Engineer+%7C+Ethical+Hacker;LLMs+%E2%80%A2+RAG+%E2%80%A2+AI+Agents+%E2%80%A2+Computer+Vision;Building+Production-Grade+AI+Systems;Founder+%40+Surveillix+AI;Shipping+Real+Impact%2C+Not+Just+Demos)](https://git.io/typing-svg)

</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    ANIMATED DIVIDER                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv1" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv1)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite"/>
  </line>
  <circle cx="450" cy="12" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

## 🐍 Contribution Snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake.svg">
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv2" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv2)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="1s" repeatCount="indefinite"/>
  </line>
  <circle cx="450" cy="12" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2.2s" begin="0.4s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

## 👨‍💻 About Me

<div align="center">

<!-- ANIMATED TERMINAL + DOT PORTRAIT SIDE BY SIDE -->
<table border="0" cellspacing="0" cellpadding="0">
<tr>
<td valign="top" width="260">

<!-- DOT MATRIX PORTRAIT - hosted from repo -->
<img src="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/main/assets/salman_dots.svg" width="240" alt="Salman Khan"/>

</td>
<td valign="top" width="20"></td>
<td valign="top">

<!-- TERMINAL CARD -->
<svg width="420" height="260" viewBox="0 0 420 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="tBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d0000"/>
      <stop offset="100%" stop-color="#000000"/>
    </linearGradient>
  </defs>
  <rect x="0" y="0" width="420" height="260" rx="10" fill="url(#tBg)" stroke="#dc2626" stroke-width="1" opacity="0.9"/>
  <!-- Title bar -->
  <rect x="0" y="0" width="420" height="32" rx="10" fill="#1a0000"/>
  <rect x="0" y="20" width="420" height="12" fill="#1a0000"/>
  <circle cx="18" cy="16" r="5" fill="#ff5f56"/>
  <circle cx="36" cy="16" r="5" fill="#ffbd2e"/>
  <circle cx="54" cy="16" r="5" fill="#27c93f"/>
  <text x="210" y="21" text-anchor="middle" fill="#666" font-size="11" font-family="'Courier New',monospace">salman@terminal ~ ./profile --live</text>
  <!-- Live dot -->
  <circle cx="395" cy="16" r="4" fill="#22c55e">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="1.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Content -->
  <text x="18" y="58" fill="#dc2626" font-size="11" font-family="'Courier New',monospace">SYSTEM.INFO</text>
  <rect x="110" y="48" width="160" height="18" rx="3" fill="#dc2626"/>
  <text x="190" y="61" text-anchor="middle" fill="#fff" font-size="10" font-family="'Courier New',monospace">codewithsalty@gmail.com</text>

  <text x="18" y="82" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Subject</text>
  <text x="18" y="82" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="82" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Salman Khan</text>

  <text x="18" y="98" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Role</text>
  <text x="18" y="98" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="98" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Full Stack AI Engineer</text>

  <text x="18" y="114" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Origin</text>
  <text x="18" y="114" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="114" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Islamabad, Pakistan</text>

  <text x="18" y="130" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Education</text>
  <text x="18" y="130" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="130" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">BS AI · NUML</text>

  <text x="18" y="146" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Status</text>
  <text x="18" y="146" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="146" text-anchor="end" fill="#22c55e" font-size="10.5" font-family="'Courier New',monospace">Open to Work</text>

  <text x="18" y="165" fill="#555" font-size="10" font-family="'Courier New',monospace">- Stack</text>

  <text x="18" y="181" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.AI</text>
  <text x="18" y="181" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="181" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">LangChain · RAG · YOLO · NLP</text>

  <text x="18" y="197" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.Backend</text>
  <text x="18" y="197" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="197" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">FastAPI · Django · Node.js</text>

  <text x="18" y="213" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.Frontend</text>
  <text x="18" y="213" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="213" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Next.js · React · Tailwind</text>

  <text x="18" y="229" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.Infra</text>
  <text x="18" y="229" fill="#3d3030" font-size="10.5" font-family="'Courier New',monospace" dx="60">·················</text>
  <text x="408" y="229" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Docker · AWS · GCP · Vercel</text>

  <text x="18" y="250" fill="#555" font-size="10" font-family="'Courier New',monospace">▸ Projects below in README ↓</text>
  <!-- blinking cursor -->
  <rect x="212" y="240" width="7" height="12" fill="#dc2626">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

</td>
</tr>
</table>

</div>

<br/>

```python
class SalmanKhan:
    def __init__(self):
        self.role       = "Full Stack AI Engineer"
        self.education  = "BS Artificial Intelligence @ NUML, Islamabad"
        self.cgpa       = 3.56
        self.certs      = ["CEH v13 (89.6%)", "Deep Learning – DeepLearning.AI",
                           "ML – Stanford", "CyberSecurity – Cisco", "CPEE", "8+ total"]
        self.expertise  = ["LLMs", "RAG", "AI Agents", "NLP", "Computer Vision"]
        self.founder_of = "Surveillix AI — edge-based retail surveillance for SMEs"

    def current_focus(self):
        return {
            "building" : ["AI Agents", "Voice AI", "Multi-modal Systems"],
            "learning" : ["Advanced RAG", "MCP Integration", "LLM Fine-tuning"],
            "exploring": ["Blockchain", "Decentralized AI"],
            "mission"  : "Ship production AI that creates real impact 🚀"
        }

    def experience(self):
        return [
            "AI Engineer @ DevRolin",
            "ML Engineer @ Elevvo Pathways",
            "Python Developer @ CosmiCode",
            "Graphic Designer @ MixDia UK",
            "5+ freelance projects on Fiverr & Upwork"
        ]
```

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv3" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv3)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="2s" repeatCount="indefinite"/>
  </line>
</svg>

<br/>

## 🚀 Featured Projects

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### ⚡ SurakshaAI
*🏆 Uraan Pakistan Techathon — Finalist*

AI-powered threat intelligence and video surveillance platform for national security — real-time border anomaly detection with YOLOv8.

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-dc2626?style=flat-square&logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/Suraksha-AI) · [🚀 Demo](https://suraksha-ai-pakistan.netlify.app)

</td>
<td width="50%" valign="top">

### 🧠 NeuroAssist-AI
*Brain Tumor Detection & Staging*

End-to-end deep learning pipeline — CNN for MRI classification + ANN for glioma gene mutation staging with 99%+ accuracy.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-dc2626?style=flat-square&logo=keras&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/NeuroAssist-Ai) · [🚀 Demo](https://neuroassistai.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 Taleem-AI
*AI-Powered Learning Platform*

Voice-first bilingual AI tutor with curriculum-grounded RAG, smart study suite, and gamified learning — built for Pakistani students.

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-dc2626?style=flat-square&logo=chainlink&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-dc2626?style=flat-square&logo=pinecone&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/Taleem-AI)

</td>
<td width="50%" valign="top">

### 🌍 AQI Predictor
*Real-time Air Quality Forecasting*

Serverless ML pipeline with automated hourly ingestion and daily retraining — live AQI forecasts with XGBoost.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-dc2626?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/aqi-predictor) · [🚀 Demo](https://pearls-aqi.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ Surveillix AI
*Edge AI Surveillance — FYP*

Edge-based retail surveillance system targeting Pakistan's SMEs — real-time theft detection, footfall analytics, and behaviour analysis.

![YOLOv8](https://img.shields.io/badge/YOLOv8-dc2626?style=flat-square&logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)

[📂 Repo](https://github.com/S4lmankhan)

</td>
<td width="50%" valign="top">

### 🔊 CallRolin
*Real-time Voice AI Agent*

Production voice-to-voice AI agent handling inbound customer support calls at scale — multi-lingual with sub-second latency.

![Whisper](https://img.shields.io/badge/Whisper-dc2626?style=flat-square&logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-111?style=flat-square&logo=socket.io&logoColor=white)

[📂 Repo](https://github.com/S4lmankhan)

</td>
</tr>
</table>

</div>

<!-- Pinned repo cards -->
<div align="center">

<a href="https://github.com/codewithsalty/Suraksha-AI">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=Suraksha-AI&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626" />
</a>
<a href="https://github.com/codewithsalty/NeuroAssist-Ai">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=NeuroAssist-Ai&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626" />
</a>
<a href="https://github.com/codewithsalty/Taleem-AI">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=Taleem-AI&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626" />
</a>
<a href="https://github.com/codewithsalty/aqi-predictor">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=aqi-predictor&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626" />
</a>

</div>

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv4" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv4)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="0.5s" repeatCount="indefinite"/>
  </line>
  <circle cx="450" cy="12" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2.2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

## 🛠️ Tech Stack

<div align="center">

<!-- AI / ML -->
<p>
<img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch&theme=dark" />
</p>
<p>
<img src="https://img.shields.io/badge/LangChain-dc2626?style=for-the-badge&logo=chainlink&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/LangGraph-dc2626?style=for-the-badge&logo=chainlink&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/HuggingFace-dc2626?style=for-the-badge&logo=huggingface&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/OpenCV-dc2626?style=for-the-badge&logo=opencv&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/YOLOv8-dc2626?style=for-the-badge&logo=openai&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/Scikit--Learn-dc2626?style=for-the-badge&logo=scikitlearn&logoColor=white&labelColor=0d0000"/>
</p>

<!-- Backend -->
<p>
<img src="https://skillicons.dev/icons?i=fastapi,django,flask,nodejs&theme=dark" />
</p>

<!-- Frontend -->
<p>
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind&theme=dark" />
</p>

<!-- Databases -->
<p>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis&theme=dark" />
</p>
<p>
<img src="https://img.shields.io/badge/Pinecone-dc2626?style=for-the-badge&logo=pinecone&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/Qdrant-dc2626?style=for-the-badge&logo=databricks&logoColor=white&labelColor=0d0000"/>
</p>

<!-- Cloud / DevOps -->
<p>
<img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,git,github&theme=dark" />
</p>
<p>
<img src="https://img.shields.io/badge/GitHub_Actions-dc2626?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/Vercel-dc2626?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d0000"/>
<img src="https://img.shields.io/badge/n8n-dc2626?style=for-the-badge&logo=n8n&logoColor=white&labelColor=0d0000"/>
</p>

<!-- Tools -->
<p>
<img src="https://skillicons.dev/icons?i=vscode,postman,figma,linux&theme=dark" />
</p>

</div>

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv5" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv5)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="1.5s" repeatCount="indefinite"/>
  </line>
  <circle cx="450" cy="12" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=S4lmankhan&show_icons=true&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626&count_private=true&include_all_commits=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=S4lmankhan&layout=compact&theme=dark&bg_color=0d0000&title_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626&langs_count=8"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=S4lmankhan&theme=dark&background=0d0000&ring=dc2626&fire=ef4444&currStreakLabel=dc2626&hide_border=false&border=dc2626"/>

</div>

### 📈 Contribution Graph

<img src="https://github-readme-activity-graph.vercel.app/graph?username=S4lmankhan&bg_color=0d0000&color=dc2626&line=dc2626&point=ef4444&area=true&hide_border=false&border_color=dc2626&area_color=3d0000"/>

<div align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=S4lmankhan&theme=github_dark"/>
<br/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=S4lmankhan&theme=github_dark"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=S4lmankhan&theme=github_dark"/>
</div>

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv6" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv6)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="2.5s" repeatCount="indefinite"/>
  </line>
</svg>

<br/>

## 🏆 Trophies & Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=S4lmankhan&theme=darkhub&no-frame=false&no-bg=true&column=7&margin-w=8&title=MultiLanguage,Commits,Repositories,Stars,Followers,PullRequest,Issues"/>

<br/><br/>

<details>
<summary><b>🎖️ Certifications — Click to expand</b></summary>
<br/>

![CEH](https://img.shields.io/badge/EC--Council_CEH_v13-89.6%25-dc2626?style=for-the-badge&labelColor=0d0000)
![NAVTTC](https://img.shields.io/badge/Ethical_Hacker-NAVTTC-dc2626?style=for-the-badge&labelColor=0d0000)
![DeepLearning](https://img.shields.io/badge/Deep_Learning-DeepLearning.AI-dc2626?style=for-the-badge&labelColor=0d0000)
![Stanford](https://img.shields.io/badge/Machine_Learning-Stanford-dc2626?style=for-the-badge&labelColor=0d0000)
![Cisco](https://img.shields.io/badge/CyberSecurity-Cisco-dc2626?style=for-the-badge&labelColor=0d0000)
![CPEE](https://img.shields.io/badge/CPEE-Prompt_Engineering-dc2626?style=for-the-badge&labelColor=0d0000)
![Udemy](https://img.shields.io/badge/Python_Full_Stack-Udemy-dc2626?style=for-the-badge&labelColor=0d0000)
![NSCT](https://img.shields.io/badge/NSCT-89.7th_Percentile-dc2626?style=for-the-badge&labelColor=0d0000)

</details>

</div>

<svg width="100%" height="24" viewBox="0 0 900 24" xmlns="http://www.w3.org/2000/svg">
  <defs><linearGradient id="dv7" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#dc2626"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient></defs>
  <line x1="50" y1="12" x2="850" y2="12" stroke="url(#dv7)" stroke-width="1.5">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" begin="3s" repeatCount="indefinite"/>
  </line>
  <circle cx="450" cy="12" r="3" fill="#dc2626">
    <animate attributeName="r" values="2;5;2" dur="2.6s" begin="1.2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

## 📫 Connect With Me

<div align="center">

[![Email](https://img.shields.io/badge/Email-dc2626?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0000)](mailto:codewithsalty@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dc2626?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0000)](https://linkedin.com/in/s4lmankhan)
[![GitHub](https://img.shields.io/badge/GitHub-dc2626?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0000)](https://github.com/S4lmankhan)
[![Portfolio](https://img.shields.io/badge/Portfolio-dc2626?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d0000)](https://salman-khan.dev)
[![Kaggle](https://img.shields.io/badge/Kaggle-dc2626?style=for-the-badge&logo=kaggle&logoColor=white&labelColor=0d0000)](https://kaggle.com/s4lmankhan)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-dc2626?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=0d0000)](https://wa.me/923425646313)

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   ANIMATED FOOTER                      -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="90" viewBox="0 0 900 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="ftBg" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="#1a0000"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>
    <linearGradient id="ftLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="transparent"/>
      <stop offset="50%" stop-color="#dc2626"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>
    <pattern id="ftDot" width="28" height="28" patternUnits="userSpaceOnUse">
      <circle cx="14" cy="14" r="0.6" fill="#dc2626" opacity="0.10"/>
    </pattern>
  </defs>
  <rect width="900" height="90" rx="8" fill="url(#ftBg)"/>
  <rect width="900" height="90" rx="8" fill="url(#ftDot)"/>
  <line x1="100" y1="18" x2="800" y2="18" stroke="url(#ftLine)" stroke-width="1">
    <animate attributeName="opacity" values="0.1;0.6;0.1" dur="5s" repeatCount="indefinite"/>
  </line>
  <text x="450" y="48" text-anchor="middle" fill="#dc2626" font-size="15" font-family="'Courier New',monospace" letter-spacing="3">
    $ thanks_for_visiting
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="70" text-anchor="middle" fill="#555" font-size="12" font-family="'Courier New',monospace">
    Let's build something amazing together
  </text>
  <circle cx="400" cy="38" r="2" fill="#dc2626">
    <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="38" r="2" fill="#dc2626">
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>
</svg>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=4000&pause=1000&color=DC2626&center=true&vCenter=true&width=600&lines=Thanks+for+visiting!+%E2%9D%A4%EF%B8%8F;Let's+build+something+amazing+together!+%F0%9F%9A%80;Open+to+collaboration+and+opportunities!+%F0%9F%A4%9D)](https://git.io/typing-svg)

</div>
