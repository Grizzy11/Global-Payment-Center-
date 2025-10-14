<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dashboard</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #f3f3f3;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: "Poppins", sans-serif;
      transition: background 0.4s ease, color 0.4s ease;
    }

    .phone-screen {
      width: 360px;
      height: 740px;
      background: white;
      border-radius: 25px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-top: 40px;
      transition: background 0.4s ease, box-shadow 0.4s ease;
      position: relative;
      overflow: hidden;
    }

    .logo-glow img {
      width: 80px;
      height: auto;
      filter: drop-shadow(0 0 20px rgba(0, 255, 128, 0.8));
    }

    .welcome-text {
      font-size: 20px;
      font-weight: 600;
      color: #000;
      margin-top: 20px;
    }

    .subtitle {
      color: #666;
      font-size: 14px;
      margin-top: 5px;
    }

    .success-glow {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at center, rgba(0, 255, 128, 0.15) 0%, transparent 70%);
      animation: pulse 2.5s infinite;
      z-index: 0;
    }

    @keyframes pulse {
      0% { opacity: 0.5; transform: scale(1); }
      50% { opacity: 1; transform: scale(1.05); }
      100% { opacity: 0.5; transform: scale(1); }
    }

    .content {
      z-index: 1;
      text-align: center;
      margin-top: 40px;
    }

    .menu {
      display: flex;
      justify-content: space-around;
      align-items: center;
      width: 90%;
      margin-top: 50px;
    }

    .menu-item {
      text-align: center;
      transition: transform 0.2s ease;
      cursor: pointer;
    }

    .menu-item img {
      width: 45px;
      height: 45px;
      margin-bottom: 10px;
    }

    .menu-item span {
      font-size: 14px;
      color: #333;
      font-weight: 500;
    }

    .menu-item:hover {
      transform: scale(1.1);
    }

    .logout-btn {
      position: absolute;
      bottom: 30px;
      background: linear-gradient(90deg, #ff5252, #ff1744);
      border: none;
      color: white;
      font-weight: 600;
      font-size: 14px;
      padding: 12px 25px;
      border-radius: 25px;
      cursor: pointer;
      transition: box-shadow 0.2s ease;
    }

    .logout-btn:hover {
      box-shadow: 0 5px 15px rgba(255, 50, 50, 0.4);
    }

    /* 🌙 Dark Mode */
    @media (prefers-color-scheme: dark) {
      body {
        background: #0f1115;
        color: #eaeaea;
      }

      .phone-screen {
        background: #1a1c20;
        box-shadow: 0 10px 30px rgba(0, 255, 128, 0.15);
      }

      .welcome-text {
        color: #fff;
      }

      .subtitle {
        color: #aaa;
      }

      .menu-item span {
        color: #eee;
      }

      .logout-btn {
        background: linear-gradient(90deg, #ff1744, #ff5252);
        box-shadow: 0 0 15px rgba(255, 50, 50, 0.4);
      }

      .logout-btn:hover {
        box-shadow: 0 0 25px rgba(255, 80, 80, 0.7);
      }
    }
  </style>
</head>
<body>
  <div class="phone-screen">
    <div class="success-glow"></div>
    <div class="content">
      <div class="logo-glow">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Google_Pay_Logo.svg/512px-Google_Pay_Logo.svg.png" alt="Logo">
      </div>
      <div class="welcome-text">Welcome Back 👋</div>
      <div class="subtitle">Your dashboard is ready</div>

      <div class="menu">
        <div class="menu-item">
          <img src="https://cdn-icons-png.flaticon.com/512/891/891462.png" alt="Send">
          <span>Send</span>
        </div>
        <div class="menu-item">
          <img src="https://cdn-icons-png.flaticon.com/512/992/992651.png" alt="Receive">
          <span>Receive</span>
        </div>
        <div class="menu-item">
          <img src="https://cdn-icons-png.flaticon.com/512/1828/1828919.png" alt="History">
          <span>History</span>
        </div>
      </div>
    </div>

    <button class="logout-btn" onclick="logout()">Logout</button>
  </div>

  <script>
    function logout() {
      window.location.href = "index.html"; // Redirect back to launch screen
    }
  </script>
</body>
</html>