<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>อร่อยล้นจาน</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f5f5f5;
    }
    header {
      background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836') center/cover;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 20px;
    }
    nav {
      background: #d62828;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .card .info {
      padding: 15px;
    }
    .card h3 {
      margin: 0 0 10px;
    }
    .price {
      color: #d62828;
      font-weight: bold;
    }
    .order {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 15px;
      background: #d62828;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>ร้านอร่อยล้นจาน</h1>
  <p>อาหารไทย รสจัด ส่งตรงถึงคุณ</p>
</header>

<nav>
  <a href="#menu">เมนู</a>
  <a href="#contact">ติดต่อ</a>
</nav>

<div class="container" id="menu">
  <h2>🍛 เมนูแนะนำ</h2>
  <div class="menu">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1604908177522-0407a1fcb8d2">
      <div class="info">
        <h3>ผัดกะเพราหมู</h3>
        <p class="price">60 บาท</p>
        <a class="order" href="#">สั่งอาหาร</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1540189549336-e6e99c3679fe">
      <div class="info">
        <h3>ต้มยำกุ้ง</h3>
        <p class="price">120 บาท</p>
        <a class="order" href="#">สั่งอาหาร</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1625943868881-9e5d74a4a1c4">
      <div class="info">
        <h3>ข้าวมันไก่</h3>
        <p class="price">50 บาท</p>
        <a class="order" href="#">สั่งอาหาร</a>
      </div>
    </div>

  </div>
</div>

<div class="container" id="contact">
  <h2>📞 ติดต่อร้าน</h2>
  <p>โทร: 09x-xxx-xxxx</p>
  <p>LINE: @aroyshop</p>
  <p>เปิดทุกวัน 09:00 - 20:00</p>
</div>

<footer>
  © 2025 ร้านอร่อยล้นจาน | GitHub Pages
</footer>

</body>
</html>
