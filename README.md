<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Pacarku Lagi Kangen</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #ffe6f0;
      text-align: center;
      padding: 50px;
    }
    .heart {
      font-size: 80px;
      color: red;
      animation: pulse 1s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    .message {
      font-size: 24px;
      margin-top: 20px;
      color: #d6336c;
    }
    button {
      padding: 10px 20px;
      font-size: 18px;
      margin-top: 30px;
      background-color: #ff80ab;
      border: none;
      border-radius: 10px;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background-color: #ff4081;
    }
  </style>
</head>
<body>

  <div class="heart">❤️</div>
  <div class="message" id="msg">Pacar tercintamu lagi kangen berat nih 😭</div>
  <button onclick="showLove()">Klik kalau kamu juga kangen</button>

  <script>
    function showLove() {
      const msg = document.getElementById('msg');
      msg.innerText = 'Yeayyy! Kita sama-sama kangen 💖💖💖';
    }
  </script>

</body>
</html>
