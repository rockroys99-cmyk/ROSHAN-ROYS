<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>A.ROSHAN ROYS | Gamer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #000;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
      text-align: center;
    }

    .container {
      background: linear-gradient(145deg, #000000, #1a1a1a);
      border: 2px solid red;
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 0 20px red;
      width: 90%;
      max-width: 400px;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      0% { box-shadow: 0 0 20px red; }
      100% { box-shadow: 0 0 40px #ff1a1a; }
    }

    h1 {
      font-size: 2em;
      letter-spacing: 2px;
      color: #ff1a1a;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2em;
      color: #ccc;
      margin-bottom: 30px;
    }

    .social-links a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      color: white;
      border: 2px solid red;
      border-radius: 30px;
      text-decoration: none;
      transition: 0.3s;
    }

    .social-links a:hover {
      background-color: red;
      color: black;
      box-shadow: 0 0 15px red;
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid red;
      margin-bottom: 20px;
      background: url('default-profile.jpg') center/cover no-repeat;
    }

    footer {
      margin-top: 20px;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile-pic"></div>
    <h1>A.ROSHAN ROYS</h1>
    <p>GAMER</p>

    <div class="social-links">
      <a href="https://www.instagram.com/IamRoshanRoyce" target="_blank">Instagram</a>
      <a href="https://www.youtube.com/@RoyceBGMI" target="_blank">YouTube</a>
    </div>

    <footer>© 2025 A.ROSHAN ROYS | All Rights Reserved</footer>
  </div>
</body>
</html>
