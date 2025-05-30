<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bazac - IPN Delivery</title>
  <style>
    :root {
      --color1: #800000;
      --color2: #a10000;
      --color3: #f8f0f0;
      --text-dark: #222;
      --text-light: #fff;
      --bg-light: #fafafa;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: var(--bg-light);
      color: var(--text-dark);
    }

    header {
      background: linear-gradient(90deg, var(--color1), var(--color2));
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header img {
      height: 120px;
    }

    header h1 {
      font-size: 32px;
      font-weight: 600;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c') no-repeat center center/cover;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: var(--text-light);
      text-align: center;
    }

    .hero h2 {
      font-size: 40px;
      background-color: rgba(0, 0, 0, 0.5);
      padding: 20px 30px;
      border-radius: 15px;
    }

    .section {
      padding: 60px 20px;
      text-align: center;
    }

    .section.bg-light {
      background-color: var(--color3);
    }

    .section h3 {
      font-size: 28px;
      margin-bottom: 20px;
      color: var(--color1);
    }

    .section p {
      max-width: 600px;
      margin: 0 auto 30px;
      font-size: 18px;
    }

    a.button {
      background: var(--color1);
      color: white;
      padding: 15px 35px;
      border-radius: 10px;
      text-decoration: none;
      font-size: 18px;
      font-weight: 600;
      transition: all 0.3s ease;
    }

    a.button:hover {
      background: var(--color2);
      transform: scale(1.05);
    }

    footer {
      background: var(--color1);
      color: white;
      text-align: center;
      padding: 25px 15px;
    }

    .social-icons {
      margin: 12px 0;
    }

    .social-icons a {
      margin: 0 12px;
      display: inline-block;
      transition: transform 0.3s ease;
    }

    .social-icons a:hover {
      transform: scale(1.2);
    }

    .social-icons img {
      width: 30px;
      height: 30px;
      /* ❌ Eliminamos el filtro que ocultaba los íconos */
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        gap: 10px;
      }

      header img {
        height: 90px;
      }

      .hero h2 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>

<header>
  <img src="https://i.imgur.com/FYTYoHj.png" alt="Logo Bazac">
  <h1>BAZAC</h1>
  <img src="https://images.seeklogo.com/logo-png/47/2/instituto-politecnico-nacional-logo-png_seeklogo-478563.png" alt="Logo IPN">
</header>

<section class="hero">
  <h2>Bienvenido a BAZAC, tu app de delivery del IPN</h2>
</section>

<section class="section">
  <h3>¿Qué es BAZAC?</h3>
  <p>Una aplicación pensada para estudiantes, docentes y trabajadores del IPN. Apoyamos el emprendimiento politécnico y llevamos lo que necesitas directamente a ti.</p>
</section>

<section class="section bg-light">
  <h3>Únete a la comunidad</h3>
  <p>Forma parte de esta red de emprendedores y usuarios IPN. ¡Regístrate ahora y haz historia con nosotros!</p>
  <a href="registro.html" class="button">Registrarse</a>
</section>

<footer>
  <div class="social-icons">
    <a href="https://facebook.com" target="_blank">
      <img src="https://img.freepik.com/vector-premium/ilustracion-vectorial-icono-redes-sociales-facebook_534308-21672.jpg?semt=ais_hybrid&w=740" alt="Facebook" />
    </a>
    <a href="https://twitter.com" target="_blank">
      <img src="https://images.freeimages.com/image/large-previews/f35/x-twitter-logo-on-black-circle-5694247.png" alt="Twitter" />
    </a>
    <a href="https://instagram.com" target="_blank">
      <img src="https://images.vexels.com/content/137198/preview/instagram-icon-colorful-102cf8.png" alt="Instagram" />
    </a>
  </div>
  <p>© 2025 Bazac - Creado por estudiantes del Instituto Politécnico Nacional</p>
  <p>Apoyando el emprendimiento politécnico, conectando ideas que se resuelven.</p>
</footer>

</body>
</html>
