<svg width="900" height="260" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#131a24"/>
    </linearGradient>
    <linearGradient id="glow" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#3fb950"/>
      <stop offset="50%" stop-color="#58a6ff"/>
      <stop offset="100%" stop-color="#bc8cff"/>
    </linearGradient>
  </defs>

  <!-- window -->
  <rect x="2" y="2" width="896" height="256" rx="14" fill="url(#bg)" stroke="#30363d" stroke-width="1.5"/>
  <rect x="2" y="2" width="896" height="256" rx="14" fill="none" stroke="url(#glow)" stroke-width="1" opacity="0.35"/>

  <!-- title bar -->
  <rect x="2" y="2" width="896" height="34" rx="14" fill="#161b22"/>
  <rect x="2" y="20" width="896" height="16" fill="#161b22"/>
  <circle cx="26" cy="19" r="6" fill="#ff5f56"/>
  <circle cx="46" cy="19" r="6" fill="#ffbd2e"/>
  <circle cx="66" cy="19" r="6" fill="#27c93f"/>
  <text x="450" y="24" font-family="SFMono-Regular,Consolas,monospace" font-size="12" fill="#8b949e" text-anchor="middle">dawood@github: ~</text>

  <!-- terminal body -->
  <text font-family="SFMono-Regular,Consolas,Menlo,monospace" font-size="16" fill="#c9d1d9">
    <tspan x="28" y="70"><tspan fill="#3fb950">dawood@github</tspan><tspan fill="#8b949e">:</tspan><tspan fill="#58a6ff">~</tspan><tspan fill="#8b949e">$</tspan> whoami</tspan>
    <tspan x="28" y="100" fill="#e6edf3">Muhammad Dawood — student, builder, permanently mid-tutorial</tspan>

    <tspan x="28" y="140"><tspan fill="#3fb950">dawood@github</tspan><tspan fill="#8b949e">:</tspan><tspan fill="#58a6ff">~</tspan><tspan fill="#8b949e">$</tspan> status --current</tspan>
    <tspan x="28" y="170" fill="#e6edf3">learning fast, shipping slow, breaking things on purpose</tspan>

    <tspan x="28" y="210"><tspan fill="#3fb950">dawood@github</tspan><tspan fill="#8b949e">:</tspan><tspan fill="#58a6ff">~</tspan><tspan fill="#8b949e">$</tspan> <tspan fill="#e6edf3">_</tspan>
      <animate attributeName="opacity" values="1;1;0;0;1" dur="1.2s" repeatCount="indefinite"/>
    </tspan>
  </text>
</svg>
