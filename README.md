<div align="center">

<!-- ═══════════════════════════════════════════════════════════════
     PIXEL-ART BANNER — SVG rendered inline
════════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 280" width="900" height="280" role="img" aria-label="Pixel-art developer room banner for Mohammad Reza Noie">
  <defs>
    <!-- Room background gradient -->
    <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0d0d1a"/>
      <stop offset="100%" stop-color="#1a0a2e"/>
    </linearGradient>
    <!-- Floor gradient -->
    <linearGradient id="floor" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#120826"/>
      <stop offset="100%" stop-color="#0a051a"/>
    </linearGradient>
    <!-- Monitor glow -->
    <radialGradient id="monGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#a855f7" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#a855f7" stop-opacity="0"/>
    </radialGradient>
    <!-- Neon pink glow -->
    <radialGradient id="pinkGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#f72585" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#f72585" stop-opacity="0"/>
    </radialGradient>
    <!-- Lamp glow -->
    <radialGradient id="lampGlow" cx="50%" cy="30%" r="60%">
      <stop offset="0%" stop-color="#7c3aed" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#7c3aed" stop-opacity="0"/>
    </radialGradient>
    <!-- Window glow -->
    <radialGradient id="winGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#3b82f6" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#3b82f6" stop-opacity="0"/>
    </radialGradient>
    <!-- Text glow filter -->
    <filter id="glow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="neonText" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- === BACKGROUND === -->
  <rect width="900" height="280" fill="url(#sky)"/>
  <!-- Floor -->
  <rect x="0" y="200" width="900" height="80" fill="url(#floor)"/>
  <!-- Floor line -->
  <rect x="0" y="200" width="900" height="2" fill="#2d1b69" opacity="0.8"/>

  <!-- Pixel grid overlay (subtle) -->
  <pattern id="grid" width="8" height="8" patternUnits="userSpaceOnUse">
    <rect width="8" height="8" fill="none" stroke="#1e0a3c" stroke-width="0.3" opacity="0.4"/>
  </pattern>
  <rect width="900" height="280" fill="url(#grid)"/>

  <!-- === BACKGROUND STARS === -->
  <circle cx="50" cy="20" r="1" fill="#a78bfa" opacity="0.8"/>
  <circle cx="120" cy="45" r="1.5" fill="#f0abfc" opacity="0.6"/>
  <circle cx="200" cy="15" r="1" fill="#93c5fd" opacity="0.7"/>
  <circle cx="310" cy="30" r="1" fill="#a78bfa" opacity="0.5"/>
  <circle cx="430" cy="10" r="1.5" fill="#f9a8d4" opacity="0.6"/>
  <circle cx="560" cy="35" r="1" fill="#93c5fd" opacity="0.8"/>
  <circle cx="680" cy="18" r="1" fill="#a78bfa" opacity="0.7"/>
  <circle cx="780" cy="42" r="1.5" fill="#f0abfc" opacity="0.5"/>
  <circle cx="850" cy="12" r="1" fill="#93c5fd" opacity="0.6"/>
  <circle cx="760" cy="60" r="1" fill="#a78bfa" opacity="0.4"/>
  <circle cx="88" cy="70" r="1" fill="#f9a8d4" opacity="0.5"/>
  <circle cx="650" cy="80" r="1" fill="#93c5fd" opacity="0.4"/>

  <!-- === WINDOW (LEFT) === -->
  <!-- Window glow -->
  <ellipse cx="110" cy="100" rx="70" ry="60" fill="url(#winGlow)"/>
  <!-- Window frame -->
  <rect x="55" y="50" width="110" height="130" rx="2" fill="#0f0523" stroke="#2d1b69" stroke-width="3"/>
  <!-- Window pane - night sky -->
  <rect x="60" y="55" width="100" height="120" fill="#04011a"/>
  <!-- Window cross -->
  <rect x="60" y="113" width="100" height="3" fill="#1e0a3c"/>
  <rect x="108" y="55" width="3" height="120" fill="#1e0a3c"/>
  <!-- Moon -->
  <circle cx="90" cy="80" r="12" fill="#f1f5f9" opacity="0.9"/>
  <circle cx="96" cy="77" r="10" fill="#04011a"/>
  <!-- Window stars -->
  <circle cx="130" cy="70" r="1" fill="#f9a8d4" opacity="0.9"/>
  <circle cx="145" cy="90" r="1" fill="#a78bfa" opacity="0.8"/>
  <circle cx="75" cy="140" r="1" fill="#93c5fd" opacity="0.7"/>
  <circle cx="140" cy="135" r="1" fill="#f0abfc" opacity="0.8"/>
  <!-- Window curtain left -->
  <polygon points="55,50 75,50 68,180 55,180" fill="#2d1463" opacity="0.9"/>
  <!-- Window curtain right -->
  <polygon points="165,50 170,50 170,180 157,180" fill="#2d1463" opacity="0.9"/>

  <!-- === BOOKSHELF (left wall) === -->
  <rect x="30" y="95" width="22" height="100" rx="1" fill="#1a0a40" stroke="#2d1b69" stroke-width="1"/>
  <!-- Books pixel style -->
  <rect x="32" y="97" width="5" height="40" fill="#7c3aed"/>
  <rect x="37" y="100" width="4" height="37" fill="#f72585"/>
  <rect x="41" y="98" width="5" height="39" fill="#3b82f6"/>
  <rect x="46" y="101" width="4" height="36" fill="#a855f7"/>
  <rect x="32" y="140" width="6" height="30" fill="#10b981"/>
  <rect x="38" y="142" width="5" height="28" fill="#f59e0b"/>
  <rect x="43" y="139" width="7" height="31" fill="#ec4899"/>
  <!-- Shelf -->
  <rect x="28" y="135" width="26" height="3" fill="#2d1b69"/>

  <!-- === DESK === -->
  <!-- Desk top -->
  <rect x="190" y="175" width="530" height="12" rx="2" fill="#1e0a4a" stroke="#3d1f8a" stroke-width="1.5"/>
  <!-- Desk legs -->
  <rect x="200" y="187" width="12" height="40" fill="#16073a"/>
  <rect x="706" y="187" width="12" height="40" fill="#16073a"/>
  <!-- Desk front panel -->
  <rect x="190" y="187" width="530" height="40" rx="0" fill="#110626" opacity="0.6"/>

  <!-- === MONITOR === -->
  <!-- Monitor glow -->
  <ellipse cx="460" cy="130" rx="120" ry="60" fill="url(#monGlow)" opacity="0.7"/>
  <!-- Monitor stand -->
  <rect x="444" y="168" width="32" height="10" rx="2" fill="#1e0a4a"/>
  <rect x="430" y="176" width="60" height="5" rx="2" fill="#1e0a4a"/>
  <!-- Monitor body -->
  <rect x="330" y="70" width="260" height="100" rx="4" fill="#0d0520" stroke="#6d28d9" stroke-width="2.5"/>
  <!-- Monitor screen -->
  <rect x="335" y="75" width="250" height="88" rx="2" fill="#080214"/>
  <!-- Screen content — code lines -->
  <!-- Line 1: purple -->
  <rect x="345" y="82" width="8" height="5" rx="1" fill="#a855f7"/>
  <rect x="355" y="82" width="40" height="5" rx="1" fill="#7c3aed" opacity="0.8"/>
  <rect x="398" y="82" width="25" height="5" rx="1" fill="#f72585" opacity="0.8"/>
  <!-- Line 2: pink -->
  <rect x="355" y="92" width="20" height="5" rx="1" fill="#f9a8d4" opacity="0.7"/>
  <rect x="378" y="92" width="50" height="5" rx="1" fill="#c4b5fd" opacity="0.6"/>
  <!-- Line 3: blue -->
  <rect x="355" y="102" width="15" height="5" rx="1" fill="#93c5fd" opacity="0.7"/>
  <rect x="373" y="102" width="60" height="5" rx="1" fill="#7c3aed" opacity="0.5"/>
  <!-- Line 4 -->
  <rect x="355" y="112" width="35" height="5" rx="1" fill="#f0abfc" opacity="0.7"/>
  <rect x="393" y="112" width="40" height="5" rx="1" fill="#a855f7" opacity="0.5"/>
  <!-- Line 5 -->
  <rect x="355" y="122" width="25" height="5" rx="1" fill="#f9a8d4" opacity="0.6"/>
  <rect x="383" y="122" width="45" height="5" rx="1" fill="#c4b5fd" opacity="0.5"/>
  <!-- Cursor blink -->
  <rect x="355" y="132" width="6" height="8" rx="1" fill="#a855f7" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0;0.9" dur="1.2s" repeatCount="indefinite"/>
  </rect>
  <!-- Screen scanline effect -->
  <rect x="335" y="75" width="250" height="88" rx="2" fill="url(#grid)" opacity="0.15"/>

  <!-- === KEYBOARD === -->
  <rect x="380" y="178" width="160" height="18" rx="3" fill="#150630" stroke="#3d1f8a" stroke-width="1.2"/>
  <!-- Key rows -->
  <rect x="385" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="393" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="401" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="409" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="417" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="425" y="181" width="6" height="4" rx="1" fill="#7c3aed"/>
  <rect x="433" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="441" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="449" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="457" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="465" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="473" y="181" width="6" height="4" rx="1" fill="#f72585"/>
  <rect x="481" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="489" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="497" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="505" y="181" width="6" height="4" rx="1" fill="#2d1b69"/>
  <!-- Row 2 -->
  <rect x="388" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="396" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="404" y="188" width="6" height="4" rx="1" fill="#a855f7"/>
  <rect x="412" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="420" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="428" y="188" width="40" height="4" rx="1" fill="#1e0a4a"/>
  <rect x="470" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="478" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="486" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="494" y="188" width="6" height="4" rx="1" fill="#2d1b69"/>
  <rect x="502" y="188" width="8" height="4" rx="1" fill="#2d1b69"/>

  <!-- === COFFEE MUG === -->
  <!-- Mug body -->
  <rect x="680" y="159" width="24" height="20" rx="3" fill="#1a0a40" stroke="#3d1f8a" stroke-width="1.2"/>
  <!-- Mug handle -->
  <path d="M704 163 Q714 163 714 169 Q714 175 704 175" fill="none" stroke="#3d1f8a" stroke-width="2"/>
  <!-- Coffee liquid -->
  <rect x="682" y="161" width="20" height="6" rx="2" fill="#7c2d12" opacity="0.8"/>
  <!-- Steam pixels -->
  <rect x="685" y="154" width="3" height="4" rx="1" fill="#c4b5fd" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="692" y="151" width="3" height="5" rx="1" fill="#c4b5fd" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="2.5s" repeatCount="indefinite"/>
  </rect>
  <rect x="699" y="154" width="3" height="4" rx="1" fill="#c4b5fd" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="1.8s" repeatCount="indefinite"/>
  </rect>

  <!-- === DESK LAMP === -->
  <!-- Lamp glow -->
  <ellipse cx="280" cy="140" rx="60" ry="50" fill="url(#lampGlow)"/>
  <!-- Lamp base -->
  <rect x="270" y="173" width="20" height="5" rx="2" fill="#1e0a4a" stroke="#3d1f8a" stroke-width="1"/>
  <!-- Lamp pole -->
  <rect x="278" y="130" width="4" height="46" rx="2" fill="#2d1b69"/>
  <!-- Lamp arm -->
  <line x1="280" y1="130" x2="260" y2="115" stroke="#2d1b69" stroke-width="3" stroke-linecap="round"/>
  <!-- Lamp head -->
  <polygon points="248,112 275,105 270,120 245,127" fill="#3d1f8a" stroke="#6d28d9" stroke-width="1"/>
  <!-- Lamp light -->
  <ellipse cx="258" cy="118" rx="10" ry="6" fill="#f0abfc" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.8;0.6" dur="3s" repeatCount="indefinite"/>
  </ellipse>

  <!-- === SMALL MONITOR (right side) === -->
  <rect x="735" y="135" width="100" height="65" rx="3" fill="#0d0520" stroke="#6d28d9" stroke-width="2"/>
  <rect x="739" y="139" width="92" height="54" rx="2" fill="#080214"/>
  <!-- Mini screen content -->
  <rect x="743" y="144" width="30" height="4" rx="1" fill="#f72585" opacity="0.7"/>
  <rect x="743" y="151" width="50" height="4" rx="1" fill="#7c3aed" opacity="0.6"/>
  <rect x="743" y="158" width="40" height="4" rx="1" fill="#a855f7" opacity="0.7"/>
  <rect x="743" y="165" width="35" height="4" rx="1" fill="#93c5fd" opacity="0.5"/>
  <rect x="743" y="172" width="55" height="4" rx="1" fill="#f9a8d4" opacity="0.6"/>
  <!-- Mini monitor stand -->
  <rect x="778" y="200" width="14" height="5" rx="1" fill="#1e0a4a"/>
  <rect x="770" y="203" width="30" height="4" rx="1" fill="#1e0a4a"/>

  <!-- === NEON SIGNS === -->
  <!-- Pink glow behind sign -->
  <ellipse cx="750" cy="55" rx="70" ry="25" fill="url(#pinkGlow)" opacity="0.8"/>
  <!-- Neon sign border -->
  <rect x="695" y="35" width="120" height="38" rx="18" fill="none" stroke="#f72585" stroke-width="2.5" opacity="0.9" filter="url(#glow)"/>
  <!-- Neon sign text: CODE -->
  <text x="755" y="59" font-family="monospace" font-size="16" font-weight="bold" fill="#f72585" text-anchor="middle" filter="url(#glow)" letter-spacing="3">CODE</text>

  <!-- Purple neon sign -->
  <ellipse cx="200" cy="45" rx="55" ry="20" fill="url(#lampGlow)" opacity="0.6"/>
  <rect x="155" y="30" width="95" height="30" rx="14" fill="none" stroke="#a855f7" stroke-width="2" opacity="0.9" filter="url(#glow)"/>
  <text x="202" y="50" font-family="monospace" font-size="11" font-weight="bold" fill="#a855f7" text-anchor="middle" filter="url(#glow)" letter-spacing="2">DEV MODE</text>

  <!-- === PLANT (right corner) === -->
  <!-- Pot -->
  <polygon points="848,230 872,230 868,200 852,200" fill="#1e0a4a" stroke="#3d1f8a" stroke-width="1.2"/>
  <!-- Soil -->
  <rect x="853" y="200" width="14" height="4" rx="1" fill="#292524"/>
  <!-- Stems -->
  <line x1="860" y1="200" x2="850" y2="180" stroke="#166534" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="860" y1="200" x2="870" y2="175" stroke="#166534" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="860" y1="195" x2="860" y2="170" stroke="#166534" stroke-width="2.5" stroke-linecap="round"/>
  <!-- Leaves -->
  <ellipse cx="847" cy="176" rx="9" ry="6" fill="#16a34a" transform="rotate(-30 847 176)"/>
  <ellipse cx="872" cy="172" rx="9" ry="6" fill="#15803d" transform="rotate(25 872 172)"/>
  <ellipse cx="860" cy="167" rx="8" ry="5" fill="#22c55e"/>

  <!-- === CONTROLLER (desk item) === -->
  <rect x="620" y="170" width="40" height="22" rx="6" fill="#1a0a40" stroke="#3d1f8a" stroke-width="1"/>
  <!-- D-pad -->
  <rect x="626" y="177" width="10" height="4" rx="1" fill="#4c1d95"/>
  <rect x="629" y="174" width="4" height="10" rx="1" fill="#4c1d95"/>
  <!-- Buttons -->
  <circle cx="652" cy="175" r="3" fill="#f72585"/>
  <circle cx="658" cy="181" r="3" fill="#a855f7"/>
  <circle cx="646" cy="181" r="3" fill="#3b82f6"/>
  <circle cx="652" cy="187" r="3" fill="#10b981"/>

  <!-- === MAIN TITLE TEXT === -->
  <!-- Backdrop glow for title -->
  <rect x="250" y="8" width="400" height="36" rx="4" fill="#0d0520" opacity="0.5"/>
  <!-- Title -->
  <text x="450" y="33" font-family="'Courier New', Courier, monospace" font-size="20" font-weight="bold"
        fill="#f0abfc" text-anchor="middle" filter="url(#neonText)" letter-spacing="1">
    Mohammad Reza Noie
  </text>
  <!-- Subtitle -->
  <text x="450" y="52" font-family="'Courier New', Courier, monospace" font-size="11"
        fill="#a78bfa" text-anchor="middle" letter-spacing="3" opacity="0.9">
    ⬡  DIGITAL SOLUTIONS DEVELOPER  ⬡
  </text>

  <!-- === FLOOR REFLECTION === -->
  <rect x="190" y="202" width="530" height="3" fill="#6d28d9" opacity="0.15"/>

  <!-- === PIXEL CORNER DECORATIONS === -->
  <!-- Top left bracket -->
  <polyline points="15,15 15,5 25,5" fill="none" stroke="#f72585" stroke-width="2" opacity="0.7"/>
  <!-- Top right bracket -->
  <polyline points="885,15 885,5 875,5" fill="none" stroke="#f72585" stroke-width="2" opacity="0.7"/>
  <!-- Bottom left bracket -->
  <polyline points="15,265 15,275 25,275" fill="none" stroke="#a855f7" stroke-width="2" opacity="0.7"/>
  <!-- Bottom right bracket -->
  <polyline points="885,265 885,275 875,275" fill="none" stroke="#a855f7" stroke-width="2" opacity="0.7"/>
