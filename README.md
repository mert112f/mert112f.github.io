<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Kartvizit</title>
    <style>
        /* Genel sıfırlamalar ve temel stil */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .card {
            background: white;
            width: 350px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .card-header {
            background-color: #333;
            color: white;
            padding: 20px;
        }

        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .card-header h1 {
            font-size: 1.5em;
            margin-bottom: 5px;
        }

        .card-header p {
            font-size: 1em;
            color: #ddd;
        }

        .card-body {
            padding: 20px;
            background-color: #fff;
        }

        .bio {
            font-size: 0.9em;
            color: #555;
            margin-bottom: 20px;
        }

        .social-links a,
        .media-links a {
            display: inline-block;
            margin: 5px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 8px 15px;
            border-radius: 5px;
            transition: all 0.3s ease;
        }

        .social-links a:hover,
        .media-links a:hover {
            background-color: #0073e6;
            color: white;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="card-header">
            <img src="profile.jpg" alt="Profil Resmi" class="profile-pic">
            <h1>Abdullah Samet Demircan</h1>
            <p>Genç Lider ve İçerik Üretici</p>
        </div>
        <div class="card-body">
            <p class="bio">Trabzon Üniversitesi Turizm Meslek Yüksekokulu öğrencisi ve Bilim ve Teknoloji Komisyonu Başkan Vekili. Gençlik Meclisi Üyesi ve sosyal medya içerik üreticisi.</p>
        </div>
        <div class="social-links">
            <a href="https://twitter.com" target="_blank">Twitter</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>
        </div>
        <div class="media-links">
            <a href="https://example.com/media1" target="_blank">Medya 1</a>
            <a href="https://example.com/media2" target="_blank">Medya 2</a>
        </div>
    </div>

    <script>
        // JavaScript kodu burada eklenebilir, örneğin etkileşimli öğeler eklemek için
        document.querySelectorAll('.social-links a').forEach(link => {
            link.addEventListener('click', () => {
                console.log(`Navigating to ${link.href}`);
            });
        });
    </script>
</body>
</html>
