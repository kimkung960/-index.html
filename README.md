<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>ละมุน | ร้านของหวาน</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: sans-serif;

      /* พื้นหลัง */
      background-image: url("images/bg.jpg");
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }

    header {
      background: rgba(255, 182, 193, 0.85);
      color: white;
      padding: 18px;
      text-align: center;
      backdrop-filter: blur(6px);
    }

    .container {
      padding: 16px;
      display: flex;
      justify-content: center;
    }

    .card {
      background: rgba(255, 255, 255, 0.9);
      border-radius: 16px;
      padding: 14px;
      box-shadow: 0 6px 14px rgba(0,0,0,.1);
      text-align: center;
      max-width: 230px;
    }

    .card img {
      width: 100%;
      height: 140px;
      object-fit: cover;
      border-radius: 12px;
    }

    .price {
      color: #ff69b4;
      font-weight: bold;
      margin: 6px 0;
    }

    a.button {
      display: inline-block;
      background: #1877f2;
      color: white;
      text-decoration: none;
      border-radius: 20px;
      padding: 8px 14px;
      margin-top: 8px;
    }
  </style>
</head>

<body>

<header>
  <h1>ละมุน</h1>
  <p>บราวนี่โฮมเมด หอมหวาน ละมุนใจ 💕</p>
</header>

<div class="container">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1606313564200-e75d5e30476c">
    <h3>บราวนี่ช็อกโกแลต</h3>
    <p class="price">25 บาท</p>

    <a 
      class="button"
      href="https://www.facebook.com/KimPhupakron"
      target="_blank"
    >
      ทัก Facebook
    </a>
  </div>
</div>

</body>
</html>
