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
      background: linear-gradient(135deg, #fdf6f9, #fff0f5, #f9f0ff);
      background-size: 600% 600%;
      animation: gradientBG 30s ease infinite;
    }
    @keyframes gradientBG {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }
    .fade-in {
      animation: fadeIn ease 2s;
    }
    @keyframes fadeIn {
      0% {opacity: 0; transform: translateY(20px);}
      100% {opacity: 1; transform: translateY(0);}
    }
    .slide-in {
      animation: slideIn 1.5s ease-out;
    }
    @keyframes slideIn {
      0% {transform: translateX(-50px); opacity: 0;}
      100% {transform: translateX(0); opacity: 1;}
    }
  </style>
</head>
<body class="text-gray-800">
  <!-- Hero Section -->
  <section class="text-center py-24 bg-pink-100 fade-in">
    <h1 class="text-6xl font-extrabold mb-4 animate-bounce">Vishneuskaya Beauty</h1>
    <p class="text-2xl italic mb-8">Ваша красота — наша страсть</p>
    <a href="https://wishnewska.booksy.com/" class="bg-pink-500 hover:bg-pink-600 text-white py-3 px-10 rounded-full text-xl shadow-md transform transition hover:scale-110">Записаться</a>
    <div class="mt-12 flex justify-center">
      <lottie-player src="https://assets1.lottiefiles.com/packages/lf20_w51pcehl.json" background="transparent" speed="1" style="width: 320px; height: 320px;" loop autoplay></lottie-player>
    </div>
  </section>

  <!-- Expanded About Section -->
  <section class="max-w-6xl mx-auto px-6 py-20 slide-in">
    <h2 class="text-4xl font-bold mb-6 text-center">Обо мне</h2>
    <p class="text-xl text-center leading-relaxed mb-4">Меня зовут Ольга Вишневская, и я посвятила свою жизнь искусству ухода за кожей. За плечами у меня десятки курсов, сертификаций и сотни довольных клиентов, которые доверяют мне своё лицо и настроение. В моей студии царит атмосфера уюта, заботы и истинной красоты.</p>
    <p class="text-xl text-center leading-relaxed">Каждая процедура — это ритуал. Индивидуальный подход, деликатное прикосновение, безопасные и эффективные методы — это мой стандарт. Приходите в Vishneuskaya Beauty и почувствуйте разницу уже после первого визита.</p>
  </section>

  <!-- Instagram Feed -->
  <section class="bg-white py-20 fade-in">
    <div class="max-w-6xl mx-auto px-4 text-center">
      <h2 class="text-4xl font-bold mb-10">📸 Instagram — живые кадры из студии</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
        <img src="https://via.placeholder.com/200" alt="insta1" class="rounded-xl shadow-md">
        <img src="https://via.placeholder.com/200" alt="insta2" class="rounded-xl shadow-md">
        <img src="https://via.placeholder.com/200" alt="insta3" class="rounded-xl shadow-md">
        <img src="https://via.placeholder.com/200" alt="insta4" class="rounded-xl shadow-md">
      </div>
      <a href="https://www.instagram.com/vishneuskaya_beauty" target="_blank" class="mt-6 inline-block text-pink-600 underline text-lg">Смотреть больше</a>
    </div>
  </section>

  <!-- Blog/News Section -->
  <section class="bg-pink-50 py-20 slide-in">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-10">🌿 Новости и советы</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-xl shadow-lg">
          <h3 class="text-xl font-bold mb-2">Топ-5 процедур для сияющей кожи</h3>
          <p class="text-sm">Рассказываю, как быстро освежить кожу перед отпуском.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-lg">
          <h3 class="text-xl font-bold mb-2">Чем отличается RF-лифтинг от массажа?</h3>
          <p class="text-sm">Глубокое сравнение процедур и рекомендации.</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-lg">
          <h3 class="text-xl font-bold mb-2">Как подготовиться к чистке лица?</h3>
          <p class="text-sm">Советы и что делать до и после процедуры.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Переход к основной части -->
  <div class="py-10 text-center">
    <a href="#" class="text-pink-700 text-xl underline hover:text-pink-900 transition">Читать больше статей →</a>
  </div>

  <!-- Остальной контент остаётся без изменений (услуги, отзывы, контакты и пр.) -->
</body>
</html>
