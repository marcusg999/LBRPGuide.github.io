<html><head><base href="https://websim.ai" />
<title>LBRP Ritual Guide - Centered Animation</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  body {
    font-family: 'Helvetica', Arial, sans-serif;
    background-color: #0a0a1a;
    color: #e0e0e0;
    line-height: 1.6;
    margin: 0;
    padding: 0;
  }
  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    box-sizing: border-box;
  }
  h1, h2 {
    color: #4a8fe7;
    text-align: center;
  }
  .canvas-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px 0;
  }
  #ritual-canvas {
    background-color: #0f1a2e;
    border: 2px solid #4a8fe7;
    border-radius: 10px;
    max-width: 100%;
    height: auto;
  }
  .controls {
    text-align: center;
    margin-top: 20px;
  }
  .control-button {
    background-color: #4a8fe7;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    margin: 10px;
    transition: background-color 0.3s;
    width: 80%;
    max-width: 200px;
  }
  .control-button:hover {
    background-color: #3a7bd5;
  }
  .step {
    background-color: #16213e;
    border-radius: 10px;
    padding: 15px;
    margin-bottom: 15px;
  }
  .step h3 {
    color: #00b4d8;
    margin-top: 0;
  }
  .disclaimer {
    font-size: 0.8em;
    color: #888;
    text-align: center;
    margin-top: 20px;
  }
  @media (max-width: 600px) {
    h1 {
      font-size: 24px;
    }
    h2 {
      font-size: 20px;
    }
    .step h3 {
      font-size: 18px;
    }
    p, ul {
      font-size: 14px;
    }
  }
