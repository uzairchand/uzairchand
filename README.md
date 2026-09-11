<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 400" width="100%" height="100%">
  <defs>

    <!-- Main Background -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#050816"/>
      <stop offset="55%" stop-color="#0B1120"/>
      <stop offset="100%" stop-color="#020617"/>
    </linearGradient>

    <!-- Blue Glow -->
    <radialGradient id="glow" cx="75%" cy="45%" r="55%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.25"/>
      <stop offset="45%" stop-color="#0EA5E9" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#020617" stop-opacity="0"/>
    </radialGradient>

    <!-- Cyan Glow -->
    <radialGradient id="cyanGlow" cx="90%" cy="90%" r="45%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
    </radialGradient>

    <!-- Grid -->
    <pattern id="grid" width="32" height="32" patternUnits="userSpaceOnUse">
      <path
        d="M 32 0 L 0 0 0 32"
        fill="none"
        stroke="#334155"
        stroke-width="0.6"
        opacity="0.25"
      />
    </pattern>

    <!-- Blue Gradient -->
    <linearGradient id="blueText" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#60A5FA"/>
      <stop offset="100%" stop-color="#22D3EE"/>
    </linearGradient>

    <!-- Glass Gradient -->
    <linearGradient id="glass" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#172033" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#0F172A" stop-opacity="0.55"/>
    </linearGradient>

  </defs>


  <!-- ================= BACKGROUND ================= -->

  <rect width="1200" height="400" fill="url(#bg)"/>

  <rect width="1200" height="400" fill="url(#grid)"/>

  <rect width="1200" height="400" fill="url(#glow)"/>

  <rect width="1200" height="400" fill="url(#cyanGlow)"/>


  <!-- ================= DECORATIVE LINES ================= -->

  <path
    d="M0 330 C180 270 260 360 430 300 S720 230 900 290 S1080 340 1200 260"
    fill="none"
    stroke="#2563EB"
    stroke-width="1"
    opacity="0.18"
  />

  <path
    d="M0 350 C180 290 280 370 450 315 S730 250 910 310 S1080 350 1200 280"
    fill="none"
    stroke="#22D3EE"
    stroke-width="1"
    opacity="0.12"
  />


  <!-- ================= LEFT ACCENT ================= -->

  <rect
    x="105"
    y="112"
    width="5"
    height="176"
    rx="2.5"
    fill="url(#blueText)"
  />

  <circle
    cx="107.5"
    cy="105"
    r="4"
    fill="#22D3EE"
  />


  <!-- ================= MAIN TEXT ================= -->

  <g transform="translate(145,0)">

    <!-- Small Label -->

    <text
      x="0"
      y="135"
      font-family="Inter, Arial, sans-serif"
      font-size="13"
      font-weight="600"
      letter-spacing="4"
      fill="#64748B"
    >
      DEVELOPER • BUILDER • CREATOR
    </text>


    <!-- Name -->

    <text
      x="0"
      y="195"
      font-family="Inter, Arial, sans-serif"
      font-size="58"
      font-weight="800"
      letter-spacing="-2"
      fill="#F8FAFC"
    >
      Uzair Chand
    </text>


    <!-- Developer Title -->

    <text
      x="2"
      y="235"
      font-family="Inter, Arial, sans-serif"
      font-size="23"
      font-weight="600"
      letter-spacing="1"
      fill="url(#blueText)"
    >
      Full Stack React Developer
    </text>


    <!-- Divider -->

    <line
      x1="2"
      y1="258"
      x2="410"
      y2="258"
      stroke="#334155"
      stroke-width="1"
    />


    <!-- Tech Stack -->

    <text
      x="2"
      y="286"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="14"
      fill="#94A3B8"
    >
      React
      <tspan fill="#38BDF8"> / </tspan>
      Next.js
      <tspan fill="#38BDF8"> / </tspan>
      Node.js
      <tspan fill="#38BDF8"> / </tspan>
      MongoDB
    </text>

  </g>


  <!-- ================= RIGHT TERMINAL CARD ================= -->

  <g transform="translate(760,92)">

    <!-- Glow Border -->

    <rect
      x="0"
      y="0"
      width="325"
      height="210"
      rx="16"
      fill="#020617"
      stroke="#1E40AF"
      stroke-width="1"
      opacity="0.95"
    />

    <!-- Glass Overlay -->

    <rect
      x="1"
      y="1"
      width="323"
      height="208"
      rx="15"
      fill="url(#glass)"
      opacity="0.75"
    />


    <!-- Terminal Header -->

    <circle cx="25" cy="25" r="5" fill="#EF4444"/>
    <circle cx="43" cy="25" r="5" fill="#F59E0B"/>
    <circle cx="61" cy="25" r="5" fill="#22C55E"/>

    <text
      x="88"
      y="29"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="11"
      fill="#64748B"
    >
      uzair@developer
    </text>


    <!-- Terminal Divider -->

    <line
      x1="20"
      y1="48"
      x2="305"
      y2="48"
      stroke="#1E293B"
      stroke-width="1"
    />


    <!-- Code -->

    <text
      x="24"
      y="78"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="13"
      fill="#64748B"
    >
      <tspan fill="#38BDF8">const</tspan>
      developer =
    </text>

    <text
      x="24"
      y="103"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="13"
      fill="#94A3B8"
    >
      {
    </text>

    <text
      x="42"
      y="128"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="13"
      fill="#A5B4FC"
    >
      name:
      <tspan fill="#4ADE80"> "Uzair"</tspan>
    </text>

    <text
      x="42"
      y="153"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="13"
      fill="#A5B4FC"
    >
      stack:
      <tspan fill="#4ADE80"> "Full Stack"</tspan>
    </text>

    <text
      x="42"
      y="178"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="13"
      fill="#A5B4FC"
    >
      status:
      <tspan fill="#4ADE80"> "Building..."</tspan>
    </text>

    <text
      x="24"
      y="201"
      font-family="JetBrains Mono, Consolas, monospace"
      font-size="13"
      fill="#94A3B8"
    >
      }
    </text>

  </g>


  <!-- ================= FLOATING CODE SYMBOLS ================= -->

  <text
    x="1115"
    y="85"
    font-family="JetBrains Mono, monospace"
    font-size="25"
    fill="#2563EB"
    opacity="0.35"
  >
    &lt;/&gt;
  </text>

  <text
    x="700"
    y="345"
    font-family="JetBrains Mono, monospace"
    font-size="18"
    fill="#22D3EE"
    opacity="0.3"
  >
    { }
  </text>

  <circle
    cx="1120"
    cy="340"
    r="3"
    fill="#38BDF8"
    opacity="0.6"
  />

  <circle
    cx="735"
    cy="70"
    r="2"
    fill="#22D3EE"
    opacity="0.7"
  />

