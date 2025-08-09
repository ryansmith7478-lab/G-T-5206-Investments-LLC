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
            --primary: #00509e;
            --secondary: #f9a826;
            --dark: #1e1e2e;
            --light: #f8f9fa;
            --gray: #6c757d;
            --light-blue: #e3f2fd;
            --success: #28a745;
            --accent: #2a9d8f;
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
            padding: 14px 32px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 16px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .btn-primary {
            background: var(--primary);
            color: white;
            box-shadow: 0 4px 15px rgba(0, 80, 158, 0.3);
        }
        
        .btn-primary:hover {
            background: #003f7d;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 80, 158, 0.4);
        }
        
        .btn-secondary {
            background: var(--secondary);
            color: white;
            box-shadow: 0 4px 15px rgba(249, 168, 38, 0.3);
        }
        
        .btn-secondary:hover {
            background: #e0971c;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(249, 168, 38, 0.4);
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
            padding: 10px 0;
            font-size: 14px;
        }
        
        .top-bar-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .contact-info {
            display: flex;
            gap: 25px;
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
            transition: all 0.3s;
            width: 32px;
            height: 32px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .social-icons a:hover {
            background: var(--secondary);
            transform: translateY(-3px);
        }
        
        /* Header */
        .header {
            background: white;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
            transition: all 0.3s;
        }
        
        .header.scrolled {
            padding: 5px 0;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
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
            gap: 12px;
            text-decoration: none;
        }
        
        .logo-icon {
            background: var(--primary);
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            transition: all 0.3s;
        }
        
        .logo:hover .logo-icon {
            transform: rotate(10deg);
            background: var(--secondary);
        }
        
        .logo-text {
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            font-size: 26px;
            color: var(--dark);
            letter-spacing: 0.5px;
        }
        
        .logo-text span {
            color: var(--primary);
            position: relative;
        }
        
        .logo-text span::after {
            content: '5206';
            position: absolute;
            top: -5px;
            right: -30px;
            font-size: 14px;
            color: var(--secondary);
            font-weight: 700;
        }
        
        .nav-links {
            display: flex;
            gap: 35px;
        }
        
        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            font-size: 16px;
            transition: all 0.3s;
            position: relative;
            padding: 5px 0;
        }
        
        .nav-links a:hover {
            color: var(--primary);
        }
        
        .nav-links a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 3px;
            background: var(--secondary);
            bottom: 0;
            left: 0;
            transition: width 0.3s;
        }
        
        .nav-links a:hover::after {
            width: 100%;
        }
        
        .nav-links a.active {
            color: var(--primary);
        }
        
        .nav-links a.active::after {
            width: 100%;
        }
        
        .mobile-toggle {
            display: none;
            font-size: 24px;
            cursor: pointer;
            color: var(--dark);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 80, 158, 0.85), rgba(30, 30, 46, 0.85)), url('https://images.unsplash.com/photo-1566576721346-d4a3b4eaeb55?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1800&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: white;
            padding: 180px 0 150px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 100px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none"><path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" fill="%23f8f9fa"></path><path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" fill="%23f8f9fa"></path><path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" fill="%23f8f9fa"></path></svg>');
            background-size: cover;
            background-repeat: no-repeat;
            transform: rotate(180deg);
        }
        
        .hero-content {
            max-width: 900px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }
        
        .hero h1 {
            font-size: 56px;
            margin-bottom: 25px;
            color: white;
            line-height: 1.2;
            text-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        
        .hero p {
            font-size: 22px;
            margin-bottom: 40px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            font-weight: 300;
        }
        
        .hero-buttons {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 30px;
        }
        
        /* Services Section */
        .services {
            background: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 70px;
        }
        
        .section-title h2 {
            font-size: 42px;
            margin-bottom: 20px;
            position: relative;
            display: inline-block;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            width: 80px;
            height: 4px;
            background: var(--secondary);
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .section-title p {
            color: var(--gray);
            max-width: 700px;
            margin: 30px auto 0;
            font-size: 18px;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 35px;
        }
        
        .service-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            transition: all 0.4s ease;
            text-align: center;
            padding: 45px 30px;
            border: 1px solid #eee;
            position: relative;
        }
        
        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: var(--primary);
            transform: scaleX(0);
            transform-origin: left;
            transition: transform 0.4s ease;
        }
        
        .service-card:hover {
            transform: translateY(-15px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.12);
        }
        
        .service-card:hover::before {
            transform: scaleX(1);
        }
        
        .service-icon {
            background: linear-gradient(135deg, var(--primary), #003f7d);
            width: 90px;
            height: 90px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 30px;
            color: white;
            font-size: 36px;
            box-shadow: 0 8px 20px rgba(0, 80, 158, 0.25);
        }
        
        .service-card h3 {
            margin-bottom: 20px;
            font-size: 24px;
        }
        
        .service-card p {
            color: var(--gray);
            font-size: 16px;
        }
        
        /* Fleet Section */
        .fleet {
            background: linear-gradient(to bottom, #f8f9fa, white);
        }
        
        .fleet-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 35px;
        }
        
        .truck-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            transition: all 0.4s ease;
            position: relative;
        }
        
        .truck-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.12);
        }
        
        .truck-image {
            height: 240px;
            overflow: hidden;
        }
        
        .truck-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .truck-card:hover .truck-image img {
            transform: scale(1.05);
        }
        
        .truck-details {
            padding: 25px;
            position: relative;
        }
        
        .truck-details h3 {
            margin-bottom: 15px;
            font-size: 22px;
            color: var(--primary);
        }
        
        .truck-features {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }
        
        .truck-feature {
            text-align: center;
            flex: 1;
        }
        
        .truck-feature i {
            font-size: 24px;
            color: var(--primary);
            margin-bottom: 8px;
        }
        
        /* Stats Section */
        .stats {
            background: linear-gradient(rgba(0, 80, 158, 0.9), rgba(30, 30, 46, 0.9)), url('https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1800&q=80');
            background-size: cover;
            background-attachment: fixed;
            color: white;
            text-align: center;
            padding: 100px 0;
            position: relative;
        }
        
        .stats::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none"><path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" fill="%23f8f9fa"></path><path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" fill="%23f8f9fa"></path><path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" fill="%23f8f9fa"></path></svg>');
            background-size: cover;
            background-repeat: no-repeat;
            transform: rotate(180deg);
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            position: relative;
            z-index: 2;
        }
        
        .stat-item {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px 20px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: all 0.4s;
        }
        
        .stat-item:hover {
            transform: translateY(-10px);
            background: rgba(255, 255, 255, 0.15);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .stat-item h3 {
            font-size: 56px;
            color: white;
            margin-bottom: 15px;
            font-weight: 800;
        }
        
        .stat-item p {
            font-size: 18px;
            font-weight: 300;
        }
        
        /* CTA Section */
        .cta {
            background: linear-gradient(to right, var(--primary), #003f7d);
            color: white;
            padding: 90px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .cta::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            transform: rotate(30deg);
        }
        
        .cta h2 {
            color: white;
            font-size: 42px;
            margin-bottom: 25px;
            position: relative;
            z-index: 2;
        }
        
        .cta p {
            max-width: 700px;
            margin: 0 auto 40px;
            font-size: 20px;
            position: relative;
            z-index: 2;
        }
        
        /* Footer */
        .footer {
            background: var(--dark);
            color: white;
            padding: 100px 0 0;
            position: relative;
        }
        
        .footer::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none"><path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" fill="%2300509e"></path><path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" fill="%2300509e"></path><path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" fill="%2300509e"></path></svg>');
            background-size: cover;
            background-repeat: no-repeat;
        }
        
        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 50px;
            margin-bottom: 70px;
            position: relative;
            z-index: 2;
        }
        
        .footer-col h3 {
            color: white;
            margin-bottom: 30px;
            position: relative;
            padding-bottom: 15px;
            font-size: 24px;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            width: 60px;
            height: 3px;
            background: var(--secondary);
            bottom: 0;
            left: 0;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 15px;
        }
        
        .footer-links a {
            color: #bbb;
            text-decoration: none;
            transition: all 0.3s;
            display: inline-block;
        }
        
        .footer-links a:hover {
            color: var(--secondary);
            transform: translateX(5px);
        }
        
        .copyright {
            text-align: center;
            padding: 30px 0;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: #bbb;
            font-size: 15px;
            position: relative;
            z-index: 2;
        }
        
        /* Legal Pages */
        .legal-page {
            padding: 100px 0;
            background: #f8f9fa;
        }
        
        .legal-content {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            padding: 60px;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            line-height: 1.8;
        }
        
        .legal-content h2 {
            margin: 40px 0 20px;
            color: var(--primary);
            font-size: 36px;
        }
        
        .legal-content h3 {
            margin: 35px 0 15px;
            font-size: 24px;
            color: var(--dark);
        }
        
        .legal-content p {
            margin-bottom: 20px;
            color: #555;
        }
        
        .legal-content ul {
            padding-left: 25px;
            margin-bottom: 25px;
        }
        
        .legal-content li {
            margin-bottom: 12px;
            color: #555;
        }
        
        .back-to-home {
            display: inline-block;
            margin-top: 40px;
        }
        
        /* Responsive Design */
        @media (max-width: 992px) {
            .hero h1 {
                font-size: 46px;
            }
            
            .section-title h2 {
                font-size: 36px;
            }
        }
        
        @media (max-width: 768px) {
            .mobile-toggle {
                display: block;
            }
            
            .nav-links {
                position: fixed;
                top: 100px;
                left: -100%;
                width: 80%;
                height: calc(100vh - 100px);
                background: white;
                flex-direction: column;
                gap: 0;
                box-shadow: 0 10px 15px rgba(0,0,0,0.1);
                transition: left 0.4s ease;
                padding: 20px;
                z-index: 1000;
            }
            
            .nav-links.active {
                left: 0;
            }
            
            .nav-links a {
                padding: 15px 0;
                border-bottom: 1px solid #eee;
                font-size: 18px;
            }
            
            .hero {
                padding: 140px 0 100px;
            }
            
            .hero h1 {
                font-size: 36px;
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
            
            .section-padding {
                padding: 70px 0;
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
    <header class="header" id="header">
        <div class="container nav-container">
            <a href="#" class="logo">
                <div class="logo-icon">
                    <i class="fas fa-truck-moving"></i>
                </div>
                <div class="logo-text">G & T <span>Investments</span></div>
            </a>
            
            <div class="mobile-toggle" id="mobileToggle">
                <i class="fas fa-bars"></i>
            </div>
            
            <nav class="nav-links" id="navLinks">
                <a href="#" class="active">Home</a>
                <a href="#about">About</a>
                <a href="#services">Services</a>
                <a href="#fleet">Fleet</a>
                <a href="#contact">Contact</a>
                <a href="#privacy">Privacy</a>
                <a href="#terms">Terms</a>
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
                    <p>Efficient transportation of goods across the region with our modern fleet and experienced drivers.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-warehouse"></i>
                    </div>
                    <h3>Warehousing Solutions</h3>
                    <p>Secure storage facilities with inventory management to streamline your supply chain.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-boxes"></i>
                    </div>
                    <h3>Supply Chain Management</h3>
                    <p>End-to-end solutions that optimize your logistics for maximum efficiency.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-shipping-fast"></i>
                    </div>
                    <h3>Expedited Shipping</h3>
                    <p>Priority shipping for time-sensitive deliveries with real-time tracking.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-globe-americas"></i>
                    </div>
                    <h3>Nationwide Distribution</h3>
                    <p>Comprehensive distribution network covering all major regions across the country.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <h3>Custom Solutions</h3>
                    <p>Tailored logistics services designed to meet your specific requirements.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Fleet Section -->
    <section class="fleet section-padding" id="fleet">
        <div class="container">
            <div class="section-title">
                <h2>Our Modern Truck Fleet</h2>
                <p>State-of-the-art vehicles for reliable transportation</p>
            </div>
            
            <div class="fleet-grid">
                <div class="truck-card">
                    <div class="truck-image">
                        <img src="https://images.unsplash.com/photo-1506152983158-b4a74a01c721?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Semi Truck">
                    </div>
                    <div class="truck-details">
                        <h3>Semi-Trailer Trucks</h3>
                        <p>Our fleet of semi-trailer trucks are equipped for long-haul transportation with maximum efficiency and safety.</p>
                        <div class="truck-features">
                            <div class="truck-feature">
                                <i class="fas fa-weight-hanging"></i>
                                <div>40,000 lbs</div>
                            </div>
                            <div class="truck-feature">
                                <i class="fas fa-ruler-combined"></i>
                                <div>53 ft</div>
                            </div>
                            <div class="truck-feature">
                                <i class="fas fa-truck-loading"></i>
                                <div>Dry Van</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="truck-card">
                    <div class="truck-image">
                        <img src="https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Refrigerated Truck">
                    </div>
                    <div class="truck-details">
                        <h3>Refrigerated Trucks</h3>
                        <p>Temperature-controlled transportation for perishable goods with real-time monitoring.</p>
                        <div class="truck-features">
                            <div class="truck-feature">
                                <i class="fas fa-snowflake"></i>
                                <div>-20°F to 70°F</div>
                            </div>
                            <div class="truck-feature">
                                <i class="fas fa-ruler-combined"></i>
                                <div>48 ft</div>
                            </div>
                            <div class="truck-feature">
                                <i class="fas fa-truck-loading"></i>
                                <div>Reefer</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="truck-card">
                    <div class="truck-image">
                        <img src="https://images.unsplash.com/photo-1603732551681-2e91159b9dc2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Box Truck">
                    </div>
                    <div class="truck-details">
                        <h3>Box Trucks</h3>
                        <p>Versatile medium-duty trucks for local and regional deliveries with easy loading access.</p>
                        <div class="truck-features">
                            <div class="truck-feature">
                                <i class="fas fa-weight-hanging"></i>
                                <div>10,000 lbs</div>
                            </div>
                            <div class="truck-feature">
                                <i class="fas fa-ruler-combined"></i>
                                <div>26 ft</div>
                            </div>
                            <div class="truck-feature">
                                <i class="fas fa-truck-loading"></i>
                                <div>LTL</div>
                            </div>
                        </div>
                    </div>
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
    
    <!-- Privacy Policy Section -->
    <section class="legal-page" id="privacy">
        <div class="container">
            <div class="legal-content">
                <h2>Privacy Policy for G & T 5206 Investments LLC</h2>
                <p>Last updated: August 10, 2023</p>
                
                <p>G & T 5206 Investments LLC ("us", "we", or "our") operates the https://gtinvestments5206.com website (the "Service").</p>
                
                <p>This page informs you of our policies regarding the collection, use, and disclosure of personal data when you use our Service and the choices you have associated with that data.</p>
                
                <h3>Information Collection and Use</h3>
                <p>We collect several different types of information for various purposes to provide and improve our Service to you.</p>
                
                <h3>Types of Data Collected</h3>
                <p><strong>Personal Data</strong></p>
                <p>While using our Service, we may ask you to provide us with certain personally identifiable information that can be used to contact or identify you ("Personal Data"). Personally identifiable information may include, but is not limited to:</p>
                <ul>
                    <li>Email address</li>
                    <li>First name and last name</li>
                    <li>Phone number</li>
                    <li>Address, State, Province, ZIP/Postal code, City</li>
                    <li>Cookies and Usage Data</li>
                </ul>
                
                <h3>Use of Data</h3>
                <p>G & T 5206 Investments LLC uses the collected data for various purposes:</p>
                <ul>
                    <li>To provide and maintain our Service</li>
                    <li>To notify you about changes to our Service</li>
                    <li>To allow you to participate in interactive features of our Service when you choose to do so</li>
                    <li>To provide customer support</li>
                    <li>To gather analysis or valuable information so that we can improve our Service</li>
                    <li>To monitor the usage of our Service</li>
                    <li>To detect, prevent and address technical issues</li>
                </ul>
                
                <h3>Data Security</h3>
                <p>The security of your data is important to us, but remember that no method of transmission over the Internet, or method of electronic storage is 100% secure. While we strive to use commercially acceptable means to protect your Personal Data, we cannot guarantee its absolute security.</p>
                
                <h3>Changes to This Privacy Policy</h3>
                <p>We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page.</p>
                
                <p>We will let you know via email and/or a prominent notice on our Service, prior to the change becoming effective and update the "effective date" at the top of this Privacy Policy.</p>
                
                <p>You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted on this page.</p>
                
                <h3>Contact Us</h3>
                <p>If you have any questions about this Privacy Policy, please contact us:</p>
                <p>By email: hashmiumaiz@gmail.com<br>
                By phone: (267) 500-5667</p>
                
                <a href="#" class="btn btn-primary back-to-home">
                    <i class="fas fa-arrow-left"></i> Back to Home
                </a>
            </div>
        </div>
    </section>
    
    <!-- Terms & Conditions Section -->
    <section class="legal-page" id="terms">
        <div class="container">
            <div class="legal-content">
                <h2>Terms and Conditions for G & T 5206 Investments LLC</h2>
                <p>Last updated: August 10, 2023</p>
                
                <p>Please read these Terms and Conditions ("Terms", "Terms and Conditions") carefully before using the https://gtinvestments5206.com website (the "Service") operated by G & T 5206 Investments LLC ("us", "we", or "our").</p>
                
                <p>Your access to and use of the Service is conditioned on your acceptance of and compliance with these Terms. These Terms apply to all visitors, users and others who access or use the Service.</p>
                
                <h3>Accounts</h3>
                <p>When you create an account with us, you must provide us information that is accurate, complete, and current at all times. Failure to do so constitutes a breach of the Terms, which may result in immediate termination of your account on our Service.</p>
                
                <h3>Intellectual Property</h3>
                <p>The Service and its original content, features and functionality are and will remain the exclusive property of G & T 5206 Investments LLC and its licensors. The Service is protected by copyright, trademark, and other laws of both the United States and foreign countries. Our trademarks and trade dress may not be used in connection with any product or service without the prior written consent of G & T 5206 Investments LLC.</p>
                
                <h3>Links To Other Web Sites</h3>
                <p>Our Service may contain links to third-party web sites or services that are not owned or controlled by G & T 5206 Investments LLC.</p>
                
                <p>G & T 5206 Investments LLC has no control over, and assumes no responsibility for, the content, privacy policies, or practices of any third party web sites or services. You further acknowledge and agree that G & T 5206 Investments LLC shall not be responsible or liable, directly or indirectly, for any damage or loss caused or alleged to be caused by or in connection with use of or reliance on any such content, goods or services available on or through any such web sites or services.</p>
                
                <h3>Termination</h3>
                <p>We may terminate or suspend access to our Service immediately, without prior notice or liability, for any reason whatsoever, including without limitation if you breach the Terms.</p>
                
                <p>All provisions of the Terms which by their nature should survive termination shall survive termination, including, without limitation, ownership provisions, warranty disclaimers, indemnity and limitations of liability.</p>
                
                <h3>Limitation of Liability</h3>
                <p>In no event shall G & T 5206 Investments LLC, nor its directors, employees, partners, agents, suppliers, or affiliates, be liable for any indirect, incidental, special, consequential or punitive damages, including without limitation, loss of profits, data, use, goodwill, or other intangible losses, resulting from (i) your access to or use of or inability to access or use the Service; (ii) any conduct or content of any third party on the Service; (iii) any content obtained from the Service; and (iv) unauthorized access, use or alteration of your transmissions or content, whether based on warranty, contract, tort (including negligence) or any other legal theory, whether or not we have been informed of the possibility of such damage, and even if a remedy set forth herein is found to have failed of its essential purpose.</p>
                
                <h3>Changes</h3>
                <p>We reserve the right, at our sole discretion, to modify or replace these Terms at any time. If a revision is material we will try to provide at least 30 days notice prior to any new terms taking effect. What constitutes a material change will be determined at our sole discretion.</p>
                
                <h3>Contact Us</h3>
                <p>If you have any questions about these Terms, please contact us:</p>
                <p>By email: hashmiumaiz@gmail.com<br>
                By phone: (267) 500-5667</p>
                
                <a href="#" class="btn btn-primary back-to-home">
                    <i class="fas fa-arrow-left"></i> Back to Home
                </a>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>G & T Investments 5206</h3>
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
                        <li><a href="#fleet">Our Fleet</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Our Services</h3>
                    <ul class="footer-links">
                        <li><a href="#services">Freight Transportation</a></li>
                        <li><a href="#services">Warehousing Solutions</a></li>
                        <li><a href="#services">Supply Chain Management</a></li>
                        <li><a href="#services">Expedited Shipping</a></li>
                        <li><a href="#services">Nationwide Distribution</a></li>
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
                <p>&copy; 2023 G & T 5206 Investments LLC. All Rights Reserved. 
                   <a href="#privacy" style="color: #bbb; margin-left: 15px;">Privacy Policy</a> 
                   <a href="#terms" style="color: #bbb; margin-left: 10px;">Terms & Conditions</a>
                </p>
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
        
        // Header scroll effect
        window.addEventListener('scroll', function() {
            const header = document.getElementById('header');
            if (window.scrollY > 50) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        });
        
        // Smooth Scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
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
                if (link.getAttribute('href') === `#${current}`) {
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
        
        // Initialize header
        window.dispatchEvent(new Event('scroll'));
    </script>
</body>
</html>
