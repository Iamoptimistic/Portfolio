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
  </style>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">
  <!-- Navigation Bar -->
  <header class="bg-white shadow-md fixed top-0 w-full z-50">
    <nav class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-xl font-bold text-blue-600">Mobolaji Abdulateef</h1>
      <ul class="flex space-x-6 font-medium">
        <li><a href="#home" class="hover:text-blue-500">Home</a></li>
        <li><a href="#portfolio" class="hover:text-blue-500">Portfolio</a></li>
        <li><a href="#research" class="hover:text-blue-500">Research</a></li>
        <li><a href="#gallery" class="hover:text-blue-500">Gallery</a></li>
        <li><a href="#cv" class="hover:text-blue-500">CV</a></li>
        <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home" class="pt-28 pb-16 container mx-auto text-center">
    <h2 class="text-4xl font-bold mb-4">Welcome to My Data Science Portfolio 👋</h2>
    <p class="text-lg max-w-2xl mx-auto mb-6">I am <strong>Mobolaji Abdulateef</strong>, a Data Scientist and Biomedical Research Enthusiast with expertise in <strong>Data Analysis, Visualization, and Predictive Modelling</strong>. My passion is using data to solve real-world challenges in health care, sustainability, and technology.</p>
    <p class="max-w-2xl mx-auto">Here you’ll find my projects, research interests, gallery of work, and professional details. Explore each section using the menu above.</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-16 bg-gray-100">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">📊 Portfolio Projects</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <!-- Project 1 -->
        <div class="bg-white shadow rounded-xl p-6">
          <h3 class="text-xl font-semibold mb-2">Employee Promotion Prediction</h3>
          <p class="mb-4">A machine learning system that predicts employee promotions using HR metrics to improve fairness, transparency, and efficiency in promotion decisions.</p>
          <p class="text-sm text-gray-600 mb-2">Tools: Python, Pandas, Scikit-learn, Matplotlib</p>
          <img src="AUC.png" alt="Model" class="rounded-lg shadow">
        </div>
        <!-- Project 2 -->
        <div class="bg-white shadow rounded-xl p-6">
          <h3 class="text-xl font-semibold mb-2">Abalone Age Prediction</h3>
          <p class="mb-4">Predicting the age of abalones using physical features and ML models to support sustainable fisheries and conservation efforts.</p>
          <p class="text-sm text-gray-600 mb-2">Tools: Python, Scikit-learn, Matplotlib</p>
          <img src="Figure_1.png" alt="Abalone Visualization" class="rounded-lg shadow">
        </div>
        <!-- Project 3 -->
        <div class="bg-white shadow rounded-xl p-6">
          <h3 class="text-xl font-semibold mb-2">Data Cleaning Task with Python</h3>
          <p class="mb-4">Cleaned and prepared a Kaggle movies dataset, addressing missing values, duplicates, and formatting issues to ensure analysis accuracy.</p>
          <p class="text-sm text-gray-600 mb-2">Tools: Python, Pandas, Seaborn</p>
          <img src="Print.png" alt="Data Cleaning" class="rounded-lg shadow">
        </div>
        <!-- Project 4 -->
        <div class="bg-white shadow rounded-xl p-6">
          <h3 class="text-xl font-semibold mb-2">Amazon Social Media Marketing in Nigeria</h3>
          <p class="mb-4">Power BI visualization analyzing Amazon’s social media influence in Nigeria through customer engagement and purchasing trends.</p>
          <p class="text-sm text-gray-600 mb-2">Tools: PowerBI</p>
          <img src="Amazon.png" alt="Amazon Visualization" class="rounded-lg shadow">
        </div>
      </div>
    </div>
  </section>

  <!-- Research Section -->
  <section id="research" class="py-16 container mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">📑 Research Interests</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-white p-6 shadow rounded-xl">
        <h3 class="text-xl font-semibold mb-2">Biomedical Research</h3>
        <p>I study computational neuroscience, sleep patterns, and mental health, applying machine learning methods to healthcare data for better insights and interventions.</p>
      </div>
      <div class="bg-white p-6 shadow rounded-xl">
        <h3 class="text-xl font-semibold mb-2">Sustainable Development & Health</h3>
        <p>Exploring how data-driven solutions can promote the Sustainable Development Goals (SDGs), particularly in antimicrobial resistance, public health, and diagnostics.</p>
      </div>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="py-16 bg-gray-100">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">🖼️ Gallery</h2>
      <p class="text-center mb-6">Here are some snapshots from my projects, visualizations, and research outputs.</p>
      <div class="grid md:grid-cols-3 gap-6">
        <img src="AUC.png" class="rounded-lg shadow" alt="Gallery Image 1">
        <img src="Figure_1.png" class="rounded-lg shadow" alt="Gallery Image 2">
        <img src="Amazon.png" class="rounded-lg shadow" alt="Gallery Image 3">
      </div>
    </div>
  </section>

  <!-- CV Section -->
  <section id="cv" class="py-16 container mx-auto text-center">
    <h2 class="text-3xl font-bold mb-4">📄 Curriculum Vitae</h2>
    <p class="mb-6">Download my full CV for details on my academic background, skills, and professional experience.</p>
    <a href="CURRICULUM VITAE- ABDULATEEF AYOOLA MOBOLAJI.pdf" class="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700">Download CV</a>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-16 bg-gray-100">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">📬 Contact Me</h2>
      <p class="mb-4">I’d love to connect! Feel free to reach out for collaborations, research opportunities, or data science projects.</p>
      <p>Email: <a href="mailto:mobolajiayoola3@gmail.com" class="text-blue-600">mobolajiayoola3@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/mobolajiabdulateef/" class="text-blue-600">LinkedIn Profile</a></p>
      <p>GitHub: <a href="https://github.com/Iamoptimistic" class="text-blue-600">GitHub</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white py-6 text-center border-t">
    <p>✨ Built by <strong>Mobolaji Abdulateef</strong> | Data Science & Biomedical Research ✨</p>
  </footer>
</body>
</html>
