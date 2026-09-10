<svg width="900" height="200" viewBox="0 0 900 200"
     xmlns="http://www.w3.org/2000/svg">

  <style>
    .letter {
      font-family: "SFMono-Regular", Consolas, "Liberation Mono", monospace;
      font-size: 58px;
      font-weight: 600;
      fill: #24292f;
    }

    @media (prefers-color-scheme: dark) {
      .letter {
        fill: #f0f6fc;
      }
    }

    .snake {
      fill: #2ea043;
      filter: url(#glow);
    }
  </style>

  <!-- Soft glow -->
  <defs>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Hello, World! -->

  <g transform="translate(170 120)">

    <text class="letter" x="0" y="0" opacity="0">
      H
      <animate attributeName="opacity"
               values="0;1;1;0"
               keyTimes="0;0.05;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="38" y="0" opacity="0">
      e
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.05;0.10;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="76" y="0" opacity="0">
      l
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.10;0.15;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="114" y="0" opacity="0">
      l
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.15;0.20;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="152" y="0" opacity="0">
      o
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.20;0.25;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="190" y="0" opacity="0">
      ,
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.25;0.30;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="245" y="0" opacity="0">
      W
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.30;0.35;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="295" y="0" opacity="0">
      o
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.35;0.40;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="333" y="0" opacity="0">
      r
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.40;0.45;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="371" y="0" opacity="0">
      l
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.45;0.50;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="409" y="0" opacity="0">
      d
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.50;0.55;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>

    <text class="letter" x="447" y="0" opacity="0">
      !
      <animate attributeName="opacity"
               values="0;0;1;1;0"
               keyTimes="0;0.55;0.60;0.85;1"
               dur="5s"
               repeatCount="indefinite"/>
    </text>


    <!-- Moving snake / glowing cursor -->

    <circle class="snake" cx="-15" cy="-18" r="6">
      <animate attributeName="cx"
               values="-15;20;58;96;134;172;220;270;315;353;391;429;470"
               keyTimes="0;0.05;0.10;0.15;0.20;0.25;0.30;0.35;0.40;0.45;0.50;0.55;0.60"
               dur="5s"
               repeatCount="indefinite"/>

      <animate attributeName="opacity"
               values="1;1;0;0"
               keyTimes="0;0.60;0.65;1"
               dur="5s"
               repeatCount="indefinite"/>
    </circle>

  </g>

</svg>
