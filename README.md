# daseroner.github.io
├── index.html<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mi Portfolio de Diseño</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Mis Diseños 📸</h1>
    <p>Sígueme en <a href="https://instagram.com/tu_usuario" target="_blank">@tu_usuario</a></p>
  </header>

  <main class="gallery">
    <!-- Repite este bloque por cada imagen -->
    <figure>
      <img src="assets/imagen1.jpg" alt="Descripción diseño 1" />
      <figcaption>Descripción breve o título</figcaption>
    </figure>
    <!-- … -->
  </main>

  <footer>
    <p>© 2025 Tu Nombre – Hecho con ❤️ usando GitHub Pages</p>
  </footer>
</body>
</html>

├── styles.css/* Reset muy simple */
* { margin:0; padding:0; box-sizing:border-box; }

body {
  font-family: sans-serif;
  line-height: 1.4;
  padding: 1rem;
  background: #fafafa;
  color: #333;
}

header, footer {
  text-align: center;
  margin-bottom: 2rem;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px,1fr));
  gap: 1rem;
}

.gallery img {
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

figcaption {
  text-align: center;
  margin-top: 0.5rem;
  font-size: 0.9rem;
}

└── assets/
    └── imagen1.jpg
    └── imagen2.jpg


