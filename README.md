<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mobolaji Abdulateef | Data Science Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      background: #ffffff;
      color: #1e293b;
    }
    section {
      padding: 4rem 0;
    }
    .card {
      background: #f8fafc;
      color: #1e293b;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(37, 99, 235, 0.5);
    }
    a, button, img {
      transition: all 0.3s ease-in-out;
    }
    a:hover, button:hover {
      color: #2563eb;
    }
    img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px rgba(37, 99, 235, 0.5);
    }
    header, footer {
      background: #1e3a8a;
    }
    header a {
      color: #f1f5f9;
    }
    header a:hover, header a.active {
      color: #93c5fd;
    }
    footer p {
      color: #e2e8f0;
    }
    /* Gallery */
    .gallery-wrapper {
      position: relative;
      overflow: hidden;
    }
    .gallery-container {
      display: flex;
      gap: 1rem;
      overflow-x: auto;
      scroll-behavior: smooth;
    }
    .gallery-container::-webkit-scrollbar {
      display: none;
    }
    .gallery-btn {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      background: rgba(30, 58, 138, 0.8);
      color: white;
      padding: 0.5rem;
      border-radius: 50%;
      cursor: pointer;
      z-index: 10;
    }
    .gallery-btn:hover {
      background: #2563eb;
    }
    .left-btn {
      left: 10px;
    }
    .right-btn {
      right: 10px;
    }
  </style>
</head>
<body class="font-sans">
  <!-- Navigation Bar -->
  <header class="shadow-md fixed top-0 w-full z-50">
    <nav class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-xl font-bold text-white">Mobolaji Abdulateef</h1>
      <ul class="flex space-x-6 font-medium">
        <li><a href="#home" class="nav-link">Home</a></li>
        <li><a href="#portfolio" class="nav-link">Portfolio</a></li>
        <li><a href="#research" class="nav-link">Research</a></li>
        <li><a href="#gallery" class="nav-link">Gallery</a></li>
        <li><a href="#cv" class="nav-link">CV</a></li>
        <li><a href="#contact" class="nav-link">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="text-center pt-28">
    <div class="container mx-auto">
      <h2 class="text-5xl font-extrabold mb-6 text-blue-600">Welcome to My Portfolio</h2>
      <p class="text-lg max-w-2xl mx-auto mb-8">I am <strong>Mobolaji Abdulateef</strong>, a Data Scientist and Biomedical Research Enthusiast. I specialize in <strong>Data Analysis, Visualization, and Predictive Modelling</strong> using Python and Power BI.</p>
      <a href="#portfolio" class="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700 font-semibold">Explore My Work</a>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">📊 Portfolio Projects</h2>
      <p class="max-w-2xl mx-auto">A selection of my work demonstrating expertise in machine learning, predictive analytics, and data visualization.</p>
    </div>
    <div class="grid md:grid-cols-2 gap-8 container mx-auto">
      <div class="card shadow rounded-xl p-6">
        <h3 class="text-xl font-semibold mb-2">Employee Promotion Prediction</h3>
        <p class="mb-4">ML system to predict employee promotions using HR metrics, enhancing transparency and fairness.</p>
        <img src="AUC.png" alt="Project">
      </div>
      <div class="card shadow rounded-xl p-6">
        <h3 class="text-xl font-semibold mb-2">Abalone Age Prediction</h3>
        <p class="mb-4">Predicting the age of abalones using measurable physical features and machine learning models.</p>
        <img src="Figure_1.png" alt="Project">
      </div>
      <div class="card shadow rounded-xl p-6">
        <h3 class="text-xl font-semibold mb-2">Data Cleaning Task with Python</h3>
        <p class="mb-4">Prepared and cleaned a Kaggle movies dataset, resolving missing values, duplicates, and inconsistencies.</p>
        <img src="Print.png" alt="Project">
      </div>
      <div class="card shadow rounded-xl p-6">
        <h3 class="text-xl font-semibold mb-2">Amazon Social Media Marketing</h3>
        <p class="mb-4">Power BI visualization of Amazon’s marketing influence in Nigeria, analyzing customer engagement trends.</p>
        <img src="Amazon.png" alt="Project">
      </div>
    </div>
  </section>

  <!-- Research Section -->
  <section id="research">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">📑 Research Interests</h2>
      <p class="max-w-3xl mx-auto">My research lies at the intersection of healthcare, sustainable development, and computational neuroscience. I use advanced analytics to study antimicrobial resistance, mental health, sleep patterns, and diagnostic imaging.</p>
    </div>
    <div class="grid md:grid-cols-2 gap-8 container mx-auto">
      <div class="card p-6 shadow rounded-xl">
        <h3 class="text-xl font-semibold mb-2">Biomedical Research</h3>
        <p>Applying machine learning to healthcare datasets for better decision-making, diagnostics, and patient outcomes.</p>
      </div>
      <div class="card p-6 shadow rounded-xl">
        <h3 class="text-xl font-semibold mb-2">Sustainable Development</h3>
        <p>Exploring data-driven policies for antimicrobial resistance, public health, and sustainable healthcare systems.</p>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">🖼️ Gallery</h2>
      <p class="max-w-2xl mx-auto">Browse through visuals from my projects and research using the arrows.</p>
    </div>
    <div class="gallery-wrapper container mx-auto">
      <button class="gallery-btn left-btn" onclick="scrollGallery(-300)">◀</button>
      <div id="galleryContainer" class="gallery-container">
        <img src="AUC.png" class="rounded-lg shadow w-80" alt="Gallery Image 1">
        <img src="Figure_1.png" class="rounded-lg shadow w-80" alt="Gallery Image 2">
        <img src="Amazon.png" class="rounded-lg shadow w-80" alt="Gallery Image 3">
        <img src="Print.png" class="rounded-lg shadow w-80" alt="Gallery Image 4">
      </div>
      <button class="gallery-btn right-btn" onclick="scrollGallery(300)">▶</button>
    </div>
  </section>

  <!-- CV Section -->
  <section id="cv">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-4 text-blue-600">📄 Curriculum Vitae</h2>
      <p class="mb-6">Download my complete CV to learn more about my academic background, professional journey, and technical expertise.</p>
      <a href="CURRICULUM VITAE- ABDULATEEF AYOOLA MOBOLAJI.pdf" class="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700">Download CV</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-6 text-blue-600">📬 Contact Me</h2>
      <p class="mb-6">Let’s connect! Reach out for collaborations, opportunities, or just to say hi.</p>
      <div class="space-y-2">
        <p>Email: <a href="mailto:mobolajiayoola3@gmail.com">mobolajiayoola3@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/mobolajiabdulateef/">LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/Iamoptimistic">GitHub</a></p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center">
    <p>✨ Built by <strong class="text-blue-300">Mobolaji Abdulateef</strong> | Data Science & Biomedical Research ✨</p>
  </footer>

  <script>
    function scrollGallery(amount) {
      document.getElementById('galleryContainer').scrollBy({
        left: amount,
        behavior: 'smooth'
      });
    }

    // Active section highlighting
    const sections = document.querySelectorAll("section");
    const navLinks = document.querySelectorAll(".nav-link");

    window.addEventListener("scroll", () => {
      let current = "";
      sections.forEach(section => {
        const sectionTop = section.offsetTop - 100;
        if (scrollY >= sectionTop) {
          current = section.getAttribute("id");
        }
      });
      navLinks.forEach(link => {
        link.classList.remove("active");
        if (link.getAttribute("href") === "#" + current) {
          link.classList.add("active");
        }
      });
    });
  </script>
</body>
</html>
