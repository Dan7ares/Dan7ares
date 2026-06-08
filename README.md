<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="1200" height="320" font-family="'Segoe UI',Roboto,Helvetica,Arial,sans-serif">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#05060f"/>
      <stop offset="55%" stop-color="#0a1430"/>
      <stop offset="100%" stop-color="#04101f"/>
    </linearGradient>
    <linearGradient id="accent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00d4ff">
        <animate attributeName="stop-color" values="#00d4ff;#7c3aed;#00ff9c;#00d4ff" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#7c3aed">
        <animate attributeName="stop-color" values="#7c3aed;#00ff9c;#00d4ff;#7c3aed" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <radialGradient id="node" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00ff9c"/>
      <stop offset="100%" stop-color="#00d4ff"/>
    </radialGradient>
  </defs>

  <rect width="1200" height="320" fill="url(#bg)"/>

  <!-- ░ neural network ░ -->
  <g stroke="url(#accent)" stroke-width="1" opacity="0.45">
    <line x1="120" y1="70" x2="320" y2="150" stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="1.2s" repeatCount="indefinite"/></line>
    <line x1="320" y1="150" x2="180" y2="250" stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="1.6s" repeatCount="indefinite"/></line>
    <line x1="320" y1="150" x2="520" y2="80"  stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="1.4s" repeatCount="indefinite"/></line>
    <line x1="320" y1="150" x2="540" y2="240" stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="2s" repeatCount="indefinite"/></line>
    <line x1="950" y1="60"  x2="1080" y2="150" stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="1.5s" repeatCount="indefinite"/></line>
    <line x1="1080" y1="150" x2="930" y2="250" stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="1.7s" repeatCount="indefinite"/></line>
    <line x1="1080" y1="150" x2="880" y2="110" stroke-dasharray="6 8"><animate attributeName="stroke-dashoffset" values="0;-28" dur="1.3s" repeatCount="indefinite"/></line>
  </g>
  <g fill="url(#node)" filter="url(#glow)">
    <circle cx="120" cy="70" r="5"><animate attributeName="r" values="4;7;4" dur="2.4s" repeatCount="indefinite"/></circle>
    <circle cx="320" cy="150" r="6"><animate attributeName="r" values="5;9;5" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="180" cy="250" r="5"><animate attributeName="r" values="4;7;4" dur="2.1s" repeatCount="indefinite"/></circle>
    <circle cx="520" cy="80" r="4"><animate attributeName="r" values="3;6;3" dur="2.7s" repeatCount="indefinite"/></circle>
    <circle cx="540" cy="240" r="4"><animate attributeName="r" values="3;6;3" dur="2.3s" repeatCount="indefinite"/></circle>
    <circle cx="950" cy="60" r="5"><animate attributeName="r" values="4;7;4" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="1080" cy="150" r="6"><animate attributeName="r" values="5;9;5" dur="3.2s" repeatCount="indefinite"/></circle>
    <circle cx="930" cy="250" r="5"><animate attributeName="r" values="4;7;4" dur="2.2s" repeatCount="indefinite"/></circle>
    <circle cx="880" cy="110" r="4"><animate attributeName="r" values="3;6;3" dur="2.6s" repeatCount="indefinite"/></circle>
  </g>

  <!-- ░ name ░ -->
  <text x="600" y="150" text-anchor="middle" font-size="52" font-weight="800" fill="#ffffff" letter-spacing="2" filter="url(#glow)">
    DANIEL SANTIAGO AMAYA
    <animate attributeName="opacity" values="0;1" dur="1.2s" fill="freeze"/>
  </text>

  <!-- accent underline -->
  <rect x="430" y="172" width="340" height="3" rx="1.5" fill="url(#accent)">
    <animate attributeName="width" values="0;340" dur="1.4s" fill="freeze"/>
    <animate attributeName="x" values="600;430" dur="1.4s" fill="freeze"/>
  </rect>

  <!-- ░ rotating roles ░ -->
  <g text-anchor="middle" font-size="22" font-weight="600">
    <text x="600" y="218" fill="#00d4ff" opacity="0">Technical Project Manager  ·  AI Solutions
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.04;0.24;0.28" dur="9.6s" begin="1.2s" repeatCount="indefinite"/>
    </text>
    <text x="600" y="218" fill="#7c3aed" opacity="0">Prompt Engineer  ·  LLM Architect
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.04;0.24;0.28" dur="9.6s" begin="3.6s" repeatCount="indefinite"/>
    </text>
    <text x="600" y="218" fill="#00ff9c" opacity="0">Automation @ Ernst &amp; Young (EY)
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.04;0.24;0.28" dur="9.6s" begin="6s" repeatCount="indefinite"/>
    </text>
    <text x="600" y="218" fill="#ffd166" opacity="0">Open to Remote  ·  US · EU · LATAM
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.04;0.24;0.28" dur="9.6s" begin="8.4s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- blinking cursor -->
  <rect x="772" y="202" width="3" height="22" fill="#00ff9c">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>

  <!-- status pill -->
  <g transform="translate(600,262)">
    <rect x="-120" y="0" width="240" height="30" rx="15" fill="#0d1b2a" stroke="url(#accent)" stroke-width="1.2"/>
    <circle cx="-95" cy="15" r="5" fill="#22c55e"><animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite"/></circle>
    <text x="12" y="20" text-anchor="middle" font-size="13" font-weight="600" fill="#d6e4ff">AVAILABLE FOR HIRE  ·  GMT-5</text>
  </g>
</svg>
