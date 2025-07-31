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

  <!-- Language Switch -->
  <section class="text-center py-6">
    <p class="text-sm">🌍 Do you speak English? <a href="index-en.html" class="underline text-pink-600">Click here</a></p>
  </section>

  <!-- WhatsApp / Telegram Floating Buttons -->
  <div class="fixed bottom-6 right-6 z-50 flex flex-col gap-3">
    <a href="https://wa.me/48730000000" target="_blank" class="bg-green-500 hover:bg-green-600 text-white p-3 rounded-full shadow-lg" title="Написать в WhatsApp">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 12l-4-4-4 4m8 0l-4 4-4-4" /></svg>
    </a>
    <a href="https://t.me/username" target="_blank" class="bg-blue-400 hover:bg-blue-500 text-white p-3 rounded-full shadow-lg" title="Написать в Telegram">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M21.05 2.52c-.72-.55-1.64-.83-2.6-.75L3.4 4.22C1.63 4.38 1.12 6.69 2.4 7.57l5.28 3.52 2.14 6.67c.2.63.94.9 1.49.53l2.75-1.84 3.15 2.35c.51.38 1.19.33 1.64-.12.46-.45.5-1.15.12-1.64l-2.35-3.15 1.84-2.75c.37-.56.1-1.3-.53-1.49L7.57 2.4C6.7 1.12 4.38 1.63 4.22 3.4l-.55 15.05c-.08.96.2 1.88.75 2.6.99 1.3 2.97 1.3 3.96 0l13.62-13.63c1.3-.99 1.3-2.97 0-3.96z"/></svg>
    </a>
  </div>

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

</body>
</html>

