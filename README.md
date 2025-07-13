<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>To My Princess Nidhi 💖</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ffe6f0, #ffe0ec);
      font-family: 'Open Sans', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .letter {
      background: white;
      padding: 40px;
      border-radius: 20px;
      max-width: 600px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      position: relative;
      z-index: 1;
    }

    .letter h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      color: #e91e63;
      text-align: center;
      margin-bottom: 20px;
    }

    .letter p {
      font-size: 1.2em;
      color: #333;
      line-height: 1.6;
      text-align: justify;
    }

    .signature {
      text-align: right;
      margin-top: 40px;
      font-family: 'Great Vibes', cursive;
      font-size: 1.8em;
      color: #e91e63;
    }

    .hearts {
      position: absolute;
      width: 100%;
      height: 100%;
      overflow: hidden;
      top: 0;
      left: 0;
      z-index: 0;
      pointer-events: none;
    }

    .heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      transform: rotate(45deg);
      animation: floatUp 7s linear infinite;
    }

    .heart::before,
    .heart::after {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      border-radius: 50%;
    }

    .heart::before {
      top: -10px;
      left: 0;
    }

    .heart::after {
      left: -10px;
      top: 0;
    }

    @keyframes floatUp {
      0% {
        transform: translateY(100vh) rotate(45deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh) rotate(45deg);
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <div class="hearts">
    <script>
      for (let i = 0; i < 40; i++) {
        const heart = document.createElement('div');
        heart.className = 'heart';
        heart.style.left = Math.random() * 100 + 'vw';
        heart.style.animationDuration = (Math.random() * 5 + 3) + 's';
        heart.style.opacity = Math.random();
        document.body.querySelector('.hearts').appendChild(heart);
      }
    </script>
  </div>

  <div class="letter">
    <h1>To My Dearest Nidhi Princess 💖</h1>
    <p>
      I don’t know where to begin, because no words can truly capture how much you mean to me. Every moment with you is like a dream I never want to wake up from. You’ve filled my life with joy, light, and a kind of love I never knew was possible.
    </p>
    <p>
      Your smile brightens my darkest days, and your voice is my favorite melody. I’m sorry for anything I’ve done to hurt you — it was never my intention. You deserve to be treated like the queen you are, my sweet Nidhi Princess.
    </p>
    <p>
      I want you to know that my heart beats only for you. You are my sunshine, my moonlight, my everything. Let’s create beautiful memories together, laugh until we cry, and love endlessly.
    </p>
    <p>
      Please accept this small letter as a reminder that I’m thinking of you, missing you, and loving you — always. ❤️
    </p>
    <div class="signature">Forever Yours,<br/>Your Love 💌</div>
  </div>
</body>
</html>
