<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mahin Rahman - Information Website</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Poppins:wght@300;500;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #1e1e2f, #12121c);
      color: white;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px 20px;
    }

    header {
      font-family: 'Orbitron', sans-serif;
      font-size: 2.8rem;
      margin-bottom: 20px;
      color: #00ffff;
      letter-spacing: 2px;
    }

    .container {
      display: flex;
      flex-direction: row;
      justify-content: center;
      gap: 40px;
      max-width: 1200px;
      width: 100%;
      backdrop-filter: blur(20px);
      background: rgba(255, 255, 255, 0.05);
      border-radius: 20px;
      box-shadow: 0 8px 32px rgba(0,0,0,0.3);
      padding: 30px;
      flex-wrap: wrap;
    }

    .name {
      font-size: 3rem;
      font-weight: 700;
      color: #00ffff;
      text-align: center;
      width: 100%;
      margin-bottom: 20px;
      font-family: 'Orbitron', sans-serif;
    }

    .left, .right {
      flex: 1;
      min-width: 280px;
    }

    .right p {
      font-size: 1rem;
      line-height: 1.6;
      text-align: justify;
    }

    .icon-list {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .icon-item {
      display: flex;
      align-items: center;
      gap: 10px;
      background: rgba(255,255,255,0.05);
      padding: 10px 15px;
      border-radius: 10px;
      transition: 0.3s;
    }

    .icon-item:hover {
      background: rgba(0,255,255,0.1);
    }

    .icon-item img {
      width: 24px;
      height: 24px;
    }

    .icon-item a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }

    @media screen and (max-width: 768px) {
      .container {
        flex-direction: column;
        align-items: center;
      }

      .name {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>

  <header>Information Website</header>

  <div class="container">
    <div class="name">Mahin Rahman</div>

    <div class="left">
      <div class="icon-list">
        <div class="icon-item">
          <img src="https://cdn-icons-png.flaticon.com/512/20/20837.png" alt="Email" />
          <a href="mailto:mahinrahman13140@gmail.com">mahinrahman13140@gmail.com</a>
        </div>
        <div class="icon-item">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp" />
          <a href="https://wa.me/8801770756964" target="_blank">WhatsApp</a>
        </div>
        <div class="icon-item">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook Profile" />
          <a href="https://www.facebook.com/mahin.rahman.757258" target="_blank">Facebook Profile</a>
        </div>
        <div class="icon-item">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook Page" />
          <a href="https://www.facebook.com/mahin0o" target="_blank">Facebook Page</a>
        </div>
        <div class="icon-item">
          <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" />
          <a href="https://www.instagram.
