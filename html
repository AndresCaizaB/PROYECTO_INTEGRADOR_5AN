<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>CONTROL DE BRAZO ROBOTICO</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --color-bg: #181b1e;
      --color-card: #bd2323;
      --color-joystick: #232321;
      --color-btn-blue: #3aa3f7;
      --color-btn-yellow: #ffe03a;
      --color-btn-shadow: #8885;
      --color-label: #fff;
      --color-shadow: #0005;
      --color-accent: #138184;
      --color-border: #fff2;
      --color-ws-ok: #4aff71;
      --color-ws-err: #ff5252;
      --isu-green: #527c7a;
    }
    body {
      background: var(--color-bg);
      color: var(--color-label);
      font-family: 'Segoe UI', Arial, sans-serif;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
    }
    .top-bar {
      display: flex;
      align-items: center;
      width: 100%;
      margin-bottom: 12px;
      margin-top: 10px;
      padding-left: 14px;
    }
    .logo-isuct {
      height: 62px;
      width: auto;
      background: transparent;
      margin-right: 22px;
      filter: drop-shadow(1px 2px 2px #0008);
    }
    .main-title {
      font-size: 2.0em;
      font-weight: bold;
      color: var(--isu-green);
      letter-spacing: 2.5px;
      text-shadow: 1px 2px 8px #000a;
      margin: 0;
      padding: 0;
      line-height: 1.1;
    }
    .card {
      background: var(--color-card);
      border-radius: 22px;
      box-shadow: 0 8px 32px var(--color-shadow);
      margin-top: 18px;
      padding: 36px 32px 22px 32px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      align-items: flex-start;
      max-width: 600px;
      width: 98vw;
    }
    .joystick-area {
      flex: 2;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-right: 32px;
      min-width: 180px;
    }
    .joystick-label {
      text-align: center;
      margin-bottom: 12px;
      font-size: 1.1em;
      color: var(--color-accent);
      font-weight: bold;
      letter-spacing: 1px;
    }
    .joystick {
      background: radial-gradient(circle at 30% 35%, #353532 60%, #191917 100%);
      box-shadow: 0 5px 25px #0009, 0 1px 2px #fff2 inset;
      border: 4px solid #111;
      border-radius: 50%;
      width: 130px;
      height: 130px;
      position: relative;
      margin-bottom: 18px;
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: box-shadow 0.2s;
    }
    .joystick-stick {
      background: #232321;
      border-radius: 50%;
      width: 52px;
      height: 52px;
      box-shadow: 0 2px 12px #000b, 0 0 0 6px #444b;
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      transition: left 0.1s, top 0.1s;
      border: 2px solid #444;
    }
    .buttons-area {
      flex: 1.2;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .btns-grid {
      display: grid;
      grid-template-columns: 55px 55px;
      grid-gap: 22px 22px;
      margin-bottom: 22px;
    }
    .btn-joy {
      width: 54px;
      height: 54px;
      border-radius: 50%;
      border: 3px solid var(--color-border);
      box-shadow: 0 4px 12px var(--color-btn-shadow);
      font-size: 1.4em;
      font-weight: bold;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: transform 0.13s, box-shadow 0.13s;
      margin: 0;
      user-select: none;
    }
    .btn-joy:active {
      transform: scale(0.93);
      box-shadow: 0 2px 4px var(--color-btn-shadow);
      filter: brightness(0.93);
    }
    .btn-blue { background: var(--color-btn-blue); color: #111; }
    .btn-yellow { background: var(--color-btn-yellow); color: #111; }
    .btn-label {
      text-align: center;
      font-size: 1em;
      color: #fff;
      margin-bottom: 5px;
      font-weight: 500;
      text-shadow: 1px 2px 5px #000c;
    }
    .sliders-area {
      display: flex;
      flex-direction: column;
      align-items: stretch;
      gap: 10px;
      width: 100%;
      margin-top: 6px;
    }
    .slider-group {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 6px;
    }
    .slider-label {
      min-width: 60px;
      margin-right: 9px;
      color: var(--isu-green);
      font-weight: bold;
      letter-spacing: 1px;
    }
    input[type=range] {
      flex: 1;
      margin: 0 7px;
      accent-color: var(--isu-green);
      background: #fff1;
      border-radius: 8px;
      height: 7px;
    }
    .value-label {
      width: 32px;
      text-align: right;
      color: #7bd1ff;
      font-family: monospace;
    }
    .ws-status {
      margin-top: 10px;
      margin-bottom: 0;
      padding: 4px 18px;
      border-radius: 8px;
      font-size: 1em;
      font-weight: bold;
      background: #fff1;
      display: inline-block;
      box-shadow: 0 1px 6px #0004;
      letter-spacing: 1px;
    }
    .ws-connected { color: var(--color-ws-ok); }
    .ws-closed, .ws-error { color: var(--color-ws-err); }
    @media (max-width: 740px) {
      .card { flex-direction: column; align-items: center; padding: 22px 6vw 14px 6vw;}
      .joystick-area {margin-right: 0; margin-bottom: 18px;}
      .top-bar { flex-direction: column; align-items: flex-start; padding-left: 0;}
      .logo-isuct { margin-right: 0; margin-bottom: 10px;}
      .main-title { font-size: 1.3em; padding-left: 6px;}
    }
  </style>
</head>
<body>
  <div class="top-bar">
    <img src="https://images.githubusercontent.com/user-images/BOAP1988/ISU-LOGO.png" alt="ISU Central Técnico" class="logo-isuct" />
    <span class="main-title">CONTROL DE BRAZO ROBOTICO</span>
  </div>
  <div id="wsStatus" class="ws-status ws-closed">WebSocket: Desconectado</div>
  <div class="card">
    <div class="joystick-area">
      <div class="joystick-label">Joystick</div>
      <div class="joystick" id="joystick">
        <div class="joystick-stick" id="joystickStick"></div>
      </div>
      <div id="axisLabel" style="margin-top:10px;font-size:1em;color:#fff9;">
        X: <span id="jxVal">0</span> &nbsp; Y: <span id="jyVal">0</span>
      </div>
    </div>
    <div class="buttons-area">
      <div class="btn-label">Botones</div>
      <div class="btns-grid">
        <button class="btn-joy btn-yellow" id="btnA" onclick="sendButton('A')">A</button>
        <button class="btn-joy btn-blue" id="btnB" onclick="sendButton('B')">B</button>
        <button class="btn-joy btn-blue" id="btnC" onclick="sendButton('C')">C</button>
        <button class="btn-joy btn-yellow" id="btnD" onclick="sendButton('D')">D</button>
      </div>
      <div class="sliders-area">
        <div class="slider-group">
          <span class="slider-label">Base:</span>
          <input type="range" min="0" max="180" value="90" id="base" oninput="updateSlider('base')">
          <span class="value-label" id="baseVal">90</span>
        </div>
        <div class="slider-group">
          <span class="slider-label">Hombro:</span>
          <input type="range" min="0" max="180" value="90" id="hombro" oninput="updateSlider('hombro')">
          <span class="value-label" id="hombroVal">90</span>
        </div>
        <div class="slider-group">
          <span class="slider-label">Codo:</span>
          <input type="range" min="0" max="180" value="90" id="codo" oninput="updateSlider('codo')">
          <span class="value-label" id="codoVal">90</span>
        </div>
        <div class="slider-group">
          <span class="slider-label">Pinza:</span>
          <input type="range" min="0" max="180" value="90" id="pinza" oninput="updateSlider('pinza')">
          <span class="value-label" id="pinzaVal">90</span>
        </div>
      </div>
    </div>
  </div>
  <script>
    // Cambia esta IP por la del ESP32
    const wsHost = 'ws://192.168.100.226/ws';
    let ws;
    let wsStatus = document.getElementById('wsStatus');
    let reconnectInterval = 1000; // ms

    function setWsStatus(state, text) {
      wsStatus.textContent = text;
      wsStatus.classList.remove('ws-connected', 'ws-closed', 'ws-error');
      wsStatus.classList.add(state);
    }

    function connectWebSocket() {
      ws = new WebSocket(wsHost);

      ws.onopen = () => setWsStatus('ws-connected', 'WebSocket: Conectado');
      ws.onclose = () => {
        setWsStatus('ws-closed', 'WebSocket: Desconectado');
        setTimeout(connectWebSocket, reconnectInterval);
      };
      ws.onerror = () => {
        setWsStatus('ws-error', 'WebSocket: Error');
        ws.close();
      };
    }
    connectWebSocket();

    // --- SLIDERS ---
    function updateSlider(servo) {
      let val = document.getElementById(servo).value;
      document.getElementById(servo + "Val").textContent = val;
      enviarServos();
    }

    let enviarTimeout;
    function enviarServos() {
      if (enviarTimeout) clearTimeout(enviarTimeout);
      enviarTimeout = setTimeout(() => {
        let base = document.getElementById('base').value;
        let hombro = document.getElementById('hombro').value;
        let codo = document.getElementById('codo').value;
        let pinza = document.getElementById('pinza').value;
        let joyX = lastJoyX ?? 0;
        let joyY = lastJoyY ?? 0;
        if (ws.readyState === WebSocket.OPEN) {
          ws.send(`S,${base},${hombro},${codo},${pinza},${joyX},${joyY}`);
        }
      }, 35);
    }

    // --- BOTONES ---
    function sendButton(btnId) {
      if (ws.readyState === WebSocket.OPEN) {
        ws.send(`B,${btnId}`);
      }
      // Efecto visual
      const btn = document.getElementById('btn'+btnId);
      btn.style.boxShadow = '0 2px 9px #fff8';
      setTimeout(()=>btn.style.boxShadow='', 200);
    }

    // --- JOYSTICK VIRTUAL ---
    const joystick = document.getElementById("joystick");
    const stick = document.getElementById("joystickStick");
    const axisLabel = document.getElementById("axisLabel");
    const jxVal = document.getElementById("jxVal");
    const jyVal = document.getElementById("jyVal");
    let dragging = false, joyCenter = {x:0, y:0}, lastJoyX=0, lastJoyY=0, dragOrigin={x:0,y:0};

    function norm(val, min, max) { return Math.max(min, Math.min(max, val)); }

    function sendJoystick(x, y) {
      lastJoyX = x; lastJoyY = y;
      jxVal.textContent = x;
      jyVal.textContent = y;
      if (ws.readyState === WebSocket.OPEN) {
        ws.send(`J,${x},${y}`);
      }
      enviarServos();
    }

    function getRelativeCoords(e) {
      const rect = joystick.getBoundingClientRect();
      let x = (e.touches ? e.touches[0].clientX : e.clientX) - rect.left;
      let y = (e.touches ? e.touches[0].clientY : e.clientY) - rect.top;
      return { x, y };
    }

    function joystickStart(e) {
      e.preventDefault();
      dragging = true;
      const rect = joystick.getBoundingClientRect();
      joyCenter.x = rect.width/2;
      joyCenter.y = rect.height/2;
      dragOrigin = getRelativeCoords(e);
      moveStick(e);
    }
    function joystickMove(e) {
      if (!dragging) return;
      moveStick(e);
    }
    function joystickEnd(e) {
      dragging = false;
      stick.style.left = "50%";
      stick.style.top = "50%";
      sendJoystick(0,0);
    }
    function moveStick(e) {
      const pos = getRelativeCoords(e);
      let dx = pos.x - joyCenter.x;
      let dy = pos.y - joyCenter.y;
      const maxR = 48;
      const mag = Math.sqrt(dx*dx + dy*dy);
      if (mag > maxR) { dx *= maxR/mag; dy *= maxR/mag; }
      stick.style.left = (50 + dx/joystick.offsetWidth*100) + "%";
      stick.style.top = (50 + dy/joystick.offsetHeight*100) + "%";
      // Normalizado a -100 .. 100
      let nx = Math.round(norm(dx, -maxR, maxR) / maxR * 100);
      let ny = -Math.round(norm(dy, -maxR, maxR) / maxR * 100);
      sendJoystick(nx, ny);
    }
    joystick.addEventListener('mousedown', joystickStart);
    joystick.addEventListener('touchstart', joystickStart, {passive:false});
    document.addEventListener('mousemove', joystickMove);
    document.addEventListener('touchmove', joystickMove, {passive:false});
    document.addEventListener('mouseup', joystickEnd);
    document.addEventListener('touchend', joystickEnd);

    // Inicializa valores
    enviarServos();
  </script>
</body>
</html>
