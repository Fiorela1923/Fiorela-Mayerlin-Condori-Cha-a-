# Fiorela-Mayerlin-Condori-Cha-a-<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fiorela Mayerlin Condori Chaña</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      padding: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
      color: #333;
      text-align: center;
      padding: 20px;
    }
    h1 {
      font-size: 2.5em;
      margin-top: 20px;
      color: #e91e63;
    }
    h2 {
      font-size: 1.8em;
      margin-top: 40px;
      color: #3f51b5;
    }
    ul {
      list-style-type: none;
      padding: 0;
      font-size: 1.2em;
    }
    li {
      margin: 10px 0;
    }
    a {
      color: #009688;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    button {
      margin-top: 30px;
      padding: 15px 25px;
      font-size: 1em;
      background-color: #ff4081;
      color: white;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    button:hover {
      transform: scale(1.1);
      background-color: #f50057;
    }
    #mensajeDivertido {
      margin-top: 20px;
      font-size: 1.5em;
      font-weight: bold;
      color: #4caf50;
    }
    @media (max-width: 600px) {
      h1 { font-size: 1.8em; }
      h2 { font-size: 1.4em; }
      ul { font-size: 1em; }
      button { font-size: 1em; padding: 10px 20px; }
    }
    .perfil {
      font-size: 1.2em;
      max-width: 700px;
      margin: 20px auto;
      color: #555;
      text-align: left;
      background-color: #fff3e0;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body>

  <h1>🎉 ¡Hola, soy Fiorela Mayerlin Condori Chaña! 🎉</h1>

  <div class="perfil">
    <p><strong>Carrera:</strong> Administración</p>
    <p><strong>Edad:</strong> 21 años</p>
    <p><strong>Universidad:</strong> Universidad Católica San Pablo</p>
    <p><strong>Hobbies:</strong> Bailar, ver series (K-dramas)</p>
    <p><strong>Mi propósito:</strong> Ser una profesional y obtener grandes experiencias a lo largo de mi vida, así como desarrollar una sólida trayectoria en diversos ámbitos de mi carrera.</p>
  </div>

  <h2>📚 Estos son mis cursos:</h2>
  <ul>
    <li>🔢 Álgebra y Geometría</li>
    <li>💰 Cálculo Financiero</li>
    <li>⚖️ Derecho Empresarial</li>
    <li>📊 Investigación de Mercados</li>
    <li>📖 Literatura y Teatro</li>
    <li>🎵 Música y Teatro</li>
    <li>➕ Matemática Básica</li>
    <li>⛪ Teología</li>
    <li>🧠 Análisis de Datos con <a href="https://www.linkedin.com/in/ecuadrosv" target="_blank">Ernesto Cuadros Vargas</a></li>
  </ul>

  <button onclick="mostrarMensaje()">Haz clic para una sorpresa 🎁</button>

  <div id="mensajeDivertido"></div>

  <script>
    const mensajes = [
      "¡Sigue brillando, Fiorela! 🌟",
      "¡Eres una genia de los datos! 📈",
      "¡A estudiar con flow y diversión! 😎",
      "¡Vamos con todo, futura crack! 🚀",
      "¡Te mereces una ovación! 👏👏👏"
    ];

    function mostrarMensaje() {
      const mensaje = mensajes[Math.floor(Math.random() * mensajes.length)];
      document.getElementById("mensajeDivertido").innerText = mensaje;
    }
  </script>
</body>
</html>
