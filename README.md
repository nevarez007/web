# web
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Academia de Danza Estrella</title>
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Academia de Danza Estrella</h1>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="clases.html">Clases</a>
      <a href="contacto.html">Contacto</a>
      <a href="https://www.instagram.com" target="_blank">Instagram</a>
    </nav>
  </header>

  <marquee>¡Inscripciones Abiertas Todo el Año!</marquee>

  <main>
    <h2>Bienvenidos a nuestra academia</h2>
    <p>Ofrecemos clases para todas las edades y niveles.</p>
    <video src="media/video.mp4" controls width="400"></video>
    <audio src="media/musica.mp3" controls></audio>
  </main>

  <footer>
   2025 Academia Estrella</p>
  </footer>
</body>
</html>

clases.html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Nuestras Clases</title>
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Nuestras Clases</h1>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="clases.html">Clases</a>
      <a href="contacto.html">Contacto</a>
    </nav>
  </header>

  <main>
    <h2>Horarios y Precios</h2>
    <table>
      <tr><th>Día</th><th>Clase</th><th>Horario</th><th>Precio</th></tr>
      <tr><td>Lunes</td><td>Ballet</td><td>4:00 PM</td><td>$300</td></tr>
      <tr><td>Miércoles</td><td>Jazz</td><td>5:00 PM</td><td>$300</td></tr>
    </table>
  </main>

  <footer>
  2025 Academia Estrella</p>
  </footer>
</body>
</html>

contacto.html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Contacto</title>
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Contáctanos</h1>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="clases.html">Clases</a>
      <a href="contacto.html">Contacto</a>
    </nav>
  </header>

  <main>
    <h2>Formulario de inscripción</h2>
    <form>
      <label>Nombre: <input type="text" name="nombre"></label><br>
      <label>Correo: <input type="email" name="correo"></label><br>
      <label>Edad: <input type="number" name="edad"></label><br>
      <label>Clase de interés:
        <select>
          <option>Ballet</option>
          <option>Jazz</option>
          <option>Hip-hop</option>
        </select>
      </label><br>
      <input type="submit" value="Enviar">
    </form>
  </main>

  <footer>
  2025 Academia Estrella</p>
  </footer>
</body>
</html>
