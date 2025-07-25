<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EcoNotas - Tienda Ecológica</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f9f0;
      color: #2e4d2e;
    }
    header {
      background-color: #a8d5a2;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    nav a {
      margin-left: 1.5rem;
      text-decoration: none;
      color: #2e4d2e;
      font-weight: bold;
    }
    .hero {
      background-image: url('https://images.unsplash.com/photo-1523475496153-3d6cc7b5a3a4');
      background-size: cover;
      background-position: center;
      padding: 6rem 2rem;
      text-align: center;
      color: white;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    .product {
      background-color: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      margin: 0.5rem 0;
    }
    .product button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #d7ecd9;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #4a6b4a;
    }
  </style>
</head>
<body>
  <header>
    <h1>EcoNotas</h1>
    <nav>
      <a href="#">Inicio</a>
      <a href="#productos">Productos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>
  <section class="hero">
    <h2>Notas que cuidan el planeta</h2>
    <p>Con EcoNotas escribe tus ideas y protege la naturaleza.</p>
  </section>
  <section class="products" id="productos">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1616627455542-51c71620b197" alt="EcoNota Clásica">
      <h3>EcoNota Clásica</h3>
      <p>$50 MXN</p>
      <button>Agregar al carrito</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1602751588024-200b3ddf7850" alt="EcoNota Pocket">
      <h3>EcoNota Pocket</h3>
      <p>$35 MXN</p>
      <button>Agregar al carrito</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1560448074-0efb27d8f27e" alt="EcoNota Premium">
      <h3>EcoNota Premium</h3>
      <p>$70 MXN</p>
      <button>Agregar al carrito</button>
    </div>
  </section>
  <footer id="contacto">
    <p>Contacto: econotas@email.com | Tel: 921-000-0000</p>
    <p>Síguenos en redes sociales: @EcoNotasMx</p>
  </footer>
</body>
</html>
