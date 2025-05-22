<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raiden - Discord Bot Services</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: #0a0a0a;
            color: #ffffff;
            overflow-x: hidden;
        }

        .background-grid {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(255, 0, 0, 0.1) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255, 0, 0, 0.1) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: -1;
            animation: gridPulse 4s ease-in-out infinite;
        }

        @keyframes gridPulse {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 0.1; }
        }

        .glow-orb {
            position: fixed;
            width: 400px;
            height: 400px;
            background: radial-gradient(circle, rgba(255, 0, 0, 0.3) 0%, transparent 70%);
            border-radius: 50%;
            pointer-events: none;
            z-index: -1;
            animation: float 8s ease-in-out infinite;
        }

        .orb-1 {
            top: 10%;
            left: 20%;
            animation-delay: 0s;
        }

        .orb-2 {
            bottom: 20%;
            right: 10%;
            animation-delay: 4s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) translateX(0px); }
            25% { transform: translateY(-20px) translateX(10px); }
            50% { transform: translateY(10px) translateX(-15px); }
            75% { transform: translateY(-10px) translateX(5px); }
        }

        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(10, 10, 10, 0.9);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255, 0, 0, 0.2);
            z-index: 1000;
            padding: 1rem 0;
        }

        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #ff0000;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .logo-icon {
            width: 32px;
            height: 32px;
            background: linear-gradient(45deg, #ff0000, #cc0000);
            border-radius: 6px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .logo-icon::before {
            content: '';
            position: absolute;
            width: 12px;
            height: 12px;
            background: #fff;
            clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        .nav-links a {
            color: #ffffff;
            text-decoration: none;
            transition: color 0.3s ease;
            position: relative;
        }

        .nav-links a:hover {
            color: #ff0000;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: #ff0000;
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .cta-button {
            background: linear-gradient(45deg, #ff0000, #cc0000);
            color: white;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(255, 0, 0, 0.3);
        }

        main {
            padding-top: 100px;
        }

        .hero {
            text-align: center;
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 4rem;
            font-weight: 800;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, #ffffff, #ff0000);
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textGlow 3s ease-in-out infinite;
        }

        @keyframes textGlow {
            0%, 100% { filter: brightness(1); }
            50% { filter: brightness(1.2); }
        }

        .hero p {
            font-size: 1.25rem;
            margin-bottom: 2rem;
            color: #cccccc;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .services {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .services h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #ff0000;
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            margin-bottom: 4rem;
        }

        .service-card {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 0, 0, 0.2);
            border-radius: 12px;
            padding: 2rem;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 0, 0, 0.1), transparent);
            transition: left 0.5s ease;
        }

        .service-card:hover::before {
            left: 100%;
        }

        .service-card:hover {
            transform: translateY(-5px);
            border-color: #ff0000;
            box-shadow: 0 20px 40px rgba(255, 0, 0, 0.2);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(45deg, #ff0000, #cc0000);
            border-radius: 12px;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .bot-icon::before {
            content: '';
            position: absolute;
            width: 24px;
            height: 20px;
            background: #fff;
            border-radius: 4px;
        }

        .bot-icon::after {
            content: '';
            position: absolute;
            width: 8px;
            height: 8px;
            background: #ff0000;
            border-radius: 50%;
            top: 18px;
            left: 18px;
            box-shadow: 8px 0 0 #ff0000;
        }

        .moderation-icon::before {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            border: 3px solid #fff;
            border-radius: 50%;
        }

        .moderation-icon::after {
            content: '';
            position: absolute;
            width: 12px;
            height: 3px;
            background: #fff;
            top: 28px;
            left: 24px;
            border-radius: 2px;
            box-shadow: 0 -6px 0 #fff, 0 6px 0 #fff;
        }

        .music-icon::before {
            content: '';
            position: absolute;
            width: 16px;
            height: 16px;
            border: 3px solid #fff;
            border-radius: 50% 50% 50% 0;
            transform: rotate(-45deg);
        }

        .music-icon::after {
            content: '';
            position: absolute;
            width: 6px;
            height: 12px;
            background: #fff;
            border-radius: 3px;
            top: 20px;
            left: 32px;
        }

        .utility-icon::before {
            content: '';
            position: absolute;
            width: 20px;
            height: 3px;
            background: #fff;
            border-radius: 2px;
            box-shadow: 0 6px 0 #fff, 0 12px 0 #fff, 0 18px 0 #fff;
        }

        .utility-icon::after {
            content: '';
            position: absolute;
            width: 8px;
            height: 8px;
            background: #fff;
            border-radius: 2px;
            top: 16px;
            right: 16px;
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #ffffff;
        }

        .service-card p {
            color: #cccccc;
            line-height: 1.6;
            margin-bottom: 1.5rem;
        }

        .feature-list {
            list-style: none;
        }

        .feature-list li {
            color: #aaaaaa;
            margin-bottom: 0.5rem;
            position: relative;
            padding-left: 1.5rem;
        }

        .feature-list li::before {
            content: '';
            position: absolute;
            left: 0;
            top: 8px;
            width: 6px;
            height: 6px;
            background: #ff0000;
            border-radius: 50%;
        }

        .stats {
            background: rgba(255, 255, 255, 0.03);
            padding: 4rem 2rem;
            text-align: center;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            max-width: 800px;
            margin: 0 auto;
        }

        .stat-item {
            padding: 1.5rem;
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 800;
            color: #ff0000;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            color: #cccccc;
            font-size: 1rem;
        }

        footer {
            background: rgba(255, 255, 255, 0.03);
            padding: 3rem 2rem 1rem;
            text-align: center;
            border-top: 1px solid rgba(255, 0, 0, 0.2);
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2rem;
            flex-wrap: wrap;
        }

        .footer-links a {
            color: #cccccc;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-links a:hover {
            color: #ff0000;
        }

        .footer-bottom {
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding-top: 1rem;
            color: #666666;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .nav-links {
                display: none;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .service-grid {
                grid-template-columns: 1fr;
            }
        }

        .pulse {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(255, 0, 0, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(255, 0, 0, 0); }
            100% { box-shadow: 0 0 0 0 rgba(255, 0, 0, 0); }
        }
    </style>
</head>
<body>
    <div class="background-grid"></div>
    <div class="glow-orb orb-1"></div>
    <div class="glow-orb orb-2"></div>

    <header>
        <nav>
            <a href="#" class="logo">
                <div class="logo-icon"></div>
                Raiden
            </a>
            <ul class="nav-links">
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <a href="#contact" class="cta-button">Get Started</a>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Raiden</h1>
            <p>Professional Discord bot development services that bring your server to life with cutting-edge automation and engagement features.</p>
            <div class="hero-buttons">
                <a href="#services" class="cta-button pulse">View Services</a>
                <a href="#contact" class="cta-button">Contact Us</a>
            </div>
        </section>

        <section class="services" id="services">
            <h2>Discord Bot Services</h2>
            <div class="service-grid">
                <div class="service-card">
                    <div class="service-icon bot-icon"></div>
                    <h3>Custom Bot Development</h3>
                    <p>Tailored Discord bots built from scratch to meet your specific server needs and requirements.</p>
                    <ul class="feature-list">
                        <li>Custom commands and functionality</li>
                        <li>Database integration</li>
                        <li>Advanced permissions system</li>
                        <li>24/7 uptime guarantee</li>
                    </ul>
                </div>

                <div class="service-card">
                    <div class="service-icon moderation-icon"></div>
                    <h3>Moderation Bots</h3>
                    <p>Advanced moderation systems to keep your Discord server safe and well-organized.</p>
                    <ul class="feature-list">
                        <li>Auto-moderation features</li>
                        <li>Warning and punishment system</li>
                        <li>Spam and raid protection</li>
                        <li>Detailed logging system</li>
                    </ul>
                </div>

                <div class="service-card">
                    <div class="service-icon music-icon"></div>
                    <h3>Music Bots</h3>
                    <p>High-quality music bots with premium features for the ultimate listening experience.</p>
                    <ul class="feature-list">
                        <li>Multiple platform support</li>
                        <li>Queue management</li>
                        <li>High-quality audio streaming</li>
                        <li>Playlist functionality</li>
                    </ul>
                </div>

                <div class="service-card">
                    <div class="service-icon utility-icon"></div>
                    <h3>Utility Bots</h3>
                    <p>Comprehensive utility bots to enhance server functionality and user experience.</p>
                    <ul class="feature-list">
                        <li>Server management tools</li>
                        <li>Role management system</li>
                        <li>Welcome and goodbye messages</li>
                        <li>Custom embed messages</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="stats">
            <div class="stats-grid">
                <div class="stat-item">
                    <div class="stat-number">500+</div>
                    <div class="stat-label">Bots Deployed</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">99.9%</div>
                    <div class="stat-label">Uptime</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">1M+</div>
                    <div class="stat-label">Users Served</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">24/7</div>
                    <div class="stat-label">Support</div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content">
            <div class="footer-links">
                <a href="#services">Services</a>
                <a href="#about">About</a>
                <a href="#contact">Contact</a>
                <a href="#privacy">Privacy</a>
                <a href="#terms">Terms</a>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Raiden. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
