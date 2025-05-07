
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
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

        h2 {
            color: #00ffff;
            font-size: 1.8em;
            margin-bottom: 10px;
            text-shadow: 0 0 5px #00ffffaa;
        }

        p {
            font-size: 1.1em;
            margin-bottom: 16px;
            color: #c9d1d9;
        }

        ul {
            margin-top: 10px;
            padding-left: 25px;
        }

        ul li {
            margin-bottom: 12px;
            font-size: 1.05em;
            color: #e6f1ff;
        }

        strong {
            color: #00ffff;
        }

        .image {
         width: 100%;
         max-width: 400px;
         height: auto;
         border-radius: 10px;
         margin: 25px auto;
         display: block;
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
        <h1>JavaScript</h1>
    </header>

    <!-- Konten -->
    <section class="content">
        <h2>Penjelasan JavaScript</h2>
        <p>
            JavaScript adalah bahasa pemrograman yang digunakan di hampir semua situs web modern.
            Ia memungkinkan pengembang untuk membuat halaman web yang tidak hanya statis, tetapi juga dapat merespon aksi pengguna secara real-time.
            Bersama HTML dan CSS, JavaScript membentuk "tiga pilar" utama dalam pengembangan antarmuka web.
        </p>
        <p>
            JavaScript pertama kali dikembangkan oleh Netscape dan kini telah menjadi standar industri yang didukung oleh semua browser modern.
            JavaScript berjalan di sisi klien (browser) dan memungkinkan halaman web berinteraksi secara langsung dengan pengguna tanpa harus selalu mengirim data ke server.
        </p>

        <h2>Fungsi dan Kegunaan JavaScript</h2>
        <ul>
            <li><strong>Manipulasi Elemen HTML (DOM):</strong> Bisa menambah, menghapus, atau mengubah konten dan struktur HTML secara langsung di browser.</li>
            <li><strong>Menangani Interaksi Pengguna (Event Handling):</strong> Merespons aksi seperti klik, hover, scroll, atau input pengguna.</li>
            <li><strong>Validasi Formulir:</strong> Mengecek input pengguna sebelum data dikirim ke server, seperti mengecek email sudah diisi atau belum.</li>
            <li><strong>Menampilkan dan Menyembunyikan Konten:</strong> Bisa membuat popup, menu dropdown, tab, dan lainnya yang muncul saat dibutuhkan.</li>
            <li><strong>Mengambil Data dari Server (AJAX/Fetch):</strong> Mengambil atau mengirim data tanpa perlu me-*reload* halaman, contohnya menampilkan produk dari database langsung di halaman.</li>
            <li><strong>Membuat Efek Interaktif dan Animasi Ringan:</strong> Seperti slideshow gambar, highlight saat mouse diarahkan, dan animasi saat konten muncul.</li>
        </ul>

        <img src="/assets/images/javascript.jpg" alt="JavaScript" class="image">
    </section>

</body>
</html>
