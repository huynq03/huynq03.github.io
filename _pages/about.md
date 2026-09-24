---
layout: portfolio-home
permalink: /
title: Nguyen Quang Huy
redirect_from:
  - /about/
  - /about.html
---

<section class="portfolio-hero" aria-labelledby="hero-title">
  <div>
    <p class="portfolio-eyebrow">Robotics / Mechatronics</p>
    <h1 id="hero-title">Nguyen Quang Huy</h1>
    <p class="portfolio-hero__role">Robotics &amp; Mechatronics Engineer</p>
  </div>
  <div class="portfolio-hero__bottom">
    <p>I build robotic systems across hardware, control, simulation and learning-based control.</p>
    <div class="portfolio-links" aria-label="Contact links">
      <a href="https://github.com/huynq03">GitHub ↗</a>
      <a href="{{ '/files/Nguyen-Quang-Huy-CV.pdf' | relative_url }}">CV ↗</a>
      <a href="mailto:{{ site.author.email }}">Email ↗</a>
    </div>
  </div>
</section>

<section id="projects" class="portfolio-section" aria-labelledby="projects-title">
  <div class="portfolio-section__heading"><span class="portfolio-section__number">01</span><h2 id="projects-title">Projects</h2></div>
  <div class="portfolio-section__body">
    {% for project in site.data.projects %}
    <article class="portfolio-project">
      <span class="portfolio-project__index">/ {{ forloop.index | prepend: '0' | slice: -2, 2 }}</span>
      <div>
        <h3>{{ project.title }}</h3>
        <p>{{ project.description }}</p>
        <p class="portfolio-project__tech">{{ project.technology }}</p>
      </div>
    </article>
    {% endfor %}
  </div>
</section>

<section id="experience" class="portfolio-section" aria-labelledby="experience-title">
  <div class="portfolio-section__heading"><span class="portfolio-section__number">02</span><h2 id="experience-title">Experience</h2></div>
  <div class="portfolio-section__body">
    <article class="portfolio-experience"><p class="portfolio-experience__date">Mar – Jul 2024</p><div><h3>IoT Challenge 2024 · Team Member</h3><p class="portfolio-experience__organization">FPT Software, Hanoi (remote)</p><p>Researched and developed IoT solutions for building energy optimization systems.</p></div></article>
    <article class="portfolio-experience"><p class="portfolio-experience__date">May 2023 – Jan 2024</p><div><h3>Intern</h3><p class="portfolio-experience__organization">Brickone Institute of Technology</p><p>Programmed Arduino and designed a basic web interface for Wi-Fi control using ESP32.</p></div></article>
    <article class="portfolio-experience"><p class="portfolio-experience__date">Fall 2022 – present*</p><div><h3>Research and Development Intern</h3><p class="portfolio-experience__organization">R&amp;D Cimlab, Hanoi University of Science and Technology</p><p>Studied machining methods and graduation projects.</p></div></article>
    <p class="portfolio-note">* Dates reflect the existing CV and have not been recently verified.</p>
  </div>
</section>

<section id="about" class="portfolio-section" aria-labelledby="about-title">
  <div class="portfolio-section__heading"><span class="portfolio-section__number">03</span><h2 id="about-title">About</h2></div>
  <div class="portfolio-section__body portfolio-about">
    <p>I studied Mechatronics Engineering at Hanoi University of Science and Technology. My work spans robotics, control, reinforcement learning, embedded systems, and autonomous systems.</p>
    <dl><div><dt>Education</dt><dd>B.S. in Mechatronics Engineering<br>Hanoi University of Science and Technology<br>2021 – present*</dd></div><div><dt>Interests</dt><dd>Robotics · Control · Reinforcement Learning · Embedded Systems · Autonomous Systems</dd></div></dl>
    <p class="portfolio-note">* Education status reflects the existing CV and has not been recently verified.</p>
  </div>
</section>
