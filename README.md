<div align="center">

<svg width="100%" height="220" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a0c"/>
      <stop offset="100%" stop-color="#14141a"/>
    </linearGradient>
    <linearGradient id="gold" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c9a84c"/>
      <stop offset="100%" stop-color="#f0d98c"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="900" height="220" fill="url(#bg)"/>

  <!-- grid lines -->
  <g stroke="#c9a84c" stroke-opacity="0.08" stroke-width="1">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="180" x2="900" y2="180"/>
    <line x1="60" y1="0" x2="60" y2="220"/>
    <line x1="840" y1="0" x2="840" y2="220"/>
  </g>

  <!-- corner brackets -->
  <g stroke="url(#gold)" stroke-width="2" fill="none">
    <path d="M20,20 L20,50 M20,20 L50,20"/>
    <path d="M880,20 L880,50 M880,20 L850,20"/>
    <path d="M20,200 L20,170 M20,200 L50,200"/>
    <path d="M880,200 L880,170 M880,200 L850,200"/>
  </g>

  <!-- HUD tag -->
  <text x="60" y="35" font-family="Space Mono, monospace" font-size="11" fill="#c9a84c" opacity="0.7">[ SYSTEM://USER_PROFILE ]</text>
  <text x="840" y="35" font-family="Space Mono, monospace" font-size="11" fill="#c9a84c" opacity="0.7" text-anchor="end">STATUS: ONLINE</text>

  <!-- main title with pulsing glow -->
  <text x="450" y="115" font-family="Playfair Display, serif" font-size="46" fill="url(#gold)" text-anchor="middle" filter="url(#glow)" font-weight="700">
    UMAID KHAN
    <animate attributeName="opacity" values="1;0.75;1" dur="2.5s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="148" font-family="Space Mono, monospace" font-size="14" fill="#e8e8e8" text-anchor="middle" letter-spacing="3">FULL-STACK DEV // GAME DEV // CREATIVE CODER</text>

  <!-- sweeping scan line -->
  <rect x="0" y="0" width="6" height="220" fill="#c9a84c" opacity="0.25">
    <animate attributeName="x" values="0;894;0" dur="6s" repeatCount="indefinite"/>
  </rect>

  <!-- bottom scan line -->
  <text x="60" y="195" font-family="Space Mono, monospace" font-size="10" fill="#c9a84c" opacity="0.6">MUMBAI, IN</text>
  <text x="840" y="195" font-family="Space Mono, monospace" font-size="10" fill="#c9a84c" opacity="0.6" text-anchor="end">v2.0.26</text>
</svg>

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-umaidkhan.vercel.app-c9a84c?style=for-the-badge&logo=vercel&logoColor=black)](https://umaidkhan.vercel.app)
[![Email](https://img.shields.io/badge/EMAIL-umaidkhan8108%40gmail.com-0a0a0c?style=for-the-badge&logo=gmail&logoColor=c9a84c)](mailto:umaidkhan8108@gmail.com)

<br>

<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&size=18&duration=3000&pause=800&color=C9A84C&center=true&vCenter=true&width=600&lines=building+dark-luxury+interfaces...;React+%2B+F[...]">

</div>

<br>

```typescript
interface Developer {
  name: string;
  location: "Mumbai, India";
  education: "BSc Information Technology — SIWS College, Wadala";
  stack: {
    frontend: ["React", "Vite", "TailwindCSS", "Framer Motion", "Three.js"];
    mobile: ["Kotlin", "Java", "Flutter", "Firebase"];
    gamedev: ["Godot 4", "GDScript"];
  };
  aesthetic: "dark luxury — gold accents, cinematic motion";
  status: "shipping projects, hunting opportunities";
}

const me: Developer = {
  name: "Umaid Khan",
  location: "Mumbai, India",
  education: "BSc Information Technology — SIWS College, Wadala",
  stack: {
    frontend: ["React", "Vite", "TailwindCSS", "Framer Motion", "Three.js"],
    mobile: ["Kotlin", "Java", "Flutter", "Firebase"],
    gamedev: ["Godot 4", "GDScript"],
  },
  aesthetic: "dark luxury — gold accents, cinematic motion",
  status: "shipping projects, hunting opportunities",
};
```

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0a0c,100:0a0a0c&height=3&section=header&animation=fadeIn" width="100%"/>

## ⟡ FEATURED BUILDS

I've updated this section to list projects that actually exist in your public repositories. I removed entries that didn't match any public repo (InvoiceVault, Runebound Chronicles, AMV.FORGE) to avoid showing unfinished or non-existent links. If you want specific private/WIP projects listed here, tell me their names and I will add them as unlinked entries or placeholders.

<table>
<tr>
<td width="50%" valign="top">

### 🔭 Portfolio-web
Cinematic dark-luxury portfolio — hero animations and project showcases. (public)

[View repo](https://github.com/Umaidkhan12/Portfolio-web)

`JavaScript` `React` `Framer Motion`

</td>
<td width="50%" valign="top">

### 🤖 AI-Project
Early AI/ML experiments and demos. (public)

[View repo](https://github.com/Umaidkhan12/AI-Project)

`HTML` `ML experiments`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 MultiPersonality_AI
A conversational / persona-based AI prototype. (public)

[View repo](https://github.com/Umaidkhan12/MultiPersonality_AI)

`Python` `NLP`

</td>
<td width="50%" valign="top">

### 🎨 Computer Graphic & Animation
Graphics and animation experiments (C++). (public)

[View repo](https://github.com/Umaidkhan12/Computer-graphic-and-animation)

`C++` `Graphics`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎥 Gesture-Voice-PPT0
A gesture + voice powered PPT controller prototype. (public)

[View repo](https://github.com/Umaidkhan12/Gesture-Voice-PPT0)

`Python` `Computer Vision` `Speech`

</td>
<td width="50%" valign="top">

### 🚕 Uber_Clone
Android/Kotlin clone project — maps & location features. (public)

[View repo](https://github.com/Umaidkhan12/Uber_Clone)

`Kotlin` `Android`

</td>
</tr>
</table>

<br>

## ⟡ OTHER PUBLIC REPOS

Below are other public repos in your account — I can add any of these to the featured section with a short blurb.

- [AI-Project](https://github.com/Umaidkhan12/AI-Project) — HTML experiments
- [18050](https://github.com/Umaidkhan12/18050) — Java
- [BankGUI](https://github.com/Umaidkhan12/BankGUI)
- [BankSystemCLI](https://github.com/Umaidkhan12/BankSystemCLI) — C# CLI
- [BroadcastingAndGPS](https://github.com/Umaidkhan12/BroadcastingAndGPS) — Kotlin
- [C-sharp](https://github.com/Umaidkhan12/C-sharp) — C# examples
- [C-Sharp-GUI](https://github.com/Umaidkhan12/C-Sharp-GUI) — C# GUI
- [CoffeeShop](https://github.com/Umaidkhan12/CoffeeShop)
- [Compiler](https://github.com/Umaidkhan12/Compiler) — Kotlin
- [DashboardApp](https://github.com/Umaidkhan12/DashboardApp) — Kotlin
- [Java-Practical](https://github.com/Umaidkhan12/Java-Practical)
- [Java-Project](https://github.com/Umaidkhan12/Java-Project)
- [Kotlin-ClassWork](https://github.com/Umaidkhan12/Kotlin-ClassWork)
- [MultiPersonality_AI](https://github.com/Umaidkhan12/MultiPersonality_AI)
- [QIS_Project](https://github.com/Umaidkhan12/QIS_Project)
- [ShoppingCart](https://github.com/Umaidkhan12/ShoppingCart)
- [Uber_Clone](https://github.com/Umaidkhan12/Uber_Clone)


<br>

## ⟡ PRIVATE / WIP PROJECTS

If you want private or WIP projects shown on this page (as names only), reply with their names and a one-line blurb for each. I will add them as unlinked entries so they remain private but visible on your profile.

<br>

## ⟡ SKILL MATRIX

```
Frontend (React/Vite/Tailwind)   ████████████████████ 95%
Mobile  (Kotlin/Flutter)         ███████████████░░░░░ 75%
Game Dev (Godot/GDScript)        ████████████████░░░░ 80%
Backend (Firebase/Express)       █████████████░░░░░░░ 65%
Creative / Motion Design          ██████████████████░░ 90%
```

<br>

<div align="center">

```
[ LORD OF MYSTERIES — currently re-reading ]
[ status: open to web dev opportunities ]
```

<img src="https://github-readme-stats.vercel.app/api?username=Umaidkhan12&show_icons=true&theme=radical&hide_border=true&bg_color=0a0a0c&title_color=c9a84c&icon_color=c9a84c&text_color=e8e8e8" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Umaidkhan12&theme=radical&hide_border=true&background=0a0a0c&ring=c9a84c&fire=c9a84c&currStreakLabel=c9a84c" width="48%"/>

</div>
