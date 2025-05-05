<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BerMatModZ: Hacker & Dev Zone</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(135deg, #000000, #0a0a0a);
      font-family: 'Share Tech Mono', monospace;
      color: #00ffea;
      overflow-x: hidden;
      background-image: url('https://www.transparenttextures.com/patterns/cubes.png');
    }
    header {
      background: radial-gradient(circle, #0ff 0%, #000 100%);
      padding: 3rem;
      text-align: center;
      box-shadow: 0 0 25px #00ffea, inset 0 0 10px #ff00c8;
      border-bottom: 3px dashed #ff00c8;
    }
    header h1 {
      font-size: 3rem;
      text-shadow: 0 0 8px #00ffea, 0 0 12px #ff00c8;
      animation: flicker 2s infinite alternate;
    }
    @keyframes flicker {
      0% { opacity: 1; }
      50% { opacity: 0.8; }
      100% { opacity: 1; }
    }
    .glitch {
      color: #00ffea;
      position: relative;
    }
    .glitch::before, .glitch::after {
      content: attr(data-text);
      position: absolute;
      left: 0;
      width: 100%;
      overflow: hidden;
      color: #ff00c8;
    }
    .glitch::before {
      animation: glitchTop 2s infinite linear alternate-reverse;
      top: -2px;
    }
    .glitch::after {
      animation: glitchBottom 2s infinite linear alternate-reverse;
      bottom: -2px;
    }
    @keyframes glitchTop {
      0% { clip-path: inset(0 0 90% 0); }
      100% { clip-path: inset(0 0 10% 0); }
    }
    @keyframes glitchBottom {
      0% { clip-path: inset(90% 0 0 0); }
      100% { clip-path: inset(10% 0 0 0); }
    }
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      margin-bottom: 1rem;
      font-size: 2.5rem;
      color: #ff00c8;
      text-shadow: 0 0 5px #00ffea;
      border-bottom: 2px dotted #00ffea;
    }
    .card {
      background: #111;
      padding: 2rem;
      margin-bottom: 2rem;
      border: 2px double #00ffea;
      border-radius: 15px;
      transition: transform 0.3s, box-shadow 0.3s;
      box-shadow: 0 0 20px #0ff2, inset 0 0 10px #ff00c822;
      position: relative;
    }
    .card::after {
      content: '★';
      position: absolute;
      top: 10px;
      right: 20px;
      font-size: 2rem;
      color: #ff00c8;
    }
    .card:hover {
      transform: scale(1.03);
      box-shadow: 0 0 30px #00ffea, 0 0 10px #ff00c8 inset;
    }
    .socials {
      display: flex;
      gap: 1.5rem;
      justify-content: center;
      margin-top: 2rem;
      flex-wrap: wrap;
    }
    .socials a {
      color: #00ffea;
      font-size: 1.8rem;
      transition: transform 0.3s, color 0.3s;
      text-decoration: none;
      text-shadow: 0 0 5px #ff00c8;
    }
    .socials a:hover {
      transform: scale(1.3);
      color: #ff00c8;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.95rem;
      background: #0f0f0f;
      color: #888;
      border-top: 2px dashed #00ffea44;
    }
  </style>
</head>
<body>
  <header>
    <h1 class="glitch" data-text="BerMatModZ: Hacker & Dev Zone">BerMatModZ: Hacker & Dev Zone</h1>
    <p style="color:#ff00c8; font-size: 1.2rem;">"El código es mi voz, el mundo digital mi campo de batalla."</p>
  </header>  <section id="sobremi">
    <h2>Sobre mí</h2>
    <div class="card">
      <p><strong>Nombre:</strong> Anth'Zz Berrocal</p>
      <p><strong>Alias:</strong> BerMatModZ</p>
      <p><strong>Ubicación:</strong> Andahuaylas, Perú</p>
      <p><strong>Especialidad:</strong> Desarrollo de bots, ciberseguridad, tecnología e inteligencia artificial.</p>
      <p><strong>Extra:</strong> Apasionado por el gimnasio y el mundo hacker.</p>
    </div>
  </section>  <section id="proyectos">
    <h2>Proyectos Destacados</h2>
    <div class="card">
      <h3>⚡BerMat-Bot MD🔥</h3>
      <p>Bot de WhatsApp con IA, juegos, stickers, y funciones avanzadas. Diseñado para dominar el entorno digital.</p>
    </div>
    <div class="card">
      <h3>BerMat_Mods</h3>
      <p>Herramientas personalizadas y mods para usuarios expertos. Potencia máxima para mentes poderosas.</p>
    </div>
    <div class="card">
      <h3>FAMA</h3>
      <p>Fuerza Anónima de Mentes Avanzadas: red secreta de elite cibernética con objetivos revolucionarios.</p>
    </div>
  </section>  <section id="contacto">
    <h2>Contacto</h2>
    <p>Conéctate conmigo en mis redes sociales:</p>
    <div class="socials">
      <a href="https://github.com/Anthzberrocal" target="_blank">GitHub</a>
      <a href="https://t.me/Anthzberrocal" target="_blank">Telegram</a>
      <a href="https://instagram.com/Anthzberrocal" target="_blank">Instagram</a>
    </div>
  </section>  <footer>
    <p>&copy; 2025 BerMatModZ. Todos los derechos reservados. – Dominando la red desde Andahuaylas.</p>
  </footer>
</body>
</html>
