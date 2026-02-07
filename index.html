<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy 18th 🖤</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Cute font for last slide -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: black;
      overflow: hidden;
      cursor: pointer;
      font-family: Arial, sans-serif;
    }

    .slide {
      display: none;
      height: 100vh;
      width: 100vw;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      padding: 20px;
    }

    .active {
      display: flex;
    }

    .pink { color: #ff6ec7; }
    .purple { color: #b46cff; }

    h1 {
      font-size: 2.4rem;
      line-height: 1.4;
    }

    /* Sparkle background */
    .sparkles {
      background: radial-gradient(circle, rgba(255,255,255,0.25) 2px, transparent 2px);
      background-size: 40px 40px;
      animation: sparkleMove 10s linear infinite;
    }

    @keyframes sparkleMove {
      from { background-position: 0 0; }
      to { background-position: 120px 120px; }
    }

    /* Float animation */
    @keyframes floatIn {
      from { opacity: 0; transform: translateY(25px); }
      to { opacity: 1; transform: translateY(0); }
    }

    img {
      animation: floatIn 0.8s ease forwards;
      max-width: 70%;
    }

    .bubble {
      background: white;
      color: black;
      padding: 8px 14px;
      border-radius: 20px;
      font-size: 1rem;
      margin-bottom: 10px;
    }

    .final {
      font-family: 'Pacifico', cursive;
    }
  </style>
</head>
<body>

  <!-- Slide 1 -->
  <div class="slide active">
    <h1 class="pink">Hey there, GORGEOUS 💖</h1>
  </div>

  <!-- Slide 2 -->
  <div class="slide">
    <h1 class="purple">You’re 18 now!!</h1>
  </div>

  <!-- Slide 3 -->
  <div class="slide">
    <h1 class="pink">It’s a big year, you know.</h1>
  </div>

  <!-- Slide 4 -->
  <div class="slide sparkles">
    <h1 class="purple">Happy Birthday, fairy!! ✨</h1>
  </div>

  <!-- Slide 5 : Kuromi waving -->
  <div class="slide">
    <div class="bubble">hi</div>
    <img src="https://media.tenor.com/7w0k3G6KXbEAAAAi/kuromi-sanrio.gif" alt="Kuromi waving">
  </div>

  <!-- Slide 6 : Kuromi with cake -->
  <div class="slide" id="blowSlide">
    <h1 class="purple">Blow into your phone 💨</h1>
    <img id="cakeImg"
      src="https://media.tenor.com/F1wzZ0pniwEAAAAi/birthday-cake-candle.gif"
      alt="Cake with candles"
      style="margin-top:20px;">
  </div>

  <!-- Slide 7 : Final message -->
  <div class="slide">
    <h1 class="purple final">
      I hope this new year brings you one step closer to achieving your goals and dreams 💜<br><br>
      YOU GO SAM ✨<br><br>
      HAPPY 18TH BIRTHDAY AGAIN
    </h1>
  </div>

<script>
  const slides = document.querySelectorAll('.slide');
  let current = 0;
  let micStarted = false;

  document.body.addEventListener('click', () => {
    if (slides[current].id === 'blowSlide' && !micStarted) {
      startMic();
      micStarted = true;
      return;
    }
    nextSlide();
  });

  function nextSlide() {
    slides[current].classList.remove('active');
    current++;
    if (current < slides.length) {
      slides[current].classList.add('active');
    }
  }

  // 🎤 Blow detection
  function startMic() {
    navigator.mediaDevices.getUserMedia({ audio: true }).then(stream => {
      const audioContext = new AudioContext();
      const mic = audioContext.createMediaStreamSource(stream);
      const analyser = audioContext.createAnalyser();
      mic.connect(analyser);
      analyser.fftSize = 256;

      const data = new Uint8Array(analyser.frequencyBinCount);

      function detectBlow() {
        analyser.getByteFrequencyData(data);
        let volume = data.reduce((a, b) => a + b) / data.length;

        if (volume > 40) {
          document.getElementById('cakeImg').src =
            "https://media.tenor.com/9k6ZqZzJpN0AAAAi/candle-blow.gif";
          setTimeout(nextSlide, 1200);
        } else {
          requestAnimationFrame(detectBlow);
        }
      }
      detectBlow();
    }).catch(() => {
      // fallback
      document.getElementById('cakeImg').onclick = nextSlide;
    });
  }
</script>

</body>
</html>
