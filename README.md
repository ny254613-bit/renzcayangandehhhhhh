# renzcayangandehhhhhh
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maaf Untukmu, Andeh Cayang</title>
    <style>
        body {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%);
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .star {
            position: absolute;
            color: #fff;
            font-size: 20px;
            animation: float 6s ease-in-out infinite;
            opacity: 0.8;
        }

        .heart {
            position: absolute;
            color: #ff6b9d;
            font-size: 24px;
            animation: heartFloat 8s ease-in-out infinite;
            opacity: 0.9;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            25% { transform: translateY(-20px) rotate(90deg); }
            50% { transform: translateY(-40px) rotate(180deg); }
            75% { transform: translateY(-20px) rotate(270deg); }
        }

        @keyframes heartFloat {
            0%, 100% { transform: translateY(0px) scale(1); }
            25% { transform: translateY(-30px) scale(1.1); }
            50% { transform: translateY(-60px) scale(1.2); }
            75% { transform: translateY(-30px) scale(1.1); }
        }

        .container {
            position: relative;
            z-index: 2;
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
            text-align: center;
        }

        .main-title {
            font-size: 3.5rem;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            margin-bottom: 20px;
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from { text-shadow: 2px 2px 4px rgba(0,0,0,0.3), 0 0 20px rgba(255,255,255,0.3); }
            to { text-shadow: 2px 2px 4px rgba(0,0,0,0.3), 0 0 30px rgba(255,255,255,0.6); }
        }

        .subtitle {
            font-size: 1.8rem;
            color: #ffeaa7;
            margin-bottom: 40px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
        }

        .message-card {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            margin: 30px 0;
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 8px 32px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .message-card:hover {
            transform: translateY(-5px);
        }

        .message-text {
            font-size: 1.3rem;
            line-height: 1.8;
            color: #fff;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
            margin-bottom: 20px;
        }

        .love-quote {
            font-style: italic;
            font-size: 1.1rem;
            color: #ffeaa7;
            border-left: 4px solid #ff6b9d;
            padding-left: 20px;
            margin: 20px 0;
        }

        .promise-section {
            background: rgba(255, 107, 157, 0.2);
            border-radius: 15px;
            padding: 30px;
            margin: 30px 0;
        }

        .promise-title {
            font-size: 2rem;
            color: #ff6b9d;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
        }

        .promise-list {
            list-style: none;
            padding: 0;
        }

        .promise-list li {
            font-size: 1.2rem;
            color: #fff;
            margin: 15px 0;
            padding: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            transition: background 0.3s ease;
        }

        .promise-list li:hover {
            background: rgba(255, 255, 255, 0.2);
        }

        .promise-list li::before {
            content: "💕 ";
            margin-right: 10px;
        }

        .final-message {
            font-size: 1.5rem;
            color: #ffeaa7;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            margin-top: 40px;
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .signature {
            font-size: 1.3rem;
            color: #ff6b9d;
            margin-top: 30px;
            font-style: italic;
        }

        @media (max-width: 768px) {
            .main-title {
                font-size: 2.5rem;
            }
            
            .subtitle {
                font-size: 1.4rem;
            }
            
            .message-card {
                padding: 25px;
            }
            
            .message-text {
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    
    <div class="container">
        <h1 class="main-title">Maaf Untukmu</h1>
        <h2 class="subtitle">Andeh Cayang ❤️</h2>
        
        <div class="message-card">
            <p class="message-text">
                Sayang, aku tahu aku telah melakukan kesalahan yang membuatmu kecewa. 
                Kata "maaf" mungkin terasa sederhana, tapi dari lubuk hati yang paling dalam, 
                aku benar-benar menyesal atas semua yang telah terjadi.
            </p>
            
            <div class="love-quote">
                "Cinta sejati bukan tentang tidak pernah bertengkar, 
                tapi tentang selalu kembali dan memperbaiki kesalahan bersama-sama."
            </div>
            
            <p class="message-text">
                Andeh adalah segalanya bagiku. Senyummu adalah matahari di hariku, 
                tawamu adalah musik terindah yang pernah kudengar. 
                Aku tidak bisa membayangkan hidup tanpa dirimu di sisiku.
            </p>
        </div>

        <div class="promise-section">
            <h3 class="promise-title">Janjiku Untukmu</h3>
            <ul class="promise-list">
                <li>Aku akan lebih mendengarkan perasaanmu dengan hati yang terbuka</li>
                <li>Aku akan lebih berhati-hati dengan kata-kata dan tindakanku</li>
                <li>Aku akan selalu berusaha membuatmu bahagia setiap hari</li>
                <li>Aku akan menjadi pasangan yang lebih baik untukmu</li>
                <li>Aku akan mencintaimu dengan sepenuh hati, selamanya</li>
            </ul>
        </div>

        <div class="message-card">
            <p class="message-text">
                Kita telah melewati begitu banyak hal bersama, dan aku tidak ingin 
                kesalahan ini mengakhiri cerita indah kita. Mari kita tulis chapter baru 
                yang penuh dengan cinta, pengertian, dan kebahagiaan.
            </p>
            
            <div class="love-quote">
                "Bersamamu, aku belajar bahwa cinta bukan hanya tentang kebahagiaan, 
                tapi juga tentang tumbuh dan menjadi lebih baik bersama-sama."
            </div>
            
            <p class="message-text">
                Andeh cayang, maukah kamu memberiku kesempatan untuk membuktikan 
                bahwa cintaku padamu lebih kuat dari kesalahan yang pernah kubuat? 
                Maukah kita berjalan bersama lagi, tangan dalam tangan, 
                menuju masa depan yang lebih indah?
            </p>
        </div>

        <div class="final-message">
            Aku mencintaimu lebih dari kata-kata yang bisa kuungkapkan ✨
        </div>
        
        <div class="signature">
            Dengan cinta yang tulus,<br>
            Pasanganmu yang menyayangimu ❤️
        </div>
    </div>

    <script>
        // Create floating stars and hearts
        function createFloatingElements() {
            const starsContainer = document.getElementById('stars');
            
            // Create stars
            for (let i = 0; i < 15; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.innerHTML = '✨';
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                star.style.animationDelay = Math.random() * 6 + 's';
                star.style.animationDuration = (Math.random() * 4 + 4) + 's';
                starsContainer.appendChild(star);
            }
            
            // Create hearts
            for (let i = 0; i < 12; i++) {
                const heart = document.createElement('div');
                heart.className = 'heart';
                heart.innerHTML = '💖';
                heart.style.left = Math.random() * 100 + '%';
                heart.style.top = Math.random() * 100 + '%';
                heart.style.animationDelay = Math.random() * 8 + 's';
                heart.style.animationDuration = (Math.random() * 6 + 6) + 's';
                starsContainer.appendChild(heart);
            }
        }

        // Initialize floating elements when page loads
        window.addEventListener('load', createFloatingElements);

        // Add smooth scroll behavior for better UX
        document.documentElement.style.scrollBehavior = 'smooth';
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98ac67618251fd9e',t:'MTc1OTgyOTY3OC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
