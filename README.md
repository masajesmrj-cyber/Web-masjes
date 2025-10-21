<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>MasajesMRJ — Bienestar y Relajación</title>
  <meta name="description" content="Masajes profesionales en Tobarra (Albacete). Relájate, renueva tu cuerpo y mejora tu bienestar con MasajesMRJ.">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --color-primario: #b5a89f;
      --color-texto: #2b2b2b;
      --color-fondo: #f8f7f5;
      --color-card: #ffffff;
      --color-gris: #777;
      --max: 1100px;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--color-fondo);
      color: var(--color-texto);
      line-height: 1.6;
    }
    header {
      background: var(--color-card);
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      padding: 1rem 2rem;
    }
    .container { max-width: var(--max); margin: auto; padding: 1rem; }
    h1, h2, h3 { color: var(--color-texto); }
    h1 { font-size: 2rem; }
    h2 { margin-top: 1.5rem; }
    .hero {
      text-align: center;
      padding: 3rem 1rem;
    }
    .hero p {
      color: var(--color-gris);
      max-width: 600px;
      margin: 1rem auto;
    }
    .btn {
      background: var(--color-primario);
      color: white;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
      margin-top: 1rem;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .service {
      background: var(--color-card);
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    footer {
      text-align: center;
      color: var(--color-gris);
      font-size: 0.9rem;
      padding: 2rem 0;
      margin-top: 3rem;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      background: var(--color-card);
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    input, textarea, select {
      padding: 0.75rem;
      border: 1px solid #ddd;
      border-radius: 6px;
      font-size: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>MasajesMRJ — Bienestar y Relajación</h1>
      <p>Tobarra, Albacete, España</p>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <p>En MasajesMRJ te ayudamos a desconectar del estrés y recuperar tu bienestar con masajes profesionales personalizados. Relájate, respira y deja que cuidemos de ti.</p>
      <button class="btn" onclick="document.getElementById('contacto').scrollIntoView({behavior:'smooth'})">
        Reserva tu cita
      </button>
    </section>

    <section id="servicios">
      <h2>Servicios</h2>
      <div class="services">
        <div class="service">
          <h3>Masaje de Relajación</h3>
          <p>Ideal para reducir el estrés y relajar la mente. Técnicas suaves y ambiente tranquilo.</p>
        </div>
        <div class="service">
          <h3>Masaje Terapéutico</h3>
          <p>Alivia dolores musculares y contracturas. Enfocado en la recuperación corporal.</p>
        </div>
        <div class="service">
          <h3>Masaje Deportivo</h3>
          <p>Perfecto antes o después del ejercicio. Mejora el rendimiento y previene lesiones.</p>
        </div>
      </div>
    </section>

    <section id="contacto" style="margin-top:3rem;">
      <h2>Contacto y reservas</h2>
      <p>Puedes enviarnos tu consulta o solicitud de cita. Te responderemos lo antes posible.</p>
      <form action="https://formspree.io/f/mkgqaenv" method="POST">
        <label>Nombre</label>
        <input type="text" name="nombre" required>
        <label>Correo electrónico</label>
        <input type="email" name="email" required>
        <label>Tipo de masaje</label>
        <select name="servicio">
          <option>Relajación</option>
          <option>Terapéutico</option>
          <option>Deportivo</option>
        </select>
        <label>Mensaje</label>
        <textarea name="mensaje" rows="4" placeholder="Cuéntanos en qué podemos ayudarte"></textarea>
        <button type="submit" class="btn">Enviar mensaje</button>
      </form>
    </section>
  </main>

  <footer>
    © 2025 MasajesMRJ — Tobarra, Albacete. Todos los derechos reservados.  
    <br>
    Contacto: <a href="mailto:masajesmrj@gmail.com">masajesmrj@gmail.com</a>
  </footer>
</body>
</html>
