<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GÜLDÜNYA</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&family=Amiri&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@700&display=swap'); /* استيراد خط فخم */

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Cairo', sans-serif;
      background: url('https://cdn.pixabay.com/photo/2017/08/30/06/48/starry-sky-2695560_960_720.jpg') no-repeat center center fixed;
      background-size: cover;
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
      background: rgba(0, 0, 0, 0.5); /* إضافة خلفية مظلمة مع الشفافية */
      border: 2px solid #fff;
      border-radius: 25px;
      padding: 60px 80px;
      backdrop-filter: blur(12px);
      animation: fadeIn 2s ease-out;
      box-shadow: 0 0 40px rgba(128, 0, 0, 0.6);
      text-align: center;
      position: relative;
    }

    .main-title {
      font-size: 90px;
      font-weight: 700; /* جعل الخط ثقيل أكثر */
      font-family: 'Roboto Slab', serif; /* تغيير الخط إلى فخم */
      color: #fff;
      position: relative;
      text-shadow: 0 0 25px #fff, 0 0 40px #800000;
      animation: fadeInUp 2s ease-out, shine 4s infinite linear;
    }

    .main-title::after {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(120deg, transparent, rgba(255,255,255,0.7), transparent);
      transform: skewX(-20deg);
      animation: shimmer 3s infinite;
    }

    .subtitle {
      font-size: 28px;
      margin-top: 12px;
      font-weight: 700;
      color: #ffffffcc;
      animation: slideIn 2s ease-out;
    }

    .welcome {
      font-size: 24px;
      margin-top: 25px;
      color: #ffffffee;
      animation: fadeInUp 3s ease-out;
    }

    .welcome span {
      float: left;
      margin-left: 12px;
    }

    .youtube-box {
      background: rgba(255, 255, 255, 0.2);
      border: 2px solid #fff;
      border-radius: 18px;
      margin-top: 35px;
      padding: 22px 35px;
      box-shadow: 0 0 20px rgba(255,255,255,0.35);
      display: flex;
      align-items: center;
      gap: 20px;
      animation: fadeInUp 2s ease-out;
    }

    .youtube-box p {
      font-size: 22px;
      color: #fff;
      font-weight: bold;
    }

    .youtube-icon img {
      width: 60px;
      height: auto;
      transition: transform 0.3s ease;
      border-radius: 12px;
    }

    .youtube-icon img:hover {
      transform: scale(1.1);
    }

    .shape {
      position: absolute;
      border-radius: 50%;
      opacity: 0.15;
      animation: float 6s ease-in-out infinite;
    }

    .shape1 {
      width: 160px;
      height: 160px;
      background: #fff;
      top: 8%;
      left: 5%;
      animation-delay: 0s;
    }

    .shape2 {
      width: 110px;
      height: 110px;
      background: #800000;
      bottom: 12%;
      right: 8%;
      animation-delay: 2s;
    }

    .shape3 {
      width: 85px;
      height: 85px;
      background: #ffffff;
      top: 28%;
      right: 18%;
      animation-delay: 4s;
    }

    .shape4 {
      width: 70px;
      height: 70px;
      background: #800000;
      bottom: 30%;
      left: 15%;
      animation-delay: 3s;
    }

    .shape5 {
      width: 100px;
      height: 100px;
      background: #fff;
      top: 60%;
      left: 45%;
      animation-delay: 1.5s;
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
    <p class="welcome">أهلا بكم في موقع التفاحة<span>🍏❤️</span></p><!-- YouTube Section -->
    <div class="youtube-box">
      <a href="https://youtu.be/rngxuyPZ7Zo?si=2VO7flsBKrJsJFgt" target="_blank" class="youtube-icon">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube Logo">
      </a>
      <p>دوسي على علامة اليوتيوب كده يا تفاحة ❤️</p>
    </div>
  </div>  
  <!-- Floating shapes -->
  <div class="shape shape1"></div>
  <div class="shape shape2"></div>
  <div class="shape shape3"></div>
  <div class="shape shape4"></div>
  <div class="shape shape5"></div>
</body>
</html>
