# Career-Compass-AI
#AI-powered career and placement assistant for students, built with Botpress.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Career Compass AI - Home</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }

        /* Navigation Header */
        header {
            background-color: #ffffff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #2563eb;
        }

        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: #64748b;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #2563eb;
        }

        /* Main Hero Section */
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            min-height: 75vh;
            padding: 2rem 5%;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: #0f172a;
        }

        .hero p {
            font-size: 1.25rem;
            color: #475569;
            max-width: 600px;
            margin-bottom: 2rem;
        }

        .cta-btn {
            background-color: #2563eb;
            color: white;
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(37, 99, 235, 0.3);
            transition: transform 0.2s, background-color 0.2s;
        }

        .cta-btn:hover {
            background-color: #1d4ed8;
            transform: translateY(-2px);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            background-color: #ffffff;
            border-top: 1px solid #e2e8f0;
            color: #94a3b8;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- Header Navigation -->
    <header>
        <div class="logo">Career Compass AI</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Features</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="hero">
        <h1>Your AI-Powered Career & Placement Assistant</h1>
        <p>Get personalized interview preparation, resume assistance, and career guidance instantly.</p>
        <button class="cta-btn" onclick="window.botpressWebChat.sendEvent({ type: 'show' })">Chat with Us</button>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Career Compass AI. All rights reserved.</p>
    </footer>

    <!-- Botpress Webchat Code -->
    <script src="https://cdn.botpress.cloud/webchat/v3.7/inject.js"></script>
    <script src="https://files.bpcontent.cloud/2026/02/23/03/20260223033206-IOV3Y1VP.js" defer></script>

</body>
</html>
