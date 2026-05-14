
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <style>
  /* GITHUB-IN AVTOMATIK YAZISINI VE BOSLUGUNU SILEN HISSE */
        header.page-header, 
        .project-name, 
        .project-tagline, 
        footer.site-footer {
            display: none !important;
            visibility: hidden !important;
            height: 0 !important;
            padding: 0 !important;
            margin: 0 !important;
        }

        section.main-content {
            max-width: 100% !important;
            padding: 0 !important;
            margin: 0 !important;
        }
        
        
        /* ÜMUMİ SIFIRLAMA */
        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }
        
        body {
            font-family: 'Arial Black', sans-serif;
            background: #F3E5F5;
            color: #4A148C;
            text-transform: uppercase;
            -webkit-tap-highlight-color: transparent;
        }

        /* HEADER - ARXA FON */
        .header {
            height: 100vh;
            width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            background: url('https://gamingonphone.com/wp-content/uploads/2023/01/PUBG-Mobile-S2G-Esports-champions-PMGC-2022.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed; /* PC-də sürüşəndə qəşəng görünür */
            color: white;
            padding: 20px;
        }

        /* QARALTMA QATI */
        .header::before {
            content: "";
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.55);
            z-index: 1;
        }

        .header-content {
            position: relative;
            z-index: 2;
            width: 100%;
            max-width: 1200px;
        }

        .champ-tag {
            font-size: clamp(1rem, 4vw, 1.8rem);
            color: #FFD700;
            letter-spacing: 6px;
            margin-bottom: 15px;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.8);
        }

        /* LOQO EFFEKTİ */
        .logo-wrapper {
            display: inline-block;
            text-decoration: none;
            transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .main-logo {
            width: clamp(100px, 15vw, 150px); /* Ekran ölçüsünə görə dəyişir */
            height: clamp(100px, 15vw, 150px);
            border-radius: 50%;
            border: 5px solid #FFD700;
            box-shadow: 0 0 25px rgba(255, 215, 0, 0.4);
            display: block;
        }

        .logo-wrapper:hover, .logo-wrapper:active {
            transform: rotate(15deg) scale(1.1);
        }

        .title-link {
            font-size: clamp(2rem, 8vw, 5rem);
            text-decoration: none;
            color: white;
            display: block;
            margin-top: 20px;
            text-shadow: 2px 2px 15px rgba(0,0,0,1);
            transition: 0.3s ease;
        }

        .title-link:hover {
            color: #FFD700;
        }

        /* ÜYELER SİSTEMİ (GRID) */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 50px 20px;
            display: grid;
            /* Kompüterdə yanaşı, teldə tək sütun üçün ağıllı nizam */
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background: #ffffff;
            padding: 20px;
            border-radius: 15px;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 15px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.06);
            transition: 0.3s ease;
            border: 1px solid transparent;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: #FFD700;
            box-shadow: 0 10px 20px rgba(106, 27, 154, 0.15);
        }

        .card img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 2px solid #f3e5f5;
        }

        .card h2 {
            font-size: 1rem;
            color: #4A148C;
            letter-spacing: 0.5px;
        }

        footer {
            text-align: center;
            padding: 50px 20px;
            font-size: 0.8rem;
            color: #888;
            letter-spacing: 2px;
            background: #fff;
        }

        /* MOBİL ÜÇÜN XÜSUSİ DÜZƏLİŞLƏR */
        @media (max-width: 768px) {
            .header {
                background-attachment: scroll; /* Mobildə donma olmasın deyə */
                background-position: center;
            }
            .container {
                grid-template-columns: 1fr; /* Teldə mütləq tək sütun */
                padding: 30px 15px;
            }
            .card {
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <header class="header">
        <div class="header-content">
            <div class="champ-tag">S2G ŞAMPİYON</div>
            
            <a href="#members" class="logo-wrapper">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s" class="main-logo">
            </a>
            
            <a href="https://www.tiktok.com/@s2gespor" target="_blank" class="title-link">S2G TEAM</a>
            
            <p style="margin-top: 30px; font-size: 11px; letter-spacing: 3px; opacity: 0.9;">KAYDIRARAK ÜYELERİ GÖR</p>
        </div>
    </header>

    <div class="container" id="members">
        <a href="https://www.tiktok.com/@buluteditss7" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>BULUTEDITSS7</h2>
        </a>
        <a href="https://www.tiktok.com/@s2galixs.0" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GALIXS.0</h2>
        </a>
        <a href="https://www.tiktok.com/@lureeditss4" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>LUREEDITSS4</h2>
        </a>
        <a href="https://www.tiktok.com/@s2gportali" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GPORTALI</h2>
        </a>
        <a href="https://www.tiktok.com/@s2gcontex" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GCONTEX</h2>
        </a>
        <a href="https://www.tiktok.com/@s2gculture" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GCULTURE</h2>
        </a>
        <a href="https://www.tiktok.com/@s2gluxee" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GLUXEE</h2>
        </a>
        <a href="https://www.tiktok.com/@s2galis7" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GALIS7</h2>
        </a>
        <a href="https://www.tiktok.com/@hermasadadavarizz" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>HERMASADADAVARIZZ</h2>
        </a>
        <a href="https://www.tiktok.com/@revansevinn" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>REVANSEVIN</h2>
        </a>
        <a href="https://www.tiktok.com/@s2glyno" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GLYNO</h2>
        </a>
        <a href="https://www.tiktok.com/@s2gloyz" target="_blank" class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXBv_P3V_CitVwYsL5HD2QwF8RmqeFSOWfWg&s">
            <h2>S2GLOYZ</h2>
        </a>
    </div>

    <footer>
        S2G TEAM PRODUCTION © 2026 | TÜM HAKLARI SAKLIDIR
    </footer>

</body>
</html>
