# crypto-exchange-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Crypto Exchange</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background: #f9f9f9;
      color: #111;
    }
    header {
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: white;
      border-bottom: 1px solid #eee;
    }
    .logo {
      font-size: 24px;
      font-weight: 700;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #111;
    }
    .auth-buttons button {
      margin-left: 10px;
      padding: 8px 16px;
      border: none;
      cursor: pointer;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1611078489935-2f8b7a4f89a4?fit=crop&w=1200&q=80') no-repeat center center/cover;
      height: 300px;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
    }
    .search-box {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
    }
    .search-box input,
    .search-box select,
    .search-box button {
      margin: 5px;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .yellow-bar {
      background: #ffe100;
      padding: 15px;
      text-align: center;
      font-weight: 600;
    }
    .crypto-logos {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #ffe100;
      padding: 20px 0;
    }
    .crypto-logos a img {
      height: 30px;
    }
    .features {
      display: flex;
      justify-content: space-around;
      padding: 40px 20px;
      background: #fff;
    }
    .feature {
      text-align: center;
      max-width: 200px;
    }
    .crypto-section {
      display: flex;
      justify-content: space-around;
      background: #fff;
      padding: 20px;
    }
    .crypto-section div {
      padding: 10px;
      background: #f2f2f2;
      border-radius: 8px;
    }
    .cta {
      background: #e3d5ff;
      text-align: center;
      padding: 40px 20px;
    }
    .cta button {
      background: #111;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      font-weight: bold;
    }
    footer {
      background: #111;
      color: white;
      padding: 40px;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    footer div {
      margin: 10px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Frame Marketplace</div>
    <nav>
      <a href="#">Buy</a>
      <a href="#">Sell</a>
      <a href="#">Create an offer</a>
    </nav>
    <div class="auth-buttons">
      <button>Log in</button>
      <button>Sign up</button>
    </div>
  </header>

  <section class="hero">
    <div class="search-box">
      <select><option>Offer type</option></select>
      <select><option>Currency</option></select>
      <select><option>Payment</option></select>
      <select><option>Location</option></select>
      <button>Search</button>
    </div>
  </section>

  <div class="yellow-bar">
    Buy/Sell the favorites with 0% Fees*
  </div>
  <div class="crypto-logos">
    <a href="https://bitcoin.org" target="_blank"><img src="https://cryptologos.cc/logos/bitcoin-btc-logo.png" alt="BTC"></a>
    <a href="https://tether.to" target="_blank"><img src="https://cryptologos.cc/logos/tether-usdt-logo.png" alt="USDT"></a>
    <a href="https://www.binance.com" target="_blank"><img src="https://cryptologos.cc/logos/binance-coin-bnb-logo.png" alt="BNB"></a>
    <a href="https://ethereum.org" target="_blank"><img src="https://cryptologos.cc/logos/ethereum-eth-logo.png" alt="ETH"></a>
    <a href="https://solana.com" target="_blank"><img src="https://cryptologos.cc/logos/solana-sol-logo.png" alt="SOL"></a>
  </div>

  <section class="features">
    <div class="feature">
      <h4>Security First</h4>
      <p>Enhanced protection, safe transactions</p>
    </div>
    <div class="feature">
      <h4>Instant Trades</h4>
      <p>Lightning-fast deals</p>
    </div>
    <div class="feature">
      <h4>100+ Payment Methods</h4>
      <p>Flexible transactions</p>
    </div>
  </section>

  <section class="crypto-section">
    <div>
      <p>Buy BTC at 100,000 BDT</p>
    </div>
    <div>
      <p>Sell USDT at 110 BDT</p>
    </div>
    <div>
      <p>Buy ETH at 150,000 BDT</p>
    </div>
  </section>

  <section class="cta">
    <h2>Sign up and buy or sell crypto in 5 minutes with zero commission fees</h2>
    <button>Get started</button>
  </section>

  <footer>
    <div>
      <h4>Product</h4>
      <p>Buy</p>
      <p>Sell</p>
      <p>Wallet</p>
    </div>
    <div>
      <h4>About</h4>
      <p>Company</p>
      <p>Careers</p>
    </div>
    <div>
      <h4>Support</h4>
      <p>Help Center</p>
      <p>Contact</p>
    </div>
  </footer>
</body>
</html>
