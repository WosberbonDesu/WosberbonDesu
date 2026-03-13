<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d0221"/>
      <stop offset="50%" style="stop-color:#150050"/>
      <stop offset="100%" style="stop-color:#0d0221"/>
    </linearGradient>
    <linearGradient id="neonCyan" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00d4ff;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="rocketBody" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#a78bfa"/>
      <stop offset="100%" style="stop-color:#00d4ff"/>
    </linearGradient>
    <linearGradient id="flame" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00ffc8"/>
      <stop offset="40%" style="stop-color:#00d4ff"/>
      <stop offset="100%" style="stop-color:#a78bfa;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glowStrong">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <radialGradient id="star" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ffffff;stop-opacity:0"/>
    </radialGradient>
  </defs>
  
  <!-- Background -->
  <rect width="900" height="200" fill="url(#bgGrad)" rx="12"/>
  
  <!-- Stars -->
  <circle cx="50" cy="30" r="1.5" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="80" r="1" fill="white" opacity="0.6">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="25" r="1.2" fill="white" opacity="0.7">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="380" cy="55" r="1" fill="white" opacity="0.5">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="520" cy="35" r="1.3" fill="white" opacity="0.9">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="70" r="1" fill="white" opacity="0.6">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="780" cy="20" r="1.5" fill="white" opacity="0.8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="850" cy="90" r="1" fill="white" opacity="0.5">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="100" cy="150" r="1.2" fill="white" opacity="0.7">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="2.1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="140" r="1" fill="white" opacity="0.6">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="160" r="1.3" fill="white" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="310" cy="130" r="0.8" fill="white" opacity="0.5">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.9s" repeatCount="indefinite"/>
  </circle>
  <circle cx="590" cy="110" r="1.1" fill="white" opacity="0.6">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="820" cy="160" r="0.9" fill="white" opacity="0.7">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.7s" repeatCount="indefinite"/>
  </circle>

  <!-- Rocket -->
  <g transform="translate(100, 40)" filter="url(#glow)">
    <!-- Flame trail -->
    <path d="M30,120 Q25,140 20,165 Q30,155 40,165 Q35,140 30,120" fill="url(#flame)" opacity="0.9">
      <animate attributeName="d" values="M30,120 Q25,140 20,165 Q30,155 40,165 Q35,140 30,120;M30,120 Q22,145 18,170 Q30,158 42,170 Q38,145 30,120;M30,120 Q25,140 20,165 Q30,155 40,165 Q35,140 30,120" dur="0.5s" repeatCount="indefinite"/>
    </path>
    <!-- Rocket body -->
    <path d="M30,20 L20,50 L15,90 L20,120 L40,120 L45,90 L40,50 Z" fill="url(#rocketBody)" stroke="#00d4ff" stroke-width="0.5"/>
    <!-- Nose cone -->
    <path d="M30,5 L20,50 L40,50 Z" fill="#a78bfa" stroke="#00d4ff" stroke-width="0.5"/>
    <!-- Window -->
    <circle cx="30" cy="60" r="7" fill="#0d0221" stroke="#00ffc8" stroke-width="1.5"/>
    <circle cx="30" cy="60" r="4" fill="#00d4ff" opacity="0.3"/>
    <!-- Fins -->
    <path d="M15,90 L5,115 L15,115 Z" fill="#a78bfa" stroke="#00d4ff" stroke-width="0.5"/>
    <path d="M45,90 L55,115 L45,115 Z" fill="#a78bfa" stroke="#00d4ff" stroke-width="0.5"/>
    <!-- Particles -->
    <circle cx="25" cy="145" r="2" fill="#00ffc8" opacity="0.6">
      <animate attributeName="cy" values="145;180;145" dur="1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.8;0;0.8" dur="1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="35" cy="150" r="1.5" fill="#00d4ff" opacity="0.5">
      <animate attributeName="cy" values="150;185;150" dur="0.8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0;0.7" dur="0.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="30" cy="155" r="1" fill="#a78bfa" opacity="0.4">
      <animate attributeName="cy" values="155;190;155" dur="1.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0;0.6" dur="1.2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Text -->
  <text x="200" y="75" font-family="'Courier New', monospace" font-size="14" fill="#6e7681" letter-spacing="6">SYSTEM STATUS</text>
  <text x="200" y="110" font-family="'Courier New', monospace" font-size="28" fill="#00d4ff" font-weight="bold" filter="url(#glow)" letter-spacing="2">MISSION: BUILD THE FUTURE</text>
  <text x="200" y="145" font-family="'Courier New', monospace" font-size="13" fill="#a78bfa" letter-spacing="3">FULL-STACK • AI • CLOUD • ARCHITECTURE</text>
  
  <!-- Status indicators -->
  <circle cx="200" cy="170" r="4" fill="#00ffc8" filter="url(#glow)">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="212" y="174" font-family="'Courier New', monospace" font-size="11" fill="#00ffc8">ALL SYSTEMS OPERATIONAL</text>

  <!-- Right side decoration - orbital rings -->
  <g transform="translate(790, 100)">
    <ellipse cx="0" cy="0" rx="50" ry="15" fill="none" stroke="#00d4ff" stroke-width="0.5" opacity="0.3" transform="rotate(-20)"/>
    <ellipse cx="0" cy="0" rx="65" ry="20" fill="none" stroke="#a78bfa" stroke-width="0.5" opacity="0.2" transform="rotate(10)"/>
    <circle cx="0" cy="0" r="8" fill="#150050" stroke="#00d4ff" stroke-width="1" filter="url(#glow)"/>
    <circle cx="0" cy="0" r="3" fill="#00d4ff" opacity="0.5"/>
    <!-- Orbiting dot -->
    <circle r="3" fill="#00ffc8" filter="url(#glow)">
      <animateMotion dur="4s" repeatCount="indefinite">
        <mpath href="#orbit1"/>
      </animateMotion>
    </circle>
  </g>
  <path id="orbit1" d="M740,100 A50,15 -20 1,1 740.01,100" fill="none" stroke="none"/>
  
  <!-- Neon line bottom -->
  <rect x="0" y="196" width="900" height="4" fill="url(#neonCyan)" opacity="0.6"/>
</svg>
