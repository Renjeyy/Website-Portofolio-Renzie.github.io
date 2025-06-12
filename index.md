<!-- Styling untuk memperlebar konten dan menata navigasi -->
<style>
/* Perlebar konten utama */
.page-content {
  max-width: 1000px !important;
  width: 90%;
  margin: 0 auto;
}

/* Navigasi sticky di atas */
nav {
  background-color: #f2f2f2;
  padding: 1em;
  position: sticky;
  top: 0;
  z-index: 1000;
  border-bottom: 1px solid #ccc;
}
nav ul {
  list-style-type: none;
  display: flex;
  gap: 2em;
  justify-content: center;
  margin: 0;
  padding: 0;
}
nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}
section {
  padding: 2em 0;
}
h2 {
  border-bottom: 2px solid #ccc;
  padding-bottom: 0.5em;
}
</style>

<!-- Navigasi -->
<nav>
  <ul>
    <li><a href="#about-me">About Me</a></li>
    <li><a href="#projects">Projects and Publications</a></li>
    <li><a href="#experiences">Experiences</a></li>
  </ul>
</nav>

<!-- Bagian konten -->
<section id="about-me">
  ## About Me
  ### Summary
  Saya adalah mahasiswa FMIPA Universitas Indonesia dengan ketertarikan di bidang pengembangan perangkat lunak, machine learning, dan teknologi open source. Saya senang membangun solusi praktis berbasis teknologi dan aktif dalam pengembangan proyek pribadi maupun kolaboratif.

  ### Expertise
  - Pemrograman: Python, JavaScript, HTML/CSS
  - Web Development: React, Node.js, Jekyll
  - Data Science: Pandas, scikit-learn, matplotlib
  - Tools: Git, VS Code, Figma

  ### Education
  - **Universitas Indonesia** – S1 Ilmu Komputer (2021–sekarang)  
    Fokus pada kecerdasan buatan, rekayasa perangkat lunak, dan data mining.
</section>

<section id="projects">
  ## Projects and Publications
  - **Website Portofolio** – Dibuat menggunakan GitHub Pages dan Jekyll.
  - **Publikasi** – "Analisis Algoritma Machine Learning untuk Prediksi X", dipublikasikan di Jurnal Informatika, 2022.
</section>

<section id="experiences">
  ## Experiences
  - **Internship di PT Teknologi Hebat** – Software Engineer Intern (2023)
  - **Asisten Dosen** – Struktur Data dan Algoritma (2022–2023)
</section>
