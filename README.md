<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>G & T 5206 Investments LLC | Premium Logistics Solutions</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&family=Open+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #1a5fb4;
            --secondary: #ff6b35;
            --dark: #1e1e2e;
            --light: #f8f9fa;
            --gray: #6c757d;
            --light-blue: #e3f2fd;
            --success: #28a745;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Open Sans', sans-serif;
            color: #333;
            line-height: 1.6;
            overflow-x: hidden;
            background-color: #f5f7fa;
        }
        
        h1, h2, h3, h4, h5 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            color: var(--dark);
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 28px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        
        .btn-primary {
            background: var(--primary);
            color: white;
        }
        
        .btn-primary:hover {
            background: #0d4a9c;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(26, 95, 180, 0.25);
        }
        
        .btn-secondary {
            background: var(--secondary);
            color: white;
        }
        
        .btn-secondary:hover {
            background: #e05a2a;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(255, 107, 53, 0.25);
        }
        
        .btn-outline {
            background: transparent;
            border: 2px solid var(--primary);
            color: var(--primary);
        }
        
        .btn-outline:hover {
            background: var(--primary);
            color: white;
        }
        
        .section-padding {
            padding: 100px 0;
        }
        
        /* Top Bar */
        .top-bar {
            background: var(--dark);
            color: white;
            padding: 8px 0;
            font-size: 14px;
        }
        
        .top-bar-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .contact-info {
            display: flex;
            gap: 20px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            transition: color 0.3s;
        }
        
        .contact-info a:hover {
            color: var(--secondary);
        }
        
        .social-icons {
            display: flex;
            gap: 15px;
        }
        
        .social-icons a {
            color: white;
            font-size: 16px;
            transition: color 0.3s;
        }
        
        .social-icons a:hover {
            color: var(--secondary);
        }
        
        /* Header */
        .header {
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
        }
        
        .logo-icon {
            background: var(--primary);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
        }
        
        .logo-text {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            font-size: 24px;
            color: var(--dark);
        }
        
        .logo-text span {
            color: var(--primary);
        }
        
        .nav-links {
            display: flex;
            gap: 30px;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            font-size: 16px;
            transition: color 0.3s;
            position: relative;
        }
        
        .nav-links a:hover {
            color: var(--primary);
        }
        
        .nav-links a.active {
            color: var(--primary);
        }
        
        .nav-links a.active::after {
            content: '';
            position: absolute;
            width: 100%;
            height: 2px;
            background: var(--primary);
            bottom: -5px;
            left: 0;
        }
        
        .mobile-toggle {
            display: none;
            font-size: 24px;
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(26, 95, 180, 0.9), rgba(30, 30, 46, 0.9)), url('https://images.unsplash.com/photo-1601924994987-69e26d50dc26?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1800&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 150px 0;
            text-align: center;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            color: white;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .hero-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        /* Services Section */
        .services {
            background: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }
        
        .section-title h2 {
            font-size: 36px;
            margin-bottom: 15px;
            position: relative;
            display: inline-block;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            width: 60%;
            height: 3px;
            background: var(--primary);
            bottom: -10px;
            left: 20%;
        }
        
        .section-title p {
            color: var(--gray);
            max-width: 700px;
            margin: 20px auto 0;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
            padding: 40px 30px;
            border: 1px solid #eee;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .service-icon {
            background: var(--light-blue);
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 25px;
            color: var(--primary);
            font-size: 32px;
        }
        
        .service-card h3 {
            margin-bottom: 15px;
            font-size: 22px;
        }
        
        /* How it works */
        .process {
            background: var(--light);
        }
        
        .process-steps {
            display: flex;
            justify-content: space-between;
            position: relative;
            margin-top: 50px;
        }
        
        .process-steps::before {
            content: '';
            position: absolute;
            top: 40px;
            left: 10%;
            right: 10%;
            height: 3px;
            background: var(--primary);
            z-index: 1;
        }
        
        .step {
            text-align: center;
            position: relative;
            z-index: 2;
            width: 22%;
        }
        
        .step-number {
            background: var(--primary);
            color: white;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            font-weight: bold;
            margin: 0 auto 25px;
            border: 5px solid var(--light);
        }
        
        .step h3 {
            margin-bottom: 15px;
        }
        
        /* CTA Section */
        .cta {
            background: linear-gradient(to right, var(--primary), #0d4a9c);
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        
        .cta h2 {
            color: white;
            font-size: 36px;
            margin-bottom: 20px;
        }
        
        .cta p {
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 18px;
        }
        
        /* About Section */
        .about {
            background: white;
        }
        
        .about-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            gap: 50px;
            align-items: center;
        }
        
        .about-image {
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
        }
        
        .about-image img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .about-text h2 {
            margin-bottom: 25px;
        }
        
        .about-features {
            margin-top: 30px;
        }
        
        .feature-item {
            display: flex;
            gap: 15px;
            margin-bottom: 20px;
        }
        
        .feature-icon {
            background: var(--light-blue);
            color: var(--primary);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            flex-shrink: 0;
        }
        
        .feature-text h4 {
            margin-bottom: 5px;
        }
        
        /* Stats Section */
        .stats {
            background: linear-gradient(rgba(26, 95, 180, 0.9), rgba(30, 30, 46, 0.9)), url('https://images.unsplash.com/photo-1531973576160-7125cd663d86?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1800&q=80');
            background-size: cover;
            background-attachment: fixed;
            color: white;
            text-align: center;
            padding: 80px 0;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .stat-item h3 {
            font-size: 48px;
            color: white;
            margin-bottom: 10px;
        }
        
        /* Contact Section */
        .contact {
            background: white;
        }
        
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }
        
        .contact-info-box {
            background: var(--light-blue);
            padding: 40px;
            border-radius: 8px;
        }
        
        .contact-info-box h3 {
            margin-bottom: 30px;
            color: var(--primary);
        }
        
        .contact-detail {
            display: flex;
            gap: 15px;
            margin-bottom: 25px;
        }
        
        .contact-icon {
            background: var(--primary);
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            flex-shrink: 0;
        }
        
        .contact-text h4 {
            font-size: 18px;
            margin-bottom: 5px;
        }
        
        .contact-form {
            background: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
        }
        
        .form-control {
            width: 100%;
            padding: 14px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-family: 'Open Sans', sans-serif;
            font-size: 16px;
            transition: border 0.3s;
        }
        
        .form-control:focus {
            outline: none;
            border-color: var(--primary);
        }
        
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        
        /* Footer */
        .footer {
            background: var(--dark);
            color: white;
            padding: 70px 0 0;
        }
        
        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 50px;
        }
        
        .footer-col h3 {
            color: white;
            margin-bottom: 25px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            width: 50px;
            height: 2px;
            background: var(--secondary);
            bottom: 0;
            left: 0;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 12px;
        }
        
        .footer-links a {
            color: #bbb;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-links a:hover {
            color: var(--secondary);
        }
        
        .copyright {
            text-align: center;
            padding: 25px 0;
            border-top: 1px solid #444;
            color: #bbb;
            font-size: 14px;
        }
        
        /* Page Navigation */
        .page-nav {
            background: linear-gradient(to right, var(--primary), #0d4a9c);
            padding: 20px 0;
            color: white;
        }
        
        .page-nav .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .page-nav h2 {
            color: white;
            font-size: 28px;
        }
        
        .breadcrumb {
            display: flex;
            list-style: none;
        }
        
        .breadcrumb li {
            margin-left: 10px;
        }
        
        .breadcrumb li a {
            color: rgba(255,255,255,0.8);
            text-decoration: none;
        }
        
        .breadcrumb li a:hover {
            color: white;
        }
        
        .breadcrumb li::after {
            content: '/';
            margin-left: 10px;
            color: rgba(255,255,255,0.5);
        }
        
        .breadcrumb li:last-child::after {
            content: '';
        }
        
        /* Responsive Design */
        @media (max-width: 992px) {
            .hero h1 {
                font-size: 40px;
            }
            
            .process-steps {
                flex-wrap: wrap;
            }
            
            .step {
                width: 48%;
                margin-bottom: 40px;
            }
            
            .process-steps::before {
                display: none;
            }
            
            .about-content {
                grid-template-columns: 1fr;
            }
        }
        
        @media (max-width: 768px) {
            .mobile-toggle {
                display: block;
            }
            
            .nav-links {
                position: absolute;
                top: 100%;
                left: 0;
                right: 0;
                background: white;
                flex-direction: column;
                gap: 0;
                box-shadow: 0 10px 15px rgba(0,0,0,0.1);
                clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
                transition: clip-path 0.4s ease;
            }
            
            .nav-links.active {
                clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
            }
            
            .nav-links a {
                padding: 15px 20px;
                border-bottom: 1px solid #eee;
            }
            
            .hero {
                padding: 100px 0;
            }
            
            .hero h1 {
                font-size: 32px;
            }
            
            .hero p {
                font-size: 18px;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .top-bar-content {
                flex-direction: column;
                gap: 10px;
                text-align: center;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 10px;
            }
            
            .step {
                width: 100%;
            }
            
            .page-nav .container {
                flex-direction: column;
                gap: 15px;
                text-align: center;
            }
            
            .breadcrumb {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <!-- Top Bar -->
    <div class="top-bar">
        <div class="container top-bar-content">
            <div class="contact-info">
                <a href="tel:2675005667"><i class="fas fa-phone"></i> (267) 500-5667</a>
                <a href="mailto:hashmiumaiz@gmail.com"><i class="fas fa-envelope"></i> hashmiumaiz@gmail.com</a>
            </div>
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </div>
    
    <!-- Header -->
    <header class="header">
        <div class="container nav-container">
            <a href="#" class="logo">
                <div class="logo-icon">
                    <i class="fas fa-truck-moving"></i>
                </div>
                <div class="logo-text">G & T <span>Logistics</span></div>
            </a>
            
            <div class="mobile-toggle" id="mobileToggle">
                <i class="fas fa-bars"></i>
            </div>
            
            <nav class="nav-links" id="navLinks">
                <a href="#" class="active">Home</a>
                <a href="#about">About Us</a>
                <a href="#services">Services</a>
                <a href="#process">How It Works</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container hero-content">
            <h1>Premium Logistics & Transportation Solutions</h1>
            <p>G & T 5206 Investments LLC provides reliable, efficient, and cost-effective logistics services tailored to your business needs.</p>
            <div class="hero-buttons">
                <a href="#contact" class="btn btn-primary">Get a Quote</a>
                <a href="#services" class="btn btn-secondary">Our Services</a>
            </div>
        </div>
    </section>
    
    <!-- Services Section -->
    <section class="services section-padding" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Logistics Services</h2>
                <p>Comprehensive solutions for all your transportation and supply chain needs</p>
            </div>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-truck"></i>
                    </div>
                    <h3>Freight Transportation</h3>
                    <p>Efficient and reliable transportation of goods across the region with our modern fleet and experienced drivers.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-warehouse"></i>
                    </div>
                    <h3>Warehousing Solutions</h3>
                    <p>Secure storage facilities with inventory management to streamline your supply chain operations.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-boxes"></i>
                    </div>
                    <h3>Supply Chain Management</h3>
                    <p>End-to-end supply chain solutions that optimize your logistics for maximum efficiency.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-shipping-fast"></i>
                    </div>
                    <h3>Expedited Shipping</h3>
                    <p>Priority shipping services for time-sensitive deliveries with real-time tracking.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-globe-americas"></i>
                    </div>
                    <h3>Nationwide Distribution</h3>
                    <p>Comprehensive distribution network covering all major cities and regions across the country.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <h3>Custom Solutions</h3>
                    <p>Tailored logistics services designed to meet your specific business requirements.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- About Section -->
    <section class="about section-padding" id="about">
        <div class="container">
            <div class="section-title">
                <h2>About Our Company</h2>
                <p>Learn about our mission, vision, and values</p>
            </div>
            
            <div class="about-content">
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="G & T Logistics Team">
                </div>
                
                <div class="about-text">
                    <h2>Your Trusted Logistics Partner</h2>
                    <p>G & T 5206 Investments LLC was founded with a mission to transform the logistics industry through innovation, reliability, and exceptional customer service. With years of experience and a dedicated team of professionals, we've built a reputation for excellence in transportation and supply chain management.</p>
                    
                    <p>Our state-of-the-art facilities and modern fleet of vehicles ensure that your goods are handled with care and delivered on time, every time. We pride ourselves on our commitment to sustainability and ethical business practices.</p>
                    
                    <div class="about-features">
                        <div class="feature-item">
                            <div class="feature-icon">
                                <i class="fas fa-medal"></i>
                            </div>
                            <div class="feature-text">
                                <h4>Industry Expertise</h4>
                                <p>Over 15 years of experience in logistics and transportation</p>
                            </div>
                        </div>
                        
                        <div class="feature-item">
                            <div class="feature-icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div class="feature-text">
                                <h4>Strategic Location</h4>
                                <p>Centrally located in Bala Cynwyd for efficient distribution</p>
                            </div>
                        </div>
                        
                        <div class="feature-item">
                            <div class="feature-icon">
                                <i class="fas fa-users"></i>
                            </div>
                            <div class="feature-text">
                                <h4>Dedicated Team</h4>
                                <p>Professional staff committed to your success</p>
                            </div>
                        </div>
                    </div>
                    
                    <a href="#contact" class="btn btn-primary">Contact Us</a>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Process Section -->
    <section class="process section-padding" id="process">
        <div class="container">
            <div class="section-title">
                <h2>How Our Process Works</h2>
                <p>Simple steps to get your goods where they need to be</p>
            </div>
            
            <div class="process-steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Request a Quote</h3>
                    <p>Contact us with your shipment details to receive a competitive quote.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Schedule Pickup</h3>
                    <p>We coordinate a convenient time to collect your shipment.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Transportation</h3>
                    <p>Your goods are transported safely and efficiently to the destination.</p>
                </div>
                
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Delivery</h3>
                    <p>We deliver your shipment on time with proof of delivery.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Stats Section -->
    <section class="stats">
        <div class="container">
            <div class="stats-grid">
                <div class="stat-item">
                    <h3>15+</h3>
                    <p>Years of Experience</p>
                </div>
                
                <div class="stat-item">
                    <h3>250+</h3>
                    <p>Happy Clients</p>
                </div>
                
                <div class="stat-item">
                    <h3>5000+</h3>
                    <p>Successful Deliveries</p>
                </div>
                
                <div class="stat-item">
                    <h3>98%</h3>
                    <p>On-Time Rate</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- CTA Section -->
    <section class="cta">
        <div class="container">
            <h2>Ready to Streamline Your Logistics?</h2>
            <p>Get in touch with our team today to discuss how we can optimize your supply chain and reduce transportation costs.</p>
            <a href="#contact" class="btn btn-secondary">Contact Us Now</a>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section class="contact section-padding" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
                <p>Reach out to our logistics experts for any inquiries or quotes</p>
            </div>
            
            <div class="contact-container">
                <div class="contact-info-box">
                    <h3>Get In Touch</h3>
                    
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Our Location</h4>
                            <p>191 Presidential Boulevard Suite 110<br>Bala Cynwyd, PA 19004</p>
                        </div>
                    </div>
                    
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Call Us</h4>
                            <p>(267) 500-5667</p>
                        </div>
                    </div>
                    
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Email Us</h4>
                            <p>hashmiumaiz@gmail.com</p>
                        </div>
                    </div>
                    
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Business Hours</h4>
                            <p>Monday-Friday: 8AM - 6PM<br>Saturday: 9AM - 2PM</p>
                        </div>
                    </div>
                </div>
                
                <div class="contact-form">
                    <h3>Send Us a Message</h3>
                    <form>
                        <div class="form-group">
                            <label for="name">Full Name</label>
                            <input type="text" id="name" class="form-control" placeholder="Your Name">
                        </div>
                        
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" class="form-control" placeholder="Your Email">
                        </div>
                        
                        <div class="form-group">
                            <label for="phone">Phone Number</label>
                            <input type="tel" id="phone" class="form-control" placeholder="Your Phone">
                        </div>
                        
                        <div class="form-group">
                            <label for="service">Service Interested In</label>
                            <select id="service" class="form-control">
                                <option value="">Select a Service</option>
                                <option value="freight">Freight Transportation</option>
                                <option value="warehouse">Warehousing Solutions</option>
                                <option value="supply">Supply Chain Management</option>
                                <option value="expedited">Expedited Shipping</option>
                                <option value="distribution">Nationwide Distribution</option>
                                <option value="custom">Custom Solutions</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" class="form-control" placeholder="How can we help you?"></textarea>
                        </div>
                        
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>G & T Logistics</h3>
                    <p>Providing premium logistics and transportation solutions with efficiency, reliability, and exceptional customer service.</p>
                    <div class="social-icons" style="margin-top: 20px;">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#process">How It Works</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Our Services</h3>
                    <ul class="footer-links">
                        <li><a href="#">Freight Transportation</a></li>
                        <li><a href="#">Warehousing Solutions</a></li>
                        <li><a href="#">Supply Chain Management</a></li>
                        <li><a href="#">Expedited Shipping</a></li>
                        <li><a href="#">Nationwide Distribution</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Contact Info</h3>
                    <ul class="footer-links">
                        <li><i class="fas fa-map-marker-alt"></i> 191 Presidential Blvd, Bala Cynwyd, PA 19004</li>
                        <li><i class="fas fa-phone"></i> (267) 500-5667</li>
                        <li><i class="fas fa-envelope"></i> hashmiumaiz@gmail.com</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="copyright">
            <div class="container">
                <p>&copy; 2023 G & T 5206 Investments LLC. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
    
    <script>
        // Mobile Navigation Toggle
        const mobileToggle = document.getElementById('mobileToggle');
        const navLinks = document.getElementById('navLinks');
        
        mobileToggle.addEventListener('click', () => {
            navLinks.classList.toggle('active');
        });
        
        // Smooth Scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                if (this.getAttribute('href') === '#') return;
                
                e.preventDefault();
                
                navLinks.classList.remove('active');
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Highlight active navigation based on scroll position
        window.addEventListener('scroll', function() {
            const sections = document.querySelectorAll('section');
            const navLinks = document.querySelectorAll('.nav-links a');
            
            let current = '';
            
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                
                if (pageYOffset >= (sectionTop - sectionHeight / 3)) {
                    current = section.getAttribute('id');
                }
            });
            
            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href').substring(1) === current) {
                    link.classList.add('active');
                }
            });
        });
        
        // Form submission
        const contactForm = document.querySelector('.contact-form form');
        if (contactForm) {
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                alert('Thank you for your message! We will contact you shortly.');
                this.reset();
            });
        }
    </script>
</body>
</html>
