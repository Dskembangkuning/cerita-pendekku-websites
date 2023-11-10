# cerita-pendekku-websites
<!DOCTYPE html>
<html>
<head>
    <title>Website Cerita Pendekku</title>
    <!-- Tambahkan link CSS untuk Bootstrap -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-JZR6e5i5aB3WuKT8C1D6x6N1tPd9z4g6d4lFhRiP2YccDzR/5Jf5o7k4voZbZ85+g" crossorigin="anonymous">

    <style>
        /* Ganti warna tautan menjadi biru, hijau, dan pink */
        a {
            color: blue;
        }

        a:hover {
            color: green;
        }

        a:active {
            color: pink;
        }

        /* Tambahkan latar belakang dengan gradasi tiga warna */
        body {
            background: linear-gradient(to right, #00bfff, #00ff00, #ff1493);
            font-family: 'Comic Sans MS', sans-serif;
        }

        /* Gaya untuk kartu profil */
        .profile-card {
            border: 1px solid #ccc;
            border-radius: 10px;
            padding: 10px;
            text-align: center;
            background: linear-gradient(to right, #FFD700, #FFA500);
            margin-bottom: 20px;
        }

        .profile-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 10px auto;
        }

        .profile-name {
            font-size: 24px;
            font-weight: bold;
        }

        .profile-description {
            font-size: 16px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <div class="profile-card">
        <img class="profile-image" src="img/profil.jpg" alt="Foto Profil">
        <h1 class="profile-name">KertasBiru</h1>
    </div>
    <h1>Selamat Datang di Website Cerita Pendekku</h1>
    <nav>
        <ul>
            <li><a href="#">Beranda</a></li>

            <li><a href="cerita1.html" target="_blank">Cerita 1</a></li>
            <li><a href="cerita2.html" target="_blank">Cerita 2</a></li>
            <li><a href="cerita3.html" target="_blank">Cerita 3</a></li>
        </ul>
    </nav>
    
</header>

<main>
    <article>
        <h2>Cerita Pertamaku</h2>
        <p>Deskripsi Cerita Pertamaku.</p>
        <a href="https://www.youtube.com/watch?v=VIDEO_ID">Ceritaku di YouTube</a>
    </article>

    <article>
        <h2>Cerita Keduaku</h2>
        <p>Deskripsi Cerita Keduaku.</p>
        <a href="https://www.tiktok.com/@kertasbiru2023?_t=8hELr5aXJ1b&_r=1">Ceritaku di TikTok</a>
    </article>

    <!-- Artikel berita lainnya dapat ditambahkan di sini -->
</main>

<footer>
    <p>Hak Cipta © 2023 Website Cerita Pendekku</p>
</footer>

<!-- Tambahkan skrip JavaScript untuk Bootstrap (opsional) -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js" integrity="sha384-D7X5H6U/7Gl+ZrC7upUAJzVxGgZxto4FFlKR5Bgh4LXQqK52Pm/6MGvaE6x1twBq" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrZXEmTTYSY6lxfF5r5l3bHvELvbv4WlFdVU/5CFUJqN1iAZTL2owWQujJT" crossorigin="anonymous"></script>

</body>
</html>
