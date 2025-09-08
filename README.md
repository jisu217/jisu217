<!-- 줄기 (코드 라인들) -->
<text x="0" y="20" text-anchor="middle" font-size="12" fill="#10b981">|</text>
<text x="0" y="35" text-anchor="middle" font-size="12" fill="#10b981">|</text>
<text x="0" y="50" text-anchor="middle" font-size="12" fill="#10b981">|</text>
<text x="0" y="65" text-anchor="middle" font-size="12" fill="#10b981">|</text>
<text x="0" y="80" text-anchor="middle" font-size="12" fill="#10b981">|</text>

<!-- 잎사귀 (코드 브랜치) -->
<text x="-15" y="40" text-anchor="middle" font-size="10" fill="#34d399">\</text>
<text x="-10" y="45" text-anchor="middle" font-size="10" fill="#34d399">_</text>
<text x="15" y="60" text-anchor="middle" font-size="10" fill="#34d399">/</text>
<text x="10" y="65" text-anchor="middle" font-size="10" fill="#34d399">_</text>

<!-- 꽃잎들 (점선 패턴) -->
<g>
  <animateTransform attributeName="transform" type="rotate" values="0; 3; -3; 0" dur="4s" repeatCount="indefinite"/>
  
  <!-- 위쪽 꽃잎 -->
  <text x="0" y="-30" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
  <text x="0" y="-45" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
  <text x="-3" y="-37" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  <text x="3" y="-37" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  
  <!-- 오른쪽 위 꽃잎 -->
  <text x="25" y="-20" text-anchor="middle" font-size="14" fill="#f472b6" transform="rotate(45)">●</text>
  <text x="35" y="-30" text-anchor="middle" font-size="12" fill="#f9a8d4" transform="rotate(45)">●</text>
  
  <!-- 오른쪽 꽃잎 -->
  <text x="40" y="0" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
  <text x="55" y="0" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
  <text x="47" y="-3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  <text x="47" y="3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  
  <!-- 오른쪽 아래 꽃잎 -->
  <text x="25" y="20" text-anchor="middle" font-size="14" fill="#f472b6" transform="rotate(-45)">●</text>
  <text x="35" y="30" text-anchor="middle" font-size="12" fill="#f9a8d4" transform="rotate(-45)">●</text>
  
  <!-- 아래쪽 꽃잎 -->
  <text x="0" y="30" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
  <text x="0" y="45" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
  <text x="-3" y="37" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  <text x="3" y="37" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  
  <!-- 왼쪽 아래 꽃잎 -->
  <text x="-25" y="20" text-anchor="middle" font-size="14" fill="#f472b6" transform="rotate(45)">●</text>
  <text x="-35" y="30" text-anchor="middle" font-size="12" fill="#f9a8d4" transform="rotate(45)">●</text>
  
  <!-- 왼쪽 꽃잎 -->
  <text x="-40" y="0" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
  <text x="-55" y="0" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
  <text x="-47" y="-3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  <text x="-47" y="3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
  
  <!-- 왼쪽 위 꽃잎 -->
  <text x="-25" y="-20" text-anchor="middle" font-size="14" fill="#f472b6" transform="rotate(-45)">●</text>
  <text x="-35" y="-30" text-anchor="middle" font-size="12" fill="#f9a8d4" transform="rotate(-45)">●</text>
</g>

<!-- 꽃 중심 (함수 기호) -->
<text x="0" y="5" text-anchor="middle" font-size="16" fill="#fbbf24">*</text>
<animate attributeName="font-size" values="16; 20; 16" dur="2s" repeatCount="indefinite"/>
