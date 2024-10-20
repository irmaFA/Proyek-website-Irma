<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistem Persamaan Linear Dua Variabel</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* Mengatur desain global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        /* Mengatur lebar konten utama */
        .container {
            max-width: 900px;
            width: 100%;
            margin: 0 auto;
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 10px;
        }

        h1 {
            font-size: 22px;
            color: #1757fa;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }

        /* Section konten utama */
        h2 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #111111;
            border-bottom: 2px solid #a05c04e7;
            padding-bottom: 5px;
        }

        h3 {
            font-size: 18px;
            margin-bottom: 10px;
            color: #2c1c07e7;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 10px;
            text-align: justify;
            color: #000000;
        }

        ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }

        li {
            font-size: 16px;
            margin-bottom: 5px;
            color: #000000;
        }

        /* Responsif untuk tampilan mobile */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 22px;
            }

            h2 {
                font-size: 20px;
            }

            h3 {
                font-size: 18px;
            }

            p, li {
                font-size: 14px;
            }

            .container {
                padding: 10px;
            }

            iframe {
                min-height: 200px;
            }
        }

        /* Responsif untuk iframe video */
        iframe {
            max-width: 100%;
            height: auto;
            border: 0;
            border-radius: 8px;
        }

        /* Footer diatur dengan flexbox agar selalu di tengah halaman */
        footer {
            text-align: center;
            margin: 20px auto;
            font-size: 14px;
            color: #000;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-shrink: 0;
        }
        
    </style>
</head>
<body>
    <!-- Navbar Responsif dengan warna biru -->
    <nav class="navbar navbar-expand-lg bg-primary w-100">
        <div class="container-fluid">
            <a class="navbar-brand" href="spldvweb.html">HOME</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="materiweb.html">MATERI</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="mediaweb.html">MEDIA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="lembarkerjaweb.html">LEMBAR KERJA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="latihanweb.html">TUGAS</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>


    <div class="container">
        <h1>1. Sistem Persamaan Linear Dua Variabel</h1>
        <h3>Sebelum masuk pada materi, sebaiknya simak video berikut ini</h3>
        <div class="embed-responsive" style="position: relative; padding-bottom: 56.25%; height: 0;">
            <iframe src="https://www.youtube.com/embed/GbPkZ92QDLI?si=_i315cotaZa2bE_0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
        </div>
        
        <h2>Konsep Persamaan Linear Dua Variabel</h2>
        <p>Persamaan linier dua variabel adalah persamaan yang dapat dituliskan dalam bentuk:</p>
        <p><strong>Ax + By = C</strong></p>
        <p>Di mana:</p>
        <ul>
            <li><strong>A</strong>, <strong>B</strong>, dan <strong>C</strong> adalah bilangan tetap (konstanta).</li>
            <li><strong>x</strong> dan <strong>y</strong> adalah variabel.</li>
        </ul>
    
    
        <footer>
            &copy; 2024 Persamaan Linier Dua Variabel
        </footer>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
