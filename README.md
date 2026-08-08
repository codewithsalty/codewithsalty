<div align="center">

<!-- ╔══════════════════════════════════════════════════════╗ -->
<!--                  HERO BANNER                           -->
<!-- ╚══════════════════════════════════════════════════════╝ -->

<svg width="800" height="300" viewBox="0 0 800 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bg" cx="50%" cy="40%" r="65%">
      <stop offset="0%"   stop-color="#1c0000"/>
      <stop offset="60%"  stop-color="#0a0000"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#7f0000"/>
      <stop offset="40%"  stop-color="#dc2626"/>
      <stop offset="70%"  stop-color="#f87171"/>
      <stop offset="100%" stop-color="#7f0000"/>
    </linearGradient>
    <linearGradient id="sweep" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="transparent"/>
      <stop offset="50%"  stop-color="#dc2626"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="dots" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="12" cy="12" r="0.6" fill="#dc2626" opacity="0.08"/>
    </pattern>
  </defs>

  <rect width="800" height="300" fill="url(#bg)"/>
  <rect width="800" height="300" fill="url(#dots)"/>

  <!-- Corner brackets -->
  <polyline points="14,48 14,14 48,14" fill="none" stroke="#dc2626" stroke-width="1.8">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3.5s" repeatCount="indefinite"/>
  </polyline>
  <polyline points="752,14 786,14 786,48" fill="none" stroke="#dc2626" stroke-width="1.8">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3.5s" begin="0.6s" repeatCount="indefinite"/>
  </polyline>
  <polyline points="14,252 14,286 48,286" fill="none" stroke="#dc2626" stroke-width="1.8">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3.5s" begin="1.2s" repeatCount="indefinite"/>
  </polyline>
  <polyline points="752,286 786,286 786,252" fill="none" stroke="#dc2626" stroke-width="1.8">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="3.5s" begin="1.8s" repeatCount="indefinite"/>
  </polyline>

  <!-- Top sweep lines -->
  <line x1="60" y1="34" x2="340" y2="34" stroke="url(#sweep)" stroke-width="1" opacity="0.5">
    <animate attributeName="opacity" values="0.2;0.7;0.2" dur="4s" repeatCount="indefinite"/>
  </line>
  <line x1="460" y1="34" x2="740" y2="34" stroke="url(#sweep)" stroke-width="1" opacity="0.5">
    <animate attributeName="opacity" values="0.2;0.7;0.2" dur="4s" begin="0.4s" repeatCount="indefinite"/>
  </line>

  <!-- Shield icon -->
  <g transform="translate(400,72)" filter="url(#glow)">
    <path d="M0,-24 L18,-12 L18,10 Q18,28 0,34 Q-18,28 -18,10 L-18,-12 Z"
          fill="none" stroke="#dc2626" stroke-width="1.8">
      <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.8s" repeatCount="indefinite"/>
    </path>
    <text y="7" text-anchor="middle" fill="#dc2626" font-size="11"
          font-family="'Courier New',monospace" font-weight="700">AI</text>
  </g>

  <!-- NAME -->
  <text x="400" y="140" text-anchor="middle"
        fill="url(#nameGrad)"
        font-size="48" font-weight="900"
        font-family="'Segoe UI',Arial,sans-serif"
        letter-spacing="10" filter="url(#glow)">
    SALMAN KHAN
    <animate attributeName="opacity" values="0.85;1;0.85" dur="3.5s" repeatCount="indefinite"/>
  </text>

  <!-- Role line -->
  <text x="400" y="172" text-anchor="middle"
        fill="#ef4444" font-size="13"
        font-family="'Courier New',monospace"
        letter-spacing="4" opacity="0.88">
    AI ENGINEER  ·  FULL STACK DEVELOPER  ·  FOUNDER
  </text>

  <!-- Terminal box -->
  <rect x="210" y="190" width="380" height="28" rx="4"
        fill="#0d0000" stroke="#dc2626" stroke-width="0.8" opacity="0.85"/>
  <text x="400" y="208" text-anchor="middle"
        fill="#ef4444" font-size="12"
        font-family="'Courier New',monospace">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
    $ ship production AI — not just demos █
  </text>

  <!-- Bottom rule -->
  <line x1="80" y1="244" x2="720" y2="244" stroke="url(#sweep)" stroke-width="1">
    <animate attributeName="opacity" values="0.15;0.6;0.15" dur="5s" repeatCount="indefinite"/>
  </line>

  <!-- Status bar -->
  <circle cx="98" cy="263" r="3" fill="#22c55e">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="1.6s" repeatCount="indefinite"/>
  </circle>
  <text x="108" y="267" fill="#555" font-size="10.5" font-family="'Courier New',monospace">📍 ISLAMABAD, PK</text>
  <text x="255" y="267" fill="#555" font-size="10.5" font-family="'Courier New',monospace">🎓 BS AI · NUML · 3.56</text>
  <text x="420" y="267" fill="#555" font-size="10.5" font-family="'Courier New',monospace">🏆 URAAN FINALIST</text>
  <text x="566" y="267" fill="#555" font-size="10.5" font-family="'Courier New',monospace">🛡️ CEH v13</text>
