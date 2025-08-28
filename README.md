<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eclipse Tools</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: radial-gradient(circle at top, #0f0c29, #302b63, #24243e);
      color: white;
      overflow-x: hidden;
    }

    /* Fundo animado */
    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: -1;
    }

    h1 {
      text-align: center;
      margin-top: 50px;
      font-size: 3rem;
      background: linear-gradient(90deg, #ff00ff, #00ffff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 20px rgba(255, 0, 255, 0.6), 0 0 30px rgba(0, 255, 255, 0.6);
    }

    p {
      text-align: center;
      margin-top: -10px;
      font-size: 1.2rem;
      color: #bbb;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
      max-width: 1200px;
      margin: auto;
    }

    .card {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 15px;
      padding: 25px;
      text-align: center;
      transition: 0.3s;
      border: 1px solid rgba(255, 255, 255, 0.1);
      cursor: pointer;
      box-shadow: 0 0 15px rgba(255,255,255,0.1);
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 0 25px rgba(255,255,255,0.4);
      border-color: rgba(255,255,255,0.3);
    }

    .card h2 {
      font-size: 1.5rem;
      margin-bottom: 10px;
      color: #fff;
      text-shadow: 0 0 10px #00ffff, 0 0 20px #ff00ff;
    }

    .card a {
      text-decoration: none;
      color: #00e0ff;
      font-weight: bold;
      transition: 0.2s;
    }

    .card a:hover {
      color: #ff00ff;
      text-shadow: 0 0 10px #ff00ff;
    }
  </style>
</head>
<body>

  <div id="particles-js"></div>

  <h1>Eclipse Tools</h1>
  <p>Ferramentas de Automação Educacional</p>

  <div class="cards">
    <div class="card">
      <h2>Leia</h2>
      <a href="https://leiasp.cupiditys.lol/" target="_blank">Acessar</a>
    </div>
    <div class="card">
      <h2>Tarefas</h2>
      <a href="https://taskitos.cupiditys.lol/" target="_blank">Acessar</a>
    </div>
    <div class="card">
      <h2>Speak</h2>
      <a href="https://speakify.cupiditys.lol/" target="_blank">Acessar</a>
    </div>
    <div class="card">
      <h2>Redação</h2>
      <a href="https://redacao.cupiditys.lol/" target="_blank">Acessar</a>
    </div>
    <div class="card">
      <h2>Prepara SP</h2>
      <a href="https://crimsonstrauss.xyz/preparasp" target="_blank">Acessar</a>
    </div>
    <div class="card">
      <h2>Khan</h2>
      <a href='javascript:fetch("https://raw.githubusercontent.com/Niximkk/Khanware/refs/heads/main/Khanware.js").then(t=>t.text()).then(eval);'>Acessar</a>
    </div>
    <div class="card">
      <h2>Alura</h2>
      <a href="https://crimsonstrauss.xyz/alura" target="_blank">Acessar</a>
    </div>
  </div>

  <!-- Script Particles.js -->
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": { "value": 80 },
        "size": { "value": 3 },
        "move": { "speed": 2 },
        "line_linked": { "enable": true },
        "color": { "value": "#ffffff" }
      }
    });
  </script>

</body>
</html>
