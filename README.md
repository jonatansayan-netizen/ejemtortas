<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tortas Express Perú</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-pink-50 font-sans">
  <!-- Header -->
  <header class="bg-pink-600 text-white p-6 shadow-lg">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">Tortas Express Perú</h1>
      <a href="https://wa.me/51988614195?text=Hola%20TORTASEXPRESS%20quiero%20solicitar%20una%20Torta" target="_blank" class="bg-white text-pink-600 px-4 py-2 rounded-xl font-semibold">Haz tu pedido</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="text-center py-16 bg-gradient-to-r from-pink-500 to-rose-400 text-white">
    <h2 class="text-5xl font-extrabold mb-4">Tortas deliciosas en tiempo récord</h2>
    <p class="text-xl mb-6">Entrega rápida en todo Lima • Personalizadas para cada ocasión</p>
    <a href="#catalogo" class="bg-white text-pink-600 px-8 py-3 rounded-2xl font-bold shadow-lg">Ver Catálogo</a>
  </section>

  <!-- Catálogo -->
  <section id="catalogo" class="max-w-6xl mx-auto py-16 px-6">
    <h3 class="text-4xl font-bold text-center text-pink-700 mb-12">Nuestro Catálogo</h3>

    <div class="grid md:grid-cols-3 gap-8">
      <!-- Producto 1 -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587" alt="Torta de chocolate sabrosa" class="w-full h-56 object-cover">
        <div class="p-6 text-center">
          <h4 class="text-2xl font-bold mb-2">Torta de Chocolate</h4>
          <p class="text-gray-600 mb-4">Rellena de fudge y cubierta con ganache.</p>
          <span class="text-3xl font-extrabold text-pink-600">S/ 75</span>
        </div>
      </div>

      <!-- Producto 2 -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1621303837174-89787a7d4729" alt="Torta de Fresa" class="w-full h-56 object-cover">
        <div class="p-6 text-center">
          <h4 class="text-2xl font-bold mb-2">Torta de Fresa</h4>
          <p class="text-gray-600 mb-4">Bizcocho suave con crema y fresas naturales.</p>
          <span class="text-3xl font-extrabold text-pink-600">S/ 60</span>
        </div>
      </div>

      <!-- Producto 3 -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1559620192-032c4bc4674e" alt="Torta Personalizada" class="w-full h-56 object-cover">
        <div class="p-6 text-center">
          <h4 class="text-2xl font-bold mb-2">Torta Personalizada</h4>
          <p class="text-gray-600 mb-4">Diseño especial según tu ocasión.</p>
          <span class="text-3xl font-extrabold text-pink-600"> S/ 75</span>
        </div>
      </div>

      <!-- Producto 4 -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://tofuu.getjusto.com/orioneat-local/resized2/rw5WZnpfL7cFrQ2oy-300-x.webp" alt="Alfajor" class="w-full h-56 object-cover">
        <div class="p-6 text-center">
          <h4 class="text-2xl font-bold mb-2">Alfajores</h4>
          <p class="text-gray-600 mb-4">Suaves galletas rellenas de manjar y azúcar en polvo.</p>
          <span class="text-3xl font-extrabold text-pink-600">S/ 12 (caja)</span>
        </div>
      </div>

      <!-- Producto 5 -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://panoli.pe/wp-content/uploads/2020/02/IMG_0421-1.jpg" alt="Pionono" class="w-full h-56 object-cover">
        <div class="p-6 text-center">
          <h4 class="text-2xl font-bold mb-2">Pionono</h4>
          <p class="text-gray-600 mb-4">Enrollado dulce relleno de manjar y espolvoreado.</p>
          <span class="text-3xl font-extrabold text-pink-600">S/ 18</span>
        </div>
      </div>

      <!-- Producto 6 -->
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://www.lanacion.com.ar/resizer/v2/a-la-hora-de-pensar-en-empanadas-de-carne-vale-la-64QJ4Q4NLZCERNGU22MPWDJMUI.png?auth=c0aa5a91ec3666c78a72b12e472f80e77f9defc516ab3049a0a9b5eec9bee2fc&width=880&height=586&quality=70&smart=true" alt="Empanada" class="w-full h-56 object-cover">
        <div class="p-6 text-center">
          <h4 class="text-2xl font-bold mb-2">Empanada</h4>
          <p class="text-gray-600 mb-4">Empanadas dulces y saladas recién horneadas.</p>
          <span class="text-3xl font-extrabold text-pink-600">S/ 6 c/u</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Beneficios -->
  <section class="bg-pink-100 py-16">
    <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-8 text-center px-6">
      <div>
        <h4 class="text-2xl font-bold text-pink-700 mb-2">Entrega Rápida</h4>
        <p>Recibe tu torta en menos de 24 horas.</p>
      </div>
      <div>
        <h4 class="text-2xl font-bold text-pink-700 mb-2">Alta Calidad</h4>
        <p>Ingredientes frescos y preparación artesanal.</p>
      </div>
      <div>
        <h4 class="text-2xl font-bold text-pink-700 mb-2">Pedidos por WhatsApp</h4>
        <p>Atención inmediata y personalizada.</p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section id="pedidos" class="text-center py-16 bg-pink-600 text-white">
    <h3 class="text-4xl font-bold mb-4">Haz tu pedido ahora</h3>
    <p class="mb-6">Contáctanos por WhatsApp y separa tu torta hoy mismo</p>
    <a href="https://wa.me/51988614195?text=Hola%20TORTASEXPRESS%20quiero%20solicitar%20una%20Torta" target="_blank" class="bg-white text-pink-600 px-8 py-3 rounded-2xl font-bold">Pedir por WhatsApp</a>
  </section>

  <!-- Footer -->
  <footer class="bg-pink-700 text-white text-center p-6">
    <p>© 2026 Tortas Express Perú — Todos los derechos reservados</p>
  </footer>
</body>
</html>
