<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kadheeshtha OCYM</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
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
            font-weight: bold;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            transition: opacity 0.3s;
            font-weight: 500;
        }

        .nav-links a:hover {
            opacity: 0.8;
        }

        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 150px 2rem 100px;
            text-align: center;
            margin-top: 60px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            animation: fadeInDown 1s;
        }

        .hero p {
            font-size: 1.3rem;
            max-width: 800px;
            margin: 0 auto 2rem;
            opacity: 0.95;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        .welcome-section {
            text-align: center;
            margin-bottom: 4rem;
        }

        .welcome-section h2 {
            font-size: 2.5rem;
            color: #667eea;
            margin-bottom: 1.5rem;
        }

        .welcome-text {
            font-size: 1.1rem;
            line-height: 1.8;
            max-width: 900px;
            margin: 0 auto;
            color: #555;
        }

        .programs {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .program-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .program-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .program-card h3 {
            color: #667eea;
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .program-card p {
            color: #666;
            line-height: 1.6;
        }

        .icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        footer {
            background: #2d3748;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1.1rem;
            }

            .nav-links {
                gap: 1rem;
            }

            nav {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Kadheeshtha OCYM</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#programs">Programs</a></li>
                <li><a href="#events">Events</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Welcome to St. Mary's Kadheeshtha Youth Movement</h1>
        <p>Empowering youth through faith, service, and community</p>
    </section>

    <div class="container">
        <section class="welcome-section">
            <h2>Peace and Blessings</h2>
            <div class="welcome-text">
                <p>Welcome to the official website of St. Mary's Kadheeshtha Youth Movement (OCYM). We are a vibrant community of young believers dedicated to serving God, our church, and our community through faith, fellowship, and action.</p>
                <br>
                <p>Our movement stands as a pillar of support for St. Mary's Church, actively participating in and organizing various initiatives that strengthen our spiritual bonds and make a meaningful impact in the lives of those around us.</p>
                <br>
                <p>Whether you're seeking spiritual growth, looking to serve others, or wanting to be part of a dynamic youth community, you've found your home. Join us as we walk together in faith and purpose.</p>
            </div>
        </section>

        <section id="programs">
            <h2 style="text-align: center; font-size: 2.5rem; color: #667eea; margin-bottom: 3rem;">Our Programs</h2>
            <div class="programs">
                <div class="program-card">
                    <div class="icon">🤲</div>
                    <h3>Charitable Donations</h3>
                    <p>We organize regular donation drives to support the less fortunate in our community. Through your generosity, we provide food, clothing, and essential supplies to those in need, embodying the spirit of Christian charity.</p>
                </div>
                <div class="program-card">
                    <div class="icon">❤️</div>
                    <h3>Community Service</h3>
                    <p>Our members actively engage in helping programs throughout the year, visiting the sick, supporting elderly members of our parish, and reaching out to families facing difficulties. Service is at the heart of what we do.</p>
                </div>
                <div class="program-card">
                    <div class="icon">🎭</div>
                    <h3>Cultural Programs</h3>
                    <p>We celebrate our rich heritage through vibrant cultural events, performances, and festivals. These programs bring our community together, preserve our traditions, and showcase the talents of our youth.</p>
                </div>
                <div class="program-card">
                    <div class="icon">⛪</div>
                    <h3>Church Event Support</h3>
                    <p>As dedicated members of St. Mary's Church, we actively support and participate in all church events and celebrations. From feast days to special services, our youth movement stands ready to serve.</p>
                </div>
            </div>
        </section>
    </div>

    <section id="contact" style="background: #f7fafc; padding: 4rem 0;">
        <div class="container">
            <h2 style="text-align: center; font-size: 2.5rem; color: #667eea; margin-bottom: 3rem;">Contact Us</h2>
            
            <div style="max-width: 800px; margin: 0 auto;">
                <div style="background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); margin-bottom: 2rem;">
                    <h3 style="color: #667eea; margin-bottom: 1.5rem; font-size: 1.8rem;">Church Leadership</h3>
                    <div style="border-left: 4px solid #667eea; padding-left: 1.5rem; margin-bottom: 1.5rem;">
                        <h4 style="color: #2d3748; font-size: 1.3rem; margin-bottom: 0.5rem;">Fr. Jacob Kallichethu</h4>
                        <p style="color: #666; margin-bottom: 0.3rem;">Church Vicar</p>
                        <p style="color: #667eea; font-weight: 600;">📞 +91 89211 68399</p>
                    </div>
                </div>

                <div style="background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);">
                    <h3 style="color: #667eea; margin-bottom: 1.5rem; font-size: 1.8rem;">Youth Movement Leaders</h3>
                    
                    <div style="border-left: 4px solid #667eea; padding-left: 1.5rem; margin-bottom: 1.5rem;">
                        <h4 style="color: #2d3748; font-size: 1.3rem; margin-bottom: 0.5rem;">Romy Vargheese</h4>
                        <p style="color: #666; margin-bottom: 0.3rem;">Youth Secretary</p>
                        <p style="color: #667eea; font-weight: 600;">📞 +91 94473 86273</p>
                    </div>

                    <div style="border-left: 4px solid #667eea; padding-left: 1.5rem;">
                        <h4 style="color: #2d3748; font-size: 1.3rem; margin-bottom: 0.5rem;">Nijin Tiju</h4>
                        <p style="color: #666; margin-bottom: 0.3rem;">Youth Treasurer</p>
                        <p style="color: #667eea; font-weight: 600;">📞 +91 99479 89185</p>
                    </div>
                </div>

                <div style="text-align: center; margin-top: 2rem; padding: 1.5rem; background: white; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);">
                    <p style="color: #666; font-size: 1.1rem;">Feel free to reach out to us for any inquiries, to join our programs, or to learn more about our youth movement. We're here to serve!</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 St. Mary's Kadheeshtha Youth Movement (OCYM). All rights reserved.</p>
        <p>Serving our community with faith, hope, and love.</p>
    </footer>
</body>
</html>