</svg>


<h1 align="center">Hi 👋, I'm Uzair Chand</h1>

<h3 align="center">
  Full-Stack React Developer
</h3>

<p align="center">
  I build modern, responsive and interactive web experiences
  with React, Next.js and modern web technologies.
</p>

<p align="center">
  <a href="https://github.com/uzairchand">
    <img src="https://img.shields.io/github/followers/uzairchand?label=Followers&style=for-the-badge" />
  </a>
  <a href="https://github.com/uzairchand">
    <img src="https://img.shields.io/github/stars/uzairchand?label=Stars&style=for-the-badge" />
  </a>
</p>
## 👨‍💻 About Me

I'm Uzair Chand, a developer focused on building modern web applications
with clean interfaces, smooth interactions and practical functionality.

- ⚛️ React.js Developer
- ▲ Building with Next.js
- 🟢 Learning Node.js & backend development
- 🎨 Interested in modern UI/UX and animations
- 🚀 Building real-world projects
- 📚 Always learning new technologies
## 🛠️ Tech Stack

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nextjs,tailwind" />
</p>

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb" />
</p>

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,netlify" />
</p>
## 🌱 Currently Learning

```text
Node.js
   ↓
Express.js
   ↓
MongoDB
   ↓
REST APIs
   ↓
Full-Stack Development

Isse recruiter ko clearly pata chalega ke tum **frontend se full-stack ki taraf move kar rahe ho.**

---

# 5. Featured Projects

Abhi fake projects add nahi karenge.

Temporary:

```md
## 🚀 Featured Projects

### ☕ Brew & Bean

Animated coffee website built with Next.js.

**Tech:** Next.js • Tailwind CSS • Framer Motion

---

### 🍕 SliceHub POS

Pizza shop order-taking and POS management system.

**Tech:** React.js • Tailwind CSS • JavaScript

---

### 💧 Water Plant Website

Modern corporate website for a mineral water company.

**Tech:** React.js • Tailwind CSS • Framer Motion

---

### 💻 Personal Portfolio

Personal developer portfolio with modern animations and interactive UI.

**Tech:** React.js • Tailwind CSS • GSAP
## 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=uzairchand&show_icons=true&hide_border=true&rank_icon=github" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=uzairchand&hide_border=true" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=uzairchand&layout=compact&hide_border=true" />
</p>
## 🔥 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=uzairchand&hide_border=true" />
</p>
## 🌐 Connect With Me

<p align="center">
  <a href="https://github.com/uzairchand">
    GitHub
  </a>
  •
  <a href="https://uzairchandportfolio.netlify.app/">
    Portfolio
  </a>
  •
  <a href="YOUR_LINKEDIN_URL">
    LinkedIn
  </a>
</p>
<br />

<p align="center">
  <b>Build. Learn. Improve. Repeat. 🚀</b>
</p>

<p align="center">
  ⭐ Thanks for visiting my profile!
</p>
