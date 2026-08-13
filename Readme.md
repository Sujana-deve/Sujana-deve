<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════ -->

<!--                            HERO                                        -->

<!-- ═══════════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="300" viewBox="0 0 900 300" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#050014"/>
      <stop offset="45%" stop-color="#12002b"/>
      <stop offset="100%" stop-color="#001b2e"/>
    </linearGradient>

```
<linearGradient id="text" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#00F5FF"/>
  <stop offset="35%" stop-color="#7C3AED"/>
  <stop offset="65%" stop-color="#EC4899"/>
  <stop offset="100%" stop-color="#00F5FF"/>
  <animate attributeName="x1" values="0%;100%;0%" dur="6s" repeatCount="indefinite"/>
  <animate attributeName="x2" values="100%;0%;100%" dur="6s" repeatCount="indefinite"/>
</linearGradient>

<radialGradient id="glow">
  <stop offset="0%" stop-color="#7C3AED" stop-opacity=".45"/>
  <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
</radialGradient>

<filter id="blur">
  <feGaussianBlur stdDeviation="25"/>
</filter>

<filter id="neon">
  <feGaussianBlur stdDeviation="3" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>
```

  </defs>

  <!-- background -->

  <rect width="900" height="300" rx="24" fill="url(#bg)"/>

  <!-- ambient glow -->

  <circle cx="130" cy="100" r="120" fill="url(#glow)" filter="url(#blur)">
    <animate attributeName="cx" values="130;760;130" dur="12s" repeatCount="indefinite"/>
  </circle>

  <circle cx="760" cy="210" r="100" fill="url(#glow)" filter="url(#blur)">
    <animate attributeName="cy" values="210;70;210" dur="9s" repeatCount="indefinite"/>
  </circle>

  <!-- stars -->

  <g fill="#ffffff">
    <circle cx="90" cy="55" r="1.5">
      <animate attributeName="opacity" values=".2;1;.2" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="220" r="1">
      <animate attributeName="opacity" values="1;.2;1" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="730" cy="60" r="1.5">
      <animate attributeName="opacity" values=".3;1;.3" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="820" cy="180" r="1">
      <animate attributeName="opacity" values="1;.2;1" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- orbit -->

<ellipse
cx="450"
cy="150"
rx="330"
ry="95"
fill="none"
stroke="#7C3AED"
stroke-opacity=".25"
stroke-width="1"
stroke-dasharray="5 12"

>

```
<animateTransform
```

```
  attributeName="transform"
  type="rotate"
  from="0 450 150"
  to="360 450 150"
  dur="18s"
  repeatCount="indefinite"/>
```

  </ellipse>

  <!-- title -->

<text
 x="450"
 y="125"
 text-anchor="middle"
 font-family="Arial, sans-serif"
 font-size="54"
 font-weight="800"
 fill="url(#text)"
 filter="url(#neon)">
SUJANA SHARMA </text>

<text
 x="450"
 y="160"
 text-anchor="middle"
 font-family="monospace"
 font-size="15"
 letter-spacing="4"
 fill="#A5B4FC">
FULL-STACK DEVELOPER </text>

<text
 x="450"
 y="194"
 text-anchor="middle"
 font-family="monospace"
 font-size="12"
 fill="#64748B">
PYTHON  •  DJANGO  •  REACT  •  AUTOMATION </text>

  <!-- animated line -->

  <rect x="300" y="220" width="300" height="1" fill="#7C3AED">
    <animate attributeName="width" values="100;300;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x" values="400;300;400" dur="4s" repeatCount="indefinite"/>
  </rect>

</svg>

<br>

### `building things that probably started as "just a small script"`

</div>

---

<div align="center">

### ⚡ `CURRENTLY IN THE LAB`

<img src="https://img.shields.io/badge/Python-★★★★★-00F5FF?style=for-the-badge&logo=python&logoColor=white&labelColor=080014"/>
<img src="https://img.shields.io/badge/Django-★★★★★-7C3AED?style=for-the-badge&logo=django&logoColor=white&labelColor=080014"/>
<img src="https://img.shields.io/badge/React-★★★★☆-EC4899?style=for-the-badge&logo=react&logoColor=white&labelColor=080014"/>
<img src="https://img.shields.io/badge/JavaScript-★★★★☆-F59E0B?style=for-the-badge&logo=javascript&logoColor=white&labelColor=080014"/>

<br><br>

```text
╭────────────────────────────────────────────────────────────╮
│                                                            │
│   🧠  learning       system design + scalable backends   │
│   ⚙️  building       Django / React applications         │
│   🤖  exploring      AI-powered automation               │
│   📊  working on     data processing pipelines            │
│                                                            │
╰────────────────────────────────────────────────────────────╯
```

</div>

---

## 🌌 `THE STACK`

<div align="center">

<svg width="100%" height="190" viewBox="0 0 900 190" xmlns="http://www.w3.org/2000/svg">

