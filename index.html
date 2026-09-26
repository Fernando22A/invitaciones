
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Mis Quince Años - IRINA</title>
  <style>
    body {
      background-color: #050e21;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      min-height: 100vh;
      /* Evita que se seleccione el texto por accidente al deslizar en el celular */
      -webkit-user-select: none;
      user-select: none;
      -webkit-touch-callout: none;
    }

    .invitation-container {
      width: 100%;
      max-width: 480px;
      text-align: center;
      background-color: #050e21;
    }

    /* Imágenes unidas perfectamente y con transición suave al cargar */
    .invitation-container img {
      width: 100%;
      height: auto;
      display: block;
      margin: 0;
      padding: 0;
      border: none;
    }

    /* Sección del botón y el mapa */
    .map-section {
      padding: 35px 15px 70px 15px; /* Margen inferior extra para que luzca bien el botón animado */
      width: 100%;
      box-sizing: border-box;
      background-color: #050e21;
    }

    /* Animación de pulso para el botón de ubicación */
    @keyframes latido {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.06);
      }
      100% {
        transform: scale(1);
      }
    }

    /* Estilo del botón de ubicación con animación aplicada */
    .btn-ubicacion {
      background-color: #c0c0c0;
      color: #050e21;
      padding: 14px 25px;
      border-radius: 25px;
      font-family: 'Georgia', serif;
      font-weight: bold;
      font-size: 1.1em;
      text-decoration: none;
      display: inline-block;
      box-shadow: 0 4px 15px rgba(0,0,0,0.4);
      letter-spacing: 1px;
      animation: latido 2s infinite ease-in-out; /* Animación constante activa */
      transition: background-color 0.3s;
    }

    .btn-ubicacion:hover {
      background-color: #e0e0e0;
    }

    /* Estilo para el botón flotante de música (subido a 80px para no ser tapado) */
    .music-btn {
      position: fixed;
      bottom: 80px; 
      right: 20px;
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(5px);
      border: 1px solid rgba(255, 255, 255, 0.4);
      color: white;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      font-size: 20px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 1000;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      transition: background 0.3s, transform 0.2s;
    }

    .music-btn:hover {
      background: rgba(255, 255, 255, 0.4);
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <!-- Audio de fondo (con loop para que se repita) -->
  <audio id="background-audio" loop>
    <source src="Moonstruck.mp3" type="audio/mp3">
  </audio>

  <!-- Botón flotante para controlar la música manualmente -->
  <button class="music-btn" id="music-toggle" onclick="toggleMusic()" title="Reproducir / Pausar música">
    🎵
  </button>

  <div class="invitation-container">
    <!-- Imagen 1 carga de inmediato -->
    <img src="foto3.jpeg" alt="Invitación Irina - Parte 1" />
    
    <!-- Imágenes 2 y 3 con lazy loading para optimizar velocidad -->
    <img src="foto22.jpeg" alt="Invitación Irina - Parte 2" loading="lazy" />
    <img src="foto2.jpeg" alt="Invitación Irina - Parte 3" loading="lazy" />
    
    <!-- Botón interactivo para ver la ubicación en Google Maps -->
    <div class="map-section">
      <a href="https://www.google.com/maps/place/Rincon+De+Lorenzo/@-27.505876,-58.833958,19z/data=!4m6!3m5!1s0x94456c77ae2749b7:0xa639e7a19a33dfac!8m2!3d-27.5058764!4d-58.8339577!16s%2Fg%2F11f0l3f4ql?hl=es&entry=ttu&g_ep=EgoyMDI2MDkwMi4wIKXMDSoASAFQAw%3D%3D" target="_blank" class="btn-ubicacion">
        📍 VER UBICACIÓN
      </a>
    </div>
  </div>

  <!-- Script para la música -->
  <script>
    const audio = document.getElementById('background-audio');
    const musicBtn = document.getElementById('music-toggle');
    let isPlaying = false;

    function toggleMusic() {
      if (isPlaying) {
        audio.pause();
        musicBtn.textContent = '🔇';
        isPlaying = false;
      } else {
        audio.currentTime = 9; // Salta al segundo 9
        audio.play().then(() => {
          musicBtn.textContent = '🎵';
          isPlaying = true;
        }).catch(error => {
          console.log("El navegador requirió interacción previa.");
        });
      }
    }

    // Intenta reproducir automáticamente al primer toque en la pantalla
    document.body.addEventListener('click', function() {
      if (!isPlaying) {
        audio.currentTime = 9; // Salta al segundo 9 también aquí
        audio.play().then(() => {
          musicBtn.textContent = '🎵';
          isPlaying = true;
        }).catch(() => {});
      }
    }, { once: true });
  </script>

</body>
</html>
