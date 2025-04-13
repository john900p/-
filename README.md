<!DOCTYPE html>
<html>
<head>
  <title>تسجيل الدخول إلى فيسبوك</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f0f2f5;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      padding-top: 60px;
    }

    .main-area {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .facebook-logo {
      color: #1877f2;
      font-size: 60px; /* حجم أكبر للوجو */
      font-weight: bold;
      margin-bottom: 20px;
      text-align: center;
    }

    .facebook-slogan {
      font-size: 24px;
      color: #1c1e21;
      margin-bottom: 20px;
      text-align: center;
    }

    .container {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      padding: 20px;
      width: 350px;
      text-align: center;
    }

    input[type="text"],
    input[type="password"] {
      width: calc(100% - 24px);
      padding: 14px; /* حجم أكبر شوية */
      margin-bottom: 10px;
      border: 1px solid #ddd;
      border-radius: 6px;
      box-sizing: border-box;
      font-size: 16px; /* حجم خط أكبر شوية للإدخال */
    }

    button {
      background-color: #1877f2;
      color: #fff;
      padding: 16px 20px; /* حجم أكبر للزر */
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 18px; /* حجم خط أكبر للزر */
      font-weight: bold;
      width: 100%;
      margin-bottom: 15px;
    }

    button:hover {
      background-color: #166fe5;
    }

    a {
      color: #1877f2;
      text-decoration: none;
      font-size: 14px;
    }

    a:hover {
      text-decoration: underline;
    }

    hr {
      border: none;
      border-bottom: 1px solid #ddd;
      margin: 20px 0;
    }

    .create-account {
      background-color: #42b72a;
      color: #fff;
      padding: 16px 20px; /* نفس حجم زر تسجيل الدخول */
      border: none;
      border-radius: 6px; /* نفس حواف زر تسجيل الدخول */
      cursor: pointer;
      font-size: 18px; /* نفس حجم خط زر تسجيل الدخول */
      font-weight: bold;
      text-decoration: none;
      display: inline-block;
      margin-top: 15px;
    }

    .create-account:hover {
      background-color: #36a420;
    }

    .footer {
      margin-top: 30px;
      color: #737373;
      font-size: 12px;
    }

    .footer a {
      color: #737373;
      margin: 0 5px;
    }

    .footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="main-area">
    <div class="facebook-logo">Facebook</div>
    <div class="facebook-slogan">Connect with friends and the world around you on Facebook.</div>
    <div class="container">
      <input type="text" placeholder="Email or phone number">
      <input type="password" placeholder="Password">
      <button type="submit">Log In</button>
      <a href="#">Forgot password?</a>
      <hr>
      <a href="#" class="create-account">Create new account</a>
    </div>
    <div class="footer">
      <a href="#">English (US)</a><a href="#">العربية</a><a href="#">Français (France)</a><a href="#">Deutsch</a><a href="#">日本語</a><a href="#">한국어</a><a href="#">中文(简体)</a><a href="#">Español</a><a href="#">Português (Brasil)</a><a href="#">Italiano</a><a href="#">More...</a>
      <br><br>
      Facebook © 2025
    </div>
  </div>
</body>
</html>
