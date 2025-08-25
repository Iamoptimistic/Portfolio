<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mobolaji Abdulateef | Data Science Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    body { background: #ffffff; color: #1e293b; }
    section { padding: 4rem 0; }
    .card { background: #f8fafc; transition: transform 0.3s, box-shadow 0.3s; }
    .card:hover { transform: translateY(-5px); box-shadow: 0 0 20px rgba(37,99,235,0.5); }
    a, button, img { transition: all 0.3s ease-in-out; }
    a:hover, button:hover { color: #2563eb; }
    header, footer { background: #1e3a8a; }
    header a { color: #f1f5f9; }
    header a:hover, header a.active { color: #93c5fd; }
    footer p { color: #e2e8f0; }
    /* Scrollable containers */
    .scroll-wrapper { position: relative; overflow: hidden; }
    .scroll-container { display: flex; gap: 1rem; overflow-x: auto; scroll-behavior: smooth; padding-bottom: 1rem; }
    .scroll-container::-webkit-scrollbar { display: none; }
    .scroll-btn { position: absolute; top: 50%; transform: translateY(-50%); background: rgba(30,58,138,0.8); color: white; padding: 0.5rem; border-radius: 50%; cursor: pointer; z-index: 10; }
    .scroll-btn:hover { background: #2563eb; }
    .left-btn { left: 10px; }
    .right-btn { right: 10px; }
    /* Lightbox */
    #lightbox { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.9); display: flex; align-items: center; justify-content: center; visibility: hidden; opacity: 0; transition: opacity 0.3s ease; z-index: 100; }
    #lightbox.active { visibility: visible; opacity: 1; }
    #lightbox img { max-width: 90%; max-height: 80%; border-radius: 10px; }
    #lightbox p { color: white; margin-top: 1rem; font-size: 1rem; text-align: center; }
  </style>
</head>
<body class="font-sans">

  <!-- Navigation -->
  <header class="shadow-md fixed top-0 w-full z-50">
    <nav class="container mx-auto flex justify-between items-center p-4">
      <div class="flex items-center space-x-3">
        <img src="Profile.jpg" alt="Profile Picture" class="w-10 h-10 rounded-full border-2 border-white">
        <h1 class="text-xl font-bold text-white">Mobolaji Abdulateef</h1>
      </div>
      <ul class="flex space-x-6 font-medium">
        <li><a href="#home" class="nav-link">Home</a></li>
        <li><a href="#portfolio" class="nav-link">Portfolio</a></li>
        <li><a href="#gallery" class="nav-link">Gallery</a></li>
        <li><a href="#artwork" class="nav-link">My Artwork</a></li>
        <li><a href="#contact" class="nav-link">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero -->
  <section id="home" class="text-center pt-28">
    <div class="container mx-auto">
      <h2 class="text-5xl font-extrabold mb-6 text-blue-600">Welcome to My Portfolio</h2>
      <p class="text-lg max-w-2xl mx-auto mb-8">
        I am <strong>Mobolaji Abdulateef</strong>, a veterinarian and certified Data scientist with keen interest in Biomedical Research. 
      My research focus include neurobiology, bioimaging and environmental toxicology.
      </p>
      <a href="#portfolio" class="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700 font-semibold">
        Explore My Work
      </a>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">📊 Portfolio Projects</h2>
      <p class="max-w-2xl mx-auto">A selection of my work demonstrating expertise in machine learning, predictive analytics, and data visualization.</p>
    </div>
    <div class="scroll-wrapper container mx-auto">
      <button class="scroll-btn left-btn" onclick="scrollContent('portfolioContainer', -300)">◀</button>
      <div id="portfolioContainer" class="scroll-container">
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <h3 class="text-xl font-semibold mb-2">Employee Promotion Prediction</h3>
          <p class="mb-4">ML system to predict employee promotions using HR metrics, enhancing transparency and fairness.</p>
          <img src="AUC.png" class="rounded-lg mb-2" alt="Employee Promotion Prediction" onclick="openLightbox(this)">
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <h3 class="text-xl font-semibold mb-2">Abalone Age Prediction</h3>
          <p class="mb-4">Predicting the age of abalones using measurable physical features and machine learning models.</p>
          <img src="Figure_1.png" class="rounded-lg mb-2" alt="Abalone Age Prediction" onclick="openLightbox(this)">
        </div>
        <!-- add more cards here if needed -->
      </div>
      <button class="scroll-btn right-btn" onclick="scrollContent('portfolioContainer', 300)">▶</button>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">🖼️ Gallery</h2>
      <p class="max-w-2xl mx-auto">Browse through visuals from my projects, research and conferences.</p>
    </div>
    <div class="scroll-wrapper container mx-auto">
      <button class="scroll-btn left-btn" onclick="scrollContent('galleryContainer', -300)">◀</button>
      <div id="galleryContainer" class="scroll-container">
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Savan1.jpg" class="rounded-lg mb-2" alt="SAVAN Conference Day 1" onclick="openLightbox(this)">
          <p>SAVAN Conference Day 1</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Savan2.jpg" class="rounded-lg mb-2" alt="SAVAN Conference Day 2" onclick="openLightbox(this)">
          <p>SAVAN Conference Day 2</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Savan3.jpg" class="rounded-lg mb-2" alt="SAVAN Conference Day 2" onclick="openLightbox(this)">
          <p>SAVAN Conference with BlueBlood Veterinary Hospital Staff</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Alumni1.jpg" class="rounded-lg mb-2" alt="SAVAN Conference Day 2" onclick="openLightbox(this)">
          <p>Presented my research work at the maiden edition of the Alumni meeting</p>
        </div>
      </div>
      <button class="scroll-btn right-btn" onclick="scrollContent('galleryContainer', 300)">▶</button>
    </div>
  </section>

  <!-- Artwork -->
  <section id="artwork">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">🎨 My Artwork</h2>
      <p class="max-w-2xl mx-auto">Microscope images and scientific visuals from my biomedical research.</p>
    </div>
    <div class="scroll-wrapper container mx-auto">
      <button class="scroll-btn left-btn" onclick="scrollContent('artworkContainer', -300)">◀</button>
      <div id="artworkContainer" class="scroll-container">
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Picture1.jpg" class="rounded-lg mb-2" alt="Transverse section of Cerebellum (X40, H&E)" onclick="openLightbox(this)">
          <p>Transverse section of Cerebellum of African Side-neck Turtle (Pelusios castaneus) (X40, H&E)</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Picture2.jpg" class="rounded-lg mb-2" alt="Transverse section of Cerebellum (Pelusios castaneus) (X100, H&E)" onclick="openLightbox(this)">
          <p>ransverse section of Cerebellum (Pelusios castaneus) (X100, H&E)</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Picture3.jpg" class="rounded-lg mb-2" alt="Cerebellum (X400, H&E)" onclick="openLightbox(this)">
          <p>Transverse section of Cerebellum (Pelusious castaneus) (X400, H&E)</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Ulcer1.jpg" class="rounded-lg mb-2" alt="Transverse section of Stomach (X40, H&E)" onclick="openLightbox(this)">
          <p>Transverse section of Stomach showing sloughing-off of the intestinal lining (X100, H&E)</p>
        </div>
        <div class="card shadow rounded-xl p-4 text-center w-80 flex-shrink-0">
          <img src="Cardiac1.jpg" class="rounded-lg mb-2" alt=" longitudinal Section of Cardiac muscle, note the crossing intercalated disc, nucleus at the margin and branching of the muscle fibers (X100, H&E)" onclick="openLightbox(this)">
          <p>longitudinal Section of Cardiac muscle, note the crossing intercalated disc, nucleus at the margin and branching of the muscle fibers (X100, H&E)</p>
        </div>
      </div>
      <button class="scroll-btn right-btn" onclick="scrollContent('artworkContainer', 300)">▶</button>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-6 text-blue-600">📬 Contact Me</h2>
      <p class="mb-6">Let’s connect! Reach out for collaborations, opportunities, or just to say hi.</p>
      <div class="space-y-2 mb-8">
        <p>Email: <a href="mailto:mobolajiayoola3@gmail.com">mobolajiayoola3@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/mobolajiabdulateef/">LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/Iamoptimistic">GitHub</a></p>
      </div>
      <h3 class="text-2xl font-bold mb-4 text-blue-600">📄 Curriculum Vitae</h3>
      <p class="mb-6">Download my complete CV to learn more about my academic background, professional journey, and technical expertise.</p>
      <a href="CURRICULUM VITAE- ABDULATEEF AYOOLA MOBOLAJI.pdf" class="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700">Download CV</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center">
    <p>✨ Built by <strong class="text-blue-300">Mobolaji Abdulateef</strong> | Data Science & Biomedical Research ✨</p>
  </footer>

  <!-- Lightbox -->
  <div id="lightbox" onclick="closeLightbox()">
    <div class="text-center">
      <img id="lightbox-img" src="" alt="Expanded View">
      <p id="lightbox-caption"></p>
    </div>
  </div>

  <script>
    function scrollContent(containerId, amount) {
      document.getElementById(containerId).scrollBy({ left: amount, behavior: 'smooth' });
    }

    function openLightbox(img) {
      document.getElementById('lightbox-img').src = img.src;
      document.getElementById('lightbox-caption').innerText = img.alt;
      document.getElementById('lightbox').classList.add('active');
    }

    function closeLightbox() {
      document.getElementById('lightbox').classList.remove('active');
    }

    // Highlight active nav link
    const sections = document.querySelectorAll("section");
    const navLinks = document.querySelectorAll(".nav-link");

    window.addEventListener("scroll", () => {
      let current = "";
      sections.forEach(section => {
        const sectionTop = section.offsetTop - 100;
        if (scrollY >= sectionTop) current = section.getAttribute("id");
      });
      navLinks.forEach(link => {
        link.classList.remove("active");
        if (link.getAttribute("href") === "#" + current) link.classList.add("active");
      });
    });
  </script>
</body>
</html>
