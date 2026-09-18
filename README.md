
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="AKINWALE SHERIFF BUILDING CONSTRUCTION - Building, renovation and construction services in Benin City, Edo State, Nigeria.">
  <meta name="keywords" content="Akinwale Sheriff Building Construction, construction company Benin City, house building Edo State, house renovation">
  <title>AKINWALE SHERIFF BUILDING CONSTRUCTION</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: #111;
      color: white;
      padding: 18px 6%;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 3px 10px rgba(0,0,0,.25);
    }

    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
    }

    .logo span {
      color: #f4b400;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
      font-size: 14px;
    }

    nav a:hover {
      color: #f4b400;
    }

    .hero {
      min-height: 78vh;
      display: flex;
      align-items: center;
      padding: 70px 6%;
      background:
        linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
        url("https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1600&q=80")
        center/cover;
      color: white;
    }

    .hero-content {
      max-width: 750px;
    }

    .hero h1 {
      font-size: clamp(35px, 7vw, 70px);
      line-height: 1.05;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #f4b400;
    }

    .hero p {
      font-size: 18px;
      max-width: 650px;
      margin-bottom: 28px;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .btn {
      display: inline-block;
      padding: 13px 22px;
      border-radius: 7px;
      text-decoration: none;
      font-weight: bold;
      border: none;
      cursor: pointer;
    }

    .primary {
      background: #f4b400;
      color: #111;
    }

    .dark {
      background: #222;
      color: white;
    }

    section {
      padding: 65px 6%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 40px;
    }

    .section-title h2 {
      font-size: 34px;
      margin-bottom: 8px;
    }

    .section-title p {
      color: #666;
    }

    .about {
      background: white;
    }

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 35px;
      align-items: center;
    }

    .about-image {
      width: 100%;
      min-height: 350px;
      border-radius: 15px;
      object-fit: cover;
    }

    .services-grid,
    .house-grid,
    .gallery {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 13px;
      box-shadow: 0 5px 20px rgba(0,0,0,.08);
    }

    .card h3 {
      margin: 12px 0 8px;
    }

    .icon {
      font-size: 40px;
    }

    .house-card {
      background: white;
      border-radius: 13px;
      overflow: hidden;
      box-shadow: 0 5px 20px rgba(0,0,0,.08);
    }

    .house-card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .house-info {
      padding: 18px;
    }

    .house-info h3 {
      margin-bottom: 5px;
    }

    .gallery-item {
      position: relative;
      background: white;
      border-radius: 13px;
      overflow: hidden;
      min-height: 220px;
      box-shadow: 0 5px 20px rgba(0,0,0,.08);
    }

    .gallery-item img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .add-card {
      min-height: 220px;
      border: 3px dashed #f4b400;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: #fffdf5;
      cursor: pointer;
    }

    .add-card:hover {
      background: #fff7d6;
    }

    .plus {
      font-size: 55px;
      color: #f4b400;
      display: block;
    }

    .upload-text {
      font-weight: bold;
    }

    input[type="file"] {
      display: none;
    }

    .contact {
      background: #111;
      color: white;
    }

    .contact-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 35px;
    }

    .contact-box {
      background: #1d1d1d;
      padding: 28px;
      border-radius: 14px;
    }

    .contact-box p {
      margin: 13px 0;
    }

    .contact-box a {
      color: #f4b400;
      text-decoration: none;
    }

    footer {
      background: #080808;
      color: #aaa;
      text-align: center;
      padding: 25px;
      font-size: 14px;
    }

    @media(max-width: 800px) {
      nav {
        display: none;
      }

      .about-grid,
      .contact-grid,
      .services-grid,
      .house-grid,
      .gallery {
        grid-template-columns: 1fr;
      }

      .hero {
        min-height: 70vh;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="nav">
    <div class="logo">AKINWALE <span>SHERIFF</span></div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#houses">House Types</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<!-- HERO -->
<section class="hero" id="home">
  <div class="hero-content">
    <p>🏗️ BUILD • RENOVATE • TRANSFORM</p>

    <h1>
      AKINWALE <span>SHERIFF</span><br>
      BUILDING CONSTRUCTION
    </h1>

    <p>
      Professional building and renovation services in Benin City,
      Edo State and beyond. We help turn building ideas into real homes.
    </p>

    <div class="buttons">
      <a class="btn primary" href="#contact">Contact Us</a>
      <a class="btn dark" href="https://wa.me/2348062106726" target="_blank">
        WhatsApp Us
      </a>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="about">
  <div class="section-title">
    <h2>About Us</h2>
    <p>Building your vision from foundation to finishing.</p>
  </div>

  <div class="about-grid">

    <img class="about-image"
      src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1000&q=80"
      alt="Building construction">

    <div>
      <h2>AKINWALE SHERIFF BUILDING CONSTRUCTION</h2>

      <p>
        We provide building construction and renovation services for
        residential and other building projects.
      </p>

      <br>

      <p>
        Our services cover planning, block work, foundation work,
        structural construction, plastering, roofing, tiling,
        finishing and renovation.
      </p>

      <br>

      <strong>📍 Benin City, Edo State, Nigeria</strong>

      <br><br>

      <div class="buttons">
        <a class="btn primary" href="#projects">View Projects</a>
        <a class="btn dark" href="tel:08062106726">Call Now</a>
      </div>
    </div>

  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="section-title">
    <h2>Our Services</h2>
    <p>Construction services for different stages of your project.</p>
  </div>

  <div class="services-grid">

    <div class="card">
      <div class="icon">🏠</div>
      <h3>House Construction</h3>
      <p>Construction of residential houses from foundation to finishing.</p>
    </div>

    <div class="card">
      <div class="icon">🔨</div>
      <h3>Renovation</h3>
      <p>Renovation and improvement of existing buildings.</p>
    </div>

    <div class="card">
      <div class="icon">📐</div>
      <h3>Building Plans</h3>
      <p>House planning and floor-plan concepts for building projects.</p>
    </div>

    <div class="card">
      <div class="icon">🧱</div>
      <h3>Block Work</h3>
      <p>Block laying and masonry work for building projects.</p>
    </div>

    <div class="card">
      <div class="icon">🏗️</div>
      <h3>Foundation Work</h3>
      <p>Foundation and structural construction services.</p>
    </div>

    <div class="card">
      <div class="icon">✨</div>
      <h3>Finishing</h3>
      <p>Plastering, tiling and other finishing works.</p>
    </div>

  </div>
</section>

<!-- HOUSE TYPES -->
<section id="houses" class="about">
  <div class="section-title">
    <h2>Different House Types</h2>
    <p>Examples of residential designs and building types.</p>
  </div>

  <div class="house-grid">

    <div class="house-card">
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80"
           alt="3 Bedroom Bungalow">
      <div class="house-info">
        <h3>3-Bedroom Bungalow</h3>
        <p>Single-storey family home with bedrooms, living area and service spaces.</p>
      </div>
    </div>

    <div class="house-card">
      <img src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=900&q=80"
           alt="4 Bedroom Duplex">
      <div class="house-info">
        <h3>4-Bedroom Duplex</h3>
        <p>Two-storey residential home suitable for a larger family.</p>
      </div>
    </div>

    <div class="house-card">
      <img src="https://images.unsplash.com/photo-1600566753190-17f0baa2a6c3?auto=format&fit=crop&w=900&q=80"
           alt="Modern House">
      <div class="house-info">
        <h3>Modern Family House</h3>
        <p>Contemporary residential design with modern architectural features.</p>
      </div>
    </div>

    <div class="house-card">
      <img src="https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=900&q=80"
           alt="2 Bedroom House">
      <div class="house-info">
        <h3>2-Bedroom House</h3>
        <p>Compact residential design suitable for a smaller household.</p>
      </div>
    </div>

    <div class="house-card">
      <img src="https://images.unsplash.com/photo-1600047509807-ba8f99d2cdde?auto=format&fit=crop&w=900&q=80"
           alt="Luxury Duplex">
      <div class="house-info">
        <h3>Luxury Duplex</h3>
        <p>Spacious two-storey home with premium residential features.</p>
      </div>
    </div>

    <div class="house-card">
      <img src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?auto=format&fit=crop&w=900&q=80"
           alt="Bungalow">
      <div class="house-info">
        <h3>Modern Bungalow</h3>
        <p>Modern single-storey design suitable for residential living.</p>
      </div>
    </div>

  </div>
</section>

<!-- PROJECT GALLERY -->
<section id="projects">
  <div class="section-title">
    <h2>Our Projects</h2>
    <p>Add your own construction pictures below.</p>
  </div>

  <div class="gallery" id="gallery">

    <!-- ADD YOUR OWN PHOTO -->
    <label class="gallery-item add-card">
      <div>
        <span class="plus">+</span>
        <span class="upload-text">ADD YOUR PROJECT PHOTO</span>
        <br>
        <small>Tap here to select an image</small>
        <input type="file" accept="image/*" onchange="addPhoto(event)">
      </div>
    </label>

  </div>
</section>

<!-- CONTACT -->
<section class="contact" id="contact">
  <div class="section-title">
    <h2>Contact Us</h2>
    <p>Let's discuss your next building project.</p>
  </div>

  <div class="contact-grid">

    <div class="contact-box">
      <h2>AKINWALE SHERIFF BUILDING CONSTRUCTION</h2>

      <p>📍 <strong>Location:</strong><br>
        Benin City, Edo State, Nigeria
      </p>

      <p>📞 <strong>Phone:</strong><br>
        <a href="tel:08062106726">08062106726</a><br>
        <a href="tel:08125642296">08125642296</a>
      </p>

      <p>📧 <strong>Email:</strong><br>
        <a href="mailto:buildingsheriff68@gmail.com">
          buildingsheriff68@gmail.com
        </a>
      </p>
    </div>

    <div class="contact-box">
      <h2>Chat With Us</h2>

      <p>
        Send us a message on WhatsApp for enquiries,
        building projects and renovation work.
      </p>

      <br>

      <a class="btn primary"
         href="https://wa.me/2348062106726?text=Hello%20Akinwale%20Sheriff%20Building%20Construction%2C%20I%20want%20to%20make%20an%20enquiry."
         target="_blank">
        💬 WhatsApp 1
      </a>

      <br><br>

      <a class="btn primary"
         href="https://wa.me/2348125642296?text=Hello%20Akinwale%20Sheriff%20Building%20Construction%2C%20I%20want%20to%20make%20an%20enquiry."
         target="_blank">
        💬 WhatsApp 2
      </a>
    </div>

  </div>
</section>

<footer>
  © <span id="year"></span> AKINWALE SHERIFF BUILDING CONSTRUCTION.
  All Rights Reserved.
  <br>
  BUILD AND RENOVATE THE HOUSE • TRAVEL TO ANYWHERE
</footer>

<script>

  document.getElementById("year").textContent =
    new Date().getFullYear();

  function addPhoto(event) {

    const file = event.target.files[0];

    if (!file) return;

    const reader = new FileReader();

    reader.onload = function(e) {

      const gallery = document.getElementById("gallery");

      const item = document.createElement("div");

      item.className = "gallery-item";

      item.innerHTML = `
        <img src="${e.target.result}" alt="Akinwale Sheriff Building Construction Project">
      `;

      gallery.insertBefore(item, gallery.firstElementChild);
    };

    reader.readAsDataURL(file);
  }

</script>

</body>
</html>
