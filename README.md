<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Toko Item Roblox</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #0f62fe;
      padding: 20px;
      color: white;
      text-align: center;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .items {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: white;
      padding: 15px;
      border-radius: 15px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }
    .btn {
      display: inline-block;
      background: #0f62fe;
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 10px;
      margin-top: 10px;
      transition: 0.2s;
    }
    .btn:hover {
      background: #0043b5;
    }
    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      background: #ddd;
    }
  </style>
</head>
<body>
  <header>
    <h1>Toko Item Roblox</h1>
    <p>Jual beli item Roblox dengan aman & cepat</p>
  </header>

  <div class="container">
    <h2>Daftar Item</h2>
    <div class="items">
      <div class="card">
        <img src="https://via.placeholder.com/250" alt="Item 1" />
        <h3>Katalog Item 1</h3>
        <p>Harga: 50 Robux</p>
        <a href="#" class="btn">Beli Sekarang</a>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/250" alt="Item 2" />
        <h3>Katalog Item 2</h3>
        <p>Harga: 120 Robux</p>
        <a href="#" class="btn">Beli Sekarang</a>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/250" alt="Item 3" />
        <h3>Katalog Item 3</h3>
        <p>Harga: 80 Robux</p>
        <a href="#" class="btn">Beli Sekarang</a>
      </div>
    </div>
  </div>

  <footer>
    <p>© 2025 Toko Item Roblox. Semua Hak Dilindungi.</p>
  </footer>
</body>
</html>
