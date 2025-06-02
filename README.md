## Hi welcome 👋

**MILENIUMTVI/MILENIUMTVI** 

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Transmisión en Vivo</title>
  <!-- Estilos de Video.js -->
  <link href="https://vjs.zencdn.net/8.10.0/video-js.css" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      padding: 20px;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
    }
    h1 {
      color: #222;
      margin-bottom: 20px;
    }
    .video-js {
      width: 90%;
      max-width: 900px;
      margin: 0 auto;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <h1>Transmisión en Vivo</h1>
  <!-- Reproductor de Video.js -->
  <video-js id="my-video" class="video-js" controls preload="auto" autoplay muted>
    <source src="[TU_URL_M3U8](https://app.viloud.tv/hls/channel/c8984eee3163b175a0c725860f53749d.m3u8)" type="application/x-mpegURL">
    <p>Tu navegador no soporta el video.</p>
  </video-js>
  <!-- Script de Video.js -->
  <script src="https://vjs.zencdn.net/8.10.0/video.min.js"></script>
  <script>
    // Inicializa el reproductor
    var player = videojs('my-video');
  </script>
</body>
</html>
