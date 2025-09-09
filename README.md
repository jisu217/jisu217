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
  
  <!-- 큰 꽃 1 - 왼쪽 (점선으로 이루어진 꽃) -->
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
      <text x="25" y="-20" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="35" y="-30" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
      
      <!-- 오른쪽 꽃잎 -->
      <text x="40" y="0" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="55" y="0" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
      <text x="47" y="-3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
      <text x="47" y="3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
      
      <!-- 오른쪽 아래 꽃잎 -->
      <text x="25" y="20" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="35" y="30" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
      
      <!-- 아래쪽 꽃잎 -->
      <text x="0" y="30" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="0" y="45" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
      <text x="-3" y="37" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
      <text x="3" y="37" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
      
      <!-- 왼쪽 아래 꽃잎 -->
      <text x="-25" y="20" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="-35" y="30" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
      
      <!-- 왼쪽 꽃잎 -->
      <text x="-40" y="0" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="-55" y="0" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
      <text x="-47" y="-3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
      <text x="-47" y="3" text-anchor="middle" font-size="10" fill="#fce7f3">.</text>
      
      <!-- 왼쪽 위 꽃잎 -->
      <text x="-25" y="-20" text-anchor="middle" font-size="14" fill="#f472b6">●</text>
      <text x="-35" y="-30" text-anchor="middle" font-size="12" fill="#f9a8d4">●</text>
    </g>
    
    <!-- 꽃 중심 (함수 기호) -->
    <text x="0" y="5" text-anchor="middle" font-size="16" fill="#fbbf24">*</text>
    <animate attributeName="font-size" values="16; 20; 16" dur="2s" repeatCount="indefinite"/>
  </g>
  
  <!-- 큰 꽃 2 - 중앙 (해시태그 스타일) -->
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
  
  <!-- 큰 꽃 3 - 오른쪽 (바이너리 스타일) -->
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
  
  <!-- 중간 사이즈 꽃 1 - 함수 스타일 -->
  <g transform="translate(280, 190)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="280,190; 280,185; 280,190" dur="1.9s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="15" text-anchor="middle" font-size="10" fill="#10b981">|</text>
    <text x="0" y="28" text-anchor="middle" font-size="10" fill="#10b981">|</text>
    <text x="0" y="41" text-anchor="middle" font-size="10" fill="#10b981">|</text>
    
    <!-- 잎사귀 -->
    <text x="-10" y="25" text-anchor="middle" font-size="8" fill="#34d399">\</text>
    <text x="10" y="35" text-anchor="middle" font-size="8" fill="#34d399">/</text>
    
    <!-- 꽃잎들 -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; 2; -2; 0" dur="3.1s" repeatCount="indefinite"/>
      
      <text x="0" y="-18" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="0" y="-28" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="15" y="-10" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="22" y="-17" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="22" y="0" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="32" y="0" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="15" y="10" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="22" y="17" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="0" y="18" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="0" y="28" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="-15" y="10" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="-22" y="17" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="-22" y="0" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="-32" y="0" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
      
      <text x="-15" y="-10" text-anchor="middle" font-size="11" fill="#f59e0b">$</text>
      <text x="-22" y="-17" text-anchor="middle" font-size="9" fill="#fbbf24">o</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="3" text-anchor="middle" font-size="12" fill="#dc2626">%</text>
    <animate attributeName="font-size" values="12; 15; 12" dur="2.1s" repeatCount="indefinite"/>
  </g>
  
  <!-- 중간 사이즈 꽃 2 - 배열 스타일 -->
  <g transform="translate(520, 180)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="520,180; 520,175; 520,180" dur="2.1s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="18" text-anchor="middle" font-size="10" fill="#10b981">:</text>
    <text x="0" y="30" text-anchor="middle" font-size="10" fill="#10b981">:</text>
    <text x="0" y="42" text-anchor="middle" font-size="10" fill="#10b981">:</text>
    
    <!-- 잎사귀 -->
    <text x="-12" y="28" text-anchor="middle" font-size="8" fill="#34d399">[</text>
    <text x="12" y="38" text-anchor="middle" font-size="8" fill="#34d399">]</text>
    
    <!-- 꽃잎들 -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; -3; 3; 0" dur="3.4s" repeatCount="indefinite"/>
      
      <text x="0" y="-20" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="0" y="-32" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="17" y="-12" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="25" y="-20" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="25" y="0" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="37" y="0" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="17" y="12" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="25" y="20" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="0" y="20" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="0" y="32" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="-17" y="12" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="-25" y="20" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="-25" y="0" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="-37" y="0" text-anchor="middle" font-size="10" fill="#34d399">]</text>
      
      <text x="-17" y="-12" text-anchor="middle" font-size="12" fill="#10b981">[</text>
      <text x="-25" y="-20" text-anchor="middle" font-size="10" fill="#34d399">]</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="4" text-anchor="middle" font-size="14" fill="#7c3aed">{}</text>
    <animate attributeName="font-size" values="14; 17; 14" dur="1.9s" repeatCount="indefinite"/>
  </g>
  
  <!-- 작은 꽃 1 - 연산자 스타일 -->
  <g transform="translate(200, 160)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="200,160; 200,155; 200,160" dur="1.5s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="10" text-anchor="middle" font-size="8" fill="#10b981">|</text>
    <text x="0" y="20" text-anchor="middle" font-size="8" fill="#10b981">|</text>
    
    <!-- 꽃잎들 -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; 5; -5; 0" dur="2.8s" repeatCount="indefinite"/>
      <text x="0" y="-8" text-anchor="middle" font-size="8" fill="#f472b6">+</text>
      <text x="6" y="-3" text-anchor="middle" font-size="6" fill="#fda4af">·</text>
      <text x="6" y="3" text-anchor="middle" font-size="6" fill="#fda4af">·</text>
      <text x="0" y="8" text-anchor="middle" font-size="8" fill="#f472b6">+</text>
      <text x="-6" y="3" text-anchor="middle" font-size="6" fill="#fda4af">·</text>
      <text x="-6" y="-3" text-anchor="middle" font-size="6" fill="#fda4af">·</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="2" text-anchor="middle" font-size="8" fill="#dc2626">=</text>
    <animate attributeName="font-size" values="8; 10; 8" dur="1.7s" repeatCount="indefinite"/>
  </g>
  
  <!-- 작은 꽃 2 - 포인터 스타일 -->
  <g transform="translate(600, 140)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="600,140; 600,135; 600,140" dur="1.8s" repeatCount="indefinite"/>
    
    <!-- 줄기 -->
    <text x="0" y="12" text-anchor="middle" font-size="8" fill="#10b981">|</text>
    <text x="0" y="22" text-anchor="middle" font-size="8" fill="#10b981">|</text>
    
    <!-- 꽃잎들 -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0; -4; 4; 0" dur="2.5s" repeatCount="indefinite"/>
      <text x="0" y="-6" text-anchor="middle" font-size="7" fill="#06b6d4">*</text>
      <text x="4" y="-2" text-anchor="middle" font-size="5" fill="#7dd3fc">○</text>
      <text x="4" y="2" text-anchor="middle" font-size="5" fill="#7dd3fc">○</text>
      <text x="0" y="6" text-anchor="middle" font-size="7" fill="#06b6d4">*</text>
      <text x="-4" y="2" text-anchor="middle" font-size="5" fill="#7dd3fc">○</text>
      <text x="-4" y="-2" text-anchor="middle" font-size="5" fill="#7dd3fc">○</text>
    </g>
    
    <!-- 꽃 중심 -->
    <text x="0" y="2" text-anchor="middle" font-size="9" fill="#f59e0b">&amp;</text>
    <animate attributeName="font-size" values="9; 11; 9" dur="1.6s" repeatCount="indefinite"/>
  </g>
  
  <!-- 아주 작은 꽃들 -->
  <g transform="translate(350, 120)" font-family="'Courier New', monospace">
    <animateTransform attributeName="transform" type="translate" values="350,120; 350,117; 350,120" dur="1.2s" repeatCount="indefinite"/>
    <text x="0" y="0" text-anchor="middle" font-size="6" fill="#a855f7">•</text>
    <text x="-3" y="-2" text-anchor="middle" font-size="4" fill="#c084fc">.</text>
    <text x
