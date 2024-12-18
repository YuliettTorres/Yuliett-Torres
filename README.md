<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yuliett Torres | Modelo e Influencer</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0c0c0c;
            color: #fff;
            text-align: center;
        }
        header {
            padding: 30px 10px;
            background-color: #b90539;
            color: white;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            text-transform: uppercase;
        }
        .content {
            padding: 20px;
        }
        .social-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px 0;
        }
        .social-item {
            position: relative;
            cursor: pointer;
        }
        .social-item img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .social-item:hover img {
            transform: scale(1.05);
        }
        .social-name {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(0, 0, 0, 0.7);
            padding: 5px 10px;
            font-size: 1.2em;
            border-radius: 5px;
            color: #fff;
        }
        footer {
            margin-top: 30px;
            font-size: 0.8em;
            color: #bbb;
            background-color: #111;
            padding: 10px 0;
        }
    </style>
    <script>
        function redirect(url) {
            const encryptedUrl = atob(url);
            window.location.href = encryptedUrl;
        }
    </script>
</head>
<body>
    <header>
        <h1>Yuliett Torres</h1>
        <p>Modelo e Influencer de Contenido Sexy</p>
    </header>
    <div class="content">
        <p>Conecta conmigo en mis redes sociales y disfruta de contenido exclusivo.</p>
        <div class="social-gallery">
            <div class="social-item" onclick="redirect('aHR0cHM6Ly93d3cuaW5zdGFncmFtLmNvbS95dWxpZXR0LnRvcnJlcyc=')">
                <img src="/mnt/data/IMG_8753.JPG" alt="Instagram">
                <div class="social-name">Instagram</div>
            </div>
            <div class="social-item" onclick="redirect('aHR0cHM6Ly90Lm1lL3l1bGlldHR0b3JyZXNvZmljaWFs')">
                <img src="/mnt/data/D7EE56AF-B431-4BCC-9BB0-310981082758.JPG" alt="Telegram">
                <div class="social-name">Telegram</div>
            </div>
            <div class="social-item" onclick="redirect('aHR0cHM6Ly93d3cuZmFjZWJvb2suY29tL1l1bGlldHR0b3JyZXNzb2ZpY2lhbC8=')">
                <img src="/mnt/data/43F14BA2-6E9C-4013-873C-C6480EBE1B81.JPG" alt="Facebook">
                <div class="social-name">Facebook</div>
            </div>
            <div class="social-item" onclick="redirect('aHR0cHM6Ly9vbmx5ZmFucy5jb20veXVsaWV0dHRvcnJlc2xpdmVz')">
                <img src="/mnt/data/11C2D611-C58A-4241-B6CD-D908006B1AF8.JPG" alt="Contenido Exclusivo">
                <div class="social-name">Contenido Exclusivo</div>
            </div>
            <div class="social-item" onclick="redirect('aHR0cHM6Ly90Lm1lL1l1bGlldHRUb3JyZXNUZWxlZ3JhbQ==')">
                <img src="/mnt/data/7149D77B-1BE1-427A-998F-49A2EBA0AF85.JPG" alt="Mis Fans Exclusivos">
                <div class="social-name">Mis Fans Exclusivos</div>
            </div>
        </div>
    </div>
    <footer>
        &copy; 2024 Yuliett Torres. Todos los derechos reservados.
    </footer>
</body>
</html>
