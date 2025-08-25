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
      background: linear-gradient(to right, #000000, #3B5B2A);
      color: #e5e7eb;
    }
    section {
      background: transparent;
    }
    .card {
      background: rgba(59, 91, 42, 0.8);
      color: #f9fafb;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(0, 255, 100, 0.6);
    }
    a, button, img {
      transition: all 0.3s ease-in-out;
    }
    a:hover, button:hover {
      color: #22c55e;
      text-shadow: 0 0 10px #22c55e;
    }
    img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px rgba(0, 255, 100, 0.6);
    }
    header, footer {
      background: #000000;
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
      background: rgba(0, 0, 0, 0.6);
      color: #22c55e;
      padding: 0.5rem;
      border-radius: 50%;
      cursor: pointer;
      z-index: 10;
    }
    .gallery-btn:hover {
      background: rgba(34, 197, 94, 0.8);
      color: white;
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
    <nav class="container mx-auto flex justify-between items-center p-4 text-gray-200">
      <h1 class="text-xl font-bold text-green-400">Mobolaji Abdulateef</h1>
      <ul class="flex space-x-6 font-medium">
        <li><a href="#home">Home</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#research">Research</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#cv">CV</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="pt-32 pb-20 text-center">
    <div class="container mx-auto">
      <h2 class="text-5xl font-extrabold mb-6 text-green-400">Welcome to My Portfolio</h2>
      <p class="text-lg max-w-2xl mx-auto mb-8">I am <strong>Mobolaji Abdulateef</strong>, a Data Scientist and Biomedical Research Enthusiast. I specialize in <strong>Data Analysis, Visualization, and Predictive Modelling</strong> using Python and Power BI.</p>
      <a href="#portfolio" class="bg-green-600 text-white px-6 py-3 rounded-lg shadow hover:bg-green-700 font-semibold">Explore My Work</a>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-20">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-green-400">📊 Portfolio Projects</h2>
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
  <section id="research" class="py-20">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-green-400">📑 Research Interests</h2>
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
  <section id="gallery" class="py-20">
    <div class="container mx-auto text-center mb-12">
      <h2 class="text-4xl font-bold mb-4 text-green-400">🖼️ Gallery</h2>
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
  <section id="cv" class="py-20">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-4 text-green-400">📄 Curriculum Vitae</h2>
      <p class="mb-6">Download my complete CV to learn more about my academic background, professional journey, and technical expertise.</p>
      <a href="CURRICULUM VITAE- ABDULATEEF AYOOLA MOBOLAJI.pdf" class="bg-green-600 text-white px-6 py-3 rounded-lg shadow hover:bg-green-700">Download CV</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-6 text-green-400">📬 Contact Me</h2>
      <p class="mb-6">Let’s connect! Reach out for collaborations, opportunities, or just to say hi.</p>
      <div class="space-y-2">
        <p>Email: <a href="mailto:mobolajiayoola3@gmail.com">mobolajiayoola3@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/mobolajiabdulateef/">LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/Iamoptimistic">GitHub</a></p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-400">
    <p>✨ Built by <strong class="text-green-400">Mobolaji Abdulateef</strong> | Data Science & Biomedical Research ✨</p>
  </footer>

  <script>
    function scrollGallery(amount) {
      document.getElementById('galleryContainer').scrollBy({
        left: amount,
        behavior: 'smooth'
      });
    }
  </script>
</body>
</html>
