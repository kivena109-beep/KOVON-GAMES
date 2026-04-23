<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KIVENIOO ELITE GAMES</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@700&family=Orbitron:wght@500;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --neon-blue: #00f3ff;
            --neon-pink: #ff00ff;
            --main-bg: #050505;
        }

        body {
            background-color: var(--main-bg);
            color: white;
            font-family: 'Cairo', sans-serif;
            margin: 0;
            overflow-x: hidden;
        }

        /* خلفية سينمائية */
        .hero {
            height: 60vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(5,5,5,1)), 
                        url('https://images.unsplash.com/photo-1542751371-adc38448a05e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border-bottom: 3px solid var(--neon-blue);
        }

        h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 4rem;
            margin: 0;
            text-transform: uppercase;
            background: linear-gradient(to right, var(--neon-blue), var(--neon-pink));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            filter: drop-shadow(0 0 15px var(--neon-blue));
        }

        .container {
            max-width: 1400px;
            margin: -100px auto 50px;
            padding: 20px;
        }

        .games-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 35px;
        }

        /* كارت اللعبة الفخم */
        .game-card {
            background: rgba(20, 20, 20, 0.9);
            border: 1px solid #333;
            border-radius: 20px;
            padding: 10px;
            transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            position: relative;
        }

        .game-card:hover {
            transform: scale(1.03);
            border-color: var(--neon-blue);
            box-shadow: 0 0 30px rgba(0, 243, 255, 0.3);
        }

        iframe {
            width: 100%;
            height: 450px;
            border: none;
            border-radius: 15px;
            background: #000;
        }

        .game-info {
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .game-title {
            font-size: 1.3rem;
            font-weight: bold;
            color: #fff;
            text-shadow: 0 0 5px var(--neon-blue);
        }

        .status {
            font-size: 0.8rem;
            background: rgba(0, 243, 255, 0.1);
            color: var(--neon-blue);
            padding: 5px 12px;
            border-radius: 20px;
            border: 1px solid var(--neon-blue);
        }

        footer {
            padding: 40px;
            background: #000;
            opacity: 0.7;
        }
    </style>
</head>
<body>

<div class="hero">
    <h1>KIVENIOO HUB</h1>
    <p style="font-size: 1.5rem; letter-spacing: 2px;">أقوى تجربة ألعاب أونلاين 2026</p>
</div>

<div class="container">
    <div class="games-grid">
        
        <div class="game-card">
            <iframe src="https://www.retrogames.cc/embed/16845-mortal-kombat-rev-1-1.html" allowfullscreen></iframe>
            <div class="game-info">
                <span class="game-title">Mortal Kombat</span>
                <span class="status">LIVE 4K</span>
            </div>
        </div>

        <div class="game-card">
            <iframe src="https://www.retrogames.cc/embed/10042-tekken-3.html" allowfullscreen></iframe>
            <div class="game-info">
                <span class="game-title">Tekken 3</span>
                <span class="status">HIGH FPS</span>
            </div>
        </div>

        <div class="game-card">
            <iframe src="https://www.retrogames.cc/embed/16847-super-mario-world-usa.html" allowfullscreen></iframe>
            <div class="game-info">
                <span class="game-title">Super Mario World</span>
                <span class="status">CLASSIC</span>
            </div>
        </div>

        <div class="game-card">
            <iframe src="https://www.retrogames.cc/embed/9085-street-fighter-ii-the-world-warrior-world-910522.html" allowfullscreen></iframe>
            <div class="game-info">
                <span class="game-title">Street Fighter II</span>
                <span class="status">PRO</span>
            </div>
        </div>

        <div class="game-card">
            <iframe src="https://www.retrogames.cc/embed/19323-sonic-the-hedgehog-usa-europe.html" allowfullscreen></iframe>
            <div class="game-info">
                <span class="game-title">Sonic Hedgehog</span>
                <span class="status">SPEED</span>
            </div>
        </div>

        <div class="game-card">
            <iframe src="https://www.retrogames.cc/embed/7473-metal-slug-super-vehicle-001.html" allowfullscreen></iframe>
            <div class="game-info">
                <span class="game-title">Metal Slug</span>
                <span class="status">ACTION</span>
            </div>
        </div>

    </div>
</div>

<footer>
    <p>تم التصميم بواسطة Kivenioo لعام 2026</p>
</footer>

</body>
</html>
