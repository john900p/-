<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GÜLDÜNYA</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background: url('https://cdn.pixabay.com/photo/2017/08/30/06/48/starry-sky-2695560_960_720.jpg') no-repeat center center fixed;
      background-size: cover;
    }

    .container {
      position: relative;
      padding: 50px;
      color: white;
    }

    /* إرجاع الخط القديم لـ GÜLDÜNYA */
    h1 {
      font-family: 'Arial', sans-serif;
      font-size: 70px;
      color: #fff;
      text-transform: uppercase;
      letter-spacing: 5px;
      animation: glowing 2s ease-in-out infinite;
    }

    @keyframes glowing {
      0% {
        text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000;
      }
      50% {
        text-shadow: 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000, 0 0 50px #ff0000;
      }
      100% {
        text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000;
      }
    }

    /* تصميم زر اليوتيوب */
    .youtube-logo {
      font-size: 24px;
      color: red;
      text-decoration: none;
      display: inline-block;
      margin-top: 50px;
      padding: 10px 20px;
      border: 2px solid red;
      border-radius: 5px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .youtube-logo:hover {
      background-color: red;
      color: white;
    }

    /* تأثير النص */
    p {
      font-size: 20px;
      color: #fff;
      font-weight: bold;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>GÜLDÜNYA</h1>
    <p>My Fav Person For Ever</p>
    <a href="https://youtu.be/rngxuyPZ7Zo?si=2VO7flsBKrJsJFgt" class="youtube-logo" target="_blank">دوسي على علامة اليوتيوب كده يا تفاحة ❤️</a>
  </div>

</body>
</html>
