<div align="center">

<svg width="900" height="360" viewBox="0 0 900 360" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="aurora1" cx="20%" cy="40%" r="60%">
      <stop offset="0%" style="stop-color:#6c2bd9;stop-opacity:0.18"/>
      <stop offset="100%" style="stop-color:#6c2bd9;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="aurora2" cx="80%" cy="30%" r="55%">
      <stop offset="0%" style="stop-color:#0ea5e9;stop-opacity:0.14"/>
      <stop offset="100%" style="stop-color:#0ea5e9;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="aurora3" cx="50%" cy="90%" r="50%">
      <stop offset="0%" style="stop-color:#10b981;stop-opacity:0.12"/>
      <stop offset="100%" style="stop-color:#10b981;stop-opacity:0"/>
    </radialGradient>
    <linearGradient id="name-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#e8e8f0"/>
      <stop offset="40%" style="stop-color:#a78bfa"/>
      <stop offset="70%" style="stop-color:#38bdf8"/>
      <stop offset="100%" style="stop-color:#34d399"/>
    </linearGradient>
    <linearGradient id="stroke-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6c2bd9;stop-opacity:0.4"/>
      <stop offset="50%" style="stop-color:#0ea5e9;stop-opacity:0.4"/>
      <stop offset="100%" style="stop-color:#10b981;stop-opacity:0.4"/>
    </linearGradient>
    <filter id="glow-v">
      <feGaussianBlur stdDeviation="8" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow-sm">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="dot-grid" width="30" height="30" patternUnits="userSpaceOnUse">
      <circle cx="15" cy="15" r="0.8" fill="#ffffff" opacity="0.06"/>
    </pattern>
  </defs>

  <!-- BG -->
  <rect width="900" height="360" fill="#03040a"/>
  <rect width="900" height="360" fill="url(#dot-grid)"/>

  <!-- AURORA BLOBS -->
  <rect width="900" height="360" fill="url(#aurora1)"/>
  <rect width="900" height="360" fill="url(#aurora2)"/>
  <rect width="900" height="360" fill="url(#aurora3)"/>

  <!-- CORNER BRACKETS - thin white -->
  <g stroke="#ffffff" stroke-width="1.2" fill="none" opacity="0.12">
    <path d="M 24,24 L 24,56 M 24,24 L 56,24"/>
    <path d="M 876,24 L 876,56 M 876,24 L 844,24"/>
    <path d="M 24,336 L 24,304 M 24,336 L 56,336"/>
    <path d="M 876,336 L 876,304 M 876,336 L 844,336"/>
  </g>

  <!-- STATUS PILL -->
  <rect x="36" y="40" width="140" height="22" rx="11" fill="#10b98110" stroke="#10b98128" stroke-width="0.8"/>
  <circle cx="52" cy="51" r="3.5" fill="#10b981" opacity="0.9"/>
  <text x="61" y="55.5" font-family="'Courier New', monospace" font-size="9.5" fill="#10b981" letter-spacing="1.5">AVAILABLE</text>

  <!-- BIG BACKGROUND LETTERS -->
  <text x="450" y="220" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="220" font-weight="900" fill="#ffffff" opacity="0.025" letter-spacing="-10">LM</text>

  <!-- NAME — 3-layer depth trick -->
  <!-- depth shadow -->
  <text x="454" y="194" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="80" font-weight="900" fill="#6c2bd9" opacity="0.3" letter-spacing="4">LAKSHAY</text>
  <text x="454" y="274" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="80" font-weight="900" fill="#0ea5e9" opacity="0.2" letter-spacing="4">MEGHLAN</text>
  <!-- mid layer -->
  <text x="452" y="192" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="80" font-weight="900" fill="url(#name-grad)" opacity="0.6" letter-spacing="4">LAKSHAY</text>
  <text x="452" y="272" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="80" font-weight="900" opacity="0.6" letter-spacing="4">
    <tspan fill="url(#stroke-grad)" stroke="url(#stroke-grad)" stroke-width="0.5">MEGHLAN</tspan>
  </text>
  <!-- top layer -->
  <text x="450" y="190" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="80" font-weight="900" fill="url(#name-grad)" letter-spacing="4" filter="url(#glow-v)">LAKSHAY</text>
  <!-- outline version for second name -->
  <text x="450" y="270" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="80" font-weight="900" fill="none" stroke="url(#stroke-grad)" stroke-width="1.5" letter-spacing="14" opacity="0.8">MEGHLAN</text>

  <!-- SUBTITLE -->
  <text x="450" y="302" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#4b5563" letter-spacing="3">AI FULL STACK DEVELOPER  ·  FOUNDER OF RADAR  ·  DELHI 🇮🇳</text>

  <!-- DIVIDER -->
  <line x1="200" y1="315" x2="700" y2="315" stroke="url(#stroke-grad)" stroke-width="0.5" opacity="0.4"/>

  <!-- BOTTOM TAGS -->
  <g font-family="'Courier New', monospace" font-size="9.5" letter-spacing="1">
    <rect x="170" y="324" width="96" height="20" rx="3" fill="#6c2bd910" stroke="#6c2bd930" stroke-width="0.7"/>
    <text x="218" y="337.5" text-anchor="middle" fill="#a78bfa">MERN STACK</text>

    <rect x="278" y="324" width="86" height="20" rx="3" fill="#0ea5e910" stroke="#0ea5e930" stroke-width="0.7"/>
    <text x="321" y="337.5" text-anchor="middle" fill="#38bdf8">GEMINI AI</text>

    <rect x="376" y="324" width="90" height="20" rx="3" fill="#10b98110" stroke="#10b98125" stroke-width="0.7"/>
    <text x="421" y="337.5" text-anchor="middle" fill="#34d399">LANGCHAIN</text>

    <rect x="478" y="324" width="100" height="20" rx="3" fill="#6c2bd910" stroke="#6c2bd930" stroke-width="0.7"/>
    <text x="528" y="337.5" text-anchor="middle" fill="#a78bfa">AWS · AGENTS</text>

    <rect x="590" y="324" width="100" height="20" rx="3" fill="#0ea5e910" stroke="#0ea5e930" stroke-width="0.7"/>
    <text x="640" y="337.5" text-anchor="middle" fill="#38bdf8">@TECHCHEFZ</text>
  </g>

  <!-- DECORATIVE CIRCUIT LINES -->
  <g stroke="#ffffff" stroke-width="0.6" fill="none" opacity="0.07">
    <path d="M 24,180 L 80,180 L 100,160 L 140,160"/>
    <path d="M 24,200 L 75,200 L 95,220 L 130,220"/>
    <path d="M 876,180 L 820,180 L 800,160 L 760,160"/>
    <path d="M 876,200 L 825,200 L 805,220 L 770,220"/>
  </g>
  <g fill="#a78bfa" opacity="0.25">
    <circle cx="80" cy="180" r="2"/><circle cx="140" cy="160" r="1.5"/>
    <circle cx="820" cy="180" r="2"/><circle cx="760" cy="160" r="1.5"/>
  </g>
  <g fill="#38bdf8" opacity="0.2">
    <circle cx="75" cy="200" r="2"/><circle cx="130" cy="220" r="1.5"/>
    <circle cx="825" cy="200" r="2"/><circle cx="770" cy="220" r="1.5"/>
  </g>

  <!-- RADAR PULSE RINGS (bottom center) -->
  <g opacity="0.15" fill="none" stroke="#10b981">
    <circle cx="450" cy="345" r="5" stroke-width="1.5"/>
    <circle cx="450" cy="345" r="12" stroke-width="0.8"/>
    <circle cx="450" cy="345" r="20" stroke-width="0.4"/>
  </g>
  <circle cx="450" cy="345" r="3" fill="#10b981" opacity="0.5"/>
