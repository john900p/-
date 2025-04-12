<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GÜLDÜNYA</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(to bottom right, #800000, #ffffff);
      color: #fff;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      position: relative;
      overflow: hidden;
    }

    .title-container {
      background: rgba(255, 255, 255, 0.1);
      border: 2px solid #fff;
      border-radius: 20px;
      padding: 50px 70px;
      backdrop-filter: blur(10px);
      animation: fadeIn 2s ease-out;
      box-shadow: 0 0 30px rgba(128, 0, 0, 0.5);
      text-align: center;
      position: relative;
    }

    .main-title {
      font-size: 80px;
      font-weight: bold;
      color: #fff;
      position: relative;
      text-shadow: 0 0 15px #fff, 0 0 30px #800000;
      animation: fadeInUp 2s ease-out, shine 4s infinite linear;
    }

    .main-title::after {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(120deg, transparent, rgba(255,255,255,0.6), transparent);
      transform: skewX(-20deg);
      animation: shimmer 3s infinite;
    }

    .subtitle {
      font-size: 24px;
      margin-top: 10px;
      color: #ffffffcc;
      animation: slideIn 2s ease-out;
    }

    .welcome {
      font-size: 22px;
      margin-top: 20px;
      color: #ffffffee;
      animation: fadeInUp 3s ease-out;
    }

    .welcome span {
      float: left;
      margin-left: 10px;
    }

    .youtube-box {
      background: rgba(255, 255, 255, 0.15);
      border: 2px solid #fff;
      border-radius: 15px;
      margin-top: 30px;
      padding: 20px 30px;
      box-shadow: 0 0 15px rgba(255,255,255,0.3);
      display: flex;
      align-items: center;
      gap: 15px;
      animation: fadeInUp 2s ease-out;
    }

    .youtube-box p {
      font-size: 20px;
      color: #fff;
    }

    .youtube-icon {
      width: 50px;
      height: 50px;
      background: #ff0000;
      border-radius: 12px;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: transform 0.3s ease;
    }

    .youtube-icon:hover {
      transform: scale(1.1);
    }

    .youtube-icon img {
      width: 28px;
      height: 28px;
    }

    .shape {
      position: absolute;
      border-radius: 50%;
      opacity: 0.2;
      animation: float 6s ease-in-out infinite;
    }

    .shape1 {
      width: 150px;
      height: 150px;
      background: #fff;
      top: 10%;
      left: 5%;
      animation-delay: 0s;
    }

    .shape2 {
      width: 100px;
      height: 100px;
      background: #800000;
      bottom: 15%;
      right: 10%;
      animation-delay: 2s;
    }

    .shape3 {
      width: 80px;
      height: 80px;
      background: #ffffff;
      top: 30%;
      right: 20%;
      animation-delay: 4s;
    }

    @keyframes shimmer {
      0% { left: -100%; }
      50% { left: 100%; }
      100% { left: 100%; }
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    @keyframes slideIn {
      0% { transform: translateY(-100px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(50px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
  </style>
</head>
<body>
  <div class="title-container">
    <h1 class="main-title">GÜLDÜNYA</h1>
    <p class="subtitle">My Fav Person For Ever</p>
    <p class="welcome">أهلا بكم في موقع التفاحة<span>🍏❤️</span></p>

    <!-- YouTube Section -->
    <div class="youtube-box">
      <a href="https://youtu.be/rngxuyPZ7Zo?si=2VO7flsBKrJsJFgt" target="_blank" class="youtube-icon">
        <!-- YouTube Logo -->
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube Logo">
      </a>
      <p>دوسي على علامة اليوتيوب كده يا تفاحه ❤️</p>
    </div>
  </div>

  <!-- Floating shapes -->
  <div class="shape shape1"></div>
  <div class="shape shape2"></div>
  <div class="shape shape3"></div>
</body>
</html><!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GÜLDÜNYA</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(to bottom right, #800000, #ffffff);
      color: #fff;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      position: relative;
      overflow: hidden;
    }

    .title-container {
      background: rgba(255, 255, 255, 0.1);
      border: 2px solid #fff;
      border-radius: 20px;
      padding: 50px 70px;
      backdrop-filter: blur(10px);
      animation: fadeIn 2s ease-out;
      box-shadow: 0 0 30px rgba(128, 0, 0, 0.5);
      text-align: center;
      position: relative;
    }

    .main-title {
      font-size: 80px;
      font-weight: bold;
      color: #fff;
      position: relative;
      text-shadow: 0 0 15px #fff, 0 0 30px #800000;
      animation: fadeInUp 2s ease-out, shine 4s infinite linear;
    }

    .main-title::after {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(120deg, transparent, rgba(255,255,255,0.6), transparent);
      transform: skewX(-20deg);
      animation: shimmer 3s infinite;
    }

    .subtitle {
      font-size: 24px;
      margin-top: 10px;
      color: #ffffffcc;
      animation: slideIn 2s ease-out;
    }

    .welcome {
      font-size: 22px;
      margin-top: 20px;
      color: #ffffffee;
      animation: fadeInUp 3s ease-out;
    }

    .welcome span {
      float: left;
      margin-left: 10px;
    }

    .youtube-box {
      background: rgba(255, 255, 255, 0.15);
      border: 2px solid #fff;
      border-radius: 15px;
      margin-top: 30px;
      padding: 20px 30px;
      box-shadow: 0 0 15px rgba(255,255,255,0.3);
      display: flex;
      align-items: center;
      gap: 15px;
      animation: fadeInUp 2s ease-out;
    }

    .youtube-box p {
      font-size: 20px;
      color: #fff;
    }

    .youtube-icon {
      width: 50px;
      height: 50px;
      background: #ff0000;
      border-radius: 12px;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: transform 0.3s ease;
    }

    .youtube-icon:hover {
      transform: scale(1.1);
    }

    .youtube-icon img {
      width: 28px;
      height: 28px;
    }

    .shape {
      position: absolute;
      border-radius: 50%;
      opacity: 0.2;
      animation: float 6s ease-in-out infinite;
    }

    .shape1 {
      width: 150px;
      height: 150px;
      background: #fff;
      top: 10%;
      left: 5%;
      animation-delay: 0s;
    }

    .shape2 {
      width: 100px;
      height: 100px;
      background: #800000;
      bottom: 15%;
      right: 10%;
      animation-delay: 2s;
    }

    .shape3 {
      width: 80px;
      height: 80px;
      background: #ffffff;
      top: 30%;
      right: 20%;
      animation-delay: 4s;
    }

    @keyframes shimmer {
      0% { left: -100%; }
      50% { left: 100%; }
      100% { left: 100%; }
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    @keyframes slideIn {
      0% { transform: translateY(-100px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(50px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
  </style>
</head>
<body>
  <div class="title-container">
    <h1 class="main-title">GÜLDÜNYA</h1>
    <p class="subtitle">My Fav Person For Ever</p>
    <p class="welcome">أهلا بكم في موقع التفاحة<span>🍏❤️</span></p>

    <!-- YouTube Section -->
    <div class="youtube-box">
      <a href="https://youtu.be/rngxuyPZ7Zo?si=2VO7flsBKrJsJFgt" target="_blank" class="youtube-icon">
        <!-- YouTube Logo -->
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube Logo">
      </a>
      <p>دوسي على علامة اليوتيوب كده يا تفاحه ❤️</p>
    </div>
  </div>

  <!-- Floating shapes -->
  <div class="shape shape1"></div>
  <div class="shape shape2"></div>
  <div class="shape shape3"></div>
</body>
</html>
