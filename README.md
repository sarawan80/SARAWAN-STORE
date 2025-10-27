# SARAWAN-STORE
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>برغي أسود 3000PCS</title>
  <style>
    body {
      font-family: "Tajawal", sans-serif;
      text-align: center;
      background-color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #111;
      color: white;
      padding: 15px;
      font-size: 20px;
    }
    img {
      width: 300px;
      max-width: 90%;
      margin-top: 40px;
    }
    h1 {
      font-size: 26px;
      margin-top: 20px;
      color: #111;
    }
    button {
      background-color: #1a73e8;
      color: white;
      border: none;
      border-radius: 8px;
      padding: 12px 24px;
      font-size: 18px;
      cursor: pointer;
      margin-top: 20px;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #0c5fd3;
    }
    #msg {
      color: green;
      font-weight: bold;
      margin-top: 15px;
    }
    #cartCount {
      background: red;
      color: white;
      border-radius: 50%;
      padding: 3px 8px;
      font-size: 14px;
      margin-left: 6px;
    }
  </style>
</head>
<body>
  <header>
    🛒 السلة: <span id="cartCount">0</span>
  </header>

  <main>
    <img src="A_digital_photograph_features_a_single_black_metal.png" alt="برغي أسود">
    <h1>برغي أسود 3000PCS</h1>
    <button onclick="addToCart()">أضف إلى السلة</button>
    <div id="msg"></div>
  </main>

  <script>
    let cartCount = 0;
    function addToCart() {
      cartCount++;
      document.getElementById('cartCount').textContent = cartCount;
      const msg = document.getElementById('msg');
      msg.textContent = '✅ تمت إضافة المنتج إلى السلة';
      setTimeout(() => msg.textContent = '', 2500);
    }
  </script>
</body>
</html>