</svg>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=14&duration=2400&pause=700&color=A78BFA&center=true&vCenter=true&width=700&lines=Less+friction.+More+conversation.+More+execution.;Building+Radar+%E2%80%94+AI+OS+for+Startups+%F0%9F%9A%80;signal+%E2%86%92+community+%E2%86%92+workflow+%E2%86%92+agents;Founders+shouldn%27t+fill+forms.+They+should+just+talk.;WhatsApp+flows.+AI+agents.+No+dashboards." alt="Typing"/>

<br/>

![](https://img.shields.io/badge/%E2%97%8F_AVAILABLE-03040a?style=for-the-badge&labelColor=03040a&color=03040a&logo=statuspage&logoColor=10b981)
![](https://img.shields.io/badge/RADAR_PHASE_3_%E2%9A%A1_LIVE-03040a?style=for-the-badge&labelColor=03040a&color=03040a&logo=google&logoColor=a78bfa)
![](https://img.shields.io/badge/AI_FULL_STACK-03040a?style=for-the-badge&labelColor=03040a&color=03040a&logo=openai&logoColor=38bdf8)
<img src="https://komarev.com/ghpvc/?username=lakshaymeghlan&style=for-the-badge&color=03040a&label=VIEWS&labelColor=03040a"/>

</div>

<br/>

---

<!-- ══════════════════════════════════════
     WHO
══════════════════════════════════════ -->

<img align="right" width="280" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif"/>

```python
class LakshayMeghlan(AIFullStackDeveloper):

    def __init__(self):
        self.building   = "Radar — AI OS for Startups 🚀"
        self.location   = "Delhi, India 🇮🇳"
        self.org        = "@techchefz"
        self.contact    = "lakshaymeghlan24@gmail.com"

        self.ai_stack   = ["Gemini AI", "LangChain",
                           "OpenAI", "Prompt Engineering"]
        self.fullstack  = ["React", "Node.js", "Express",
                           "MongoDB", "Firebase", "Python"]
        self.cloud      = ["AWS", "Vercel", "Git"]
        self.learning   = ["AWS Certs", "SQL",
                           "System Design", "AI Agents"]

    def vision(self):
        return "signal → community → workflow → agents"

    def ask_me_about(self):
        return ["AI", "Full Stack", "Startups",
                "Crypto", "Stocks", "Agentic Systems"]
```

<br clear="right"/>

---

<!-- ══════════════════════════════════════
     RADAR
══════════════════════════════════════ -->

## `◈` &nbsp; Current Mission

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════╗
║  ⚡  R A D A R  —  AI Operating System for Startups                          ║
║                                                  [ PHASE 3 LIVE ]           ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║  The Problem                                                                 ║
║  Most startup platforms work the old way.                                    ║
║  Fill forms. Switch tabs. Enter everything manually. Repeat.                 ║
║                                                                              ║
║  The Solution                                                                ║
║  What if founders could interact with a startup ecosystem                    ║
║  through conversation instead of friction?                                   ║
║                                                                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║  01 ▸ Conversational Hiring Agent                                            ║
║       Describe a role naturally → AI extracts structured job data            ║
║       No forms. No friction. Just chat.                                      ║
║                                                                              ║
║  02 ▸ Intelligent Inbox + Founder Messaging                                  ║
║       Contextual outreach directly from startup cards                        ║
║       discover → connect → act                                               ║
║                                                                              ║
║  03 ▸ Personalization Layer                                                  ║
║       Upvote startups · liked states · curated profile                       ║
║       The ecosystem learns what you care about                               ║
║                                                                              ║
║  04 ▸ Agentic Ecosystem  [ BUILDING NOW ]                                    ║
║       AI agents inside Radar                                                 ║
║       WhatsApp flows — apply to jobs without opening the site                ║
║                                                                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║  STACK   React · Node.js · MongoDB · Express · Gemini AI · LangChain        ║
║  LINK    https://lnkd.in/gGEBSPDs                                           ║
║  STATUS  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░  Phase 3 shipped · Phase 4 building          ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

</div>

> *"Less dashboards. Less friction. Less form filling.*
> *More conversation. More automation. More execution."*
>
> **`signal`** `→` **`community`** `→` **`workflow`** `→` **`agents`**
>
> 🔗 **[Try Radar Live →](https://lnkd.in/gGEBSPDs)**

---

<!-- ══════════════════════════════════════
     SKILLS — custom SVG
══════════════════════════════════════ -->

![Skills](./skills.svg)

---

<!-- ══════════════════════════════════════
     STACK
══════════════════════════════════════ -->

## `◈` &nbsp; Stack

<div align="center">

**`── 🧠 AI Layer ──`**

![Gemini](https://img.shields.io/badge/Gemini_AI-03040a?style=flat-square&logo=google&logoColor=a78bfa)
![OpenAI](https://img.shields.io/badge/OpenAI-03040a?style=flat-square&logo=openai&logoColor=38bdf8)
![LangChain](https://img.shields.io/badge/LangChain-03040a?style=flat-square&logo=chainlink&logoColor=34d399)
![HuggingFace](https://img.shields.io/badge/HuggingFace-03040a?style=flat-square&logo=huggingface&logoColor=fbbf24)
![Python](https://img.shields.io/badge/Python-03040a?style=flat-square&logo=python&logoColor=a78bfa)
![TensorFlow](https://img.shields.io/badge/TensorFlow-03040a?style=flat-square&logo=tensorflow&logoColor=38bdf8)

**`── ⚡ Full Stack ──`**

![React](https://img.shields.io/badge/React-03040a?style=flat-square&logo=react&logoColor=38bdf8)
![JavaScript](https://img.shields.io/badge/JavaScript-03040a?style=flat-square&logo=javascript&logoColor=fbbf24)
![Node.js](https://img.shields.io/badge/Node.js-03040a?style=flat-square&logo=node.js&logoColor=34d399)
![Express](https://img.shields.io/badge/Express-03040a?style=flat-square&logo=express&logoColor=9ca3af)
![MongoDB](https://img.shields.io/badge/MongoDB-03040a?style=flat-square&logo=mongodb&logoColor=34d399)
![Firebase](https://img.shields.io/badge/Firebase-03040a?style=flat-square&logo=firebase&logoColor=fbbf24)
![HTML5](https://img.shields.io/badge/HTML5-03040a?style=flat-square&logo=html5&logoColor=f87171)
![CSS3](https://img.shields.io/badge/CSS3-03040a?style=flat-square&logo=css3&logoColor=38bdf8)
![Sass](https://img.shields.io/badge/Sass-03040a?style=flat-square&logo=sass&logoColor=f472b6)
![Bootstrap](https://img.shields.io/badge/Bootstrap-03040a?style=flat-square&logo=bootstrap&logoColor=a78bfa)

**`── ☁ Cloud & Tools ──`**

![AWS](https://img.shields.io/badge/AWS-03040a?style=flat-square&logo=amazon-aws&logoColor=fbbf24)
![Vercel](https://img.shields.io/badge/Vercel-03040a?style=flat-square&logo=vercel&logoColor=9ca3af)
![Git](https://img.shields.io/badge/Git-03040a?style=flat-square&logo=git&logoColor=f87171)
![GitHub](https://img.shields.io/badge/GitHub-03040a?style=flat-square&logo=github&logoColor=9ca3af)
![Postman](https://img.shields.io/badge/Postman-03040a?style=flat-square&logo=postman&logoColor=f97316)
![VS Code](https://img.shields.io/badge/VSCode-03040a?style=flat-square&logo=visual-studio-code&logoColor=38bdf8)

</div>

---

<!-- ══════════════════════════════════════
     ANALYTICS
══════════════════════════════════════ -->

## `◈` &nbsp; Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=lakshaymeghlan&show_icons=true&hide_border=true&bg_color=03040a&title_color=a78bfa&text_color=4b5563&icon_color=38bdf8&include_all_commits=true&count_private=true"/>
&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lakshaymeghlan&layout=compact&langs_count=6&hide_border=true&bg_color=03040a&title_color=a78bfa&text_color=4b5563"/>

<br/>

<img width="55%" src="https://github-readme-streak-stats.herokuapp.com/?user=lakshaymeghlan&hide_border=true&background=03040a&stroke=a78bfa20&ring=a78bfa&fire=38bdf8&currStreakNum=e8e8f0&sideNums=e8e8f0&currStreakLabel=a78bfa&sideLabels=a78bfa&dates=4b5563"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=lakshaymeghlan&bg_color=03040a&color=a78bfa&line=6c2bd950&point=a78bfa&area=true&area_color=6c2bd910&hide_border=true" width="100%"/>

</div>

---

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=lakshaymeghlan&theme=darkhub&no-frame=true&no-bg=true&row=1&column=7" width="100%"/>
</div>

---

## `◈` &nbsp; Active Processes

```bash
┌────────────────────────────────┬─────────┬────────────────────────────────┐
│  PROCESS                       │   CPU   │  STATUS                        │
├────────────────────────────────┼─────────┼────────────────────────────────┤
│  radar_phase4_agents           │   99%   │  🔨 building — AI agents       │
│  whatsapp_flow_integration     │   80%   │  🤖 agentic — no-site flows    │
│  scale_ai_infra                │   45%   │  🔧 planning — beyond quotas   │
│  learn_aws_sql_sysdesign       │   30%   │  📖 studying — prod scale      │
│  touch_grass                   │    1%   │  ⏸  suspended — always         │
└────────────────────────────────┴─────────┴────────────────────────────────┘
```

---

## `◈` &nbsp; Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_PORTFOLIO-03040a?style=for-the-badge&labelColor=03040a)](https://lakshays-portfolio.vercel.app/)
&nbsp;
[![Radar](https://img.shields.io/badge/⚡_RADAR_APP-03040a?style=for-the-badge&logo=google&logoColor=a78bfa&labelColor=03040a)](https://lnkd.in/gGEBSPDs)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-03040a?style=for-the-badge&logo=linkedin&logoColor=38bdf8&labelColor=03040a)](https://linkedin.com/in/lakshay-meghlan-77512321b)
&nbsp;
[![Twitter](https://img.shields.io/badge/TWITTER-03040a?style=for-the-badge&logo=x&logoColor=9ca3af&labelColor=03040a)](https://twitter.com/lakshay_meghlan)
&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-03040a?style=for-the-badge&logo=gmail&logoColor=f87171&labelColor=03040a)](mailto:lakshaymeghlan24@gmail.com)

</div>

---

<div align="center">

<br/>

*"Less dashboards. Less friction.*
*More conversation. More* ***execution.***"

`AI Developer` &nbsp;·&nbsp; `@techchefz` &nbsp;·&nbsp; `Delhi` &nbsp;·&nbsp; `Radar Phase 3 Live`

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:03040a,30:6c2bd915,60:0ea5e915,100:03040a&height=100&section=footer&text=signal+%E2%86%92+community+%E2%86%92+workflow+%E2%86%92+agents&fontSize=13&fontColor=a78bfa&fontAlignY=65&animation=twinkling"/>

</div>
