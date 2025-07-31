<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Savda Stock</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 20px;
      background: #f2f2f2;
    }

    h1 {
      text-align: center;
      background: #1e3d59;
      color: white;
      padding: 15px;
      border-radius: 10px;
      letter-spacing: 1px;
    }

    .section {
      margin: 30px 0;
    }

    .section h2 {
      background-color: #343a40;
      color: #fff;
      padding: 10px 15px;
      border-radius: 8px;
      font-size: 20px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 15px;
    }

    .card {
      flex: 1 1 220px;
      background-color: white;
      border-left: 8px solid #0077b6;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card.inward { border-left-color: #28a745; }
    .card.outward { border-left-color: #ffc107; }
    .card.balance { border-left-color: #17a2b8; }

    .material-name {
      font-weight: 600;
      font-size: 16px;
      color: #333;
    }

    .balance {
      font-size: 20px;
      font-weight: bold;
      color: #111;
      margin-top: 5px;
    }
  </style>
</head>
<body>

  <h1>Savda Stock</h1>

  <!-- Inward Section -->
  <div class="section">
    <h2>Inward</h2>
    <div class="cards">
      <div class="card inward">
        <div class="material-name">Vaccum Bag 13kg</div>
        <div class="balance">1020</div>
      </div>
      <div class="card inward">
        <div class="material-name">PE Form 1.5 MM (Nos)</div>
        <div class="balance">157500</div>
      </div>
      <div class="card inward">
        <div class="material-name">Fevicol (kg)</div>
        <div class="balance">4</div>
      </div>
    </div>
  </div>

  <!-- Outward Section -->
  <div class="section">
    <h2>Outward</h2>
    <div class="cards">
      <div class="card outward"><div class="material-name">Roshana Box (Nos)</div><div class="balance">1500</div></div>
      <div class="card outward"><div class="material-name">Vaccum Bag 13kg</div><div class="balance">30</div></div>
      <div class="card outward"><div class="material-name">PE Form 1.5 MM (Nos)</div><div class="balance">3500</div></div>
      <div class="card outward"><div class="material-name">Sachets (Nos)</div><div class="balance">1600</div></div>
      <div class="card outward"><div class="material-name">Germination Paper (kg)</div><div class="balance">32</div></div>
      <div class="card outward"><div class="material-name">Fungicide (kg)</div><div class="balance">4</div></div>
      <div class="card outward"><div class="material-name">Truti (kg)</div><div class="balance">10</div></div>
      <div class="card outward"><div class="material-name">Bleaching Powder (g)</div><div class="balance">0.2</div></div>
      <div class="card outward"><div class="material-name">Rubber (kg)</div><div class="balance">1</div></div>
      <div class="card outward"><div class="material-name">Roshana Sticker (Nos)</div><div class="balance">20000</div></div>
    </div>
  </div>

  <!-- Total Balance Section -->
  <div class="section">
    <h2>Total Stock Balance</h2>
    <div class="cards">
      <div class="card balance"><div class="material-name">King Brown Box (Nos)</div><div class="balance">2360</div></div>
      <div class="card balance"><div class="material-name">Alaa Brown Box (Nos)</div><div class="balance">0</div></div>
      <div class="card balance"><div class="material-name">Bandhan Premium</div><div class="balance">1500</div></div>
      <div class="card balance"><div class="material-name">King White Box (Nos)</div><div class="balance">0</div></div>
      <div class="card balance"><div class="material-name">Alaa White Box (Nos)</div><div class="balance">500</div></div>
      <div class="card balance"><div class="material-name">Roshana Box (Nos)</div><div class="balance">9400</div></div>
      <div class="card balance"><div class="material-name">Laibaah Box (Nos)</div><div class="balance">350</div></div>
      <div class="card balance"><div class="material-name">Haniya Box (Nos)</div><div class="balance">800</div></div>
      <div class="card balance"><div class="material-name">Shabad Box (Nos)</div><div class="balance">280</div></div>
      <div class="card balance"><div class="material-name">Vaccum Bag 13kg</div><div class="balance">3090</div></div>
      <div class="card balance"><div class="material-name">Vaccum Bag 7kg</div><div class="balance">0</div></div>
      <div class="card balance"><div class="material-name">PE Form 1.5 MM (Nos)</div><div class="balance">98000</div></div>
      <div class="card balance"><div class="material-name">Sachets (Nos)</div><div class="balance">105000</div></div>
      <div class="card balance"><div class="material-name">Fevicol (kg)</div><div class="balance">300</div></div>
      <div class="card balance"><div class="material-name">Germination Paper (kg)</div><div class="balance">915</div></div>
      <div class="card balance"><div class="material-name">Fungicide (kg)</div><div class="balance">200</div></div>
      <div class="card balance"><div class="material-name">Truti (kg)</div><div class="balance">980</div></div>
      <div class="card balance"><div class="material-name">Bleaching Powder (g)</div><div class="balance">22.3</div></div>
      <div class="card balance"><div class="material-name">Rubber (kg)</div><div class="balance">12.5</div></div>
      <div class="card balance"><div class="material-name">King Sticker (Nos)</div><div class="balance">56000</div></div>
      <div class="card balance"><div class="material-name">Alaa Sticker (Nos)</div><div class="balance">4650000</div></div>
      <div class="card balance"><div class="material-name">Roshana Sticker (Nos)</div><div class="balance">5020000</div></div>
      <div class="card balance"><div class="material-name">Laibaah Sticker (Nos)</div><div class="balance">0</div></div>
      <div class="card balance"><div class="material-name">Haniya Sticker (Nos)</div><div class="balance">0</div></div>
      <div class="card balance"><div class="material-name">Other Sticker</div><div class="balance">2520000</div></div>
    </div>
  </div>

</body>
</html>
