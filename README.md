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
