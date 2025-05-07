<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ruby dan Jekyll</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0d1117;
      color: #e6f1ff;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 50px 20px 20px;
    }

    header h1 {
      font-size: 3rem;
      color: #00ffff;
      text-shadow: 0 0 10px #00ffff88;
    }

    .content {
      max-width: 900px;
      margin: 30px auto;
      background-color: #161b22;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px #00ffff33;
    }

    h2, h3, h4 {
      color: #00ffff;
      text-shadow: 0 0 5px #00ffffaa;
    }

    h2 {
      font-size: 1.8em;
      margin-bottom: 10px;
    }

    h3 {
      font-size: 1.4em;
      margin: 25px 0 10px;
    }

    h4 {
      font-size: 1.2em;
      margin: 20px 0 10px;
    }

    p {
      font-size: 1.1em;
      margin-bottom: 16px;
      color: #c9d1d9;
    }

    ul {
      margin: 15px 0;
      padding-left: 25px;
    }

    li {
      margin-bottom: 12px;
      font-size: 1.05em;
      color: #e6f1ff;
    }

    a {
      color: #00ffff;
      text-decoration: underline;
    }

    .image {
      width: 100%;
      max-width: 500px;
      display: block;
      margin: 25px auto;
      border-radius: 12px;
      box-shadow: 0 0 10px #00ffff44;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }

      nav {
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Ruby dan Jekyll</h1>
  </header>

  <!-- Content -->
  <section class="content">
    <h2>Penjelasan Ruby dan Jekyll</h2>

    <h3>Apa itu Ruby?</h3>
    <p>Ruby adalah bahasa pemrograman dinamis dan berorientasi objek yang terkenal karena sintaksnya yang bersih dan mudah dibaca. Ruby sangat populer di kalangan pengembang web karena framework-nya seperti Ruby on Rails, dan juga karena menjadi dasar dari Jekyll.</p>

    <h4>Fungsi Utama Ruby</h4>
    <ul>
      <li><strong>Pengembangan Web:</strong> Digunakan dalam framework Ruby on Rails untuk membangun aplikasi web.</li>
      <li><strong>Skrip Otomatisasi:</strong> Cocok untuk membuat skrip guna mempermudah tugas-tugas berulang.</li>
      <li><strong>Aplikasi CLI:</strong> Bisa digunakan untuk membuat aplikasi berbasis command line.</li>
      <li><strong>Prototyping Cepat:</strong> Sintaks yang sederhana mempercepat pembuatan prototipe aplikasi.</li>
      <li><strong>Sistem Paket (Gem):</strong> Ruby menggunakan "gem" untuk manajemen pustaka dan ekstensi.</li>
    </ul>

    <h3>Apa itu Jekyll?</h3>
    <p>Jekyll adalah static site generator berbasis Ruby yang digunakan untuk membuat website statis seperti blog atau dokumentasi. Jekyll cocok untuk pengembang yang ingin membangun situs tanpa database dan backend.</p>

    <h4>Fungsi Utama Jekyll</h4>
    <ul>
      <li><strong>Membangun Website Statis:</strong> Mengubah file Markdown menjadi HTML secara otomatis.</li>
      <li><strong>Blogging Tanpa CMS:</strong> Menulis postingan cukup dengan file <code>.md</code>, tanpa panel admin.</li>
      <li><strong>Integrasi GitHub Pages:</strong> Bisa langsung di-host di GitHub Pages tanpa konfigurasi tambahan.</li>
      <li><strong>Layout dan Template:</strong> Memungkinkan penggunaan layout yang konsisten antar halaman.</li>
      <li><strong>Konfigurasi Sederhana:</strong> Menggunakan file <code>_config.yml</code> untuk mengatur isi dan struktur situs.</li>
    </ul>

    <h3>Gambar Terkait</h3>
    <a href="/assets/images/ruby.jpg" target="_blank">
    <img src="/assets/images/ruby.jpg" alt="Ruby" class="image" />
   </a>
    <a href="/assets/images/jekyll.jpg" target="_blank">
    <img src="/assets/images/jekyll.jpg" alt="Jekyll" class="image" />
   </a>
  </section>

</body>
</html>
