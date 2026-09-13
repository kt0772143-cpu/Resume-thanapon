<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thanapon Kittikunsaeng - Online Resume</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f6f9;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        header {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }
        h1 {
            color: #2c3e50;
            font-size: 2.2rem;
            margin-bottom: 5px;
        }
        .contact-info {
            color: #666;
            font-size: 0.95rem;
        }
        section {
            margin-bottom: 30px;
        }
        h2 {
            color: #2980b9;
            font-size: 1.4rem;
            margin-bottom: 12px;
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
        }
        p, li {
            color: #444;
            font-size: 1rem;
        }
        ul {
            list-style-type: square;
            margin-left: 20px;
        }
        .item {
            margin-bottom: 15px;
        }
        .item-title {
            font-weight: bold;
            color: #2c3e50;
        }
        .item-sub {
            font-style: italic;
            color: #7f8c8d;
            font-size: 0.9rem;
        }
        .hobbies-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 10px;
        }
        .hobby-card {
            background: #f8f9fa;
            padding: 12px;
            border-radius: 6px;
            border-left: 4px solid #2980b9;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Name & Address/Contact -->
        <header>
            <h1>Thanapon Kittikunsaeng</h1>
            <div class="contact-info">
                <p>📍 Bangkok, Thailand | 📞 096-159-1851</p>
            </div>
        </header>

        <!-- Profile Statement -->
        <section>
            <h2>Profile Statement</h2>
            <p>A motivated Business Administration student at the University of the Thai Chamber of Commerce (UTCC) with strong real-time problem-solving skills under pressure. Experienced in student activity management, team coordination, and event operations.</p>
        </section>

        <!-- Education -->
        <section>
            <h2>Education</h2>
            <div class="item">
                <div class="item-title">Bachelor of Business Administration (B.B.A.)</div>
                <div class="item-sub">University of the Thai Chamber of Commerce (UTCC)</div>
            </div>
        </section>

        <!-- Work Experience / Activities -->
        <section>
            <h2>Work Experience & Activities</h2>
            <div class="item">
                <div class="item-title">Freshman Orientation Student Leader</div>
                <div class="item-sub">University of the Thai Chamber of Commerce</div>
                <ul>
                    <li>Coordinated orientation activities for incoming freshman students.</li>
                    <li>Managed team operations and handled on-site problem-solving effectively during event execution.</li>
                </ul>
            </div>
        </section>

        <!-- Interests / Hobbies -->
        <section>
            <h2>Interests & Hobbies</h2>
            <div class="hobbies-grid">
                <div class="hobby-card">
                    <strong>🏋️ Fitness & Exercise</strong>
                    <p style="font-size: 0.85rem; color: #666;">Active health & workout routine</p>
                </div>
                <div class="hobby-card">
                    <strong>📚 Reading</strong>
                    <p style="font-size: 0.85rem; color: #666;">Exploring self-development topics</p>
                </div>
                <div class="hobby-card">
                    <strong>🎮 Gaming</strong>
                    <p style="font-size: 0.85rem; color: #666;">Strategic play & problem solving</p>
                </div>
                <div class="hobby-card">
                    <strong>🎵 Music</strong>
                    <p style="font-size: 0.85rem; color: #666;">Listening across diverse genres</p>
                </div>
            </div>
        </section>
    </div>

</body>
</html>
