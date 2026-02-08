<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 370" width="900" height="370">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#040d21"/>
      <stop offset="50%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#040d21"/>
    </linearGradient>
    <linearGradient id="desk" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#1a1a2e"/>
      <stop offset="100%" style="stop-color:#0f0f1a"/>
    </linearGradient>
    <linearGradient id="neon1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff006e; stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#8338ec; stop-opacity:0.4"/>
      <stop offset="100%" style="stop-color:#3a86ff; stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="neon2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06d6a0; stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#8338ec; stop-opacity:0.3"/>
      <stop offset="100%" style="stop-color:#ff006e; stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="skin" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#f5d0a9"/>
      <stop offset="100%" style="stop-color:#e0a87c"/>
    </linearGradient>
    <linearGradient id="mug" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#5c3d2e"/>
      <stop offset="100%" style="stop-color:#3d2518"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="bigGlow">
      <feGaussianBlur stdDeviation="8" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="shadow">
      <feGaussianBlur in="SourceAlpha" stdDeviation="3" result="blur"/>
      <feOffset dx="1" dy="2" result="offsetBlur"/>
      <feFlood flood-color="#000" flood-opacity="0.5" result="color"/>
      <feComposite in="color" in2="offsetBlur" operator="in" result="shadow"/>
      <feMerge>
        <feMergeNode in="shadow"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <clipPath id="screenClip">
      <rect x="228" y="76" width="330" height="172" rx="3"/>
    </clipPath>
    <linearGradient id="btm" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#040d21;stop-opacity:0"/>
      <stop offset="100%" style="stop-color:#040d21;stop-opacity:1"/>
    </linearGradient>
  </defs>

  <style>
    @keyframes twinkle { 0%,100%{opacity:.15} 50%{opacity:1} }
    @keyframes matrixFall { 0%{transform:translateY(-120px)} 100%{transform:translateY(400px)} }
    @keyframes cursorBlink { 0%,49%{opacity:1} 50%,100%{opacity:0} }
    @keyframes headBob { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-2px)} }
    @keyframes handType { 0%,100%{transform:translateY(0)} 30%{transform:translateY(-1.5px)} 60%{transform:translateY(0)} 80%{transform:translateY(-1px)} }
    @keyframes steam1 { 0%{transform:translate(0,0);opacity:.5} 50%{transform:translate(4px,-14px);opacity:.25} 100%{transform:translate(-2px,-28px);opacity:0} }
    @keyframes steam2 { 0%{transform:translate(0,0);opacity:.4} 50%{transform:translate(-5px,-16px);opacity:.2} 100%{transform:translate(3px,-32px);opacity:0} }
    @keyframes steam3 { 0%{transform:translate(0,0);opacity:.35} 50%{transform:translate(3px,-12px);opacity:.18} 100%{transform:translate(-4px,-26px);opacity:0} }
    @keyframes float1 { 0%{transform:translateY(0) rotate(0);opacity:.6} 100%{transform:translateY(-80px) rotate(15deg);opacity:0} }
    @keyframes float2 { 0%{transform:translateY(0) rotate(0);opacity:.5} 100%{transform:translateY(-90px) rotate(-18deg);opacity:0} }
    @keyframes float3 { 0%{transform:translateY(0) rotate(0);opacity:.55} 100%{transform:translateY(-70px) rotate(12deg);opacity:0} }
    @keyframes neonPulse { 0%,100%{opacity:.15} 50%{opacity:.35} }
    @keyframes neonPulse2 { 0%,100%{opacity:.1} 50%{opacity:.25} }
    @keyframes screenGlow { 0%,100%{opacity:.03} 50%{opacity:.06} }
    @keyframes eq1 { 0%,100%{transform:scaleY(1)} 25%{transform:scaleY(3.3)} 50%{transform:scaleY(1.7)} 75%{transform:scaleY(4.3)} }
    @keyframes eq2 { 0%,100%{transform:scaleY(2.3)} 25%{transform:scaleY(1.3)} 50%{transform:scaleY(4.7)} 75%{transform:scaleY(2)} }
    @keyframes eq3 { 0%,100%{transform:scaleY(1.7)} 33%{transform:scaleY(4)} 66%{transform:scaleY(1)} }
    @keyframes eq4 { 0%,100%{transform:scaleY(3)} 30%{transform:scaleY(1.3)} 60%{transform:scaleY(3.7)} }
    @keyframes eq5 { 0%,100%{transform:scaleY(1.3)} 40%{transform:scaleY(4.3)} 70%{transform:scaleY(2)} }
    @keyframes catTail { 0%,100%{transform:rotate(0)} 50%{transform:rotate(8deg)} }
    @keyframes catBreath { 0%,100%{transform:scaleY(1)} 50%{transform:scaleY(1.04)} }
    @keyframes plantSway { 0%,100%{transform:rotate(0)} 50%{transform:rotate(3deg)} }
    @keyframes glassReflect { 0%,100%{opacity:.3} 30%{opacity:.5} 60%{opacity:.2} }
    .s{animation:twinkle 3s ease-in-out infinite}
    .m{animation:matrixFall linear infinite;font-family:monospace;font-size:10px;fill:#39ff14}
    .cb{animation:cursorBlink .8s step-end infinite}
    .hb{animation:headBob 3s ease-in-out infinite}
    .ht{animation:handType .35s ease-in-out infinite}
    .st1{animation:steam1 2.5s ease-out infinite}
    .st2{animation:steam2 3s ease-out infinite .7s}
    .st3{animation:steam3 2.8s ease-out infinite 1.4s}
    .f1{animation:float1 5s ease-out infinite}
    .f2{animation:float2 6s ease-out infinite 1s}
    .f3{animation:float3 4.5s ease-out infinite 2s}
    .np{animation:neonPulse 3s ease-in-out infinite}
    .np2{animation:neonPulse2 4s ease-in-out infinite 1.5s}
    .sg{animation:screenGlow 4s ease-in-out infinite}
    .eq1{animation:eq1 .6s ease-in-out infinite;transform-origin:center bottom}
    .eq2{animation:eq2 .7s ease-in-out infinite .1s;transform-origin:center bottom}
    .eq3{animation:eq3 .5s ease-in-out infinite .05s;transform-origin:center bottom}
    .eq4{animation:eq4 .65s ease-in-out infinite .15s;transform-origin:center bottom}
    .eq5{animation:eq5 .55s ease-in-out infinite .08s;transform-origin:center bottom}
    .ct{animation:catTail 2.5s ease-in-out infinite;transform-origin:748px 258px}
    .cbr{animation:catBreath 3s ease-in-out infinite;transform-origin:735px 258px}
    .ps{animation:plantSway 4s ease-in-out infinite;transform-origin:118px 245px}
    .gr{animation:glassReflect 2s ease-in-out infinite}
  </style>

  <!-- ===== BACKGROUND ===== -->
  <rect width="900" height="370" fill="url(#bg)"/>

  <!-- Stars -->
  <circle cx="45" cy="20" r="1" fill="#fff" class="s"/><circle cx="130" cy="40" r=".7" fill="#fff" class="s" style="animation-delay:.5s"/>
  <circle cx="210" cy="12" r="1.1" fill="#fff" class="s" style="animation-delay:1.2s"/><circle cx="310" cy="32" r=".6" fill="#c9d1d9" class="s" style="animation-delay:.8s"/>
  <circle cx="420" cy="18" r="1.2" fill="#58a6ff" class="s" style="animation-delay:2s"/><circle cx="520" cy="38" r=".8" fill="#fff" class="s" style="animation-delay:1.5s"/>
  <circle cx="600" cy="14" r=".9" fill="#c9d1d9" class="s" style="animation-delay:.3s"/><circle cx="680" cy="28" r="1" fill="#fff" class="s" style="animation-delay:1.8s"/>
  <circle cx="770" cy="42" r=".7" fill="#58a6ff" class="s" style="animation-delay:.7s"/><circle cx="850" cy="20" r=".8" fill="#fff" class="s" style="animation-delay:2.5s"/>
  <circle cx="75" cy="55" r=".5" fill="#fff" class="s" style="animation-delay:1s"/><circle cx="490" cy="50" r=".6" fill="#c9d1d9" class="s" style="animation-delay:1.7s"/>
  <circle cx="370" cy="8" r=".9" fill="#fff" class="s" style="animation-delay:.4s"/><circle cx="740" cy="10" r=".7" fill="#fff" class="s" style="animation-delay:2.2s"/>
  <circle cx="160" cy="48" r="1" fill="#8338ec" class="s" style="animation-delay:1.1s"/><circle cx="830" cy="52" r=".8" fill="#8338ec" class="s" style="animation-delay:.6s"/>

  <!-- ===== MATRIX RAIN ===== -->
  <g opacity=".12">
    <text class="m" x="35" style="animation-duration:7s"><tspan x="35" dy="0">1</tspan><tspan x="35" dy="14">0</tspan><tspan x="35" dy="14">{</tspan><tspan x="35" dy="14">;</tspan><tspan x="35" dy="14">}</tspan><tspan x="35" dy="14">0</tspan><tspan x="35" dy="14">=</tspan><tspan x="35" dy="14">1</tspan></text>
    <text class="m" x="95" style="animation-duration:9s;animation-delay:2s" opacity=".8"><tspan x="95" dy="0">0</tspan><tspan x="95" dy="14">}</tspan><tspan x="95" dy="14">1</tspan><tspan x="95" dy="14">&lt;</tspan><tspan x="95" dy="14">0</tspan><tspan x="95" dy="14">/</tspan><tspan x="95" dy="14">1</tspan></text>
    <text class="m" x="170" style="animation-duration:6s;animation-delay:1s"><tspan x="170" dy="0">{</tspan><tspan x="170" dy="14">1</tspan><tspan x="170" dy="14">0</tspan><tspan x="170" dy="14">)</tspan><tspan x="170" dy="14">;</tspan><tspan x="170" dy="14">1</tspan></text>
    <text class="m" x="650" style="animation-duration:8s;animation-delay:3s" opacity=".7"><tspan x="650" dy="0">;</tspan><tspan x="650" dy="14">0</tspan><tspan x="650" dy="14">=</tspan><tspan x="650" dy="14">1</tspan><tspan x="650" dy="14">{</tspan><tspan x="650" dy="14">0</tspan><tspan x="650" dy="14">}</tspan></text>
    <text class="m" x="720" style="animation-duration:6.5s;animation-delay:.5s"><tspan x="720" dy="0">1</tspan><tspan x="720" dy="14">&gt;</tspan><tspan x="720" dy="14">0</tspan><tspan x="720" dy="14">(</tspan><tspan x="720" dy="14">1</tspan><tspan x="720" dy="14">0</tspan></text>
    <text class="m" x="800" style="animation-duration:7.5s;animation-delay:1.5s" opacity=".9"><tspan x="800" dy="0">0</tspan><tspan x="800" dy="14">1</tspan><tspan x="800" dy="14">+</tspan><tspan x="800" dy="14">0</tspan><tspan x="800" dy="14">;</tspan><tspan x="800" dy="14">1</tspan><tspan x="800" dy="14">[</tspan></text>
    <text class="m" x="860" style="animation-duration:8.5s;animation-delay:4s" opacity=".6"><tspan x="860" dy="0">]</tspan><tspan x="860" dy="14">1</tspan><tspan x="860" dy="14">0</tspan><tspan x="860" dy="14">*</tspan><tspan x="860" dy="14">1</tspan></text>
    <text class="m" x="55" style="animation-duration:10s;animation-delay:5s" opacity=".5"><tspan x="55" dy="0">&lt;</tspan><tspan x="55" dy="14">/</tspan><tspan x="55" dy="14">&gt;</tspan><tspan x="55" dy="14">0</tspan><tspan x="55" dy="14">1</tspan></text>
  </g>

  <!-- ===== AMBIENT SCREEN GLOW ===== -->
  <ellipse cx="395" cy="160" rx="220" ry="130" fill="#58a6ff" opacity=".03" class="sg"/>
  <ellipse cx="395" cy="160" rx="160" ry="90" fill="#8338ec" opacity=".02" class="sg" style="animation-delay:2s"/>

  <!-- ===== DESK ===== -->
  <rect x="40" y="248" width="820" height="10" rx="2" fill="url(#desk)" filter="url(#shadow)"/>
  <rect x="40" y="256" width="820" height="3" fill="#080810"/>
  <!-- Desk legs -->
  <rect x="80" y="259" width="6" height="111" fill="#080810"/><rect x="814" y="259" width="6" height="111" fill="#080810"/>

  <!-- ===== NEON UNDERGLOW ===== -->
  <rect x="100" y="252" width="700" height="6" rx="3" fill="url(#neon1)" class="np"/>
  <rect x="150" y="254" width="600" height="4" rx="2" fill="url(#neon2)" class="np2"/>
  <ellipse cx="450" cy="258" rx="300" ry="15" fill="#8338ec" opacity=".06" class="np"/>

  <!-- ===== MONITOR ===== -->
  <g filter="url(#shadow)">
    <!-- Monitor frame -->
    <rect x="220" y="68" width="346" height="180" rx="8" fill="#111" stroke="#222" stroke-width="1.5"/>
    <!-- Webcam dot -->
    <circle cx="393" cy="73" r="1.5" fill="#222"/><circle cx="393" cy="73" r=".7" fill="#0a0a0a"/>
    <!-- Screen -->
    <rect x="228" y="76" width="330" height="164" rx="3" fill="#0d1117"/>
    <!-- Screen subtle glow overlay -->
    <rect x="228" y="76" width="330" height="164" rx="3" fill="#58a6ff" opacity=".015" class="sg"/>
    <!-- Monitor stand -->
    <rect x="370" y="244" width="46" height="8" rx="3" fill="#111" stroke="#222" stroke-width="1"/>
    <rect x="383" y="240" width="20" height="12" fill="#111"/>
    <!-- Chin -->
    <rect x="220" y="240" width="346" height="6" rx="0" fill="#111"/>
    <circle cx="393" cy="243" r="2" fill="#1a1a1a"/>
  </g>

  <!-- ===== CODE ON SCREEN (looping) ===== -->
  <g clip-path="url(#screenClip)">
    <!-- Tab bar -->
    <rect x="228" y="76" width="330" height="14" fill="#161b22"/>
    <rect x="232" y="76" width="85" height="14" fill="#0d1117"/>
    <text x="240" y="86" fill="#58a6ff" font-size="7" font-family="monospace">Developer.java</text>
    <circle cx="312" cy="83" r="2.5" fill="#282828"/><text x="310" y="85.5" fill="#666" font-size="5">x</text>
    <rect x="319" y="76" width="70" height="14" fill="#161b22"/>
    <text x="326" y="86" fill="#666" font-size="7" font-family="monospace">Terminal</text>

    <!-- Line numbers -->
    <text fill="#3b4048" font-size="7.5" font-family="monospace">
      <tspan x="233" y="102">1</tspan><tspan x="233" y="113">2</tspan><tspan x="233" y="124">3</tspan>
      <tspan x="233" y="135">4</tspan><tspan x="233" y="146">5</tspan><tspan x="233" y="157">6</tspan>
      <tspan x="233" y="168">7</tspan><tspan x="233" y="179">8</tspan><tspan x="233" y="190">9</tspan>
      <tspan x="230" y="201">10</tspan><tspan x="230" y="212">11</tspan><tspan x="230" y="223">12</tspan>
    </text>

    <!-- Code Line 1: public class Developer { -->
    <text x="248" y="102" fill="#ff79c6" font-size="8" font-family="monospace" opacity="0">public class<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.025;.05;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="315" y="102" fill="#50fa7b" font-size="8" font-family="monospace" opacity="0">Developer<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.05;.075;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="370" y="102" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">{<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.075;.09;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 2: String name = "Ankit"; -->
    <text x="258" y="113" fill="#ff79c6" font-size="8" font-family="monospace" opacity="0">String<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.1;.12;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="296" y="113" fill="#bd93f9" font-size="8" font-family="monospace" opacity="0">name<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.13;.15;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="320" y="113" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">=<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.155;.17;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="330" y="113" fill="#f1fa8c" font-size="8" font-family="monospace" opacity="0">"Ankit"<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.17;.2;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="370" y="113" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">;<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.2;.21;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 3: String role = "Full Stack Dev"; -->
    <text x="258" y="124" fill="#ff79c6" font-size="8" font-family="monospace" opacity="0">String<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.22;.24;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="296" y="124" fill="#bd93f9" font-size="8" font-family="monospace" opacity="0">role<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.25;.27;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="320" y="124" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">=<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.27;.28;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="330" y="124" fill="#f1fa8c" font-size="8" font-family="monospace" opacity="0">"Full Stack Dev"<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.28;.32;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="420" y="124" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">;<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.32;.33;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 4: empty -->

    <!-- Code Line 5: void code() { -->
    <text x="258" y="146" fill="#ff79c6" font-size="8" font-family="monospace" opacity="0">void<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.34;.36;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="286" y="146" fill="#50fa7b" font-size="8" font-family="monospace" opacity="0">code<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.37;.39;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="312" y="146" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">() {<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.39;.41;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 6: learn("DSA"); -->
    <text x="268" y="157" fill="#8be9fd" font-size="8" font-family="monospace" opacity="0">learn<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.42;.44;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="300" y="157" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">(<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.44;.45;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="306" y="157" fill="#f1fa8c" font-size="8" font-family="monospace" opacity="0">"DSA"<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.45;.48;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="336" y="157" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">);<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.48;.49;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 7: build("systems"); -->
    <text x="268" y="168" fill="#8be9fd" font-size="8" font-family="monospace" opacity="0">build<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.5;.52;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="300" y="168" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">(<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.52;.53;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="306" y="168" fill="#f1fa8c" font-size="8" font-family="monospace" opacity="0">"systems"<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.53;.56;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="356" y="168" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">);<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.56;.57;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 8: deploy(); -->
    <text x="268" y="179" fill="#8be9fd" font-size="8" font-family="monospace" opacity="0">deploy<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.58;.6;.6;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="306" y="179" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">();<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.6;.62;.62;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 9: } -->
    <text x="258" y="190" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">}<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.63;.65;.65;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 11: while(alive) { code(); } -->
    <text x="258" y="212" fill="#ff79c6" font-size="8" font-family="monospace" opacity="0">while<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.66;.68;.68;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="290" y="212" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">(alive) {<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.68;.71;.71;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="345" y="212" fill="#50fa7b" font-size="8" font-family="monospace" opacity="0">code();<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.71;.74;.74;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>
    <text x="390" y="212" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">}<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.74;.75;.75;.75;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Code Line 12: } -->
    <text x="248" y="223" fill="#c9d1d9" font-size="8" font-family="monospace" opacity="0">}<animate attributeName="opacity" values="0;0;1;1;1;0;0" keyTimes="0;.75;.76;.76;.76;.8;1" dur="16s" repeatCount="indefinite"/></text>

    <!-- Blinking cursor -->
    <rect x="256" y="225" width="5" height="9" fill="#58a6ff" class="cb"/>
  </g>

  <!-- ===== PLANT (left side) ===== -->
  <g class="ps">
    <path d="M108,248 L112,230 L125,230 L129,248 Z" fill="#c4652a"/>
    <rect x="110" y="227" width="18" height="4" rx="1" fill="#d4753a"/>
    <path d="M118,227 Q112,205 100,196" stroke="#2ecc71" stroke-width="1.5" fill="none"/>
    <ellipse cx="99" cy="194" rx="6" ry="4" fill="#2ecc71" transform="rotate(-25 99 194)"/>
    <path d="M118,227 Q124,202 134,192" stroke="#27ae60" stroke-width="1.5" fill="none"/>
    <ellipse cx="135" cy="190" rx="7" ry="4" fill="#27ae60" transform="rotate(18 135 190)"/>
    <path d="M118,227 Q118,208 118,195" stroke="#2ecc71" stroke-width="1.5" fill="none"/>
    <ellipse cx="118" cy="193" rx="5" ry="4" fill="#2ecc71"/>
  </g>

  <!-- ===== DEVELOPER CHARACTER ===== -->
  <g>
    <!-- Gaming chair -->
    <rect x="340" y="292" width="106" height="8" rx="4" fill="#1a1a2e"/>
    <ellipse cx="393" cy="304" rx="28" ry="4" fill="#111"/>
    <rect x="342" y="250" width="6" height="46" rx="2" fill="#222"/>
    <rect x="438" y="250" width="6" height="46" rx="2" fill="#222"/>
    <path d="M342,248 Q393,255 444,248 L442,230 Q393,237 344,230 Z" fill="#1a1a2e"/>
    <!-- Chair back with accent -->
    <rect x="340" y="172" width="5" height="62" rx="2" fill="#222"/>
    <rect x="441" y="172" width="5" height="62" rx="2" fill="#222"/>
    <path d="M340,172 Q393,167 446,172 L446,230 Q393,235 340,230 Z" fill="#1a1a2e"/>
    <path d="M340,172 Q393,167 446,172 L446,180 Q393,175 340,180 Z" fill="#8338ec" opacity=".3"/>

    <!-- Body -->
    <path d="M365,202 Q393,197 421,202 L426,244 Q393,249 360,244 Z" fill="#1e1e3f"/>
    <!-- Hoodie line -->
    <line x1="393" y1="207" x2="393" y2="244" stroke="#2a2a5f" stroke-width=".5" opacity=".5"/>
    <path d="M385,202 Q393,215 401,202" stroke="#2a2a5f" stroke-width=".8" fill="none"/>

    <!-- Arms -->
    <g class="ht">
      <path d="M365,215 Q345,230 335,244" stroke="#1e1e3f" stroke-width="11" fill="none" stroke-linecap="round"/>
      <circle cx="335" cy="246" r="5" fill="url(#skin)"/>
      <path d="M421,215 Q441,230 450,244" stroke="#1e1e3f" stroke-width="11" fill="none" stroke-linecap="round"/>
      <circle cx="450" cy="246" r="5" fill="url(#skin)"/>
    </g>

    <!-- Head -->
    <g class="hb">
      <rect x="387" y="187" width="12" height="12" fill="url(#skin)"/>
      <ellipse cx="393" cy="177" rx="20" ry="22" fill="url(#skin)"/>
      <!-- Hair -->
      <path d="M373,172 Q375,152 393,148 Q411,152 413,172" fill="#0d0d1a"/>
      <path d="M371,177 Q373,157 393,152 Q413,157 415,177" fill="#0d0d1a"/>
      <!-- Glasses frame -->
      <rect x="380" y="173" width="12" height="9" rx="3" stroke="#555" stroke-width=".8" fill="none"/>
      <rect x="396" y="173" width="12" height="9" rx="3" stroke="#555" stroke-width=".8" fill="none"/>
      <line x1="392" y1="177" x2="396" y2="177" stroke="#555" stroke-width=".8"/>
      <!-- Screen reflection in glasses -->
      <rect x="381" y="174" width="10" height="7" rx="2" fill="#58a6ff" opacity=".08" class="gr"/>
      <rect x="397" y="174" width="10" height="7" rx="2" fill="#58a6ff" opacity=".08" class="gr"/>
      <!-- Eyes behind glasses -->
      <ellipse cx="386" cy="177" rx="2.5" ry="2" fill="#fff"/>
      <ellipse cx="402" cy="177" rx="2.5" ry="2" fill="#fff"/>
      <circle cx="387" cy="177" r="1.2" fill="#0d0d1a"/>
      <circle cx="403" cy="177" r="1.2" fill="#0d0d1a"/>
      <circle cx="387.5" cy="176.5" r=".4" fill="#58a6ff" opacity=".5"/>
      <circle cx="403.5" cy="176.5" r=".4" fill="#58a6ff" opacity=".5"/>
      <!-- Eyebrows -->
      <path d="M382,171 Q386,169 390,171" stroke="#0d0d1a" stroke-width=".8" fill="none"/>
      <path d="M398,171 Q402,169 406,171" stroke="#0d0d1a" stroke-width=".8" fill="none"/>
      <!-- Nose & mouth -->
      <path d="M393,180 L391.5,184 L394.5,184" stroke="#c9946b" stroke-width=".4" fill="none"/>
      <path d="M388,188 Q393,191 398,188" stroke="#b8846b" stroke-width=".8" fill="none"/>

      <!-- Headphones -->
      <path d="M371,174 Q369,155 393,150 Q417,155 415,174" stroke="#333" stroke-width="3" fill="none"/>
      <rect x="367" y="172" width="5" height="12" rx="2.5" fill="#444"/>
      <rect x="414" y="172" width="5" height="12" rx="2.5" fill="#444"/>
      <!-- Headphone LED -->
      <rect x="366" y="174" width="3" height="8" rx="1.5" fill="#8338ec" opacity=".7">
        <animate attributeName="opacity" values=".4;.8;.4" dur="2s" repeatCount="indefinite"/>
      </rect>
      <rect x="417" y="174" width="3" height="8" rx="1.5" fill="#8338ec" opacity=".7">
        <animate attributeName="opacity" values=".4;.8;.4" dur="2s" repeatCount="indefinite" begin=".3s"/>
      </rect>

      <!-- Music EQ bars (near left headphone) -->
      <rect x="357" y="193" width="2" height="3" rx=".5" fill="#8338ec" opacity=".6" class="eq1"/>
      <rect x="360" y="193" width="2" height="3" rx=".5" fill="#a855f7" opacity=".6" class="eq2"/>
      <rect x="363" y="193" width="2" height="3" rx=".5" fill="#c084fc" opacity=".6" class="eq3"/>
      <!-- EQ bars right -->
      <rect x="421" y="193" width="2" height="3" rx=".5" fill="#c084fc" opacity=".6" class="eq4"/>
      <rect x="424" y="193" width="2" height="3" rx=".5" fill="#a855f7" opacity=".6" class="eq5"/>
      <rect x="427" y="193" width="2" height="3" rx=".5" fill="#8338ec" opacity=".6" class="eq1" style="animation-delay:.2s"/>
    </g>
  </g>

  <!-- ===== KEYBOARD (RGB) ===== -->
  <g filter="url(#shadow)">
    <rect x="300" y="252" width="186" height="44" rx="4" fill="#151520" stroke="#222" stroke-width=".5"/>
    <!-- Key rows (simplified for elegance) -->
    <g fill="#1e1e30" opacity=".9">
      <!-- Row 1 -->
      <rect x="306" y="256" width="9" height="7" rx="1"/><rect x="317" y="256" width="9" height="7" rx="1"/><rect x="328" y="256" width="9" height="7" rx="1"/>
      <rect x="339" y="256" width="9" height="7" rx="1"/><rect x="350" y="256" width="9" height="7" rx="1"/><rect x="361" y="256" width="9" height="7" rx="1"/>
      <rect x="372" y="256" width="9" height="7" rx="1"/><rect x="383" y="256" width="9" height="7" rx="1"/><rect x="394" y="256" width="9" height="7" rx="1"/>
      <rect x="405" y="256" width="9" height="7" rx="1"/><rect x="416" y="256" width="9" height="7" rx="1"/><rect x="427" y="256" width="9" height="7" rx="1"/>
      <rect x="438" y="256" width="9" height="7" rx="1"/><rect x="449" y="256" width="28" height="7" rx="1"/>
      <!-- Row 2 -->
      <rect x="306" y="265" width="13" height="7" rx="1"/><rect x="321" y="265" width="9" height="7" rx="1"/><rect x="332" y="265" width="9" height="7" rx="1"/>
      <rect x="343" y="265" width="9" height="7" rx="1"/><rect x="354" y="265" width="9" height="7" rx="1"/><rect x="365" y="265" width="9" height="7" rx="1"/>
      <rect x="376" y="265" width="9" height="7" rx="1"/><rect x="387" y="265" width="9" height="7" rx="1"/><rect x="398" y="265" width="9" height="7" rx="1"/>
      <rect x="409" y="265" width="9" height="7" rx="1"/><rect x="420" y="265" width="9" height="7" rx="1"/><rect x="431" y="265" width="9" height="7" rx="1"/>
      <rect x="442" y="265" width="35" height="7" rx="1"/>
      <!-- Row 3 -->
      <rect x="306" y="274" width="16" height="7" rx="1"/><rect x="324" y="274" width="9" height="7" rx="1"/><rect x="335" y="274" width="9" height="7" rx="1"/>
      <rect x="346" y="274" width="9" height="7" rx="1"/><rect x="357" y="274" width="9" height="7" rx="1"/><rect x="368" y="274" width="9" height="7" rx="1"/>
      <rect x="379" y="274" width="9" height="7" rx="1"/><rect x="390" y="274" width="9" height="7" rx="1"/><rect x="401" y="274" width="9" height="7" rx="1"/>
      <rect x="412" y="274" width="9" height="7" rx="1"/><rect x="423" y="274" width="9" height="7" rx="1"/><rect x="434" y="274" width="43" height="7" rx="1"/>
      <!-- Space bar -->
      <rect x="330" y="283" width="126" height="7" rx="2"/>
      <rect x="306" y="283" width="22" height="7" rx="1"/><rect x="458" y="283" width="19" height="7" rx="1"/>
    </g>
    <!-- RGB Glow overlay (color cycling) -->
    <rect x="300" y="252" width="186" height="44" rx="4" fill="#ff006e" opacity=".04">
      <animate attributeName="fill" values="#ff006e;#8338ec;#3a86ff;#06d6a0;#ffbe0b;#ff006e" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values=".02;.06;.03;.06;.02" dur="5s" repeatCount="indefinite"/>
    </rect>
    <!-- Key edge glow (subtle per-key effect) -->
    <rect x="300" y="275" width="186" height="2" fill="#8338ec" opacity=".08">
      <animate attributeName="fill" values="#ff006e;#8338ec;#3a86ff;#06d6a0;#ff006e" dur="5s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Mouse -->
  <rect x="505" y="256" width="18" height="28" rx="7" fill="#151520" stroke="#222" stroke-width=".5"/>
  <line x1="514" y1="259" x2="514" y2="265" stroke="#222" stroke-width=".5"/>
  <circle cx="514" cy="261" r="1.5" fill="#1e1e30"/>
  <!-- Mouse RGB strip -->
  <rect x="508" y="280" width="12" height="1.5" rx=".75" fill="#8338ec" opacity=".3">
    <animate attributeName="fill" values="#ff006e;#8338ec;#3a86ff;#06d6a0;#ff006e" dur="5s" repeatCount="indefinite"/>
  </rect>

  <!-- ===== COFFEE MUG ===== -->
  <g>
    <rect x="568" y="224" width="28" height="26" rx="3" fill="url(#mug)"/>
    <path d="M596,228 Q607,232 607,237 Q607,242 596,245" stroke="#5c3d2e" stroke-width="2.5" fill="none"/>
    <ellipse cx="582" cy="226" rx="12" ry="3" fill="#2c1a0e"/>
    <ellipse cx="582" cy="224" rx="14" ry="3.5" fill="none" stroke="#5c3d2e" stroke-width="1.2"/>
    <!-- Heart -->
    <text x="576" y="241" fill="#e74c3c" font-size="8" opacity=".5">&#x2665;</text>
    <!-- Steam -->
    <path d="M576,219 Q573,210 576,203" stroke="#aaa" stroke-width=".8" fill="none" class="st1"/>
    <path d="M582,218 Q585,208 582,199" stroke="#aaa" stroke-width=".8" fill="none" class="st2"/>
    <path d="M588,219 Q585,209 588,201" stroke="#aaa" stroke-width=".8" fill="none" class="st3"/>
  </g>

  <!-- ===== SLEEPING CAT ===== -->
  <g>
    <g class="cbr"><ellipse cx="735" cy="242" rx="22" ry="10" fill="#444"/>
      <path d="M720,239 Q724,236 728,239" stroke="#333" stroke-width=".6" fill="none"/>
      <path d="M732,237 Q736,234 740,237" stroke="#333" stroke-width=".6" fill="none"/>
    </g>
    <circle cx="715" cy="239" r="8" fill="#444"/>
    <polygon points="709,233 707,222 713,229" fill="#444"/><polygon points="721,233 723,222 717,229" fill="#444"/>
    <polygon points="710,231 708,225 712,229" fill="#ffb6c1" opacity=".3"/>
    <polygon points="720,231 722,225 718,229" fill="#ffb6c1" opacity=".3"/>
    <path d="M711,239 Q713,237 715,239" stroke="#222" stroke-width=".8" fill="none"/>
    <path d="M716,239 Q718,237 720,239" stroke="#222" stroke-width=".8" fill="none"/>
    <ellipse cx="715.5" cy="241.5" rx="1.2" ry=".8" fill="#ffb6c1"/>
    <g class="ct"><path d="M757,242 Q766,236 770,241 Q774,248 765,246" stroke="#444" stroke-width="3.5" fill="none" stroke-linecap="round"/></g>
    <!-- Zzz -->
    <text x="723" y="224" fill="#8338ec" font-size="6" font-family="monospace" opacity="0"><animate attributeName="opacity" values="0;.5;0" dur="2s" repeatCount="indefinite"/>z</text>
    <text x="730" y="217" fill="#8338ec" font-size="8" font-family="monospace" opacity="0"><animate attributeName="opacity" values="0;.4;0" dur="2s" repeatCount="indefinite" begin=".5s"/>z</text>
    <text x="738" y="209" fill="#8338ec" font-size="10" font-family="monospace" opacity="0"><animate attributeName="opacity" values="0;.3;0" dur="2s" repeatCount="indefinite" begin="1s"/>z</text>
  </g>

  <!-- ===== FLOATING CODE SYMBOLS ===== -->
  <text x="155" y="140" fill="#ff79c6" font-size="14" font-family="monospace" class="f1" filter="url(#glow)">{ }</text>
  <text x="670" y="120" fill="#50fa7b" font-size="12" font-family="monospace" class="f2" filter="url(#glow)">&lt;/&gt;</text>
  <text x="130" y="105" fill="#f1fa8c" font-size="10" font-family="monospace" class="f3" filter="url(#glow)">=&gt;</text>
  <text x="760" y="135" fill="#8be9fd" font-size="13" font-family="monospace" class="f1" filter="url(#glow)" style="animation-delay:1.5s">;</text>
  <text x="820" y="110" fill="#bd93f9" font-size="11" font-family="monospace" class="f2" filter="url(#glow)" style="animation-delay:3s">++</text>
  <text x="75" y="170" fill="#58a6ff" font-size="12" font-family="monospace" class="f3" filter="url(#glow)" style="animation-delay:2.5s">[ ]</text>
  <text x="790" y="165" fill="#ff79c6" font-size="10" font-family="monospace" class="f1" filter="url(#glow)" style="animation-delay:3.5s">01</text>
  <text x="110" y="200" fill="#50fa7b" font-size="11" font-family="monospace" class="f2" filter="url(#glow)" style="animation-delay:2s">==</text>
  <text x="845" y="85" fill="#f1fa8c" font-size="9" font-family="monospace" class="f3" filter="url(#glow)" style="animation-delay:1s">( )</text>

  <!-- ===== BOTTOM FADE ===== -->
  <rect x="0" y="330" width="900" height="40" fill="url(#btm)"/>

  <!-- Tagline -->
  <text x="450" y="360" fill="#58a6ff" font-size="10" font-family="monospace" text-anchor="middle" opacity=".4" filter="url(#glow)">
    while(alive) { eat(); sleep(); code(); repeat(); }
  </text>
</svg>