<defs>
  <linearGradient id="stackGradient">
    <stop offset="0%" stop-color="#00F5FF"/>
    <stop offset="50%" stop-color="#7C3AED"/>
    <stop offset="100%" stop-color="#EC4899"/>
  </linearGradient>
</defs>

<rect width="900" height="190" rx="20" fill="#080014" stroke="#21103d"/>

<!-- center -->

<circle cx="450" cy="95" r="48" fill="#120025" stroke="url(#stackGradient)" stroke-width="2"/>

<text x="450" y="91"
   text-anchor="middle"
   fill="white"
   font-family="monospace"
   font-size="13"
   font-weight="bold">
PYTHON </text>

<text x="450" y="108"
   text-anchor="middle"
   fill="#64748B"
   font-family="monospace"
   font-size="9">
CORE </text>

<!-- orbit -->

<ellipse cx="450" cy="95" rx="280" ry="70"
      fill="none"
      stroke="#7C3AED"
      stroke-opacity=".3"
      stroke-dasharray="4 10"/>

<!-- nodes -->

<g font-family="monospace" text-anchor="middle">

<circle cx="190" cy="95" r="27" fill="#0D0820" stroke="#00F5FF"/>
<text x="190" y="99" fill="#00F5FF" font-size="10">DJANGO</text>

<circle cx="300" cy="38" r="27" fill="#0D0820" stroke="#7C3AED"/>
<text x="300" y="42" fill="#A78BFA" font-size="10">REACT</text>

<circle cx="600" cy="38" r="27" fill="#0D0820" stroke="#EC4899"/>
<text x="600" y="42" fill="#F472B6" font-size="10">JS</text>

<circle cx="710" cy="95" r="27" fill="#0D0820" stroke="#F59E0B"/>
<text x="710" y="99" fill="#FBBF24" font-size="10">PANDAS</text>

<circle cx="600" cy="152" r="27" fill="#0D0820" stroke="#22C55E"/>
<text x="600" y="156" fill="#4ADE80" font-size="10">API</text>

<circle cx="300" cy="152" r="27" fill="#0D0820" stroke="#38BDF8"/>
<text x="300" y="156" fill="#38BDF8" font-size="10">SQL</text>

</g>

</svg>

</div>

---

# 🚀 `SELECTED BUILDS`

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Lead Scoring

**Time-decay lead scoring engine → Django dashboard**

A scoring pipeline using exponential decay, compound bonuses and configurable scoring rules.

**Stack**

`Python` `Django` `Pandas`

</td>

<td width="50%" valign="top">

### 🛍️ FashionHub

**Full-stack Django e-commerce**

Cart, checkout, reviews, authentication, order history and eSewa sandbox payments.

**Stack**

`Django` `PostgreSQL` `eSewa`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💬 HelloThere

**Real-time communication platform**

React frontend connected to Django Channels using WebSockets.

**Stack**

`React` `Django Channels` `WebSockets`

</td>

<td width="50%" valign="top">

### 📚 Bookify

**Content-based recommendation system**

Uses TF-IDF and cosine similarity to find books with similar content.

**Stack**

`Python` `scikit-learn`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🎮 Neon Surge

**Browser game**

A JavaScript browser game shipped with CrazyGames SDK integration.

**Stack**

`JavaScript` `Game Dev`

</td>

<td width="50%" valign="top">

### 🧩 Comment Assistant

**AI-assisted Chrome extension**

Explores AI-powered intent filtering and browser automation workflows.

**Stack**

`JavaScript` `Gemini API` `Chrome Extension`

</td>
</tr>
</table>

---

<div align="center">

## 💫 `THE DEVELOPER LOOP`

```text
          ┌─────────────┐
          │    IDEA     │
          └──────┬──────┘
                 ↓
          ┌─────────────┐
          │   BUILD     │
          └──────┬──────┘
                 ↓
          ┌─────────────┐
          │    BREAK    │
          └──────┬──────┘
                 ↓
          ┌─────────────┐
          │   DEBUG     │
          └──────┬──────┘
                 ↓
          ┌─────────────┐
          │   LEARN     │
          └──────┬──────┘
                 ↓
          ┌─────────────┐
          │   REPEAT    │
          └──────┬──────┘
                 │
                 └──────────────→ 🚀
```

</div>

---

## 📡 `CONNECT`

<div align="center">

<a href="https://sujanasharma.com.np">
<img src="https://img.shields.io/badge/PORTFOLIO-00F5FF?style=for-the-badge&logo=googlechrome&logoColor=black"/>
</a>

<a href="https://www.linkedin.com/in/sujana-sharma-49779934b/">
<img src="https://img.shields.io/badge/LINKEDIN-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:sharmasujana420@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-EC4899?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br><br>

<sub>⚡ building • breaking • learning • shipping</sub>

</div>

<br>

<div align="center">

```text
┌──────────────────────────────────────────────────────┐
│                                                      │
│              THANKS FOR DROPPING BY ✨              │
│                                                      │
│        "make it work → make it better"              │
│                                                      │
└──────────────────────────────────────────────────────┘
```

</div>
