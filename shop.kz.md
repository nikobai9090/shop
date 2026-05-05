# shop.kz
продаю штатив и одежды с китаи
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Дүкен - Штатив & Киім</title>

  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: #0f172a;
      color: white;
    }

    header {
      background: #111827;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
      color: #38bdf8;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }

    .card {
      background: #1f2937;
      width: 250px;
      margin: 15px;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card h3 {
      margin: 10px;
    }

    .price {
      margin: 10px;
      color: #22c55e;
      font-weight: bold;
    }

    .btn {
      margin: 10px;
      padding: 10px;
      width: calc(100% - 20px);
      border: none;
      background: #38bdf8;
      color: black;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
    }

    .btn:hover {
      background: #0ea5e9;
    }

    footer {
      text-align: center;
      padding: 20px;
      opacity: 0.6;
    }
  </style>
</head>

<body>

<header>
  <h1>🛒 Штатив & Киім Дүкені</h1>
</header>

<div class="container">

  <div class="card">
    <img src="https://images.unsplash.com/photo-1519183071298-a2962be96f83">
    <h3>Штатив Pro</h3>
    <div class="price">12 000 ₸</div>
    <button class="btn" onclick="buy('Штатив Pro')">Сатып алу</button>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1520975928316-56a2f7c7a8a2">
    <h3>Футболка Oversize</h3>
    <div class="price">8 500 ₸</div>
    <button class="btn" onclick="buy('Футболка Oversize')">Сатып алу</button>
  </div>

  <div class="card">
    <img src="https://images.unsplash.com/photo-1521335629791-ce4aec67dd15">
    <h3>Худи Premium</h3>
    <div class="price">15 000 ₸</div>
    <button class="btn" onclick="buy('Худи Premium')">Сатып алу</button>
  </div>

</div>

<footer>
  © 2026 Штатив & Киім дүкені
</footer>

<script>
  function buy(item) {
    alert(item + " таңдалды ✅\nТапсырыс қабылданды!");
  }
</script>

</body>
</html>