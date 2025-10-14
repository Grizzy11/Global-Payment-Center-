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
}

.caption {
  font-size: 14px;
  color: #666;
  margin-bottom: 10px;
}

.logo-glow img {
  width: 90px;
  height: auto;
  filter: drop-shadow(0 0 20px rgba(0, 255, 128, 0.8));
}

.title {
  color: #000;
  font-size: 22px;
  font-weight: 600;
  margin: 25px 0;
}

.launch-btn {
  background: linear-gradient(90deg, #00c853, #00e676);
  border: none;
  color: white;
  font-size: 16px;
  font-weight: 600;
  border-radius: 30px;
  padding: 15px 30px;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
}

.launch-btn:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 20px rgba(0, 200, 100, 0.5);
}

.payment-logos {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 80%;
  margin-top: 40px;
}

.payment-logos img {
  width: 50px;
  opacity: 0.9;
  transition: opacity 0.3s;
}

.payment-logos img:hover {
  opacity: 1;
}

/* 🌙 Dark Mode Styles */
@media (prefers-color-scheme: dark) {
  body {
    background: #0f1115;
    color: #eaeaea;
  }

  .phone-screen {
    background: #1a1c20;
    box-shadow: 0 10px 30px rgba(0, 255, 128, 0.15);
  }

  .caption {
    color: #bbb;
  }

  .title {
    color: #fff;
  }

  .launch-btn {
    background: linear-gradient(90deg, #00e676, #00c853);
    box-shadow: 0 0 15px rgba(0, 255, 128, 0.4);
  }

  .launch-btn:hover {
    box-shadow: 0 0 25px rgba(0, 255, 128, 0.7);
  }

  .payment-logos img {
    opacity: 0.8;
  }
}