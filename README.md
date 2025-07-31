# vishneuskaya-beauty
ll
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
      background-size: 50% 50%;
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
    <a href="https://wishnewska.booksy.com/" class="bg-pink-500 hover:bg-pink-600 text-white py-3 px-10 rounded-full text-xl shadow-md transform transition hover:scale-110">Записаться через букси</a>
    <a href="[https://wishnewska.booksy.com/](https://www.instagram.com/direct/t/106874287372526)" class="bg-pink-500 hover:bg-pink-600 text-white py-3 px-10 rounded-full text-xl shadow-md transform transition hover:scale-110">Записаться через интсаграмм</a>
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

<!-- Services Section -->
<section class="bg-gray-100 py-10">
    <div class="max-w-5xl mx-auto px-4">
      <h2 class="text-2xl font-bold mb-6">Услуги и цены</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-white p-4 rounded shadow">
          <h3 class="font-semibold">Чистка лица</h3>
          <p>от 150 PLN</p>
        </div>
        <div class="bg-white p-4 rounded shadow">
          <h3 class="font-semibold">RF-лифтинг</h3>
          <p>от 200 PLN</p>
        </div>
        <div class="bg-white p-4 rounded shadow">
          <h3 class="font-semibold">Кислотный пилинг</h3>
          <p>от 180 PLN</p>
        </div>
        <div class="bg-white p-4 rounded shadow">
          <h3 class="font-semibold">Массаж лица</h3>
          <p>от 120 PLN</p>
        </div>
        <!-- Добавь больше услуг по желанию  </div>
    </div> -->
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


    <!-- Chat Widget (Tawk.to example) -->
  <script type="text/javascript">
  var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
  (function(){
  var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
  s1.async=true;
  s1.src='https://embed.tawk.to/65c123abcde56789abcdef12/1hxyzabc';
  s1.charset='UTF-8';
  s1.setAttribute('crossorigin','*');
  s0.parentNode.insertBefore(s1,s0);
  })();
  </script>
  
    <!-- WhatsApp / Telegram Floating Buttons -->
  <div class="fixed bottom-6 right-6 z-50 flex flex-col gap-3">
    <a href="https://t.me/@Wishelga" target="_blank" class="bg-blue-400 hover:bg-blue-500 text-white p-3 rounded-full shadow-lg" title="Написать в Telegram">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M21.05 2.52c-.72-.55-1.64-.83-2.6-.75L3.4 4.22C1.63 4.38 1.12 6.69 2.4 7.57l5.28 3.52 2.14 6.67c.2.63.94.9 1.49.53l2.75-1.84 3.15 2.35c.51.38 1.19.33 1.64-.12.46-.45.5-1.15.12-1.64l-2.35-3.15 1.84-2.75c.37-.56.1-1.3-.53-1.49L7.57 2.4C6.7 1.12 4.38 1.63 4.22 3.4l-.55 15.05c-.08.96.2 1.88.75 2.6.99 1.3 2.97 1.3 3.96 0l13.62-13.63c1.3-.99 1.3-2.97 0-3.96z"/></svg>
    </a>
  </div>
  
  <!-- Gallery 
  <section class="max-w-5xl mx-auto px-4 py-10">
    <h2 class="text-2xl font-bold mb-6">Галерея</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded">
      <img src="https://via.placeholder.com/150" alt="Instagram photo" class="rounded">
    </div>
  </section> -->
  
  <!-- Contact Form -->
  <section class="bg-pink-50 py-20 fade-in">
    <div class="max-w-2xl mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-8">📬 Связаться с нами</h2>
      <form action="https://formspree.io/f/your_form_id" method="POST" class="space-y-6 bg-white p-6 rounded-xl shadow">
        <input type="text" name="name" placeholder="Ваше имя" required class="w-full border border-gray-300 rounded p-3">
        <input type="email" name="email" placeholder="Ваш email" required class="w-full border border-gray-300 rounded p-3">
        <textarea name="message" rows="5" placeholder="Ваше сообщение" required class="w-full border border-gray-300 rounded p-3"></textarea>
        <button type="submit" class="bg-pink-500 text-white py-2 px-6 rounded hover:bg-pink-600 transition">Отправить</button>
      </form>
    </div>
  </section>
  
  <!-- Contact Section -->
  <section class="bg-pink-50 py-10">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-2xl font-bold mb-4">Контакты</h2>
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
  
  <!-- Language Switch -->
  <section class="text-center py-6">
    <p class="text-sm">🌍 Do you speak English? <a href="index-en.html" class="underline text-pink-600">Click here</a></p>
  </section>
  
</body>
</html>
