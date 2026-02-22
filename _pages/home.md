---
layout: page
title: "Yinan Liu"
permalink: /
---

<nav style="display: flex; justify-content: center; gap: 2rem; margin-bottom: 30px; flex-wrap: wrap;">
  <a href="#about">About</a>
  <a href="#publications">Publications</a>
  <a href="#educations">Education</a>
  <a href="#internships">Internships</a>
  <a href="#honors">Honors</a>
</nav>

<h2 id="about">👋 About Me</h2>
<p>Hi! I am <strong>Yinan Liu (刘易楠)</strong>, a Ph.D. student at <strong>Tongji University</strong>, Shanghai, China.</p>
<p>My research focuses on <strong>Medical Image Analysis</strong> and <strong>Multimodal Large Language Models</strong>.</p>

<h2 id="educations">🎓 Education</h2>
<ul>
  <li><strong>Tongji University</strong> — Ph.D. in Software Engineering (Sep 2024 – Present)</li>
  <li><strong>UESTC</strong> — B.S. in Geographic Information Science (Sep 2020 – Jun 2024)</li>
</ul>

<h2 id="publications">📄 Publications</h2>
<div style="background: #f0f9ff; padding: 15px; border-radius: 8px; margin-bottom: 15px;">
  <strong>Power Line Detection Based on Maxtree and Graph Signal Processing</strong><br>
  Liu, Y., et al. — IGARSS 2023, IEEE<br>
  <a href="https://ieeexplore.ieee.org/document/10282535">📄 Paper</a>
</div>

<h2 id="internships">💼 Internships</h2>
<ul>
  <li><strong>Research Intern</strong> — CAS, Jun 2023 – Aug 2023</li>
  <li><strong>Data Science Intern</strong> — Huawei, Jul 2022 – Sep 2022</li>
</ul>

<h2 id="honors">🏆 Honors</h2>
<ul>
  <li>National Scholarship for Graduate Students (2024)</li>
  <li>Tongji University Outstanding Graduate Award (2023)</li>
</ul>

<script>
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', e => {
    e.preventDefault();
    document.getElementById(e.target.getAttribute('href').slice(1))?.scrollIntoView({behavior: 'smooth'});
  });
});
</script>
