<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elevate English Institute | Master English Language Skills</title>
    <style>
        /* ===== Global Styles ===== */
        :root {
            --primary: #2563eb;  /* Royal blue */
            --accent: #f59e0b;   /* Amber */
            --dark: #1e293b;    /* Navy blue */
            --light: #f8fafc;    /* Off-white */
            --font-main: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: var(--font-main);
            line-height: 1.6;
            color: #334155;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* ===== Header & Navigation ===== */
        header {
            background: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary);
        }

        .logo span {
            color: var(--accent);
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        /* ===== Hero Section ===== */
        .hero {
            background: linear-gradient(135deg, #2563eb 0%, #1e40af 100%);
            color: white;
            padding: 5rem 0;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 2rem;
        }

        .cta-button {
            display: inline-block;
            background: var(--accent);
            color: white;
            padding: 0.8rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        /* ===== Courses Section ===== */
        .courses {
            padding: 4rem 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }

        .section-title h2 {
            font-size: 2.2rem;
            color: var(--dark);
            position: relative;
            display: inline-block;
        }

        .section-title h2::after {
            content: '';
            position: absolute;
            width: 50%;
            height: 4px;
            background: var(--accent);
            bottom: -10px;
            left: 25%;
        }

        .course-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .course-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .course-card:hover {
            transform: translateY(-10px);
        }

        .course-img {
            height: 200px;
            background: #ddd;
            background-size: cover;
            background-position: center;
        }

        .course-content {
            padding: 1.5rem;
        }

        .course-content h3 {
            color: var(--primary);
            margin-bottom: 0.5rem;
        }

        /* ===== Testimonials ===== */
        .testimonials {
            background: var(--light);
            padding: 4rem 0;
        }

        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .testimonial-card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .testimonial-text {
            font-style: italic;
            margin-bottom: 1rem;
        }

        .testimonial-author {
            font-weight: 600;
            color: var(--primary);
        }

        /* ===== Footer ===== */
        footer {
            background: var(--dark);
            color: white;
            padding: 3rem 0 1rem;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .footer-column h3 {
            color: var(--accent);
            margin-bottom: 1rem;
            font-size: 1.2rem;
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column ul li {
            margin-bottom: 0.5rem;
        }

        .footer-column a {
            color: #cbd5e1;
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer-column a:hover {
            color: white;
        }

        .copyright {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid #334155;
        }

        /* ===== Responsive Design ===== */
        @media (max-width: 768px) {
            .nav-links {
                display: none; /* Replace with hamburger menu in real implementation */
            }

            .hero h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">Elevate<span>English</span></div>
                <div class="nav-links">
                    <a href="#">Home</a>
                    <a href="#courses">Courses</a>
                    <a href="#about">About</a>
                    <a href="#contact">Contact</a>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Unlock Your English Potential</h1>
            <p>Join our expert-led courses and achieve fluency with personalized learning paths designed for all levels.</p>
            <a href="#courses" class="cta-button">Explore Courses</a>
        </div>
    </section>

    <!-- Courses Section -->
    <section class="courses" id="courses">
        <div class="container">
            <div class="section-title">
                <h2>Our Popular Courses</h2>
            </div>
            <div class="course-grid">
                <div class="course-card">
                    <div class="course-img" style="background-image: url('https://images.unsplash.com/photo-1546410531-bb4caa6b424d?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60');"></div>
                    <div class="course-content">
                        <h3>Business English</h3>
                        <p>Master professional communication for the workplace with our specialized business English program.</p>
                    </div>
                </div>
                <div class="course-card">
                    <div class="course-img" style="background-image: url('https://images.unsplash.com/photo-1503676260728-1c00da094a0b?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60');"></div>
                    <div class="course-content">
                        <h3>IELTS Preparation</h3>
                        <p>Get the score you need with our comprehensive IELTS test preparation course.</p>
                    </div>
                </div>
                <div class="course-card">
                    <div class="course-img" style="background-image: url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60');"></div>
                    <div class="course-content">
                        <h3>Conversational English</h3>
                        <p>Build confidence in everyday speaking with our interactive conversation classes.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>What Our Students Say</h2>
            </div>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <p class="testimonial-text">"Elevate English Institute transformed my professional communication skills. I got promoted thanks to their Business English course!"</p>
                    <p class="testimonial-author">- Rajesh K., IT Professional</p>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-text">"The IELTS preparation was excellent. I scored 8.0 and got into my dream university in Canada!"</p>
                    <p class="testimonial-author">- Priya M., Student</p>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-text">"After just 3 months, I can confidently speak English with international clients. Highly recommended!"</p>
                    <p class="testimonial-author">- Amit S., Business Owner</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-column">
                    <h3>Elevate English</h3>
                    <p>Your pathway to English language excellence since 2020.</p>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#courses">Courses</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Us</h3>
                    <ul>
                        <li>123 Education Street</li>
                        <li>Mumbai, India</li>
                        <li>info@elevateenglish.edu</li>
                        <li>+91 98765 43210</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2024 Elevate English Institute. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
