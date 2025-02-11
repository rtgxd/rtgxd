<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Warmer - Buzos Comfy para Viajeros</title>
  <style>
    /* Reset global */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    /* Header */
    header {
      background-color: #fff;
      padding: 20px;
      border-bottom: 1px solid #e0e0e0;
      text-align: center;
    }
    header h1 {
      font-size: 2rem;
      color: #d35400; /* Tono cálido */
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      font-size: 1rem;
      font-weight: bold;
      color: #333;
    }
    /* Hero Section */
    .hero {
      background: url('ruta-de-tu-imagen-hero.jpg') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }
    .hero-content {
      max-width: 90%;
    }
    .hero-content h2 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    .hero-content p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    .btn {
      display: inline-block;
      background-color: #d35400;
      color: #fff;
      padding: 12px 24px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    .btn:hover {
      background-color: #e67e22;
    }
    /* Products Section */
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 40px 20px;
    }
    .product-card {
      background-color: #fff;
      border: 1px solid #e0e0e0;
      border-radius: 5px;
      width: 300px;
      margin: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }
    .product-card img {
      width: 100%;
      height: auto;
      display: block;
    }
    .product-info {
      padding: 20px;
      text-align: center;
    }
    .product-info
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Warmer - Buzos Comfy para Viajeros</title>
  <style>
    /* Reset de estilos */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #fff;
      padding: 20px;
      border-bottom: 1px solid #ddd;
      text-align: center;
    }
    header h1 {
      color: #d35400; /* tono cálido */
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .hero {
      background-image: url('ruta-de-tu-imagen-hero.jpg'); /* reemplazá con la URL de tu imagen */
      background-size: cover;
      background-position: center;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }
    .hero h2 {
      font-size: 3em;
      margin-bottom: 10px;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
    }
    .hero p {
      font-size: 1.2em;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
    }
    .btn {
      display: inline-block;
      background-color: #d35400;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
      transition: background-color 0.3s;
    }
    .btn:hover {
      background-color: #e67e22;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .product-card {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 5px;
      width: 300px;
      margin: 15px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .product-card:hover {
      transform: translateY(-5px);
    }
    .product-card img {
      width: 100%;
      height: auto;
      display: block;
    }
    .product-info {
      padding: 15px;
      text-align: center;
    }
    .product-info h3 {
      margin-bottom: 10px;
      font-size: 1.5em;
    }
    .product-info p {
      margin-bottom: 15px;
    }
    .footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    @media(max-width: 768px) {
      .products {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Warmer</h1>
    <nav>
      <ul>
        <li><a href="#productos">Productos</a></li>
        <li><a href="#nosotros">Nosotros</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <!-- Sección Hero -->
  <section class="hero">
    <div>
      <h2>Buzos Comfy para Viajeros</h2>
      <p>La máxima comodidad para parejas y adolescentes en sus aventuras.</p>
      <a href="#productos" class="btn">Ver Colección</a>
    </div>
  </section>

  <!-- Sección de Productos -->
  <section id="productos" class="products">
    <div class="product-card">
      <img src="buzo1.jpg" alt="Buzo Warmer Classic">
      <div class="product-info">
        <h3>Buzo Warmer Classic</h3>
        <p>Material: 100% algodón premium para una comodidad insuperable.</p>
        <a href="#" class="btn">Comprar</a>
      </div>
    </div>
    <div class="product-card">
      <img src="buzo2.jpg" alt="Buzo Warmer Travel">
      <div class="product-info">
        <h3>Buzo Warmer Travel</h3>
        <p>Diseño versátil ideal para aventuras y viajes.</p>
        <a href="#" class="btn">Comprar</a>
      </div>
    </div>
    <!-- Agrega más tarjetas de producto según sea necesario -->
  </section>

  <!-- Sección de Footer -->
  <footer class="footer">
    <p>&copy; 2025 Warmer. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
rtgxd/rtgxd is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
