<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>𝓖𝓾𝓵𝓭𝓾𝓷𝓎𝓪♡</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: white;
      color: #800000; /* نبيتي */
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
      text-align: center;
      overflow: hidden;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
      animation: fadeIn 2s ease-out;
    }

    p {
      font-size: 1.5em;
      margin-bottom: 20px;
      animation: fadeIn 2s 0.5s ease-out;
    }

    .youtube-link {
      font-size: 1.3em;
      margin: 20px;
      animation: fadeIn 2s 1s ease-out;
    }

    .youtube-logo {
      width: 70px;
      margin-bottom: 20px;
      cursor: pointer;
      transition: transform 0.3s ease;
    }

    .youtube-logo:hover {
      transform: scale(1.1);
    }

    .shapes {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 250px;
      height: 250px;
      background-color: rgba(0, 0, 0, 0.1);
      border-radius: 50%;
      animation: shapeAnimation 10s infinite alternate;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes shapeAnimation {
      0% {
        transform: scale(1) rotate(0deg);
      }
      100% {
        transform: scale(1.2) rotate(360deg);
      }
    }

  </style>
</head>
<body>

  <h1>𝓖𝓾𝓵𝓭𝓾𝓷𝓎𝓪♡</h1>
  <p>MY FAV PERSON</p>

  <div class="shapes"></div>

  <p>اهلا بكم في موقع احلا تفاحه 🍏</p>

  <!-- رابط اليوتيوب داخل اللوجو -->
  <a href="https://youtu.be/HRQ1k5ff7JI?si=ySk0T07NoqSX6K1K" target="_blank">
    <img class="youtube-logo" src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube Logo">
  </a>

  <div class="youtube-link">
    <p>دوسي على علامة اليوتيوب يا تفاحه ❤️</p>
  </div>

</body>
</html>