</svg>

<br/>

<!-- Badges -->
[![Profile Views](https://komarev.com/ghpvc/?username=S4lmankhan&label=PROFILE+VIEWS&color=dc2626&style=for-the-badge&labelColor=0d0000)](https://github.com/S4lmankhan)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-dc2626?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0000)](https://linkedin.com/in/s4lmankhan)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-dc2626?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d0000)](https://salman-khan.dev)
[![Open to Work](https://img.shields.io/badge/OPEN%20TO%20WORK-22c55e?style=for-the-badge&labelColor=0d0000)](https://linkedin.com/in/s4lmankhan)

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2600&pause=900&color=DC2626&center=true&vCenter=true&width=720&lines=Full+Stack+AI+Engineer+%7C+Certified+Ethical+Hacker;LLMs+%E2%80%A2+RAG+%E2%80%A2+AI+Agents+%E2%80%A2+Computer+Vision;Agentic+Workflows+%E2%80%A2+Voice+AI+%E2%80%A2+NLP;Building+Production+AI+%E2%80%94+Not+Just+Demos)](https://git.io/typing-svg)

</div>

---

## 🐍 Contribution Activity

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake.svg">
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>

---


## 👨‍💻 About Me

<div align="center">

<table border="0" cellpadding="0" cellspacing="0">
<tr>
<td width="240" align="center" valign="middle">

<!-- Dot-matrix portrait — upload salman_dots.svg to assets/ in your repo -->
<img src="https://raw.githubusercontent.com/S4lmankhan/S4lmankhan/main/assets/salman_dots.svg" width="220" alt="Salman Khan"/>

</td>
<td width="16"></td>
<td valign="top">

<!-- TERMINAL CARD matching the Arif Hasan style -->
<svg width="440" height="272" viewBox="0 0 440 272" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="tBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#110000"/>
      <stop offset="100%" stop-color="#060000"/>
    </linearGradient>
  </defs>

  <!-- Card body -->
  <rect x="0" y="0" width="440" height="272" rx="10"
        fill="url(#tBg)" stroke="#dc2626" stroke-width="1"/>

  <!-- Title bar -->
  <rect x="0" y="0" width="440" height="34" rx="10" fill="#1a0000"/>
  <rect x="0" y="24"  width="440" height="10" fill="#1a0000"/>
  <circle cx="18" cy="17" r="5" fill="#ff5f56"/>
  <circle cx="36" cy="17" r="5" fill="#ffbd2e"/>
  <circle cx="54" cy="17" r="5" fill="#27c93f"/>
  <text x="220" y="22" text-anchor="middle"
        fill="#555" font-size="11" font-family="'Courier New',monospace">
    salman@terminal — ./profile.sh --live
  </text>

  <!-- Live indicator -->
  <text x="408" y="16" text-anchor="end" fill="#555" font-size="10" font-family="'Courier New',monospace">● LIVE</text>
  <circle cx="412" cy="12" r="3.5" fill="#dc2626">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.6s" repeatCount="indefinite"/>
  </circle>

  <!-- Email pill -->
  <rect x="14" y="44" width="172" height="18" rx="3" fill="#dc2626"/>
  <text x="100" y="56.5" text-anchor="middle"
        fill="#fff" font-size="10" font-family="'Courier New',monospace">
    codewithsalty@gmail.com
  </text>

  <!-- Info rows — key · · · value -->
  <!-- Row helper: y positions 82 98 114 130 146 -->
  <text x="14"  y="84" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Subject</text>
  <text x="76"  y="84" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="84" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Salman Khan</text>

  <text x="14"  y="101" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Role</text>
  <text x="76"  y="101" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="101" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Full Stack AI Engineer</text>

  <text x="14"  y="118" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Origin</text>
  <text x="76"  y="118" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="118" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Islamabad, Pakistan</text>

  <text x="14"  y="135" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Education</text>
  <text x="76"  y="135" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="135" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">BS AI · NUML · CGPA 3.56</text>

  <text x="14"  y="152" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Status</text>
  <text x="76"  y="152" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="152" text-anchor="end" fill="#22c55e" font-size="10.5" font-family="'Courier New',monospace">Open to Work</text>

  <!-- Stack section -->
  <text x="14" y="170" fill="#3d1010" font-size="10" font-family="'Courier New',monospace">─── Stack ───────────────────────────────────</text>

  <text x="14"  y="187" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.AI</text>
  <text x="76"  y="187" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="187" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">LangChain · RAG · YOLOv8 · NLP</text>

  <text x="14"  y="204" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.Backend</text>
  <text x="76"  y="204" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="204" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">FastAPI · Django · Flask</text>

  <text x="14"  y="221" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.Frontend</text>
  <text x="76"  y="221" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="221" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Next.js · React · Tailwind</text>

  <text x="14"  y="238" fill="#dc2626" font-size="10.5" font-family="'Courier New',monospace">Core.Infra</text>
  <text x="76"  y="238" fill="#2a1010" font-size="10.5" font-family="'Courier New',monospace">·····················</text>
  <text x="426" y="238" text-anchor="end" fill="#e6edf3" font-size="10.5" font-family="'Courier New',monospace">Docker · AWS · GCP · Azure</text>

  <!-- Footer line -->
  <text x="14" y="258" fill="#3d1010" font-size="9.5" font-family="'Courier New',monospace">
    ▸ Projects &amp; stats below in README ↓
  </text>
  <rect x="240" y="248" width="7" height="11" fill="#dc2626">
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
    role       = "Full Stack AI Engineer"
    education  = "BS Artificial Intelligence @ NUML  |  CGPA: 3.56"
    location   = "Islamabad, Pakistan"
    expertise  = ["Agentic Workflows", "RAG Systems", "Voice AI",
                  "Computer Vision", "LLM Fine-tuning", "NLP"]
    certCEH    = "EC-Council CEH v13  —  89.6%"
    founder_of = "Surveillix AI  —  edge-based retail surveillance for PK SMEs"
    mission    = "Ship production AI that creates real impact 🚀"
```

---


## 🚀 Featured Projects

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

**⚡ Cyber4ce AI (SurakshaAI)**
*🏆 Uraan Pakistan Techathon — Finalist*

Defense intelligence platform with real-time video surveillance at 30 FPS, 92% drone recall (YOLOv8/v11) and a DistilBERT phishing module at 90% F1.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-dc2626?style=flat-square&logo=openai&logoColor=white)
![DistilBERT](https://img.shields.io/badge/DistilBERT-dc2626?style=flat-square&logo=huggingface&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/Suraksha-AI) · [🚀 Demo](https://suraksha-ai-pakistan.netlify.app)

</td>
<td width="50%" valign="top">

**🧠 NeuroAssist AI**
*Brain Tumor Detection — 99.2% Accuracy*

ANN-CNN hybrid classifying glioma, meningioma and pituitary tumors from 3,000+ MRIs via data augmentation.

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-dc2626?style=flat-square&logo=keras&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/NeuroAssist-Ai) · [🚀 Demo](https://neuroassistai.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📚 Taleem AI**
*Bilingual RAG Learning Platform*

Voice-first AI tutor with curriculum-grounded RAG, auto quiz/flashcard generation and gamified progression — boosted engagement 20%.

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-dc2626?style=flat-square&logo=chainlink&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Groq](https://img.shields.io/badge/Groq_API-dc2626?style=flat-square&logo=openai&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/Taleem-AI)

</td>
<td width="50%" valign="top">

**🌍 Pearls AQI Predictor**
*Real-time Air Quality Forecasting*

Serverless ML pipeline with automated hourly ingestion, daily retraining and sub-85ms FastAPI inference serving 72-hour AQI forecasts.

![XGBoost](https://img.shields.io/badge/XGBoost-dc2626?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

[📂 Repo](https://github.com/codewithsalty/aqi-predictor) · [🚀 Demo](https://pearls-aqi.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔊 CallRolin Voice Agent**
*Production Voice AI — 50+ Live Calls*

Voice-to-voice agent with custom Urdu dataset, Piper TTS migration reducing latency by 40% (500ms→300ms), cutting wait times 60%.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-111?style=flat-square&logo=socket.io&logoColor=white)

[📂 Repo](https://github.com/codewithsalty)

</td>
<td width="50%" valign="top">

**🛡️ Surveillix AI**
*Edge Surveillance — FYP / Founder*

Edge-based retail AI for Pakistani SMEs — theft detection, footfall analytics and behaviour analysis running on-device.

![YOLOv8](https://img.shields.io/badge/YOLOv8-dc2626?style=flat-square&logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[📂 Repo](https://github.com/S4lmankhan)

</td>
</tr>
</table>
</div>

<!-- Pinned cards -->
<div align="center">

[![SurakshaAI](https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=Suraksha-AI&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626)](https://github.com/codewithsalty/Suraksha-AI)
[![NeuroAssist](https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=NeuroAssist-Ai&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626)](https://github.com/codewithsalty/NeuroAssist-Ai)
[![TaleemAI](https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=Taleem-AI&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626)](https://github.com/codewithsalty/Taleem-AI)
[![AQI](https://github-readme-stats.vercel.app/api/pin/?username=codewithsalty&repo=aqi-predictor&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626)](https://github.com/codewithsalty/aqi-predictor)

</div>

---

## 🛠️ Tech Stack

<div align="center">

<!-- Row 1: Languages -->
<img src="https://skillicons.dev/icons?i=python,cpp,java,js,ts,html,css,bash&theme=dark&perline=8" />

<!-- Row 2: AI / ML -->
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,sklearn,opencv&theme=dark&perline=8" />
<br/>
<img src="https://img.shields.io/badge/LangChain-dc2626?style=flat-square&logo=chainlink&logoColor=white&labelColor=0d0000" />
<img src="https://img.shields.io/badge/LangGraph-dc2626?style=flat-square&logo=chainlink&logoColor=white&labelColor=0d0000" />
<img src="https://img.shields.io/badge/HuggingFace-dc2626?style=flat-square&logo=huggingface&logoColor=white&labelColor=0d0000" />
<img src="https://img.shields.io/badge/YOLOv8-dc2626?style=flat-square&logo=openai&logoColor=white&labelColor=0d0000" />
<img src="https://img.shields.io/badge/RAG-dc2626?style=flat-square&logo=databricks&logoColor=white&labelColor=0d0000" />
<img src="https://img.shields.io/badge/Whisper-dc2626?style=flat-square&logo=openai&logoColor=white&labelColor=0d0000" />

<!-- Row 3: Backend -->
<img src="https://skillicons.dev/icons?i=fastapi,django,flask,nodejs&theme=dark&perline=8" />

<!-- Row 4: Frontend -->
<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,figma&theme=dark&perline=8" />

<!-- Row 5: Databases -->
<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,firebase&theme=dark&perline=8" />

<!-- Row 6: Cloud & DevOps -->
<img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,git,github,linux&theme=dark&perline=8" />

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=S4lmankhan&show_icons=true&theme=dark&bg_color=0d0000&title_color=dc2626&icon_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626&count_private=true&include_all_commits=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=S4lmankhan&layout=compact&theme=dark&bg_color=0d0000&title_color=dc2626&text_color=c9d1d9&hide_border=false&border_color=dc2626&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=S4lmankhan&theme=dark&background=0d0000&ring=dc2626&fire=ef4444&currStreakLabel=dc2626&hide_border=false&border=dc2626" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=S4lmankhan&bg_color=0d0000&color=dc2626&line=dc2626&point=ef4444&area=true&hide_border=false&border_color=dc2626&area_color=1a0000" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=S4lmankhan&theme=github_dark" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=S4lmankhan&theme=github_dark" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=S4lmankhan&theme=github_dark" />

</div>

---

## 🏆 Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=S4lmankhan&theme=darkhub&no-frame=false&no-bg=true&column=7&margin-w=6&title=MultiLanguage,Commits,Repositories,Stars,Followers,PullRequest,Issues" />

</div>

<details>
<summary><b>🎖️ Certifications</b></summary>
<br/>
<div align="center">

![CEH](https://img.shields.io/badge/CEH_v13-89.6%25-dc2626?style=for-the-badge&labelColor=0d0000)
![NAVTTC](https://img.shields.io/badge/Ethical_Hacker-NAVTTC-dc2626?style=for-the-badge&labelColor=0d0000)
![DeepLearning](https://img.shields.io/badge/Deep_Learning-DeepLearning.AI-dc2626?style=for-the-badge&labelColor=0d0000)
![Stanford](https://img.shields.io/badge/Machine_Learning-Stanford-dc2626?style=for-the-badge&labelColor=0d0000)
![Cisco](https://img.shields.io/badge/CyberSecurity-Cisco-dc2626?style=for-the-badge&labelColor=0d0000)
![CPEE](https://img.shields.io/badge/CPEE-Prompt_Engineering-dc2626?style=for-the-badge&labelColor=0d0000)
![Udemy](https://img.shields.io/badge/Python_Full_Stack-Udemy-dc2626?style=for-the-badge&labelColor=0d0000)
![NSCT](https://img.shields.io/badge/NSCT-89.7th_Percentile-dc2626?style=for-the-badge&labelColor=0d0000)

</div>
</details>

---

## 📫 Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-dc2626?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0000)](mailto:codewithsalty@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dc2626?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0000)](https://linkedin.com/in/s4lmankhan)
[![GitHub](https://img.shields.io/badge/GitHub-dc2626?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0000)](https://github.com/S4lmankhan)
[![Portfolio](https://img.shields.io/badge/Portfolio-dc2626?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d0000)](https://salman-khan.dev)
[![Kaggle](https://img.shields.io/badge/Kaggle-dc2626?style=for-the-badge&logo=kaggle&logoColor=white&labelColor=0d0000)](https://kaggle.com/s4lmankhan)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-dc2626?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=0d0000)](https://wa.me/923245138640)

</div>

---

<!-- FOOTER -->
<div align="center">

<svg width="800" height="80" viewBox="0 0 800 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="ftg" cx="50%" cy="50%" r="60%">
      <stop offset="0%"   stop-color="#1a0000"/>
      <stop offset="100%" stop-color="#000000"/>
    </radialGradient>
    <linearGradient id="ftl" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="transparent"/>
      <stop offset="50%"  stop-color="#dc2626"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>
    <pattern id="fp" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="12" cy="12" r="0.55" fill="#dc2626" opacity="0.08"/>
    </pattern>
  </defs>
  <rect width="800" height="80" rx="8" fill="url(#ftg)"/>
  <rect width="800" height="80" rx="8" fill="url(#fp)"/>
  <line x1="80" y1="16" x2="720" y2="16" stroke="url(#ftl)" stroke-width="1">
    <animate attributeName="opacity" values="0.1;0.5;0.1" dur="5s" repeatCount="indefinite"/>
  </line>
  <text x="400" y="42" text-anchor="middle" fill="#dc2626"
        font-size="14" font-family="'Courier New',monospace" letter-spacing="2">
    $ thanks_for_visiting
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="400" y="62" text-anchor="middle" fill="#444"
        font-size="11" font-family="'Courier New',monospace">
    Let's build something amazing together
  </text>
  <circle cx="364" cy="34" r="2" fill="#dc2626">
    <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="436" cy="34" r="2" fill="#dc2626">
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>
