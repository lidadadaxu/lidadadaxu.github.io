---
layout: profile
profile_home: true
permalink: /
title: "Mingxu Li"
excerpt: "Assistant Researcher at the China Academy of Railway Sciences. Computer vision for railway inspection, defect segmentation and efficient inference."
redirect_from:
  - /about/
  - /about.html
---

<section class="hero" aria-labelledby="profile-name">
  <div class="hero-intro">
    <p class="eyebrow">Computer vision · Railway infrastructure</p>
    <h1 id="profile-name">Mingxu Li</h1>
    <p class="hero-role">Assistant Researcher<span>China Academy of Railway Sciences</span></p>
  </div>
  <figure class="hero-portrait">
    <img src="{{ '/images/IMG_9431.jpg' | relative_url }}" alt="Portrait of Mingxu Li" width="238" height="286">
    <figcaption>Infrastructure Inspection<br>Research Institute</figcaption>
  </figure>
  <div class="hero-main">
    <h2>Computer vision for railway inspection</h2>
    <p>I study how to detect small defects and segment their boundaries with limited data and computing resources. My work spans railway catenary and rail-surface inspection, from low-power screening to detailed recognition.</p>
    <div class="hero-actions">
      <a class="button button-primary" href="{{ '/files/Mingxu_Li_CV.pdf' | relative_url }}">Download CV <span aria-hidden="true">↓</span></a>
      <a class="button button-secondary" href="mailto:lidadaxu@hotmail.com">Email me <span aria-hidden="true">↗</span></a>
    </div>
    <div class="hero-links" aria-label="Research profiles">
      <a href="{{ site.author.googlescholar }}">Google Scholar ↗</a>
      <a href="https://github.com/lidadadaxu">GitHub ↗</a>
      <a href="https://www.linkedin.com/in/mingxu-li-1a52b3443/">LinkedIn ↗</a>
    </div>
  </div>
</section>

<section id="research" aria-label="Featured research">
  <div class="featured-paper">
    <div>
      <p class="eyebrow">Latest publication · IEEE TITS, 2026</p>
      <h2>S2R: from screening<br>to recognition</h2>
      <p>Low-power screening triggers detailed segmentation when a potential defect is found. S2R combines spiking and convolutional neural networks, with contrastive learning and hard-sample mining to distinguish defects from background interference.</p>
      <a href="https://doi.org/10.1109/TITS.2026.3694462">Read the paper <span aria-hidden="true">↗</span></a>
    </div>
    <figure class="featured-figure">
      <img src="{{ '/images/power_comp.png' | relative_url }}" alt="Segmentation IoU and relative energy consumption for the methods compared in the railway inspection study" width="878" height="700">
      <figcaption>Segmentation quality and relative energy consumption under the study's evaluation conditions.</figcaption>
    </figure>
  </div>
</section>

<section class="section" aria-labelledby="results-heading">
  <div class="section-heading">
    <div><p class="eyebrow">Selected research results</p><h2 id="results-heading">Efficient, detailed perception</h2></div>
  </div>
  <div class="research-results">
    <article class="research-result">
      <span class="result-number">71 <small>FPS on Jetson Nano</small></span>
      <h3>Surface-defect segmentation in latent space</h3>
      <p>Reduced computation by segmenting defects in the decoder latent space, with improved few-shot accuracy over the evaluated baselines.</p>
      <a href="https://doi.org/10.1109/TIM.2024.3446650">IEEE Transactions on Instrumentation and Measurement, 2024 ↗</a>
    </article>
    <article class="research-result">
      <span class="result-number">2.36<small>M parameters</small></span>
      <h3>RBNet for railway defect segmentation</h3>
      <p>A rendering-inspired architecture that moves from a coarse prediction to fine defect boundaries while keeping the model lightweight.</p>
      <a href="https://doi.org/10.1109/TIM.2023.3269107">IEEE Transactions on Instrumentation and Measurement, 2023 ↗</a>
    </article>
  </div>
</section>

<section class="section about-experience" aria-labelledby="about-heading">
  <div class="about-panel">
    <p class="eyebrow">Background</p>
    <h2 id="about-heading">About me</h2>
    <p>I received my Ph.D. in Computer Science from Southwest Jiaotong University in June 2026. During my doctorate, I completed joint research at Nanyang Technological University (August 2024–December 2025) and the University of Birmingham (January–August 2024).</p>
    <p>I also hold an M.Eng. in Software Engineering and a B.Eng. in Internet of Things Engineering. My other research includes road-crack recognition, multi-vehicle tracking and contour-guided restoration of Thangka artworks and Tibetan murals.</p>
    <a href="{{ '/cv/' | relative_url }}">Education, projects and honors ↗</a>
  </div>
  <div class="experience-panel">
    <h3>Research &amp; industry experience</h3>
    <div class="experience-entry">
      <h4>China Academy of Railway Sciences</h4>
      <p>Assistant Researcher · Railway visual inspection</p>
      <time>September 2026–present</time>
    </div>
    <div class="experience-entry">
      <h4>The Alan Turing Institute</h4>
      <p>AI Research Intern · Participated in data analysis for a Mastercard prediction project</p>
      <time>May 2024</time>
    </div>
    <div class="experience-entry">
      <h4>Tencent WeChat Group</h4>
      <p>Test Development Intern · Automated JSAPI testing for WeChat Work</p>
      <time>April–July 2021</time>
    </div>
  </div>
</section>

<section class="section" aria-labelledby="publications-heading">
  <div class="section-heading">
    <div><p class="eyebrow">Research papers</p><h2 id="publications-heading">Selected publications</h2></div>
    <a href="{{ '/publications/' | relative_url }}">View all {{ site.data.publications | size }} publications ↗</a>
  </div>
  {% include publications-list.html selected=true %}
</section>

<section class="contact-section" aria-label="Contact">
  <div><p class="eyebrow">Contact</p><p>For research collaboration and professional enquiries.</p></div>
  <a href="mailto:lidadaxu@hotmail.com">lidadaxu@hotmail.com ↗</a>
</section>
