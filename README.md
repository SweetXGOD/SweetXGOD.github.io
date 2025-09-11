<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BAURUM RADIO - Управляемое ИИ</title>
    <meta name="description" content="Первое радио, где искусственный интеллект создает музыку будущего">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #000428 0%, #004e92 100%);
            min-height: 100vh;
            color: white;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 20px;
            margin-bottom: 40px;
            animation: glow 2s infinite alternate;
        }
        
        @keyframes glow {
            from { box-shadow: 0 0 20px rgba(0, 78, 146, 0.5); }
            to { box-shadow: 0 0 40px rgba(0, 200, 255, 0.8); }
        }
        
        h1 {
            font-size: 4rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, #00b4db, #0083b0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .subtitle {
            font-size: 1.8rem;
            opacity: 0.9;
            margin-bottom: 30px;
            color: #00b4db;
        }
        
        .ai-badge {
            display: inline-block;
            background: linear-gradient(45deg, #ff0080, #ff8c00);
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: bold;
            margin-top: 20px;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .content {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            margin-top: 40px;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .feature {
            background: rgba(0, 0, 0, 0.3);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid rgba(0, 180, 219, 0.3);
            transition: transform 0.3s ease;
        }
        
        .feature:hover {
            transform: translateY(-5px);
            border-color: #00b4db;
        }
        
        .feature h3 {
            color: #00b4db;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }
        
        .status {
            text-align: center;
            margin: 40px 0;
            padding: 20px;
            background: rgba(0, 180, 219, 0.2);
            border-radius: 10px;
            border-left: 4px solid #00b4db;
        }
        
        .status-online {
            color: #00ff00;
            font-weight: bold;
        }
        
        footer {
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
            opacity: 0.8;
        }
        
        @media (max-width: 768px) {
            h1 { font-size: 2.5rem; }
            .subtitle { font-size: 1.3rem; }
            .content { padding: 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🎵 BAURUM RADIO</h1>
            <p class="subtitle">Управляемое искусственным интеллектом будущее</p>
            <div class="ai-badge">🚀 ИИ В ЭФИРЕ</div>
        </header>
        
        <div class="status">
            <h3>📡 СТАТУС СИСТЕМЫ: <span class="status-online">ONLINE</span></h3>
            <p>Нейросеть генерирует уникальные музыкальные композиции в реальном времени</p>
        </div>
        
        <div class="content">
            <h2>Добро пожаловать в эру музыкальной революции!</h2>
            <p>BAURUM RADIO - это первый в мире радиостанция, где каждый трек создается искусственным интеллектом в реальном времени. Никаких повторов, только уникальная музыка будущего!</p>
            
            <div class="features">
                <div class="feature">
                    <h3>🧠 ИИ-Генерация</h3>
                    <p>Нейросети создают музыку на основе ваших предпочтений и текущего настроения</p>
                </div>
                <div class="feature">
                    <h3>🌌 Космический саунд</h3>
                    <p>От эмбиента до электроники - звучание будущего уже здесь</p>
                </div>
                <div class="feature">
                    <h3>⚡ Реальное время</h3>
                    <p>Музыка генерируется на лету, каждый трек - уникальный</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>© 2025 BAURUM RADIO | Искусственный интеллект в каждом байте</p>
            <p>🚀 Подключайтесь к будущему музыки прямо сейчас!</p>
        </footer>
    </div>
</body>
</html>
