<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About This Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #512bd4;
            --bg: #0f172a;
            --card-bg: #1e293b;
            --text-main: #f8fafc;
            --text-dim: #94a3b8;
        }

        body {
            background-color: var(--bg);
            color: var(--text-main);
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            padding: 40px 20px;
        }

        .readme-container {
            max-width: 800px;
            margin: 0 auto;
            background: var(--card-bg);
            padding: 40px;
            border-radius: 15px;
            border: 1px solid #334155;
        }

        h1 { color: var(--primary); margin-bottom: 20px; font-size: 2rem; }
        h3 { color: var(--primary); margin-top: 30px; margin-bottom: 15px; font-family: 'Fira Code', monospace; }
        
        ul { margin-left: 20px; margin-bottom: 20px; }
        li { margin-bottom: 10px; color: var(--text-dim); }
        strong { color: var(--text-main); }

        .philosophy {
            font-style: italic;
            border-left: 3px solid var(--primary);
            padding-left: 20px;
            color: var(--text-dim);
            margin-top: 20px;
        }

        .back-link {
            display: inline-block;
            margin-top: 30px;
            color: var(--primary);
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="readme-container">
        <h1>🚀 My Personal Portfolio</h1>
        <p>Welcome! This is my personal corner on the web where I showcase my journey as a developer. Built with a "keep it simple" mindset using just <strong>HTML, CSS, and JavaScript</strong>.</p>

        <h3>✨ What's inside?</h3>
        <ul>
            <li><strong>Live GitHub Feed:</strong> No manual updates here! The site talks directly to the GitHub API to show my latest work.</li>
            <li><strong>The .NET Vibe:</strong> A clean, dark interface styled with the classic C# purple.</li>
            <li><strong>Smooth Motion:</strong> Includes some cool animations like a typing effect and project cards that pop.</li>
            <li><strong>Mobile Ready:</strong> Because code should look good on any screen.</li>
        </ul>

        <h3>🛠️ Tech Stack</h3>
        <ul>
            <li><strong>Frontend:</strong> HTML5 & CSS3 (Grid/Flexbox).</li>
            <li><strong>Logic:</strong> Vanilla JavaScript (Fetch API).</li>
            <li><strong>Vibe:</strong> Professional yet empathetic.</li>
        </ul>

        <h3>💡 My Philosophy</h3>
        <div class="philosophy">
            I believe in <strong>empathy, compassion, and solidarity</strong>. For me, coding isn't just about logic—it's about stopping, looking, listening, and growing to turn empathy into reality through software.
        </div>

        <a href="index.html" class="back-link">← Back to Portfolio</a>
    </div>

</body>
</html>
