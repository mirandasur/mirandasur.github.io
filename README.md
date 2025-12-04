<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Miranda — Portfolio</title>
  <style>
    /* —————— ESTILO EDITORIAL MINIMAL —————— */
    body {
      margin: 0;
      padding: 60px;
      font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
      background: #ffffff;
      color: #111;
      line-height: 1.6;
    }
    h1 {
      font-size: 60px;
      font-weight: 300;
      margin-bottom: 10px;
      letter-spacing: -1px;
    }
    h2 {
      font-size: 22px;
      font-weight: 300;
      margin-top: 60px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    p {
      max-width: 650px;
      font-size: 18px;
    }
    a {
      color: #111;
      text-decoration: none;
      border-bottom: 1px solid #111;
    }
    a:hover {
      opacity: 0.6;
    }
    .section {
      margin-top: 80px;
    }
    .video-embed, .image {
      margin-top: 30px;
      max-width: 800px;
      width: 100%;
    }
    nav {
      position: fixed;
      top: 40px;
      right: 40px;
      font-size: 15px;
      text-transform: uppercase;
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      gap: 8px;
    }
    nav a {
      border: none;
      font-size: 14px;
      letter-spacing: 2px;
    }
    /* Mobile */
    @media(max-width: 700px) {
      body { padding: 25px; }
      h1 { font-size: 40px; }
      nav { position: static; margin-bottom: 20px; }
      nav a { font-size: 12px; }
    }
  </style>
</head>

<body>

  <!-- —————— MENU SUPERIOR —————— -->
  <nav>
    <a href="#portfolio">Portfolio</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- —————— TITULAR EDITORIAL —————— -->
  <h1>Miranda</h1>
  <p>Dancer | Movement artist.  
     Movement research • Performance • Classes.</p>

  <!-- —————— PORTFOLIO —————— -->
  <div class="section" id="portfolio">
    <h2>Portfolio</h2>
    <p>RECENT WORK.</p>

    <!-- Video embebido de YouTube o Vimeo -->
    <div class="video-embed">
      <!-- Reemplazar VIDEO_ID con tu video -->
      <iframe width="100%" height="420"
      src="https://www.youtube.com/embed/VIDEO_ID"
      frameborder="0" allowfullscreen></iframe>
    </div>

    <!-- Otra sección de imágenes si querés -->
    <img class="image" src="https://via.placeholder.com/900x500" alt="Proyecto">
    <img class="image" src="https://via.placeholder.com/900x500" alt="Proyecto">
  </div>

  <!-- —————— ABOUT —————— -->
  <div class="section" id="about">
    <h2>About</h2>
    <p>
      Soy Miranda, bailarina y creadora multimedial.  
      Trabajo con movimiento, edición y narrativa visual para crear piezas que mezclan
      danza, viaje y estética cinematográfica.  
      Actual residente en Alemania.
    </p>
  </div>

  <!-- —————— CONTACTO —————— -->
  <div class="section" id="contact">
    <h2>Contact</h2>
    <p>
      Email: <a href="mailto:tucorreo@gmail.com">tucorreo@gmail.com</a><br>
      Instagram: <a href="https://instagram.com/TUUSER" target="_blank">@TUUSER</a><br>
      YouTube: <a href="https://youtube.com/tu_canal" target="_blank">YouTube</a>
    </p>
  </div>

</body>
</html>
# mirandasur.github.io
