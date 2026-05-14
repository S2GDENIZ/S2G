
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>S2G TEAM | MOBİL PANEL</title>
    <style>
        /* ƏSAS MOBİL AYARLAR */
        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }
        
        body {
            font-family: 'Arial Black', sans-serif;
            background: #F3E5F5;
            color: #4A148C;
            text-transform: uppercase;
            -webkit-tap-highlight-color: transparent; /* Mobilde göy kölgəni silir */
        }

        /* HEADER - MOBİL GÖRÜNÜŞÜ */
        .header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            /* Çempionluq şəkli */
            background: url('https://gamingonphone.com/wp-content/uploads/2023/01/PUBG-Mobile-S2G-Esports-champions-PMGC-2022.jpg');
            background-size: cover;
            background-position: center; /* Şəkli teldə ortalayır */
            color: white;
            padding: 20px;
        }

        /* Arxa fonun yazıları boğmaması üçün tünd qat */
        .header::before {
            content: "";
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.6);
            z-index: 1;
        }

        .header-content {
            position: relative;
            z-index: 2;
            width: 100%;
        }

        .champ-tag {
            font-size: 1.1rem;
            color: #FFD700;
            letter-spacing: 4px;
            margin-bottom: 10px;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.8);
        }

        /* LOQO VƏ MOBİL DÖNMƏ EFFEKTİ */
        .logo-wrapper {
            display: inline-block;
            text-decoration: none;
            transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .main-logo {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            border: 4px solid #FFD700;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.5);
            display: block;
        }

        /* Teldə toxunanda və ya üzərinə gələndə fırlanma */
        .logo-wrapper:active, .logo-wrapper:hover {
            transform: rotate(15deg) scale(1.1);
        }

        .title-link {
            font-size: 2.2rem;
            text-decoration: none;
            color: white;
            display: block;
            margin-top: 15px;
            text-shadow: 2px 2px 12px rgba(0,0,0,1);
        }

        /* ÜZVLƏR - MOBİLDƏ ALT-ALTA */
        .container {
            padding: 20px;
            display: grid;
            grid-template-columns: 1fr; /* Mobildə tək sütun */
            gap: 12px;
            max-width: 500px;
            margin: 0 auto;
        }

        .card {
            background: #fff;
            padding: 15px;
            border-radius: 15px;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            border-left: 0px solid #FFD700;
            transition: 0.3s;
        }

        .card:active { /* Teldə basanda reaksiya */
            background: #FAF5FF;
            transform: scale(0.98);
            border-left: 6px solid #FFD700;
        }

        .card img {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: #eee;
        }

        .card h2 {
            font-size: 0.9rem;
            color: #4A148C;
            letter-spacing: 0.5px;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            font-size: 0.7rem;
            color: #888;
            letter-spacing: 1px;
        }

        /* PLANŞET VƏ KOMPÜTER ÜÇÜN GENİŞLƏNMƏ */
        @media (min-width: 768px) {
            .container {
                grid-template-columns: 1fr 1fr;
                max-width: 1000px;
            }
            .main-logo { width: 140px; height: 140px; }
            .title-link { font-size: 4rem; }
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
            
            <p style="margin-top: 20px; font-size: 9px; opacity: 0.8; letter-spacing: 2px;">ÜYELER İÇİN AŞAĞI KAYDIR</p>
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
        S2G TEAM PRODUCTION © 2026
    </footer>

</body>
</html>