</style>
</head>
<body>
  <div class="container">
    <h1>2D Animated LBRP Ritual Guide</h1>
    <p>Welcome to the interactive 2D animated guide for performing the Lesser Banishing Ritual of the Pentagram (LBRP). This visualization tool will help you learn and practice this fundamental magical ritual.</p>
    
    <div class="canvas-container">
      <canvas id="ritual-canvas" width="600" height="400"></canvas>
    </div>
    
    <div class="controls">
      <button class="control-button" id="startButton">Start Animation</button>
      <button class="control-button" id="resetButton">Reset</button>
    </div>
    
    <h2>Ritual Steps</h2>
    
    <div class="step">
      <h3>1. The Qabalistic Cross</h3>
      <p>The animation will guide you through the following movements:</p>
      <ul>
        <li>Touch your forehead: "Atah" (Thou art)</li>
        <li>Touch your chest: "Malkuth" (Kingdom)</li>
        <li>Touch your right shoulder: "Ve-Geburah" (and the Power)</li>
        <li>Touch your left shoulder: "Ve-Gedulah" (and the Glory)</li>
        <li>Clasp your hands at your chest: "Le-Olam, Amen" (Forever, Amen)</li>
      </ul>
    </div>
    
    <div class="step">
      <h3>2. The Pentagrams</h3>
      <p>Watch as glowing pentagrams are drawn in each cardinal direction:</p>
      <ul>
        <li>East: Yellow pentagram</li>
        <li>South: Red pentagram</li>
        <li>West: Blue pentagram</li>
        <li>North: Green pentagram</li>
      </ul>
    </div>
    
    <div class="step">
      <h3>3. Calling the Archangels</h3>
      <p>Observe as each Archangel is invoked:</p>
      <ul>
        <li>East: Raphael</li>
        <li>South: Michael</li>
        <li>West: Gabriel</li>
        <li>North: Uriel</li>
      </ul>
    </div>
    
    <div class="step">
      <h3>4. Completion</h3>
      <p>The animation concludes by showing all four pentagrams glowing simultaneously, forming a protective circle.</p>
    </div>
    
    <div class="disclaimer">
      <p>Disclaimer: This animation is a learning aid and visualization tool. Effective magical practice requires personal focus, intent, and energy work beyond what can be demonstrated visually.</p>
    </div>
    
    <p>For more magical learning tools, visit our <a href="https://websim.ai/magical-studies">Magical Studies section</a> or join our <a href="https://websim.ai/forums/ritual-practice">Ritual Practice forum</a>.</p>
  </div>

  <script>
    const canvas = document.getElementById('ritual-canvas');
    const ctx = canvas.getContext('2d');
    const startButton = document.getElementById('startButton');
    const resetButton = document.getElementById('resetButton');

    let animationFrame;
    let step = 0;
    let time = 0;
    let scale = 1;

    function resizeCanvas() {
      const container = document.querySelector('.canvas-container');
      const containerWidth = container.clientWidth;
      scale = Math.min(1, containerWidth / 600);
      canvas.style.width = `${600 * scale}px`;
      canvas.style.height = `${400 * scale}px`;
    }

    window.addEventListener('resize', resizeCanvas);
    resizeCanvas();

    function drawPentagram(x, y, size, color) {
      ctx.beginPath();
      ctx.moveTo(x, y - size);
      for (let i = 0; i < 5; i++) {
        let angle = (i * 4 * Math.PI) / 5 - Math.PI / 2;
        ctx.lineTo(
          x + size * Math.cos(angle),
          y + size * Math.sin(angle)
        );
      }
      ctx.closePath();
      ctx.strokeStyle = color;
      ctx.lineWidth = 2;
      ctx.stroke();
    }

    function drawPractitioner(x, y, armPosition) {
      // Head
      ctx.beginPath();
      ctx.arc(x, y - 40, 20, 0, Math.PI * 2);
      ctx.fillStyle = '#e0e0e0';
      ctx.fill();

      // Body
      ctx.beginPath();
      ctx.moveTo(x, y - 20);
      ctx.lineTo(x, y + 60);
      ctx.strokeStyle = '#e0e0e0';
      ctx.lineWidth = 4;
      ctx.stroke();

      // Arms
      ctx.beginPath();
      if (armPosition === 'forehead') {
        ctx.moveTo(x - 30, y + 20);
        ctx.lineTo(x, y - 30);
      } else if (armPosition === 'chest') {
        ctx.moveTo(x - 30, y + 20);
        ctx.lineTo(x, y + 30);
      } else if (armPosition === 'right') {
        ctx.moveTo(x, y);
        ctx.lineTo(x + 40, y - 20);
      } else if (armPosition === 'left') {
        ctx.moveTo(x, y);
        ctx.lineTo(x - 40, y - 20);
      } else {
        ctx.moveTo(x - 30, y + 20);
        ctx.lineTo(x + 30, y + 20);
      }
      ctx.strokeStyle = '#e0e0e0';
      ctx.lineWidth = 4;
      ctx.stroke();
    }

    function drawArchangel(x, y, name) {
      ctx.font = '16px Arial';
      ctx.fillStyle = '#e0e0e0';
      ctx.textAlign = 'center';
      ctx.fillText(name, x, y);

      // Simple glow effect
      ctx.beginPath();
      ctx.arc(x, y - 30, 20, 0, Math.PI * 2);
      ctx.fillStyle = 'rgba(255, 255, 255, 0.2)';
      ctx.fill();
    }

    function animate() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      
      time += 1/60;  // Assuming 60 FPS

      switch(step) {
        case 0:  // Qabalistic Cross
          drawPractitioner(300, 200, 'forehead');
          if (time > 1) {
            step++;
            time = 0;
          }
          break;
        case 1:
          drawPractitioner(300, 200, 'chest');
          if (time > 1) {
            step++;
            time = 0;
          }
          break;
        case 2:
          drawPractitioner(300, 200, 'right');
          if (time > 1) {
            step++;
            time = 0;
          }
          break;
        case 3:
          drawPractitioner(300, 200, 'left');
          if (time > 1) {
            step++;
            time = 0;
          }
          break;
        case 4:
          drawPractitioner(300, 200, 'center');
          if (time > 1) {
            step++;
            time = 0;
          }
          break;
        case 5:  // East Pentagram
          drawPentagram(500, 200, 50, `rgba(255, 255, 0, ${Math.min(time, 1)})`);
          if (time > 2) {
            step++;
            time = 0;
          }
          break;
        case 6:  // South Pentagram
          drawPentagram(500, 200, 50, 'rgba(255, 255, 0, 1)');
          drawPentagram(300, 350, 50, `rgba(255, 0, 0, ${Math.min(time, 1)})`);
          if (time > 2) {
            step++;
            time = 0;
          }
          break;
        case 7:  // West Pentagram
          drawPentagram(500, 200, 50, 'rgba(255, 255, 0, 1)');
          drawPentagram(300, 350, 50, 'rgba(255, 0, 0, 1)');
          drawPentagram(100, 200, 50, `rgba(0, 0, 255, ${Math.min(time, 1)})`);
          if (time > 2) {
            step++;
            time = 0;
          }
          break;
        case 8:  // North Pentagram
          drawPentagram(500, 200, 50, 'rgba(255, 255, 0, 1)');
          drawPentagram(300, 350, 50, 'rgba(255, 0, 0, 1)');
          drawPentagram(100, 200, 50, 'rgba(0, 0, 255, 1)');
          drawPentagram(300, 50, 50, `rgba(0, 255, 0, ${Math.min(time, 1)})`);
          if (time > 2) {
            step++;
            time = 0;
          }
          break;
        case 9:  // Archangels
          drawPentagram(500, 200, 50, 'rgba(255, 255, 0, 1)');
          drawPentagram(300, 350, 50, 'rgba(255, 0, 0, 1)');
          drawPentagram(100, 200, 50, 'rgba(0, 0, 255, 1)');
          drawPentagram(300, 50, 50, 'rgba(0, 255, 0, 1)');
          if (time < 1) drawArchangel(500, 200, 'Raphael');
          if (time < 2 && time >= 1) drawArchangel(300, 350, 'Michael');
          if (time < 3 && time >= 2) drawArchangel(100, 200, 'Gabriel');
          if (time < 4 && time >= 3) drawArchangel(300, 50, 'Uriel');
          if (time > 4) {
            step++;
            time = 0;
          }
          break;
        case 10:  // Final glow
          drawPentagram(500, 200, 50, `rgba(255, 255, 0, ${1 + Math.sin(time * 5) * 0.2})`);
          drawPentagram(300, 350, 50, `rgba(255, 0, 0, ${1 + Math.sin(time * 5) * 0.2})`);
          drawPentagram(100, 200, 50, `rgba(0, 0, 255, ${1 + Math.sin(time * 5) * 0.2})`);
          drawPentagram(300, 50, 50, `rgba(0, 255, 0, ${1 + Math.sin(time * 5) * 0.2})`);
          drawArchangel(500, 200, 'Raphael');
          drawArchangel(300, 350, 'Michael');
          drawArchangel(100, 200, 'Gabriel');
          drawArchangel(300, 50, 'Uriel');
          break;
      }

      animationFrame = requestAnimationFrame(animate);
    }

    function startAnimation() {
      cancelAnimationFrame(animationFrame);
      step = 0;
      time = 0;
      animate();
    }

    function resetAnimation() {
      cancelAnimationFrame(animationFrame);
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      step = 0;
      time = 0;
    }

    startButton.addEventListener('click', startAnimation);
    resetButton.addEventListener('click', resetAnimation);
  </script>
</body></html>
