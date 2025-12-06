# My-fast-website
Utv
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Utv</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      width: 100%;
      padding: 20px;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      border-bottom: 2px solid gold;
    }

    header h1 {
      color: gold;
      font-size: 32px;
      margin: 0;
    }

    .container {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      width: 90%;
      margin-top: 20px;
    }

    .section {
      background: #222;
      padding: 15px;
      border-radius: 10px;
    }

    .vip {
      background: linear-gradient(45deg, black, gold);
      border: 2px solid gold;
    }

    footer {
      margin-top: 20px;
      padding: 10px;
      font-size: 20px;
      background: #000;
      width: 100%;
      text-align: center;
      border-top: 2px solid gold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Utv</h1>
  </header>

  <div class="container">
    <div class="section">
      <h2>Most Viewed Movies</h2>
      <p>Movie list here</p>
    </div>

    <div class="section">
      <h2>New Movies</h2>
      <p>Movie list here</p>
    </div>
  </div>

  <div class="container">
    <div class="section">
      <h2>Normal Category</h2>
      <ul>
        <li>Watch in HD</li>
        <li>Normal Quality</li>
        <li>Speed Control</li>
        <li>Search Bar</li>
      </ul>
    </div>

    <div class="section vip">
      <h2>VIP Category (Utsav Yadav 45y)</h2>
      <ul>
        <li>Golden Theme</li>
        <li>Download Option</li>
        <li>Share Option</li>
        <li>Membership Required</li>
      </ul>
    </div>
  </div>

  <footer>
    <b>Utv • Golden Logo</b>
  </footer>
</body>
</html>
