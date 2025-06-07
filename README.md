<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Travel & Movies</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />

  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    nav {
      background-color: #333;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px;
    }
    footer {
      background-color: #f4f4f4;
      text-align: center;
      padding: 20px;
    }
    img {
      width: 300px;
      margin: 10px;
    }
    .movie-card {
      max-width: 600px;
      margin-bottom: 2rem;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#videos">Videos</a>
    <a href="#movies">Movies</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h1>Welcome to Beautiful Travel Destinations</h1>
    <p>Discover some of the most breathtaking places around the world. From serene beaches to bustling cities, travel offers unforgettable experiences.</p>
  </section>

  <!-- Gallery Section -->
  <section id="gallery">
    <h2>Photo Gallery</h2>
    <img src="https://via.placeholder.com/300x200?text=Beach" alt="Beach" />
    <img src="https://via.placeholder.com/300x200?text=Mountains" alt="Mountains" />
    <img src="https://via.placeholder.com/300x200?text=City" alt="City" />
  </section>

  <!-- Video Section -->
  <section id="videos">
    <h2>Travel Videos</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Scxs7L0vhZ4" title="Travel video" frameborder="0" allowfullscreen></iframe>
  </section>

  <!-- Movies Section -->
  <section id="movies" class="container my-5">
    <h2 class="mb-4">Now Showing</h2>

    <!-- Movie Card 1: Ghost in the Shell -->
    <div class="card movie-card">
      <div class="row g-0">
        <div class="col-md-4">
          <img src="ghost-in-the-shell.jpg" class="img-fluid rounded-start" alt="Ghost in the Shell" />
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Ghost in the Shell</h5>
            <p class="card-text">
              In the near future, Major is the first of her kind: A human saved from a terrible crash, who is cyber-enhanced to be a perfect soldier devoted to stopping the world's most dangerous criminals.
            </p>
            <!-- Info Pill Badges -->
            <span class="badge rounded-pill bg-info text-dark me-1">12:00 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">1:30 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">3:00 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">5:30 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">7:00 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark">9:30 p.m.</span>
          </div>
        </div>
      </div>
    </div>

    <!-- Movie Card 2: Beauty and the Beast -->
    <div class="card movie-card">
      <div class="row g-0">
        <div class="col-md-4">
          <img src="beauty-and-the-beast.jpg" class="img-fluid rounded-start" alt="Beauty and the Beast" />
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Beauty and the Beast</h5>
            <p class="card-text">
              A selfish prince is cursed to become a monster for the rest of his life, unless he learns to fall in love with a beautiful young woman he keeps prisoner.
            </p>
            <!-- Info Pill Badges -->
            <span class="badge rounded-pill bg-info text-dark me-1">12:00 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">1:30 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">3:00 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">5:30 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark me-1">7:00 p.m.</span>
            <span class="badge rounded-pill bg-info text-dark">9:30 p.m.</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Form -->
  <section id="contact" class="container my-5">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label><br />
      <input type="text" id="name" name="name" class="form-control mb-3" />

      <label for="email">Email:</label><br />
      <input type="email" id="email" name="email" class="form-control mb-3" />

      <label for="message">Message:</label><br />
      <textarea id="message" name="message" rows="4" class="form-control mb-3"></textarea>

      <input type="submit" value="Submit" class="btn btn-primary" />
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Beautiful Travel Destinations & Movies. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS Bundle -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
