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
      <h1 class="text-4xl md:text-5xl font-bold text-slate-900 mb-4">Athena Amancio-Alsobrook</h1>
      <h2 class="text-xl md:text-2xl font-semibold text-teal-700 mb-6">Sport Science · Data · Social Impact</h2>
      <p class="text-slate-700 mb-6">
        I explore human performance and athlete well-being through sport science, research, 
        and data-driven insights. I am passionate about turning data into actionable improvements 
        for athletes.
      </p>
      <div class="hero-buttons flex flex-wrap gap-4">
        <a href="{{ '/projects/' | relative_url }}" class="px-6 py-3 bg-teal-700 text-white rounded-lg font-semibold hover:bg-teal-800 transition">View Projects</a>
        <a href="{{ '/about/' | relative_url }}" class="px-6 py-3 bg-teal-100 text-teal-900 rounded-lg font-semibold hover:bg-teal-200 transition">About Me</a>
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
    <h3 class="text-3xl font-bold text-slate-900 mb-8">Areas I Focus On</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="card p-6 bg-teal-50 rounded-xl shadow hover:shadow-lg transition">
        <h4 class="text-xl font-semibold mb-2 text-teal-700">Sport Science</h4>
        <p class="text-slate-700">Monitoring and optimizing athlete performance in real-world environments.</p>
      </div>
      <div class="card p-6 bg-teal-50 rounded-xl shadow hover:shadow-lg transition">
        <h4 class="text-xl font-semibold mb-2 text-teal-700">Sports Medicine</h4>
        <p class="text-slate-700">Injury prevention, rehabilitation, and long-term athlete care.</p>
      </div>
      <div class="card p-6 bg-teal-50 rounded-xl shadow hover:shadow-lg transition">
        <h4 class="text-xl font-semibold mb-2 text-teal-700">Data & Research</h4>
        <p class="text-slate-700">Analyzing and visualizing sport and health data to support evidence-based decisions.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== FEATURED PROJECTS ===== -->
<section class="section py-16 bg-gradient-to-b from-teal-50 to-white">
  <div class="container text-center">
    <h3 class="text-3xl font-bold text-slate-900 mb-8">Featured Projects</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="card p-6 bg-white rounded-xl shadow hover:shadow-lg transition">
        <img src="{{ '/static/LearnRlogo.png' | relative_url }}" alt="Project 1" class="rounded-lg mb-4">
        <h4 class="text-xl font-semibold mb-2 text-slate-900">LearnR Coding</h4>
        <p class="text-slate-700">educational platform designed to make learning R programming practical for all coders regardless of skill level.</p>
             <a href="https://learnrcoding.com" target="_blank"
             class="px-5 py-3 rounded-xl bg-teal-700 text-white font-medium hover:bg-teal-600 transition">
            Visit Website
          </a>
      </div>
      <div class="card p-6 bg-white rounded-xl shadow hover:shadow-lg transition">
        <img src="{{ '/static/DAISI.jpg' | relative_url }}" alt="Project 2" class="rounded-lg mb-4">
        <h4 class="text-xl font-semibold mb-2 text-slate-900"> Digital Solutions for Sustainable Agriculture with RuRall</h4>
        <p class="text-slate-700">Supported the Northern Italian agricultural company, RuRall, with promoting sustainable farming practices across Europe.</p>
      </div>
      <div class="card p-6 bg-white rounded-xl shadow hover:shadow-lg transition">
        <img src="{{ '/static/40yard.png' | relative_url }}" alt="Project 3" class="rounded-lg mb-4">
        <h4 class="text-xl font-semibold mb-2 text-slate-900"> The Sprint to the Draft: Evaluating the 40 Yard Dash's Impact on Wide Receiver Draft Selection</h4>
        <p class="text-slate-700">Correlational Analysis investigating whether 40-yard dash times significantly influence wide receiver draft outcomes.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== CALL TO ACTION / CONTACT ===== -->
<section id="contact" class="section py-16 bg-white">
  <div class="container text-center">
    <h3 class="text-3xl font-bold text-slate-900 mb-4">Let’s Connect</h3>
    <p class="text-slate-700 mb-6">Feel free to reach out via email or check out my work online.</p>
    <div class="flex justify-center gap-4 flex-wrap">
      <a href="mailto:aamancioalsobrook@gmail.com" class="px-6 py-3 bg-teal-700 text-white rounded-lg font-semibold hover:bg-teal-800 transition">Email</a>
      <a href="https://www.linkedin.com/in/athena-a-alsobrook-133b731b0/" target="_blank" class="px-6 py-3 bg-teal-100 text-teal-900 rounded-lg font-semibold hover:bg-teal-200 transition">LinkedIn</a>
      <a href="https://github.com/Thena03" target="_blank" class="px-6 py-3 bg-teal-100 text-teal-900 rounded-lg font-semibold hover:bg-teal-200 transition">GitHub</a>
    </div>
  </div>
</section>
