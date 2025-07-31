<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vishneuskaya Beauty</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
  <style>
    body {
      background: linear-gradient(to right, #ffe0f0, #ffe9fc);
    }
    .fade-in {
      animation: fadeIn ease 2s;
    }
    @keyframes fadeIn {
      0% {opacity: 0; transform: translateY(10px);}
      100% {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body class="text-gray-800">
  <!-- Hero Section -->
  <section class="text-center py-20 bg-pink-100 fade-in">
    <h1 class="text-5xl font-extrabold mb-4">Vishneuskaya Beauty</h1>
    <p class="text-xl italic mb-6">Ваша красота — наша страсть</p>
    <a href="https://wishnewska.booksy.com/" class="bg-pink-500 hover:bg-pink-600 text-white py-2 px-8 rounded-full text-lg shadow-md transform transition hover:scale-105">Записаться</a>
    <div class="mt-10 flex justify-center">
      <lottie-player src="https://assets4.lottiefiles.com/packages/lf20_lggrkv.json" background="transparent" speed="1" style="width: 300px; height: 300px;" loop autoplay></lottie-player>
    </div>
  </section>

  <!-- About Section -->
  <section class="max-w-4xl mx-auto px-4 py-14 fade-in">
    <h2 class="text-3xl font-bold mb-4 text-center">Обо мне</h2>
    <p class="text-lg text-center">Я, Ольга Вишневская — сертифицированный косметолог с многолетним опытом. Моя цель — подчеркнуть вашу естественную красоту, используя лучшие техники ухода за кожей. Каждый клиент для меня — как картина, которую я с любовью довожу до совершенства.</p>
  </section>

  <!-- Services Section -->
  <section class="bg-white py-14 fade-in">
    <div class="max-w-5xl mx-auto px-4">
      <h2 class="text-3xl font-bold mb-8 text-center">Услуги и цены</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-pink-50 p-6 rounded-xl shadow-md hover:shadow-lg transform hover:scale-105 transition">
          <h3 class="font-semibold text-xl">Чистка лица</h3>
          <p>от 150 PLN</p>
        </div>
        <div class="bg-pink-50 p-6 rounded-xl shadow-md hover:shadow-lg transform hover:scale-105 transition">
          <h3 class="font-semibold text-xl">RF-лифтинг</h3>
          <p>от 200 PLN</p>
        </div>
        <div class="bg-pink-50 p-6 rounded-xl shadow-md hover:shadow-lg transform hover:scale-105 transition">
          <h3 class="font-semibold text-xl">Кислотный пилинг</h3>
          <p>от 180 PLN</p>
        </div>
        <div class="bg-pink-50 p-6 rounded-xl shadow-md hover:shadow-lg transform hover:scale-105 transition">
          <h3 class="font-semibold text-xl">Массаж лица</h3>
          <p>от 120 PLN</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section class="max-w-5xl mx-auto px-4 py-14 fade-in">
    <h2 class="text-3xl font-bold mb-8 text-center">Галерея</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded-xl shadow-md">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded-xl shadow-md">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded-xl shadow-md">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded-xl shadow-md">
    </div>
  </section>

  <!-- Bonus Section -->
  <section class="bg-gradient-to-r from-pink-200 to-pink-100 py-16 text-center fade-in">
    <h2 class="text-3xl font-bold mb-4">🌸 Красота — это удовольствие</h2>
    <p class="max-w-xl mx-auto text-lg">Мы не просто делаем процедуры — мы создаём атмосферу любви к себе. Приходите и почувствуйте, как ваша кожа начинает сиять!</p>
  </section>

  <!-- Contact Section -->
  <section class="bg-pink-50 py-14 fade-in">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-4">Контакты</h2>
      <p class="mb-2">📍 <a href="https://maps.app.goo.gl/Mn5Jaidf73DYXht1A" class="underline">Warszawa, Poland</a></p>
      <p class="mb-2">📞 <a href="tel:+48730000000" class="underline">+48 730 000 000</a></p>
      <p class="mb-2">📩 <a href="mailto:beauty@vishneuskaya.pl" class="underline">beauty@vishneuskaya.pl</a></p>
      <div class="mt-4 flex justify-center space-x-4">
        <a href="https://www.instagram.com/vishneuskaya_beauty" class="underline">Instagram</a>
        <a href="https://www.facebook.com/wishelga" class="underline">Facebook</a>
        <a href="https://wishnewska.booksy.com/" class="underline">Booksy</a>
      </div>
    </div>
  </section>

  <footer class="text-center text-sm py-4 text-gray-500">
    &copy; 2025 Vishneuskaya Beauty — Сделано с любовью 💗
  </footer>
</body>
</html>
