<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vishal ❤️ Priyanshi</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      text-align: center;
      color: #333;
    }
    .container {
      padding: 40px;
    }
    h1 {
      font-size: 40px;
    }
    .heart {
      font-size: 50px;
      color: red;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 15px;
      margin: 20px auto;
      width: 85%;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    img {
      width: 200px;
      border-radius: 10px;
    }
    .qr {
      margin-top: 20px;
    }
    footer {
      margin-top: 30px;
      font-size: 14px;
    }
    #typing {
      font-size: 18px;
      min-height: 50px;
      color: #e91e63;
      font-weight: bold;
    }
    .secret-btn {
      padding: 12px 20px;
      background: #ff4d6d;
      border: none;
      color: white;
      border-radius: 25px;
      cursor: pointer;
      font-size: 16px;
    }
    .hidden-message {
      display: none;
      margin-top: 20px;
      font-size: 20px;
      color: #d63384;
      font-weight: bold;
      animation: fadeIn 1s ease-in-out;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: scale(0.9);} 
      to {opacity: 1; transform: scale(1);} 
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Vishal ❤️ Priyanshi</h1>
    <div class="heart">❤️</div><div class="card">
  <h2>About My Love</h2>
  <p>Priyanshi, you are the most beautiful part of my life. Your smile makes my world brighter and your presence makes everything better.</p>
</div>

<div class="card">
  <h2>Why I Love You</h2>
  <ul>
    <li>Your cute smile 😊</li>
    <li>Your caring nature 💖</li>
    <li>The way you understand me 🤗</li>
    <li>Every little moment with you 💫</li>
  </ul>
</div>

<div class="card">
  <h2>Typing Love Message 💌</h2>
  <div id="typing"></div>
</div>

<div class="card">
  <h2>My Promise</h2>
  <p>I promise to always take care of you, support you, and stand by your side in every situation. I will love you with all my heart forever ❤️</p>
</div>

<div class="card">
  <h2>Secret Surprise 🎁</h2>
  <button class="secret-btn" onclick="showLove()">Click Me ❤️</button>
  <div id="secret" class="hidden-message">I LOVE YOU PRIYANSHI ❤️ FOREVER AND ALWAYS 💖</div>
</div>

<div class="card">
  <h2>Our Memories</h2>
  <p>Add your favorite photos here 💕</p>
  <img src="https://via.placeholder.com/200" alt="memory">
</div>

<div class="card qr">
  <h2>Scan This QR Code</h2>
  <p>Share this website with love ❤️</p>
  <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://yourwebsite.com" alt="QR Code">
</div>

<footer>
  Made with ❤️ by Vishal for Priyanshi
</footer>

  </div>  <script>
    // Typing animation
    const text = "Priyanshi, every heartbeat of mine says your name... I love you more than anything in this world ❤️";
    let i = 0;

    function typingEffect() {
      if (i < text.length) {
        document.getElementById("typing").innerHTML += text.charAt(i);
        i++;
        setTimeout(typingEffect, 50);
      }
    }

    typingEffect();

    // Secret button
    function showLove() {
      document.getElementById("secret").style.display = "block";
    }
  </script></body>
</html>