</svg>

---

<!-- ═══════════════════════════════════════════
     ANIMATED TYPING HEADLINE
════════════════════════════════════════════ -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Mohammad+Reza+%F0%9F%91%8B;Digital+Solutions+Developer;Python+%7C+Web+%7C+Automation+%7C+UI+Design;Build%2C+learn%2C+improve%2C+repeat.)](https://git.io/typing-svg)

<!-- ═══════════════════════════════════════════
     VISITOR COUNTER + PROFILE VIEWS
════════════════════════════════════════════ -->

![Profile Views](https://komarev.com/ghpvc/?username=O-mohammad-o&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/O-mohammad-o?label=Followers&style=for-the-badge&color=f72585&labelColor=0d0520)](https://github.com/O-mohammad-o)

</div>

---

<!-- ═══════════════════════════════════════════
     CODE-BLOCK INTRO
════════════════════════════════════════════ -->

```dart
Map<String, dynamic> mohammad = {
  "Name"       : "Mohammad Reza Noie",
  "Username"   : "O-mohammad-o",
  "Role"       : "Digital Solutions Developer",
  "Location"   : "Karaj, Iran 🇮🇷",
  "Education"  : "Software Engineering — Shamsipour Technical & Vocational College (2024–2028)",
  "GPA"        : "17.5 / 20",
  "Focus"      : ["Python", "Web Development", "Automation", "WordPress", "UI Design"],
  "Currently"  : "Building IoT systems & CRM platforms @ Web Mizban Zagros",
  "Languages"  : {"Persian": "Native 🌐", "English": "Beginner 📖"},
  "Hobbies"    : ["🎙️ Podcasts", "⚽ Sports", "🎬 Movies", "👥 Friends"],
  "OpenTo"     : ["Freelance Projects", "Open Source Collaboration", "Tech Partnerships"],
  "Quote"      : "Build, learn, improve, repeat. 🚀",
};
```

---

<!-- ═══════════════════════════════════════════
     CONNECT / SOCIAL BADGES
════════════════════════════════════════════ -->

<div align="center">

### 🌐 Find Me Online

[![Telegram](https://img.shields.io/badge/Telegram-@m__Noie-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/m_Noie)
[![Instagram](https://img.shields.io/badge/Instagram-@pixlweb.ir-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/pixlweb.ir)
[![Gmail](https://img.shields.io/badge/Gmail-mohammadnoii891-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohammadnoii891@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-O--mohammad--o-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/O-mohammad-o)

</div>

---

<!-- ═══════════════════════════════════════════
     SKILLS & TECH STACK
════════════════════════════════════════════ -->

## 🛠️ Tech Stack & Skills

### 💻 Languages & Core

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

### 🎨 Frontend & Frameworks

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)

### 🌐 CMS & No-Code

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-92003B?style=for-the-badge&logo=elementor&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

### 🎯 Design & UI

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![UI Design](https://img.shields.io/badge/UI%2FUX_Design-A855F7?style=for-the-badge&logo=adobe-xd&logoColor=white)

### ⚙️ Tools & DevOps

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoftoffice&logoColor=white)

### 🌐 Networking

![Network+](https://img.shields.io/badge/CompTIA_Network+-C8202F?style=for-the-badge&logo=comptia&logoColor=white)

---

<!-- ═══════════════════════════════════════════
     GITHUB STATS CARDS
════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=O-mohammad-o&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d0520&title_color=a855f7&icon_color=f72585&text_color=c4b5fd&ring_color=7c3aed" height="180" alt="GitHub Stats"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=O-mohammad-o&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d0520&title_color=a855f7&text_color=c4b5fd&langs_count=8" height="180" alt="Top Languages"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=O-mohammad-o&theme=tokyonight&hide_border=true&background=0d0520&ring=a855f7&fire=f72585&currStreakLabel=c4b5fd&sideLabels=c4b5fd&dates=6d28d9&currStreakNum=f0abfc&sideNums=a855f7)](https://git.io/streak-stats)

</div>

---

<!-- ═══════════════════════════════════════════
     CONTRIBUTION GRAPH
════════════════════════════════════════════ -->

<div align="center">

[![Mohammad's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=O-mohammad-o&theme=tokyo-night&bg_color=0d0520&color=a855f7&line=f72585&point=f0abfc&area=true&hide_border=true)](https://github.com/O-mohammad-o)

</div>

---

<!-- ═══════════════════════════════════════════
     WORK EXPERIENCE TIMELINE
════════════════════════════════════════════ -->

## 💼 Experience

```
◆ WEB MIZBAN ZAGROS — Software Services Group            [Mar 2024 – Present]
  └─ IoT systems · CRM platforms · Device farming
     Software design & dev · UX enhancement · SEO
     🌐 webmizban-zagros.ir

◆ NOTRIKAPLAST — Restaurant Supplies Company             [Aug 2023]
  └─ Digital transformation · CRM implementation
     Modern website design & dev · SEO optimization
     Product management · Digital operations
     🌐 notrikaplast.com

◆ PIXLWEB.IR — Founder & Web Designer / Admin           [Apr 2023]
  └─ WordPress design & management services
     Domain · Hosting · Elementor · Theme/Plugin dev
     Product listing · Content management · Support
     📁 sazoseda.ir   |   olgashopping.com

◆ AKHAVAN INDUSTRIAL GROUP — Web Administrator          [May 2022]
  └─ Website admin & web development
     Content management · UX improvements
     Platform stability & security
```

---

<!-- ═══════════════════════════════════════════
     FEATURED PROJECTS / PORTFOLIO
════════════════════════════════════════════ -->

## 🚀 Portfolio Highlights

<div align="center">

| Project | Role | Stack | Live |
|:--------|:-----|:------|:----:|
| **Sazoseda** | Web Designer | WordPress · Elementor | [🔗 sazoseda.ir](https://sazoseda.ir) |
| **Olga Shopping** | Full Site Build | WordPress · WooCommerce | [🔗 olgashopping.com](https://olgashopping.com) |
| **NotrikaPlast** | Digital Transformation | WordPress · CRM · SEO | [🔗 notrikaplast.com](https://notrikaplast.com) |
| **Web Mizban Zagros** | Software Dev | IoT · CRM · Web | [🔗 webmizban-zagros.ir](https://webmizban-zagros.ir) |

</div>

---

<!-- ═══════════════════════════════════════════
     EDUCATION
════════════════════════════════════════════ -->

## 🎓 Education

```python
education = {
    "institution" : "Shamsipour Technical and Vocational College",
    "major"       : "Software Engineering",
    "period"      : "2024 — 2028",
    "grade"       : "17.5 / 20  ⭐",
    "location"    : "Tehran, Iran",
}
```

---

<!-- ═══════════════════════════════════════════
     CURRENTLY LEARNING / GOALS
════════════════════════════════════════════ -->

## 🌱 Currently Learning & Building

- 🤖 **Automation workflows** with Python & n8n
- ⚛️ **React ecosystem** — hooks, patterns, React Query
- 🏗️ **IoT & embedded systems** integration
- 📐 **Advanced UI/UX** principles & design systems
- 🐧 **Linux system administration** & DevOps basics

---

<!-- ═══════════════════════════════════════════
     QUOTE / FOOTER
════════════════════════════════════════════ -->

<div align="center">

---

### 💬 Motto

> *"Build, learn, improve, repeat."*  — Mohammad Reza Noie

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer&text=Thanks%20for%20visiting!&fontSize=24&fontColor=c4b5fd&animation=twinkling&fontAlignY=70" width="100%"/>

</div>
