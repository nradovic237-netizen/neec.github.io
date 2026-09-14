<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEEC | Video Editor & Motion Designer</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0a0a0c;
            --text-main: #f5f5f5;
            --text-muted: #888;
            --accent: #5e6ad2;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            position: relative;
        }

        .hero h1 {
            font-size: clamp(4rem, 10vw, 8rem);
            font-weight: 900;
            letter-spacing: -2px;
            margin-bottom: 0.5rem;
            background: linear-gradient(to right, #fff, #555);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero h2 {
            font-size: clamp(1.2rem, 3vw, 2rem);
            font-weight: 400;
            color: var(--text-muted);
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.1rem;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .scroll-down {
            position: absolute;
            bottom: 40px;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--text-muted);
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }

        /* Section Styling */
        section {
            padding: 6rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        h3.section-title {
            font-size: 2.5rem;
            margin-bottom: 3rem;
            border-bottom: 1px solid #333;
            padding-bottom: 1rem;
        }

        /* Portfolio Work */
        .work-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 4rem;
        }

        .work-item {
            background: #111;
            border: 1px solid #222;
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }

        .work-item:hover {
            transform: translateY(-5px);
            border-color: #444;
        }

        .video-container {
            width: 100%;
            aspect-ratio: 16 / 9;
            background: #000;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #444;
            font-size: 1.2rem;
            position: relative;
        }

<div class="video-container">
    <blockquote class="twitter-tweet" data-media-max-width="560"><p lang="en" dir="ltr">Before VS After! It is crazy what you can do with just voiceover. <a href="https://t.co/JkirvkSDgX">pic.twitter.com/JkirvkSDgX</a></p>&mdash; C Nick I Video Editor &amp; Motion Designer (@C_edit07) <a href="https://x.com/C_edit07/status/2093085643848966294?ref_src=twsrc%5Etfw">August 27, 2026</a></blockquote> <script async src="https://platform.x.com/widgets.js" charset="utf-8"></script>
    <blockquote class="twitter-tweet">
        <a href="https://twitter.com/tvoj_username/status/123456789"></a>
    </blockquote>
    <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>

        .work-info {
            padding: 2rem;
        }

        .work-info h4 {
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
        }

        .tags {
            font-size: 0.85rem;
            color: var(--accent);
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 1rem;
        }

        .tags span:not(:last-child)::after {
            content: " · ";
            color: var(--text-muted);
        }

        /* Services */
        .services-list {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .service-tag {
            padding: 1rem 2rem;
            border: 1px solid #333;
            border-radius: 50px;
            font-size: 1.2rem;
            transition: all 0.3s ease;
        }

        .service-tag:hover {
            background: var(--text-main);
            color: var(--bg-color);
        }

        /* Footer / Contact */
        footer {
            text-align: center;
            padding: 6rem 2rem;
            background: #050505;
            border-top: 1px solid #222;
        }

        footer h2 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        footer p {
            color: var(--text-muted);
            margin-bottom: 3rem;
            font-size: 1.2rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        .social-links a {
            color: var(--text-main);
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: 700;
            border-bottom: 2px solid transparent;
            padding-bottom: 5px;
            transition: border-color 0.3s;
        }

        .social-links a:hover {
            border-color: var(--accent);
        }

        /* Responsive */
        @media (min-width: 768px) {
            .work-grid {
                grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            }
        }
    </style>
</head>
<body>

    <!-- Hero -->
    <header class="hero">
        <h1>NEEC</h1>
        <h2>VIDEO EDITOR & MOTION DESIGNER</h2>
        <p>I make videos move.</p>
        <div class="scroll-down">↓ Scroll</div>
    </header>

    <!-- Selected Work -->
    <section id="work">
        <h3 class="section-title">SELECTED WORK</h3>
        
        <div class="work-grid">
            
            <!-- Video 1 -->
            <div class="work-item">
                <div class="video-container">
                    <!-- Ubaci YouTube/Vimeo iframe ili <video> tag ovde -->
                    <div class="video-placeholder">[ VIDEO PREVIEW ]</div>
                </div>
                <div class="work-info">
                    <h4>XBAE VIDEO</h4>
                    <div class="tags">
                        <span>BEFORE / AFTER</span>
                        <span>EDITING</span>
                        <span>COLOR</span>
                        <span>SOUND</span>
                    </div>
                </div>
            </div>

            <!-- Video 2 -->
            <div class="work-item">
                <div class="video-container">
                    <div class="video-placeholder">[ VIDEO PREVIEW ]</div>
                </div>
                <div class="work-info">
                    <h4>MONTHLY MAX BRAWLERS</h4>
                    <div class="tags">
                        <span>SHORT-FORM</span>
                        <span>GAMING</span>
                        <span>MOTION</span>
                    </div>
                </div>
            </div>

            <!-- Video 3 -->
            <div class="work-item">
                <div class="video-container">
                    <div class="video-placeholder">[ VIDEO PREVIEW ]</div>
                </div>
                <div class="work-info">
                    <h4>X1</h4>
                    <div class="tags">
                        <span>MOTION DESIGN</span>
                        <span>AFTER EFFECTS</span>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- What I Do -->
    <section id="services">
        <h3 class="section-title">WHAT I DO</h3>
        <div class="services-list">
            <div class="service-tag">SHORT-FORM</div>
            <div class="service-tag">GAMING CONTENT</div>
            <div class="service-tag">MOTION DESIGN</div>
            <div class="service-tag">VIDEO EDITING</div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <h2>LET'S WORK</h2>
        <p>Have a project? Let's make something worth watching.</p>
        
        <div class="social-links">
            <!-- Dodaj svoje prave linkove umesto "#" -->
            <a href="#" target="_blank">YouTube</a>
            <a href="#" target="_blank">Instagram</a>
            <a href="mailto:tvoj.email@gmail.com">Email</a>
        </div>
    </footer>

</body>
</html>
