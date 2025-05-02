
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pizza Delight | Authentic Italian Pizza</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <meta name="description" content="Enjoy delicious handcrafted pizzas at Pizza Delight. Authentic flavors, fresh ingredients, and warm hospitality.">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body, html {
      margin: 0;
      padding: 0;
    }

    header {
      background: #fff;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .nav-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
    }

    nav a {
      text-decoration: none;
      color: #333;
    }

    .hero {
      background-image: url('images/hero-pizza.jpg');
      background-size: cover;
      background-position: center;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }

    .hero h1 {
      font-size: 3rem;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
    }

    section {
      padding: 4rem 2rem;
    }

    .about-us, .menu, .gallery, .find-us {
      max-width: 1200px;
      margin: auto;
    }

    .about-img {
      max-width: 100%;
      height: auto;
    }

    .menu-item {
      margin-bottom: 2rem;
    }

    .grid-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .grid-gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 2rem;
    }

    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
      }

      .nav-container {
        flex-direction: column;
      }

      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
  </head>
<body>

  <!-- Header -->
  <header>
    <div class="nav-container">
      <img src="images/logo.png" alt="Pizza Delight Logo" width="150" />
      <nav aria-label="Main navigation">
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#menu">Menu</a></li>
          <li><a href="#carousel">Gallery</a></li>
          <li><a href="#contact">Find Us</a></li>
        </ul>
      </nav>
      <div class="social-icons">
        <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
        <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </header>

  <!-- Main Banner -->
  <main>
    <section class="hero" role="banner" aria-label="Main banner with pizza">
      <div>
        <h1>Welcome to Pizza Delight</h1>
        <p>Authentic flavors. Fresh ingredients. Warm hospitality.</p>
      </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about-us">
      <div class="row align-items-center">
        <div class="col-md-6">
          <h2>About Us</h2>
          <p>We are a family-owned pizzeria bringing traditional Italian recipes to your table. Every pizza is made with love and the freshest ingredients.</p>
        </div>
        <div class="col-md-6">
          <img src="images/about.jpg" alt="Inside Pizza Delight restaurant" class="about-img" />
        </div>
      </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="menu">
      <h2>Our Menu</h2>
      <article class="menu-item">
        <h3>Margherita Pizza</h3>
        <p>Classic delight with mozzarella, tomatoes, and basil.</p>
      </article>
      <article class="menu-item">
        <h3>Pepperoni Pizza</h3>
        <p>Bold and spicy with loads of pepperoni and cheese.</p>
      </article>
      <article class="menu-item">
        <h3>Veggie Supreme</h3>
        <p>Fresh peppers, mushrooms, onions, and olives.</p>
      </article>
    </section>

    <!-- Carousel -->
    <section id="carousel">
      <div id="pizzaCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://raw.githubusercontent.com/alsornak/Pizza-Delight/refs/heads/main/client/public/images/cheese.jpeg" class="d-block w-100" alt="Cheese Pizza" />
          </div>
          <div class="carousel-item">
            <img src="https://raw.githubusercontent.com/alsornak/Pizza-Delight/refs/heads/main/client/public/images/crazy-pepperoni.jpeg" class="d-block w-100" alt="Pepperoni Pizza" />
          </div>
          <div class="carousel-item">
            <img src="https://www.tasteofhome.com/wp-content/uploads/2023/04/The-6-Best-Pizza-Ovens-on-Amazon-for-a-Restaurant-Quality-Pie-Every-Time_social_via-amazon.com_.jpg" class="d-block w-100" alt="Pizza Oven" />
          </div>
          <div class="carousel-item">
            <img src="https://offerengine.theentertainerme.com/piza-e-vino-melville-x23945998/merchant_profile_%22hero%22_image_%28retina%29202407021454.jpg" class="d-block w-100" alt="Dining area" />
          </div>
          <div class="carousel-item">
            <img src="https://thumbs.dreamstime.com/b/italian-pizza-margherita-fresh-tomatoes-mozzarella-basil-marjoram-43460353.jpg" class="d-block w-100" alt="Italian pizza with basil" />
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#pizzaCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#pizzaCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
        </button>
      </div>
    </section>

    <!-- Gallery -->
    <section id="gallery" class="gallery">
      <h2>Photo Gallery</h2>
      <div class="grid-gallery">
        <img src="https://media.istockphoto.com/id/938742222/photo/cheesy-pepperoni-pizza.jpg?s=612x612&w=0&k=20&c=D1z4xPCs-qQIZyUqRcHrnsJSJy_YbUD9udOrXpilNpI=" alt="Pizza close-up" />
        <img src="https://offerengine.theentertainerme.com/piza-e-vino-melville-x23945998/merchant_profile_%22hero%22_image_%28retina%29202407021454.jpg" alt="Dining area" />
        <img src="https://media.istockphoto.com/id/938742222/photo/cheesy-pepperoni-pizza.jpg?s=612x612&w=0&k=20&c=D1z4xPCs-qQIZyUqRcHrnsJSJy_YbUD9udOrXpilNpI=" alt="Pizza slice with cheese pull" />
        <img src="https://images.squarespace-cdn.com/content/v1/5a4c0a7c18b27d4da21b1a12/1ff2ee41-fefa-4007-9328-30fa73ffb899/2023.04.25n.jpg?format=1500w" alt="Table setup" />
        <img src="https://cdn.shopify.com/s/files/1/0052/1512/5553/files/image_3_480x480.png?v=1661243469" alt="Wood-fired oven" />
      </div>
    </section>

    <!-- Find Us Section -->
    <section id="contact" class="find-us">
      <h2>Find Us</h2>
      <div class="row">
        <div class="col-md-6">
          <p><strong>Address:</strong> 123 Pizza Street, Flavor Town</p>
          <p><strong>Phone:</strong> (123) 456-7890</p>
          <p><strong>Email:</strong> info@pizzadelight.com</p>
        </div>
        <div class="col-md-6">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18..." width="100%" height="300" style="border:0;" allowfullscreen loading="lazy" title="Pizza Delight on Google Maps"></iframe>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Pizza Delight. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
