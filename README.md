<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Ganesh Chaturthi</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fff8e1;
      overflow: hidden;
      text-align: center;
    }
    h1 {
      font-size: 3em;
      color: #d84315;
      animation: fadeIn 3s ease-in-out;
    }
    h2 {
      font-size: 2em;
      color: #4e342e;
      animation: fadeIn 4s ease-in-out;
    }
    .ganpati-img {
      width: 250px;
      animation: pulse 5s infinite;
      margin: 20px auto;
    }
    .flowers {
      position: absolute;
      width: 100%;
      top: 0;
      left: 0;
      pointer-events: none;
    }
    .flower {
      position: absolute;
      width: 40px;
      animation: fall 10s linear infinite;
    }
    @keyframes fall {
      0% { transform: translateY(-100px) rotate(0deg); }
      100% { transform: translateY(100vh) rotate(360deg); }
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.1); }
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <h1>Happy Ganesh Chaturthi 🎉</h1>
  <h2>Ganpati Bappa Morya 🙏</h2>
  <img src="https://i.ibb.co/PG0MZf3/ganpati.png" alt="Ganpati Bappa" class="ganpati-img" />  <div class="flowers">
    <!-- Generate multiple flower elements -->
    <img src="https://i.ibb.co/6rkkz2Y/flower1.png" class="flower" style="left: 10%; animation-delay: 0s;" />
    <img src="https://i.ibb.co/6rkkz2Y/flower1.png" class="flower" style="left: 30%; animation-delay: 2s;" />
    <img src="https://i.ibb.co/6rkkz2Y/flower1.png" class="flower" style="left: 50%; animation-delay: 4s;" />
    <img src="https://i.ibb.co/6rkkz2Y/flower1.png" class="flower" style="left: 70%; animation-delay: 6s;" />
    <img src="https://i.ibb.co/6rkkz2Y/flower1.png" class="flower" style="left: 90%; animation-delay: 8s;" />
  </div>
</body>
</html>
