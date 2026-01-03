---
layout: base
title: Home
permalink: /
---

<!-- ===== HERO SECTION ===== -->
<section class="hero split py-20">
  <div class="container hero-grid flex flex-col md:flex-row items-center gap-10">

  <!-- Text Block -->
  <div class="hero-text-block md:w-1/2">
      <h1 class="text-4xl md:text-5xl font-bold text-teal-800 mb-4"> Athena Amancio-Alsobrook.</h1>
      <h2 class="text-xl md:text-2xl font-semibold text-teal-600 mb-6">Sport Science · Exercise Physiology · Data</h2>
      <p class="text-gray-700 mb-6">
        I explore human performance and athlete well-being through sport science, research, 
        and data-driven insights. I’m passionate about turning data into actionable improvements 
        for athletes.
      </p>
      <div class="hero-buttons flex flex-wrap gap-4">
        <a href="/projects" class="px-6 py-3 bg-blue-600 text-white rounded-lg font-semibold hover:bg-blue-700 transition">View Projects</a>
        <a href="/about" class="px-6 py-3 bg-blue-300 text-teal-800 rounded-lg font-semibold hover:bg-blue-400 transition">About Me</a>
      </div>
    </div>

  <!-- Hero Image -->
  <div class="hero-image md:w-1/2">
      <img src="{{ '/static/sportathena.jpg'  | relative_url }}" alt="Athena working in sport science" class="rounded-xl shadow-lg">
    </div>

  </div>
</section>

<!-- ===== AREAS OF FOCUS ===== -->
<section class="section py-16 bg-white">
  <div class="container text-center">
    <h3 class="text-3xl font-bold text-teal-800 mb-8">Areas I Focus On</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="card p-6 bg-teal-50 rounded-xl shadow hover:shadow-lg transition">
        <h4 class="text-xl font-semibold mb-2 text-teal-700">Sport Science</h4>
        <p>Monitoring and optimizing athlete performance in real-world environments.</p>
      </div>
      <div class="card p-6 bg-teal-50 rounded-xl shadow hover:shadow-lg transition">
        <h4 class="text-xl font-semibold mb-2 text-teal-700">Sports Medicine</h4>
        <p>Injury prevention, rehabilitation, and long-term athlete care.</p>
      </div>
      <div class="card p-6 bg-teal-50 rounded-xl shadow hover:shadow-lg transition">
        <h4 class="text-xl font-semibold mb-2 text-teal-700">Data & Research</h4>
        <p>Analyzing and visualizing sport and health data to support evidence-based decisions.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== FEATURED PROJECTS ===== -->
<section class="section py-16 bg-gradient-to-b from-teal-50 to-white">
  <div class="container text-center">
    <h3 class="text-3xl font-bold text-teal-800 mb-8">Featured Projects</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="card p-6 bg-white rounded-xl shadow hover:shadow-lg transition">
        <img src="/assets/images/project1.jpg" alt="Project 1" class="rounded-lg mb-4">
        <h4 class="text-xl font-semibold mb-2">Athlete Performance Dashboard</h4>
        <p>A data visualization tool for monitoring training load and recovery.</p>
      </div>
      <div class="card p-6 bg-white rounded-xl shadow hover:shadow-lg transition">
        <img src="/assets/images/project2.jpg" alt="Project 2" class="rounded-lg mb-4">
        <h4 class="text-xl font-semibold mb-2">Injury Rehab Tracker</h4>
        <p>An interactive tracker to manage athlete rehabilitation programs.</p>
      </div>
      <div class="card p-6 bg-white rounded-xl shadow hover:shadow-lg transition">
        <img src="/assets/images/project3.jpg" alt="Project 3" class="rounded-lg mb-4">
        <h4 class="text-xl font-semibold mb-2">Sports Science Research</h4>
        <p>Analyzing performance and recovery trends using R and Python.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== TESTIMONIAL / QUOTE BLOCK
<section class="section py-16 bg-teal-100">
  <div class="container text-center max-w-3xl mx-auto">
    <blockquote class="text-xl italic text-teal-900 mb-4">
      "Athena brings unmatched energy and insight to sport science research, blending data with practical athlete care."
    </blockquote>
    <p class="font-semibold text-teal-700">– Coach / Collaborator</p>
  </div>
</section> ===== -->

<!-- ===== CALL TO ACTION / CONTACT ===== -->
<section id="contact" class="section py-16 bg-white">
  <div class="container text-center">
    <h3 class="text-3xl font-bold text-teal-800 mb-4">Let’s Connect</h3>
    <p class="text-gray-700 mb-6">Feel free to reach out via email or check out my work online.</p>
    <div class="flex justify-center gap-4 flex-wrap">
      <a href="mailto:aamancioalsobrook@gmail.com" class="px-6 py-3 bg-blue-600 text-white rounded-lg font-semibold hover:bg-blue-700 transition">Email</a>
      <a href="https://www.linkedin.com/in/athena-a-alsobrook-133b731b0/" target="_blank" class="px-6 py-3 bg-blue-300 text-teal-800 rounded-lg font-semibold hover:bg-blue-400 transition">LinkedIn</a>
      <a href="https://github.com/Thena03" target="_blank" class="px-6 py-3 bg-blue-300 text-teal-800 rounded-lg font-semibold hover:bg-blue-400 transition">GitHub</a>
    </div>
  </div>
</section>

