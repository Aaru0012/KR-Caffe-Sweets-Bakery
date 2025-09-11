# KR-Caffe-Sweets-

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KR Cafe Sweets & Bakery</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }

    header {
      background: rgba(0,0,0,0.75);
      text-align: center;
      padding: 20px;
    }

    header img {
      width: 180px;
    }

    header h1 {
      margin: 10px 0;
      font-size: 2.8em;
      color: #ffcc00;
    }

    header p {
      font-size: 1.2em;
      color: #ddd;
    }

    section {
      margin: 20px auto;
      padding: 20px;
      max-width: 900px;
      border-radius: 10px;
      background: rgba(0,0,0,0.65);
    }

    h2 {
      text-align: center;
      margin-bottom: 15px;
      color: #ffcc00;
    }

    .menu-item {
      display: flex;
      justify-content: space-between;
      padding: 10px;
      border-bottom: 1px solid #444;
      font-size: 1.1em;
    }

    .menu-item:last-child {
      border-bottom: none;
    }

    .order form {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .order input, 
    .order select, 
    .order button, 
    .order textarea {
      padding: 12px;
      border: none;
      border-radius: 5px;
      font-size: 1em;
    }

    .order textarea {
      resize: none;
      height: 80px;
    }

    .order button {
      background: #ff9800;
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    .order button:hover {
      background: #e68900;
    }

    .contact p {
      text-align: center;
      font-size: 1.1em;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <img src="WhatsApp Image 2025-09-09 at 16.58.56.jpeg" alt="KR Cafe Logo">
    <h1>KR Cafe Sweets & Bakery</h1>
    <p>Fresh • Delicious • Homemade</p>
  </header>

  <!-- Menu Section -->
  <section class="menu">
    <h2>Our Menu</h2>
    <!-- Owner can modify these menu items & rates in the code -->
    <div class="menu-item"><span>Cappuccino</span><span>₹120</span></div>
    <div class="menu-item"><span>Espresso</span><span>₹100</span></div>
    <div class="menu-item"><span>Latte</span><span>₹140</span></div>
    <div class="menu-item"><span>Chocolate Cake</span><span>₹250</span></div>
    <div class="menu-item"><span>Cheesecake</span><span>₹280</span></div>
    <div class="menu-item"><span>Veg Sandwich</span><span>₹90</span></div>
    <div class="menu-item"><span>Paneer Roll</span><span>₹110</span></div>
  </section>

  
  <!-- Contact Section -->
  <section class="contact">
    <h2>Contact & Cafe Details</h2>
    <p>[opposite govt. hospital, Dudhola, Palwal, Haryana]
        </p>
    <p>[Contact no. 8700721552, 8930173542
        ]</p>
    <p>timing:- 10 AM - 10 PM </p>
    
  </section>

 
</body>
</html>
