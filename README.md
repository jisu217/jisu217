<svg width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- 그라데이션 정의 -->
    <linearGradient id="skyGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#fef7ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f0f9ff;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- 배경 -->
  <rect width="800" height="400" fill="url(#skyGrad)"/>
  
  <!-- 제목 텍스트 -->
  <text x="400" y="50" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="bold" fill="#8b5cf6">
    &lt;Welcome to My Code Garden /&gt;
    <animateTransform attributeName="transform" type="scale" values="1;1.05;1" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- 꽃 1 - 점선으로 이루어진 꽃 -->
  <g transform="translate(150, 250)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="150,250; 150,245; 150,250" dur="2s" repeatCount="indefinite"/>
    
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
  </g>
  
  <!-- 꽃 2 - 중앙 (다른 코드 스타일) -->
  <g transform="translate(400, 270)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="400,270; 405,265; 400,270" dur="2.3s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="25" text-anchor="middle" font-size="12" fill="#10b981">│</text>
    <text x="0" y="40" text-anchor="middle" font-size="12" fill="#10b981">│</text>
    <text x="0" y="55" text-anchor="middle" font-size="12" fill="#10b981">│</text>
    <text x="0" y="70" text-anchor="middle" font-size="12" fill="#10b981">║</text>
    
    <!-- 잎사귀 -->
    <text x="-18" y="45" text-anchor="middle" font-size="12" fill="#34d399">╱</text>
    <text x="-12" y="50" text-anchor="middle" font-size="10" fill="#6ee7b7">‾</text>
    <text x="18" y="60" text-anchor="middle" font-size="12" fill="#34d399">╲</text>
    <text x="12" y="65" text-anchor="middle" font-size="10" fill="#6ee7b7">‾</text>
    
    <!-- 꽃잎들 (해시태그와 점들) -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; -5; 5; 0" dur="3.5s" repeatCount="indefinite"/>
      
      <!-- 꽃잎 패턴들 -->
      <text x="0" y="-35" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="0" y="-50" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      <text x="-4" y="-42" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      <text x="4" y="-42" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      
      <text x="30" y="-25" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="42" y="-35" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      
      <text x="45" y="0" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="60" y="0" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      <text x="52" y="-4" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      <text x="52" y="4" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      
      <text x="30" y="25" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="42" y="35" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      
      <text x="0" y="35" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="0" y="50" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      <text x="-4" y="42" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      <text x="4" y="42" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      
      <text x="-30" y="25" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="-42" y="35" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      
      <text x="-45" y="0" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="-60" y="0" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
      <text x="-52" y="-4" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      <text x="-52" y="4" text-anchor="middle" font-size="8" fill="#e9d5ff">·</text>
      
      <text x="-30" y="-25" text-anchor="middle" font-size="16" fill="#a855f7">#</text>
      <text x="-42" y="-35" text-anchor="middle" font-size="12" fill="#c084fc">●</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="5" text-anchor="middle" font-size="18" fill="#f59e0b">@</text>
    <animate attributeName="font-size" values="18; 22; 18" dur="2.5s" repeatCount="indefinite"/>
  </g>
  
  <!-- 꽃 3 - 오른쪽 (바이너리 스타일) -->
  <g transform="translate(650, 260)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="650,260; 645,255; 650,260" dur="2.7s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="20" text-anchor="middle" font-size="12" fill="#10b981">1</text>
    <text x="0" y="35" text-anchor="middle" font-size="12" fill="#10b981">0</text>
    <text x="0" y="50" text-anchor="middle" font-size="12" fill="#10b981">1</text>
    <text x="0" y="65" text-anchor="middle" font-size="12" fill="#10b981">1</text>
    <text x="0" y="80" text-anchor="middle" font-size="12" fill="#10b981">0</text>
    
    <!-- 잎사귀 -->
    <text x="-15" y="50" text-anchor="middle" font-size="10" fill="#34d399">&lt;</text>
    <text x="-8" y="52" text-anchor="middle" font-size="8" fill="#6ee7b7">-</text>
    <text x="15" y="65" text-anchor="middle" font-size="10" fill="#34d399">&gt;</text>
    <text x="8" y="67" text-anchor="middle" font-size="8" fill="#6ee7b7">-</text>
    
    <!-- 꽃잎들 (바이너리 패턴) -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; 4; -4; 0" dur="4.2s" repeatCount="indefinite"/>
      
      <text x="0" y="-25" text-anchor="middle" font-size="14" fill="#06b6d4">0</text>
      <text x="0" y="-40" text-anchor="middle" font-size="12" fill="#67e8f9">1</text>
      <text x="-5" y="-32" text-anchor="middle" font-size="10" fill="#cffafe">.</text>
      <text x="5" y="-32" text-anchor="middle" font-size="10" fill="#cffafe">.</text>
      
      <text x="22" y="-15" text-anchor="middle" font-size="14" fill="#06b6d4">1</text>
      <text x="32" y="-25" text-anchor="middle" font-size="12" fill="#67e8f9">0</text>
      
      <text x="35" y="0" text-anchor="middle" font-size="14" fill="#06b6d4">0</text>
      <text x="50" y="0" text-anchor="middle" font-size="12" fill="#67e8f9">1</text>
      <text x="42" y="-3" text-anchor="middle" font-size="10" fill="#cffafe">.</text>
      <text x="42" y="3" text-anchor="middle" font-size="10" fill="#cffafe">.</text>
      
      <text x="22" y="15" text-anchor="middle" font-size="14" fill="#06b6d4">1</text>
      <text x="32" y="25" text-anchor="middle" font-size="12" fill="#67e8f9">0</text>
      
      <text x="0" y="25" text-anchor="middle" font-size="14" fill="#06b6d4">0</text>
      <text x="0" y="40" text-anchor="middle" font-size="12" fill="#67e8f9">1</text>
      
      <text x="-22" y="15" text-anchor="middle" font-size="14" fill="#06b6d4">1</text>
      <text x="-32" y="25" text-anchor="middle" font-size="12" fill="#67e8f9">0</text>
      
      <text x="-35" y="0" text-anchor="middle" font-size="14" fill="#06b6d4">0</text>
      <text x="-50" y="0" text-anchor="middle" font-size="12" fill="#67e8f9">1</text>
      
      <text x="-22" y="-15" text-anchor="middle" font-size="14" fill="#06b6d4">1</text>
      <text x="-32" y="-25" text-anchor="middle" font-size="12" fill="#67e8f9">0</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="5" text-anchor="middle" font-size="16" fill="#eab308">&</text>
    <animate attributeName="font-size" values="16; 20; 16" dur="1.8s" repeatCount="indefinite"/>
  </g>

  <!-- ================================================================ -->
  <!-- ======================== 추가된 꽃들 =========================== -->
  <!-- ================================================================ -->
  
  <!-- 꽃 4 - 괄호 스타일 (중간 크기) -->
  <g transform="translate(275, 280)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="275,280; 275,276; 275,280" dur="2.5s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="20" text-anchor="middle" font-size="12" fill="#10b981">(</text>
    <text x="0" y="35" text-anchor="middle" font-size="12" fill="#10b981">)</text>
    <text x="0" y="50" text-anchor="middle" font-size="12" fill="#10b981">(</text>
    <text x="0" y="65" text-anchor="middle" font-size="12" fill="#10b981">)</text>
    
    <!-- 잎사귀 -->
    <text x="-15" y="45" text-anchor="middle" font-size="10" fill="#34d399">//</text>
    <text x="15" y="55" text-anchor="middle" font-size="10" fill="#34d399">\\</text>
    
    <!-- 꽃잎들 (괄호 패턴) -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; 5; -5; 0" dur="5s" repeatCount="indefinite"/>
      
      <text x="0" y="-25" text-anchor="middle" font-size="16" fill="#fb923c">(</text>
      <text x="0" y="-26" text-anchor="middle" font-size="16" fill="#fb923c" transform="rotate(180)"> ( </text>
      
      <text x="25" y="0" text-anchor="middle" font-size="16" fill="#fb923c" transform="rotate(90)"> ( </text>
      <text x="25" y="0" text-anchor="middle" font-size="16" fill="#fb923c" transform="rotate(-90)"> ( </text>
      
      <text x="-25" y="0" text-anchor="middle" font-size="16" fill="#fb923c" transform="rotate(-90)"> ( </text>
      <text x="-25" y="0" text-anchor="middle" font-size="16" fill="#fb923c" transform="rotate(90)"> ( </text>
      
      <text x="0" y="25" text-anchor="middle" font-size="16" fill="#fb923c" transform="rotate(180)"> ( </text>
      <text x="0" y="26" text-anchor="middle" font-size="16" fill="#fb923c"> ( </text>
      
      <text x="18" y="-18" text-anchor="middle" font-size="12" fill="#fcd34d">[</text>
      <text x="18" y="18" text-anchor="middle" font-size="12" fill="#fcd34d" transform="rotate(-90)">[</text>
      <text x="-18" y="18" text-anchor="middle" font-size="12" fill="#fcd34d" transform="rotate(180)">[</text>
      <text x="-18" y="-18" text-anchor="middle" font-size="12" fill="#fcd34d" transform="rotate(90)">[</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="5" text-anchor="middle" font-size="16" fill="#f59e0b">$</text>
    <animate attributeName="font-size" values="16; 19; 16" dur="2.2s" repeatCount="indefinite"/>
  </g>

  <!-- 꽃 5 - 화살표 스타일 (작은 키) -->
  <g transform="translate(525, 290)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="525,290; 522,293; 525,290" dur="3.1s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="25" text-anchor="middle" font-size="12" fill="#10b981">¦</text>
    <text x="0" y="40" text-anchor="middle" font-size="12" fill="#10b981">¦</text>
    <text x="0" y="55" text-anchor="middle" font-size="12" fill="#10b981">¦</text>
    
    <!-- 잎사귀 -->
    <text x="-15" y="40" text-anchor="middle" font-size="10" fill="#34d399">&lt;&lt;</text>
    <text x="15" y="50" text-anchor="middle" font-size="10" fill="#34d399">&gt;&gt;</text>
    
    <!-- 꽃잎들 (화살표 패턴) -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; -6; 6; 0" dur="3.8s" repeatCount="indefinite"/>
      
      <text x="0" y="-20" text-anchor="middle" font-size="14" fill="#8b5cf6">^</text>
      <text x="20" y="0" text-anchor="middle" font-size="14" fill="#8b5cf6">&gt;</text>
      <text x="0" y="20" text-anchor="middle" font-size="14" fill="#8b5cf6">v</text>
      <text x="-20" y="0" text-anchor="middle" font-size="14" fill="#8b5cf6">&lt;</text>
      
      <text x="14" y="-14" text-anchor="middle" font-size="10" fill="#a78bfa">.</text>
      <text x="14" y="14" text-anchor="middle" font-size="10" fill="#a78bfa">.</text>
      <text x="-14" y="14" text-anchor="middle" font-size="10" fill="#a78bfa">.</text>
      <text x="-14" y="-14" text-anchor="middle" font-size="10" fill="#a78bfa">.</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="5" text-anchor="middle" font-size="14" fill="#fbbf24">%</text>
    <animate attributeName="opacity" values="1; 0.3; 1" dur="1.5s" repeatCount="indefinite"/>
  </g>


  <!-- ================================================================ -->
  <!-- ==================== 기존 및 추가된 작은 꽃들 ==================== -->
  <!-- ================================================================ -->
  
  <g transform="translate(250, 180)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="250,180; 250,175; 250,180" dur="1.5s" repeatCount="indefinite"/>
    <text x="0" y="0" text-anchor="middle" font-size="12" fill="#f472b6">+</text>
    <text x="-8" y="-5" text-anchor="middle" font-size="8" fill="#fda4af">·</text>
    <text x="8" y="-5" text-anchor="middle" font-size="8" fill="#fda4af">·</text>
    <text x="-8" y="5" text-anchor="middle" font-size="8" fill="#fda4af">·</text>
    <text x="8" y="5" text-anchor="middle" font-size="8" fill="#fda4af">·</text>
  </g>
  
  <g transform="translate(550, 160)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="550,160; 550,155; 550,160" dur="1.8s" repeatCount="indefinite"/>
    <text x="0" y="0" text-anchor="middle" font-size="10" fill="#06b6d4">*</text>
    <text x="-6" y="-4" text-anchor="middle" font-size="6" fill="#7dd3fc">○</text>
    <text x="6" y="-4" text-anchor="middle" font-size="6" fill="#7dd3fc">○</text>
    <text x="-6" y="4" text-anchor="middle" font-size="6" fill="#7dd3fc">○</text>
    <text x="6" y="4" text-anchor="middle" font-size="6" fill="#7dd3fc">○</text>
  </g>

  <!-- 추가된 작은 꽃 1 -->
  <g transform="translate(80, 310)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="80,310; 80,307; 80,310" dur="1.9s" repeatCount="indefinite"/>
    <text x="0" y="0" text-anchor="middle" font-size="12" fill="#f472b6">:</text>
    <text x="-8" y="0" text-anchor="middle" font-size="10" fill="#fda4af">-</text>
    <text x="8" y="0" text-anchor="middle" font-size="10" fill="#fda4af">-</text>
  </g>
  
  <!-- 추가된 작은 꽃 2 -->
  <g transform="translate(720, 320)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="720,320; 722,318; 720,320" dur="2.2s" repeatCount="indefinite"/>
    <text x="0" y="0" text-anchor="middle" font-size="14" fill="#06b6d4">;</text>
    <text x="0" y="-8" text-anchor="middle" font-size="8" fill="#7dd3fc">.</text>
    <text x="0" y="8" text-anchor="middle" font-size="8" fill="#7dd3fc">.</text>
  </g>
  
  <!-- 추가된 작은 꽃 3 (배경) -->
  <g transform="translate(330, 220)" opacity="0.8" font-family="'Courier New', monospace">
    <animate attributeName="opacity" values="0.8; 0.5; 0.8" dur="3s" repeatCount="indefinite"/>
    <text x="0" y="0" text-anchor="middle" font-size="12" fill="#a855f7">&lt;o&gt;</text>
  </g>
  
  <!-- 떨어지는 코드 조각들 -->
  <g opacity="0.7" font-family="'Courier New', monospace">
    <text x="100" y="0" text-anchor="middle" font-size="12" fill="#f472b6">{</text>
    <animateTransform attributeName="transform" type="translate" values="100,0; 120,400" dur="8s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="rotate" values="0; 360" dur="3s" repeatCount="indefinite" additive="sum"/>
    
    <text x="300" y="0" text-anchor="middle" font-size="10" fill="#a855f7">}</text>
    <animateTransform attributeName="transform" type="translate" values="300,0; 280,400" dur="10s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="rotate" values="0; -360" dur="4s" repeatCount="indefinite" additive="sum"/>
    
    <text x="500" y="0" text-anchor="middle" font-size="12" fill="#06b6d4">;</text>
    <animateTransform attributeName="transform" type="translate" values="500,0; 520,400" dur="9s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="rotate" values="0; 360" dur="2.5s" repeatCount="indefinite" additive="sum"/>
    
    <text x="700" y="0" text-anchor="middle" font-size="10" fill="#eab308">/</text>
    <animateTransform attributeName="transform" type="translate" values="700,0; 680,400" dur="7s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="rotate" values="0; -360" dur="3.5s" repeatCount="indefinite" additive="sum"/>
  </g>
  
  <!-- 하단 메시지 -->
  <text x="400" y="360" text-anchor="middle" font-family="'Courier New', monospace" font-size="14" fill="#6366f1">
    // Here blooms my code garden
    <animate attributeName="opacity" values="1; 0.5; 1" dur="2s" repeatCount="indefinite"/>
  </text>
</svg>
