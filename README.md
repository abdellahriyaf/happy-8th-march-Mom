<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>لأمي الحبيبة • 8 مارس</title>
  <!-- Google Fonts for elegant Arabic -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Cairo:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Cairo', 'Amiri', sans-serif;
      background: linear-gradient(145deg, #fef0e7 0%, #fae1d5 100%);
      color: #4a3b3b;
      overflow-x: hidden;
      position: relative;
      min-height: 100vh;
      animation: softGlow 10s infinite alternate;
    }
    @keyframes softGlow {
      0% { background: linear-gradient(145deg, #fef0e7, #fae1d5); }
      100% { background: linear-gradient(145deg, #fce6db, #f7d5c8); }
    }

    /* floating emoji background - only hearts, flowers, butterflies */
    .floating-icons {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 1;
      overflow: hidden;
    }
    .floating-icons span {
      position: absolute;
      font-size: 2rem;
      animation: float 14s infinite ease-in-out;
      filter: drop-shadow(0 5px 8px #ffd0b5);
      pointer-events: none;
    }
    @keyframes float {
      0% { transform: translateY(110vh) rotate(0deg) scale(0.8); opacity: 0; }
      20% { opacity: 0.8; }
      80% { opacity: 0.6; }
      100% { transform: translateY(-20vh) rotate(20deg) scale(1.2); opacity: 0; }
    }

    /* main sections */
    section {
      position: relative;
      z-index: 10;
      width: 100%;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2rem 1rem;
      scroll-behavior: smooth;
    }
    .content-box {
      max-width: 800px;
      text-align: center;
      background: rgba(255, 245, 235, 0.7);
      backdrop-filter: blur(6px);
      border-radius: 60px 20px 60px 20px;
      padding: 3rem 2.5rem;
      box-shadow: 0 25px 40px rgba(200, 120, 100, 0.15), 0 0 0 2px #fff5e6 inset;
      border: 1px solid #ffd9c5;
    }
    h1 {
      font-size: 3.5rem;
      font-weight: 700;
      color: #9e5f5f;
      margin-bottom: 1rem;
      text-shadow: 3px 3px 0 #ffdede;
    }
    .subtitle {
      font-size: 2rem;
      font-weight: 400;
      color: #b17878;
      margin-bottom: 2rem;
      font-family: 'Amiri', serif;
    }
    .message {
      font-size: 1.7rem;
      line-height: 1.8;
      color: #5c4242;
      margin: 2rem 0;
      background: rgba(255, 245, 235, 0.5);
      border-radius: 80px;
      padding: 1.5rem;
    }
    .arrow-down {
      margin-top: 2rem;
      font-size: 4rem;
      color: #dba1a1;
      animation: bounce 2s infinite;
      cursor: pointer;
      transition: 0.3s;
      filter: drop-shadow(0 10px 10px #ffbfbf);
    }
    .arrow-down:hover {
      color: #b96767;
      transform: scale(1.2);
    }
    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
      40% { transform: translateY(-20px); }
      60% { transform: translateY(-10px); }
    }

    /* flower section */
    .flower-title {
      font-size: 3rem;
      color: #8f5e5e;
      margin-bottom: 1.5rem;
      text-shadow: 2px 2px 0 #ffd8d8;
    }
    .flower-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 100%;
    }
    svg {
      width: 500px;
      height: 500px;
      filter: drop-shadow(0 15px 25px #ffb3b3);
      margin: 10px 0;
    }
    .petal {
      cursor: pointer;
      transition: filter 0.3s ease;
    }
    .petal:hover {
      filter: drop-shadow(0 0 12px #ff9a9a);
    }
    .center-circle {
      pointer-events: none;
    }
    .role-message {
      font-size: 2.5rem;
      font-weight: 600;
      color: #a04848;
      background: rgba(255, 240, 240, 0.8);
      backdrop-filter: blur(10px);
      padding: 1.5rem 3rem;
      border-radius: 100px;
      margin-top: 30px;
      min-height: 120px;
      display: flex;
      align-items: center;
      justify-content: center;
      border: 2px solid #ffc1c1;
      box-shadow: 0 10px 20px #ffd0d0;
      font-family: 'Amiri', serif;
      width: fit-content;
      max-width: 90%;
    }
    .deco-line {
      margin: 1rem 0;
      font-size: 2rem;
      color: #ffb6c1;
    }

    @media (max-width: 600px) {
      h1 { font-size: 2.5rem; }
      .message { font-size: 1.3rem; }
      svg { width: 350px; height: 350px; }
      .role-message { font-size: 1.8rem; }
    }
  </style>
</head>
<body>
  <!-- Floating emojis: hearts, flowers, butterflies (no bunnies) -->
  <div class="floating-icons">
    <!-- hearts -->
    <span style="top: 10%; left: 5%; animation-delay: 0s;">❤️</span>
    <span style="top: 70%; left: 85%; animation-delay: 3s;">💖</span>
    <span style="top: 30%; left: 40%; animation-delay: 5s;">💗</span>
    <span style="top: 50%; left: 15%; animation-delay: 1.5s;">💓</span>
    <!-- flowers -->
    <span style="top: 20%; left: 80%; animation-delay: 1s;">🌸</span>
    <span style="top: 85%; left: 15%; animation-delay: 5s;">🌼</span>
    <span style="top: 45%; left: 70%; animation-delay: 2.8s;">🌺</span>
    <span style="top: 60%; left: 30%; animation-delay: 4.2s;">🌷</span>
    <!-- butterflies -->
    <span style="top: 40%; left: 20%; animation-delay: 2s;">🦋</span>
    <span style="top: 55%; left: 60%; animation-delay: 4s;">🦋</span>
    <span style="top: 75%; left: 45%; animation-delay: 6s;">🦋</span>
  </div>

  <!-- SECTION 1: HOMEPAGE CONGRATULATIONS FOR MOM -->
  <section class="section-1" id="home">
    <div class="content-box">
      <div class="deco-line">
        ❤️ 🌸 🦋
      </div>
      <h1>يوم المرأة العالمي</h1>
      <div class="subtitle">إلى أمي الحبيبة</div>
      <div class="message">
        <i class="fas fa-quote-right"></i> 
        أمي الغالية .. أنتِ مصدر الحنان والأمان. في قلبك يسكن الدفء، وفي دعائك تكمن السعادة. كل عام وأنتِ النور الذي يضيء دربي. أحبك بكل ما أملك.
        <i class="fas fa-quote-left"></i>
      </div>
      <div style="font-size: 2rem; margin: 1rem;">
        ❤️ 💗 🌸
      </div>
      <div class="arrow-down" onclick="document.getElementById('flower-section').scrollIntoView({behavior: 'smooth'})">
        ⬇️
      </div>
    </div>
  </section>

  <!-- SECTION 2: FLOWER WITH QUALITIES FOR MOM -->
  <section class="section-2" id="flower-section">
    <h2 class="flower-title">أنتِ كل هذه المشاعر الجميلة</h2>
    <div class="flower-container">
      <svg viewBox="0 0 400 400">
        <!-- gradients for petals - warm tones -->
        <defs>
          <radialGradient id="grad1" cx="30%" cy="30%" r="70%">
            <stop offset="0%" stop-color="#fbc1b0" />
            <stop offset="100%" stop-color="#f7a18a" />
          </radialGradient>
          <radialGradient id="grad2" cx="30%" cy="30%" r="70%">
            <stop offset="0%" stop-color="#fad2b8" />
            <stop offset="100%" stop-color="#f5a98c" />
          </radialGradient>
          <radialGradient id="grad3" cx="30%" cy="30%" r="70%">
            <stop offset="0%" stop-color="#f8c8b5" />
            <stop offset="100%" stop-color="#f09d85" />
          </radialGradient>
          <radialGradient id="grad4" cx="30%" cy="30%" r="70%">
            <stop offset="0%" stop-color="#f9bdaa" />
            <stop offset="100%" stop-color="#e9907a" />
          </radialGradient>
          <radialGradient id="grad5" cx="30%" cy="30%" r="70%">
            <stop offset="0%" stop-color="#f9afa0" />
            <stop offset="100%" stop-color="#e6836e" />
          </radialGradient>
        </defs>

        <!-- petals (teardrop shape) with beautiful qualities -->
        <path class="petal" data-role="الدعم" d="M200,80 Q240,130 200,200 Q160,130 200,80" fill="url(#grad1)" transform="rotate(0,200,200)" />
        <path class="petal" data-role="الاهتمام" d="M200,80 Q240,130 200,200 Q160,130 200,80" fill="url(#grad2)" transform="rotate(72,200,200)" />
        <path class="petal" data-role="الحب" d="M200,80 Q240,130 200,200 Q160,130 200,80" fill="url(#grad3)" transform="rotate(144,200,200)" />
        <path class="petal" data-role="الحنان" d="M200,80 Q240,130 200,200 Q160,130 200,80" fill="url(#grad4)" transform="rotate(216,200,200)" />
        <path class="petal" data-role="التضحية" d="M200,80 Q240,130 200,200 Q160,130 200,80" fill="url(#grad5)" transform="rotate(288,200,200)" />

        <!-- center (non‑clickable) with flower emoji -->
        <circle class="center-circle" cx="200" cy="200" r="40" fill="#fff0e5" stroke="#fbb5a5" stroke-width="3" />
        <text class="center-circle" x="200" y="215" text-anchor="middle" fill="#a15454" font-size="26" font-family="Cairo">🌸</text>
      </svg>

      <div class="role-message" id="roleDisplay">🌸 إضغط على بتلة 🌸</div>
    </div>
    <div style="margin-top: 30px; color: #b47373; font-size: 1.8rem;">
      🦋 ❤️ 🌸
    </div>
  </section>

  <script>
    const roleDisplay = document.getElementById('roleDisplay');
    const petals = document.querySelectorAll('.petal');
    petals.forEach(petal => {
      petal.addEventListener('click', function(e) {
        const role = this.getAttribute('data-role');
        roleDisplay.textContent = `❀ أنتِ ${role} ❀`;
        roleDisplay.style.transform = 'scale(1.05)';
        setTimeout(() => roleDisplay.style.transform = 'scale(1)', 150);
      });
    });
  </script>
</body>
</html>
