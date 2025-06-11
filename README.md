<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DreamHome Real Estate</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }

    nav {
      background-color: #34495e;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .banner {
      background: url('https://images.unsplash.com/photo-1570129477492-45c003edd2be') no-repeat center center/cover;
      height: 300px;
      text-align: center;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 2em;
      font-weight: bold;
    }

    main {
      padding: 20px;
    }

    .section {
      margin-bottom: 40px;
    }

    .listings {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .property {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 5px;
      overflow: hidden;
      width: calc(33% - 20px);
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .property img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .property-info {
      padding: 15px;
    }

    .property-info h3 {
      margin-top: 0;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .property {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>DreamHome Real Estate</h1>
    <p>Your dream home is just a click away</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Listings</a>
    <a href="#">Agents</a>
    <a href="#">Contact</a>
  </nav>

  <div class="banner">
    Find Your Perfect Home
  </div>

  <main>
    <section class="section" id="listings">
      <h2>Featured Listings</h2>
      <div class="listings">
        <div class="property">
          <img src="https://images.unsplash.com/photo-1600585154340-be6161b89bf2" alt="House 1">
          <div class="property-info">
            <h3>Modern Family Home</h3>
            <p>3 Bed, 2 Bath, 1,800 sqft - $350,000</p>
          </div>
        </div>

        <div class="property">
          <img src="https://images.unsplash.com/photo-1572120360610-d971b9b78842" alt="House 2">
          <div class="property-info">
            <h3>Luxury Villa</h3>
            <p>5 Bed, 4 Bath, 4,000 sqft - $1,250,000</p>
          </div>
        </div>

        <div class="property">
          <img src="https://images.unsplash.com/photo-1599427301266-3b4f4bbf45cf" alt="House 3">
          <div class="property-info">
            <h3>Downtown Apartment</h3>
            <p>2 Bed, 2 Bath, 1,200 sqft - $500,000</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="contact">
      <h2>Contact Us</h2>
      <p>Email: dreamhomeinfo561</p>
      <p>Phone: (123) 456-7890</p>
      <p>Address: 154 Old Turnpike Rd, Southington, CT 06489, USA</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 DreamHome Real Estate. All rights reserved.</p>
  </footer>

</body>
</html>
