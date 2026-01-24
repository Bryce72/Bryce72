<p align="center">
  <svg width="280" height="280" viewBox="-140 -140 280 280" xmlns="http://www.w3.org/2000/svg" style="background:#000;">
    <style>
      text { font-family: 'Courier New', monospace; font-size: 11px; fill: #0f0; white-space: pre; }
    </style>
    
    <!-- Rotating cube group -->
    <g transform="translate(0,0)">
      <animateTransform 
        attributeName="transform" 
        type="rotate" 
        from="0 0 0" 
        to="360 0 0" 
        dur="20s" 
        repeatCount="indefinite"/>
      
      <!-- Back face (farthest) -->
      <text x="-60" y="-60" opacity="0.5">+----------+</text>
      <text x="-60" y="-40" opacity="0.5">|          |</text>
      <text x="-60" y="-20" opacity="0.5">|   .-.    |</text>
      <text x="-60" y="0"   opacity="0.5">|  /   \   |</text>
      <text x="-60" y="20"  opacity="0.5">|  \   /   |</text>
      <text x="-60" y="40"  opacity="0.5">|   '-'    |</text>
      <text x="-60" y="60"  opacity="0.5">+----------+</text>
      
      <!-- Left face -->
      <text x="-100" y="-40" transform="rotate(-30 -100 -40)">/          /</text>
      <text x="-100" y="-20" transform="rotate(-30 -100 -20)">/   .-.    /</text>
      <text x="-100" y="0"   transform="rotate(-30 -100 0)">/   /   \   /</text>
      <text x="-100" y="20"  transform="rotate(-30 -100 20)">/   \   /   /</text>
      <text x="-100" y="40"  transform="rotate(-30 -100 40)">/    '-'    /</text>
      
      <!-- Right face -->
      <text x="40" y="-40" transform="rotate(30 40 -40)">\          \</text>
      <text x="40" y="-20" transform="rotate(30 40 -20)">\   .-.    \</text>
      <text x="40" y="0"   transform="rotate(30 40 0)">\  /   \   \</text>
      <text x="40" y="20"  transform="rotate(30 40 20)">\  \   /   \</text>
      <text x="40" y="40"  transform="rotate(30 40 40)">\   '-'    \</text>
      
      <!-- Front face (closest – brighter) -->
      <text x="-40" y="-60">+----------+</text>
      <text x="-40" y="-40">|   ***    |</text>
      <text x="-40" y="-20">|  *****   |</text>
      <text x="-40" y="0"  >| *******  |</text>
      <text x="-40" y="20" >|  *****   |</text>
      <text x="-40" y="40" >|   ***    |</text>
      <text x="-40" y="60">+----------+</text>
      
      <!-- Top face -->
      <text x="-50" y="-80">/----------\</text>
      <text x="-50" y="-70">/   ***    \</text>
      <text x="-50" y="-60">/  *****   \</text>
      
      <!-- Bottom face -->
      <text x="-30" y="80">\----------/</text>
      <text x="-30" y="70"> \  *****  /</text>
      <text x="-30" y="60">  \  ***  /</text>
    </g>
  </svg>
  <br>
  <small>Rotating ASCII cube – pure SVG, <4 KB</small>
</p>
