<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>justedone — Проекты</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background: #0a0e1a;
            color: #e6f0ff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 40px 20px;
        }

        .container {
            max-width: 700px;
            width: 100%;
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #64aaf0;
            letter-spacing: 2px;
        }

        .subtitle {
            font-size: 1rem;
            color: #8fa8c8;
            margin-bottom: 50px;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 18px;
        }

        .link-card {
            display: flex;
            align-items: center;
            gap: 18px;
            padding: 22px 28px;
            background: #121c2e;
            border: 1px solid #1e3050;
            border-radius: 14px;
            text-decoration: none;
            color: #e6f0ff;
            transition: all 0.25s ease;
            text-align: left;
        }

        .link-card:hover {
            background: #18263c;
            border-color: #64aaf0;
            transform: translateX(6px);
            box-shadow: 0 0 20px rgba(100, 170, 240, 0.15);
        }

        .link-icon {
            width: 48px;
            height: 48px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.4rem;
            font-weight: bold;
            flex-shrink: 0;
        }

        .vk .link-icon { background: #0077FF; color: white; }
        .tiktok .link-icon { background: #000; color: white; }
        .github .link-icon { background: #24292e; color: white; }

        .link-text h2 {
            font-size: 1.15rem;
            margin-bottom: 4px;
        }

        .link-text p {
            font-size: 0.85rem;
            color: #8fa8c8;
        }

        footer {
            margin-top: 60px;
            font-size: 0.8rem;
            color: #4a5a75;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>justedone</h1>
        <p class="subtitle">ESP32 · T-Embed · Пентест · Minecraft</p>

        <div class="links">
            <a href="https://github.com/justedone/GhostClient" class="link-card github" target="_blank">
                <div class="link-icon">G</div>
                <div class="link-text">
                    <h2>GhostClient</h2>
                    <p>Скрытный форк Meteor Client для Fabric 26.2</p>
                </div>
            </a>

            <a href="https://vk.ru/justesp32" class="link-card vk" target="_blank">
                <div class="link-icon">VK</div>
                <div class="link-text">
                    <h2>ВКонтакте</h2>
                    <p>Паблик с гайдами и проектами</p>
                </div>
            </a>

            <a href="https://tiktok.com/@justesp32" class="link-card tiktok" target="_blank">
                <div class="link-icon">TT</div>
                <div class="link-text">
                    <h2>TikTok</h2>
                    <p>Видео про T-Embed, ESP32 и не только</p>
                </div>
            </a>
        </div>

        <footer>
            © justedone · 2026
        </footer>
    </div>
</body>
</html>
