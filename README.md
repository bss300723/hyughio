# bss300723.github.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mensaje Especial</title>
  <link rel="stylesheet" href="estilo.css">
</head>
<body>
  <div class="contenedor">
    <div class="mensaje">
      <p>Te amo mas allá del bien y del mal, y me importas muchisimo amo que estes en mi vida .</p>
    </div>
  </div>
</body>
</html>
body, html {
  height: 100%;
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Arial', sans-serif;
  background-color: #ffcccc; /* Color de fondo del cuerpo */
}

.contenedor {
  text-align: center;
}

.mensaje {
  background-color: #f9f9f9; /* Color de fondo del mensaje */
  padding: 20px;
  border-radius: 15px; /* Borde redondeado */
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.2); /* Sombra suave */
}

.mensaje p {
  font-size: 24px; /* Tamaño del texto */
  color: #333; /* Color del texto */
  margin: 0;
}

.mensaje::before {
  content: "\1F496"; /* Corazón Unicode como fondo */
  font-size: 50px;
  display: block;
  margin-bottom: 20px;
}
