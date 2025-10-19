<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>To my little Shivi:)</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(to right, #ffe6f0, #ffd6e6);
      font-family: 'Dancing Script', cursive;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      overflow: hidden;
    }

    #card {
      background: #ffffffee;
      padding: 50px 30px;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
      max-width: 550px;
      animation: slideIn 1.4s ease-out;
      position: relative;
    }

    h1 {
      color: #e6005c;
      font-size: 2.4em;
      margin-bottom: 20px;
      animation: fadeIn 2s ease-in;
    }

    .heart {
      width: 50px;
      height: 50px;
      background-color: #ffb6c1;
      position: relative;
      display: inline-block;
      margin: 20px 10px;
      transform: rotate(-45deg);
      animation: pulse 1.5s infinite;
    }

    .heart::before,
    .heart::after {
      content: "";
      width: 50px;
      height: 50px;
      background-color: #ffb6c1;
      border-radius: 50%;
      position: absolute;
    }

    .heart::before {
      top: -25px;
      left: 0;
    }

    .heart::after {
      left: 25px;
      top: 0;
    }

    #message {
      font-size: 1.3em;
      color: #5e1f3f;
      margin-top: 15px;
      animation: fadeIn 3s ease-in;
    }

    a {
      color: #800080;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    a:hover {
      text-decoration: underline;
      color: #c71585;
    }

    @keyframes pulse {
      0% {
        transform: rotate(-45deg) scale(1);
      }

      50% {
        transform: rotate(-45deg) scale(1.1);
      }

      100% {
        transform: rotate(-45deg) scale(1);
      }
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }

      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes slideIn {
      from {
        opacity: 0;
        transform: scale(0.9) translateY(30px);
      }

      to {
        opacity: 1;
        transform: scale(1) translateY(0);
      }
    }
  </style>
</head>

<body>
  <div id="card">
    <h1>Shiviiiiii, my sunshine 🌞</h1>
    <div class="heart"></div>
    <p id="message">
  This isn't just a birthday page.<br>
  It's a tiny window into how much I love you — endlessly, ridiculously, truly.💖
</p>

<iframe src="the second gift.html" width="100%" height="400px" style="border:none; margin-top:20px;"></iframe>

    </p>
    <div class="heart"></div>
  </div>
</body>

</html>


