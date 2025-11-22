<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ocala Innovation Partners - Building a $1B+ integrated ecosystem at the intersection of equine genetics, AI technology, and advanced mobility.">
    <title>Ocala Innovation Partners | $959M-$1.5B Exit Opportunity</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --primary: #8B0000;
            --primary-light: #B22222;
            --primary-dark: #6B0000;
            --accent: #FFD700;
            --dark: #1a1a1a;
            --gray: #333;
            --light-gray: #f5f5f5;
            --white: #ffffff;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            overflow-x: hidden;
        }
        
        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(26, 26, 26, 0.95);
            backdrop-filter: blur(10px);
            padding: 20px 0;
            z-index: 1000;
            border-bottom: 1px solid rgba(139, 0, 0, 0.3);
        }
        
        nav .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        nav .logo {
            font-size: 24px;
            font-weight: bold;
            color: var(--primary);
            text-decoration: none;
        }
        
        nav .nav-links {
            display: flex;
            gap: 30px;
            list-style: none;
        }
        
        nav .nav-links a {
            color: var(--white);
            text-decoration: none;
            transition: color 0.3s;
            font-size: 16px;
        }
        
        nav .nav-links a:hover {
            color: var(--accent);
        }
        
        .cta-button {
            background: var(--primary);
            color: var(--white);
            padding: 12px 30px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
            display: inline-block;
        }
        
        .cta-button:hover {
            background: var(--primary-light);
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(139, 0, 0, 0.3);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--dark) 0%, var(--gray) 100%);
            color: var(--white);
            padding: 180px 20px 100px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg"><defs><pattern id="grid" width="100" height="100" patternUnits="userSpaceOnUse"><path d="M 100 0 L 0 0 0 100" fill="none" stroke="rgba(139,0,0,0.1)" stroke-width="1"/></pattern></defs><rect width="100%" height="100%" fill="url(%23grid)"/></svg>');
            opacity: 0.3;
        }
        
        .hero .container {
            max-width: 1000px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }
        
        .hero h1 {
            font-size: 56px;
            font-weight: 800;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero .highlight {
            color: var(--accent);
        }
        
        .hero .subtitle {
            font-size: 24px;
            margin-bottom: 30px;
            color: rgba(255, 255, 255, 0.9);
            font-weight: 300;
        }
        
        .hero .value-prop {
            font-size: 28px;
            margin-bottom: 40px;
            padding: 20px;
            background: rgba(139, 0, 0, 0.2);
            border-radius: 10px;
            border: 2px solid var(--primary);
        }
        
        .hero-stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin-top: 60px;
        }
        
        .stat {
            padding: 30px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(139, 0, 0, 0.3);
        }
        
        .stat-number {
            font-size: 48px;
            font-weight: bold;
            color: var(--accent);
            margin-bottom: 10px;
        }
        
        .stat-label {
            font-size: 16px;
            color: rgba(255, 255, 255, 0.8);
        }
        
        /* Sections */
        .section {
            padding: 100px 20px;
        }
        
        .section.dark {
            background: var(--dark);
            color: var(--white);
        }
        
        .section.light {
            background: var(--light-gray);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .section-header {
            text-align: center;
            margin-bottom: 60px;
        }
        
        .section-header h2 {
            font-size: 42px;
            font-weight: 700;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .section.dark .section-header h2 {
            color: var(--white);
        }
        
        .section-header p {
            font-size: 20px;
            color: #666;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .section.dark .section-header p {
            color: rgba(255, 255, 255, 0.8);
        }
        
        /* Portfolio Grid */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
        }
        
        .portfolio-card {
            background: var(--white);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
            transition: all 0.3s;
            border: 2px solid transparent;
        }
        
        .portfolio-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 60px rgba(139, 0, 0, 0.2);
            border-color: var(--primary);
        }
        
        .portfolio-card h3 {
            font-size: 28px;
            color: var(--primary);
            margin-bottom: 15px;
        }
        
        .portfolio-card .tagline {
            font-size: 18px;
            color: #666;
            margin-bottom: 20px;
            font-style: italic;
        }
        
        .portfolio-card ul {
            list-style: none;
            margin: 20px 0;
        }
        
        .portfolio-card li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
            color: #444;
        }
        
        .portfolio-card li::before {
            content: '→';
            position: absolute;
            left: 0;
            color: var(--primary);
            font-weight: bold;
        }
        
        .portfolio-card .metrics {
            background: var(--light-gray);
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
        }
        
        .portfolio-card .metrics strong {
            color: var(--primary);
        }
        
        /* Ecosystem Diagram */
        .ecosystem {
            background: var(--white);
            padding: 60px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
        }
        
        .ecosystem-visual {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin: 40px 0;
        }
        
        .ecosystem-item {
            padding: 30px;
            background: linear-gradient(135deg, var(--primary-dark), var(--primary));
            color: var(--white);
            border-radius: 15px;
            position: relative;
        }
        
        .ecosystem-item h4 {
            font-size: 20px;
            margin-bottom: 10px;
        }
        
        .ecosystem-item p {
            font-size: 14px;
            opacity: 0.9;
        }
        
        .ecosystem-center {
            grid-column: 1 / -1;
            background: var(--accent);
            color: var(--dark);
            padding: 40px;
            font-size: 24px;
            font-weight: bold;
        }
        
        /* Financial Highlights */
        .financial-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin-top: 40px;
        }
        
        .financial-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 40px;
            border-radius: 15px;
            text-align: center;
            border: 2px solid rgba(139, 0, 0, 0.3);
        }
        
        .financial-card h3 {
            font-size: 18px;
            color: rgba(255, 255, 255, 0.7);
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .financial-card .big-number {
            font-size: 48px;
            font-weight: bold;
            color: var(--accent);
            margin-bottom: 10px;
        }
        
        .financial-card p {
            font-size: 16px;
            color: rgba(255, 255, 255, 0.8);
        }
        
        /* Revenue Chart */
        .revenue-chart {
            background: var(--white);
            padding: 40px;
            border-radius: 15px;
            margin-top: 40px;
        }
        
        .chart-bars {
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            height: 300px;
            margin: 40px 0;
        }
        
        .chart-bar {
            flex: 1;
            margin: 0 10px;
            background: linear-gradient(to top, var(--primary-dark), var(--primary-light));
            border-radius: 8px 8px 0 0;
            position: relative;
            transition: all 0.3s;
        }
        
        .chart-bar:hover {
            background: linear-gradient(to top, var(--primary), var(--accent));
            transform: translateY(-10px);
        }
        
        .chart-bar .value {
            position: absolute;
            top: -30px;
            left: 50%;
            transform: translateX(-50%);
            font-weight: bold;
            color: var(--primary);
            white-space: nowrap;
        }
        
        .chart-bar .label {
            text-align: center;
            margin-top: 10px;
            font-weight: 600;
            color: #666;
        }
        
        /* Competitive Advantages */
        .advantages-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 30px;
        }
        
        .advantage-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 10px;
            border-left: 4px solid var(--accent);
        }
        
        .advantage-card h3 {
            color: var(--accent);
            margin-bottom: 15px;
            font-size: 22px;
        }
        
        .advantage-card p {
            color: rgba(255, 255, 255, 0.8);
        }
        
        /* Team Section */
        .team-card {
            background: var(--white);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
        }
        
        .team-card h3 {
            color: var(--primary);
            font-size: 24px;
            margin-bottom: 15px;
        }
        
        .team-card h4 {
            color: #666;
            font-size: 18px;
            margin-bottom: 20px;
        }
        
        .team-card ul {
            list-style: none;
        }
        
        .team-card li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
            color: #444;
        }
        
        .team-card li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--primary);
            font-weight: bold;
            font-size: 18px;
        }
        
        /* Investor CTA */
        .investor-cta {
            background: linear-gradient(135deg, var(--primary-dark), var(--primary));
            color: var(--white);
            padding: 80px 20px;
            text-align: center;
        }
        
        .investor-cta h2 {
            font-size: 42px;
            margin-bottom: 20px;
        }
        
        .investor-cta p {
            font-size: 20px;
            margin-bottom: 40px;
            opacity: 0.9;
        }
        
        .investor-cta .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .cta-primary {
            background: var(--accent);
            color: var(--dark);
            padding: 18px 40px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 700;
            font-size: 18px;
            transition: all 0.3s;
            display: inline-block;
        }
        
        .cta-primary:hover {
            background: var(--white);
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(255, 215, 0, 0.3);
        }
        
        .cta-secondary {
            background: transparent;
            color: var(--white);
            padding: 18px 40px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 700;
            font-size: 18px;
            border: 2px solid var(--white);
            transition: all 0.3s;
            display: inline-block;
        }
        
        .cta-secondary:hover {
            background: var(--white);
            color: var(--primary);
        }
        
        /* Contact Form */
        .contact-form {
            background: var(--white);
            padding: 60px;
            border-radius: 20px;
            max-width: 700px;
            margin: 0 auto;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 25px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: var(--dark);
        }
        
        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 15px;
            border: 2px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s;
        }
        
        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: var(--primary);
        }
        
        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }
        
        .submit-button {
            width: 100%;
            padding: 18px;
            background: var(--primary);
            color: var(--white);
            border: none;
            border-radius: 8px;
            font-size: 18px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .submit-button:hover {
            background: var(--primary-light);
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(139, 0, 0, 0.3);
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: var(--white);
            padding: 60px 20px 30px;
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-section h3 {
            color: var(--primary);
            margin-bottom: 20px;
        }
        
        .footer-section ul {
            list-style: none;
        }
        
        .footer-section li {
            margin-bottom: 10px;
        }
        
        .footer-section a {
            color: rgba(255, 255, 255, 0.7);
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-section a:hover {
            color: var(--accent);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.5);
        }
        
        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .fade-in-up {
            animation: fadeInUp 0.8s ease-out forwards;
        }
        
        /* Responsive */
        @media (max-width: 968px) {
            .hero h1 {
                font-size: 42px;
            }
            
            .hero-stats,
            .portfolio-grid,
            .financial-grid,
            .advantages-grid,
            .footer-content {
                grid-template-columns: 1fr;
            }
            
            .ecosystem-visual {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .nav-links {
                display: none;
            }
            
            .chart-bars {
                height: 250px;
            }
        }
        
        /* Scroll Progress Bar */
        .progress-bar {
            position: fixed;
            top: 0;
            left: 0;
            height: 4px;
            background: var(--accent);
            z-index: 9999;
            transition: width 0.1s;
        }
    </style>
</head>
<body>
    <!-- Progress Bar -->
    <div class="progress-bar" id="progressBar"></div>
    
    <!-- Navigation -->
    <nav>
        <div class="container">
            <a href="#" class="logo">OCALA INNOVATION PARTNERS</a>
            <ul class="nav-links">
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#financials">Financials</a></li>
                <li><a href="#team">Team</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <a href="#contact" class="cta-button">Request Info</a>
        </div>
    </nav>
    
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1 class="fade-in-up">Building the Future of <span class="highlight">Equine Excellence</span></h1>
            <p class="subtitle fade-in-up">An integrated ecosystem of high-growth businesses at the intersection of genetics, AI technology, and advanced mobility</p>
            <div class="value-prop fade-in-up">
                <strong>$6.2M Capital Raise</strong> | <strong>$959M-$1.5B Exit Target</strong> (Year 5-7)
            </div>
            <div class="hero-stats">
                <div class="stat fade-in-up">
                    <div class="stat-number">$116M</div>
                    <div class="stat-label">Year 5 Revenue Target</div>
                </div>
                <div class="stat fade-in-up">
                    <div class="stat-number">70%</div>
                    <div class="stat-label">EBITDA Margin (Year 5)</div>
                </div>
                <div class="stat fade-in-up">
                    <div class="stat-number">6</div>
                    <div class="stat-label">Integrated Businesses</div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- The Opportunity -->
    <section class="section light">
        <div class="container">
            <div class="section-header">
                <h2>The Opportunity</h2>
                <p>We're not building a business. We're building an ecosystem that creates unbeatable competitive moats through data, location, and integration.</p>
            </div>
            <div class="ecosystem">
                <h3 style="font-size: 32px; margin-bottom: 30px; color: var(--primary);">How The Ecosystem Works</h3>
                <div class="ecosystem-visual">
                    <div class="ecosystem-item">
                        <h4>EquiGenix Performance Pro</h4>
                        <p>Collects genetic data from elite horses</p>
                    </div>
                    <div class="ecosystem-item">
                        <h4>Pinnacle Equine</h4>
                        <p>Analyzes genetics, creates nutrition plans</p>
                    </div>
                    <div class="ecosystem-item">
                        <h4>Horse Capital Nutrition</h4>
                        <p>Fulfills custom supplement subscriptions</p>
                    </div>
                    <div class="ecosystem-item">
                        <h4>Sire & Shield</h4>
                        <p>Provides genetic risk-based insurance</p>
                    </div>
                    <div class="ecosystem-item">
                        <h4>Elite Experiences</h4>
                        <p>Cross-sells to wealthy WEC attendees</p>
                    </div>
                    <div class="ecosystem-item">
                        <h4>eVTOL Infrastructure</h4>
                        <p>Brings ultra-wealthy to all businesses</p>
                    </div>
                    <div class="ecosystem-center">
                        Each business makes the others MORE valuable<br>
                        <span style="font-size: 18px; opacity: 0.8;">Customer LTV: $250K-$1M across all touchpoints</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Portfolio -->
    <section id="portfolio" class="section">
        <div class="container">
            <div class="section-header">
                <h2>The Portfolio</h2>
                <p>Six complementary businesses that share customers, data, and infrastructure</p>
            </div>
            <div class="portfolio-grid">
                <div class="portfolio-card">
                    <h3>1. EquiGenix Performance Pro</h3>
                    <p class="tagline">Elite Genetic Testing & DNA Databases</p>
                    <ul>
                        <li>Comprehensive 40+ SNP genetic panels</li>
                        <li>Performance trait analysis & predictions</li>
                        <li>DNA database and parentage verification</li>
                        <li>Pre-purchase genetic evaluations</li>
                        <li>Breeding optimization analysis</li>
                        <li>Partners: Animal Genetics, UC Davis VGL</li>
                    </ul>
                    <div class="metrics">
                        <p><strong>Year 5:</strong> $12.5M revenue | 90% gross margin</p>
                        <p><strong>Exit:</strong> $188M-$313M (Neogen, Zoetis)</p>
                    </div>
                </div>
                
                <div class="portfolio-card">
                    <h3>2. Pinnacle Equine</h3>
                    <p class="tagline">Advanced Nutrigenomics & Personalized Nutrition</p>
                    <ul>
                        <li>Genetic nutrition consultations</li>
                        <li>AI-powered supplement recommendations</li>
                        <li>Quarterly optimization programs</li>
                        <li>Competition preparation nutrition</li>
                        <li>Training barn consultation services</li>
                        <li>On-site at World Equestrian Center</li>
                    </ul>
                    <div class="metrics">
                        <p><strong>Year 5:</strong> $7.8M revenue | 85% gross margin</p>
                        <p><strong>Exit:</strong> $94M-$156M (Strategic wellness buyer)</p>
                    </div>
                </div>
                
                <div class="portfolio-card">
                    <h3>3. Horse Capital Nutrition</h3>
                    <p class="tagline">Premium Equine Supplements & Nutrition Products</p>
                    <ul>
                        <li>Custom-formulated genetic-based supplements</li>
                        <li>Monthly subscription service ($249-$399)</li>
                        <li>Marine collagen delivery systems</li>
                        <li>Retail location at WEC</li>
                        <li>GMP-certified manufacturing (Uckele)</li>
                        <li>2,500 elite racing stables target</li>
                    </ul>
                    <div class="metrics">
                        <p><strong>Year 5:</strong> $79.5M revenue | 82% gross margin</p>
                        <p><strong>Exit:</strong> $636M-$954M (Mars Petcare, Zoetis)</p>
                    </div>
                </div>
                
                <div class="portfolio-card">
                    <h3>4. Sire & Shield</h3>
                    <p class="tagline">Specialty Horse & Dog Insurance</p>
                    <ul>
                        <li>Equine mortality & loss of use insurance</li>
                        <li>Major medical coverage</li>
                        <li>Genetic risk-based underwriting</li>
                        <li>Expanding into canine insurance</li>
                        <li>Office at World Equestrian Center</li>
                        <li>85% gross margins (commission-based)</li>
                    </ul>
                    <div class="metrics">
                        <p><strong>Year 5:</strong> $12.3M revenue | 85% gross margin</p>
                        <p><strong>Exit:</strong> $148M-$246M (Markel, insurance brokerages)</p>
                    </div>
                </div>
                
                <div class="portfolio-card">
                    <h3>5. Ocala Elite Experiences</h3>
                    <p class="tagline">Premium Events at World Equestrian Center</p>
                    <ul>
                        <li>Corporate event production ($75K-500K each)</li>
                        <li>VIP membership club "The Paddock Club"</li>
                        <li>Elite rider brand management</li>
                        <li>Exclusive WEC partnership</li>
                        <li>IATSE Local 631 crew relationships</li>
                        <li>First revenue within 90 days</li>
                    </ul>
                    <div class="metrics">
                        <p><strong>Year 5:</strong> $15M revenue | 55% gross margin</p>
                        <p><strong>Exit:</strong> $45M-$75M (ASM Global, Live Nation)</p>
                    </div>
                </div>
                
                <div class="portfolio-card">
                    <h3>6. AAM Infrastructure Partners</h3>
                    <p class="tagline">Advanced Air Mobility - eVTOL Vertiports</p>
                    <ul>
                        <li>WEC vertiport + Ocala Airport hub</li>
                        <li>First equestrian facility with eVTOL access</li>
                        <li>$5M-15M federal grants secured</li>
                        <li>Partnerships: Joby, Archer, Beta, Lilium</li>
                        <li>Commercial operations 2027-2028</li>
                        <li>70% gross margins on operations</li>
                    </ul>
                    <div class="metrics">
                        <p><strong>Year 5:</strong> $10M revenue | 70% gross margin</p>
                        <p><strong>Exit:</strong> $100M-$200M (eVTOL manufacturers)</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Financial Highlights -->
    <section id="financials" class="section dark">
        <div class="container">
            <div class="section-header">
                <h2>Financial Projections</h2>
                <p>Aggressive but achievable growth with expanding margins and multiple exit paths</p>
            </div>
            
            <div class="financial-grid">
                <div class="financial-card">
                    <h3>Year 1</h3>
                    <div class="big-number">$8.7M</div>
                    <p>Revenue | 26% EBITDA</p>
                </div>
                <div class="financial-card">
                    <h3>Year 3</h3>
                    <div class="big-number">$44.1M</div>
                    <p>Revenue | 60% EBITDA</p>
                </div>
                <div class="financial-card">
                    <h3>Year 5</h3>
                    <div class="big-number">$116M</div>
                    <p>Revenue | 70% EBITDA</p>
                </div>
            </div>
            
            <div class="revenue-chart">
                <h3 style="text-align: center; font-size: 28px; margin-bottom: 10px; color: var(--primary);">Revenue Growth Trajectory</h3>
                <p style="text-align: center; color: #666; margin-bottom: 40px;">Combined revenue across all business units (millions)</p>
                <div class="chart-bars">
                    <div class="chart-bar" style="height: 15%;">
                        <div class="value">$8.7M</div>
                    </div>
                    <div class="chart-bar" style="height: 38%;">
                        <div class="value">$22.8M</div>
                    </div>
                    <div class="chart-bar" style="height: 74%;">
                        <div class="value">$44.1M</div>
                    </div>
                    <div class="chart-bar" style="height: 85%;">
                        <div class="value">$75.9M</div>
                    </div>
                    <div class="chart-bar" style="height: 100%;">
                        <div class="value">$116M</div>
                    </div>
                </div>
                <div style="display: flex; justify-content: space-between;">
                    <div class="label">Year 1</div>
                    <div class="label">Year 2</div>
                    <div class="label">Year 3</div>
                    <div class="label">Year 4</div>
                    <div class="label">Year 5</div>
                </div>
            </div>
            
            <div style="background: rgba(255, 255, 255, 0.05); padding: 40px; border-radius: 15px; margin-top: 60px; text-align: center;">
                <h3 style="font-size: 32px; margin-bottom: 20px; color: var(--accent);">Unit Economics</h3>
                <div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 30px; margin-top: 30px;">
                    <div>
                        <p style="font-size: 16px; color: rgba(255,255,255,0.7); margin-bottom: 10px;">Customer LTV</p>
                        <p style="font-size: 36px; color: var(--accent); font-weight: bold;">$250K-$1M</p>
                    </div>
                    <div>
                        <p style="font-size: 16px; color: rgba(255,255,255,0.7); margin-bottom: 10px;">Blended CAC</p>
                        <p style="font-size: 36px; color: var(--accent); font-weight: bold;">$2,650</p>
                    </div>
                    <div>
                        <p style="font-size: 16px; color: rgba(255,255,255,0.7); margin-bottom: 10px;">LTV:CAC Ratio</p>
                        <p style="font-size: 36px; color: var(--accent); font-weight: bold;">94:1 - 377:1</p>
                    </div>
                    <div>
                        <p style="font-size: 16px; color: rgba(255,255,255,0.7); margin-bottom: 10px;">Payback Period</p>
                        <p style="font-size: 36px; color: var(--accent); font-weight: bold;">5-6 months</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Competitive Advantages -->
    <section class="section light">
        <div class="container">
            <div class="section-header">
                <h2>Why We Win</h2>
                <p>Multiple defensible moats that compound over time</p>
            </div>
            <div class="advantages-grid">
                <div class="advantage-card" style="background: var(--white); color: var(--dark);">
                    <h3>Data Moat</h3>
                    <p>Every genetic test strengthens our AI algorithm. By Year 5, we'll have the world's largest proprietary equine genetic database—impossible to replicate.</p>
                </div>
                <div class="advantage-card" style="background: var(--white); color: var(--dark);">
                    <h3>Geographic Monopoly</h3>
                    <p>First-mover in Ocala (Horse Capital of the World) + exclusive WEC partnership creates unbreakable local dominance.</p>
                </div>
                <div class="advantage-card" style="background: var(--white); color: var(--dark);">
                    <h3>Technology Lead</h3>
                    <p>18-24 month head start on competitors. Proprietary AI algorithms, genetic panels, and manufacturing partnerships can't be quickly replicated.</p>
                </div>
                <div class="advantage-card" style="background: var(--white); color: var(--dark);">
                    <h3>Network Effects</h3>
                    <p>Each business makes the others more valuable. Cross-selling reduces CAC by 60%. Customer LTV increases 3-4x through integrated services.</p>
                </div>
                <div class="advantage-card" style="background: var(--white); color: var(--dark);">
                    <h3>Infrastructure Assets</h3>
                    <p>eVTOL vertiports require $5M+ investment and 2+ years to build. Land appreciates 5-10x. First-mover becomes regional hub.</p>
                </div>
                <div class="advantage-card" style="background: var(--white); color: var(--dark);">
                    <h3>Patent Portfolio</h3>
                    <p>Patents pending on AI algorithms, genetic marker panels, and formulation methods. Trade secrets protect manufacturing and customer data.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Team -->
    <section id="team" class="section">
        <div class="container">
            <div class="section-header">
                <h2>Leadership & Execution</h2>
                <p>Proven entrepreneur with deep local expertise and established relationships</p>
            </div>
            <div class="team-card">
                <h3>Steve - Founder & CEO</h3>
                <h4>Proven Multi-Business Operator | Ocala Local Expert</h4>
                <ul>
                    <li><strong>15-20 years</strong> entertainment production (AV, rigging, event production)</li>
                    <li><strong>IATSE Local 631 member</strong> with exclusive WEC crew relationships</li>
                    <li><strong>Multiple successful ventures:</strong> LocalReach Events, Clean Slate Property Services, After Dark Eats, Showroom Quality, Union Built Supply</li>
                    <li><strong>Marketing consultant</strong> for major Ocala businesses</li>
                    <li><strong>Deep understanding</strong> of equine industry, nutrition science, and wellness</li>
                    <li><strong>Central Florida native</strong> with established community relationships</li>
                    <li><strong>Track record</strong> of building and scaling businesses from scratch</li>
                </ul>
                
                <h3 style="margin-top: 40px;">Advisory Board & Key Hires</h3>
                <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px; margin-top: 20px;">
                    <div>
                        <h4 style="color: var(--primary); font-size: 16px;">Scientific Advisor</h4>
                        <p style="color: #666;">Equine veterinarian, university research partnerships</p>
                    </div>
                    <div>
                        <h4 style="color: var(--primary); font-size: 16px;">Technology Advisor</h4>
                        <p style="color: #666;">AI/genomics executive from human health tech</p>
                    </div>
                    <div>
                        <h4 style="color: var(--primary); font-size: 16px;">CTO (Hiring)</h4>
                        <p style="color: #666;">PhD in genetics/bioinformatics, AI/ML platform development</p>
                    </div>
                    <div>
                        <h4 style="color: var(--primary); font-size: 16px;">Head of Sales (Hiring)</h4>
                        <p style="color: #666;">10+ years selling to elite racing operations</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Investment CTA -->
    <section class="investor-cta">
        <div class="container">
            <h2>Join Us in Building a $1B+ Company</h2>
            <p>At the intersection of genetics, technology, and luxury</p>
            <div class="cta-buttons">
                <a href="#contact" class="cta-primary">Request Investment Deck</a>
                <a href="#contact" class="cta-secondary">Schedule Meeting</a>
            </div>
            <div style="margin-top: 60px; padding-top: 40px; border-top: 1px solid rgba(255,255,255,0.2);">
                <p style="font-size: 24px; margin-bottom: 30px;"><strong>Investment Opportunity</strong></p>
                <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 40px; max-width: 900px; margin: 0 auto;">
                    <div>
                        <p style="font-size: 18px; opacity: 0.9; margin-bottom: 10px;">Capital Raise</p>
                        <p style="font-size: 32px; font-weight: bold; color: var(--accent);">$6.2M</p>
                    </div>
                    <div>
                        <p style="font-size: 18px; opacity: 0.9; margin-bottom: 10px;">Exit Timeline</p>
                        <p style="font-size: 32px; font-weight: bold; color: var(--accent);">5-7 Years</p>
                    </div>
                    <div>
                        <p style="font-size: 18px; opacity: 0.9; margin-bottom: 10px;">Target Exit</p>
                        <p style="font-size: 32px; font-weight: bold; color: var(--accent);">$959M-$1.5B</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact Form -->
    <section id="contact" class="section light">
        <div class="container">
            <div class="section-header">
                <h2>Get in Touch</h2>
                <p>Request our full investment memorandum and financial model</p>
            </div>
            <div class="contact-form">
                <form id="investorForm">
                    <div class="form-group">
                        <label for="name">Full Name *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email Address *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Phone Number</label>
                        <input type="tel" id="phone" name="phone">
                    </div>
                    <div class="form-group">
                        <label for="investor_type">Investor Type *</label>
                        <select id="investor_type" name="investor_type" required>
                            <option value="">Select...</option>
                            <option value="angel">Angel Investor</option>
                            <option value="vc">Venture Capital</option>
                            <option value="pe">Private Equity</option>
                            <option value="strategic">Strategic Buyer</option>
                            <option value="family">Family Office</option>
                            <option value="other">Other</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="interest">Areas of Interest *</label>
                        <select id="interest" name="interest" required>
                            <option value="">Select...</option>
                            <option value="full_platform">Full Platform Acquisition</option>
                            <option value="hcn">Horse Capital Nutrition</option>
                            <option value="analytics">Performance Analytics</option>
                            <option value="events">Elite Events</option>
                            <option value="evtol">eVTOL Infrastructure</option>
                            <option value="multiple">Multiple Businesses</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="investment_size">Investment Size Range</label>
                        <select id="investment_size" name="investment_size">
                            <option value="">Select...</option>
                            <option value="100k-250k">$100K - $250K</option>
                            <option value="250k-500k">$250K - $500K</option>
                            <option value="500k-1m">$500K - $1M</option>
                            <option value="1m-2m">$1M - $2M</option>
                            <option value="2m+">$2M+</option>
                            <option value="strategic">Strategic Acquisition</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" placeholder="Tell us about your investment focus, timeline, and any specific questions..."></textarea>
                    </div>
                    <button type="submit" class="submit-button">Request Investment Materials</button>
                    <p style="margin-top: 20px; font-size: 14px; color: #666; text-align: center;">
                        By submitting, you'll receive our full investment deck, financial model, and executive summary.
                        We typically respond within 24 hours.
                    </p>
                </form>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Ocala Innovation Partners</h3>
                <p style="color: rgba(255,255,255,0.7); margin-top: 15px;">
                    Building the future of equine excellence through integrated businesses in genetics, technology, events, and advanced mobility.
                </p>
                <p style="color: rgba(255,255,255,0.7); margin-top: 15px;">
                    Based in Ocala, Florida<br>
                    The Horse Capital of the World
                </p>
            </div>
            <div class="footer-section">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#financials">Financial Projections</a></li>
                    <li><a href="#team">Leadership Team</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>For Investors</h3>
                <ul>
                    <li><a href="#contact">Request Investment Deck</a></li>
                    <li><a href="#contact">Schedule Meeting</a></li>
                    <li><a href="#contact">Download Executive Summary</a></li>
                    <li><a href="#contact">View Data Room</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2025 Ocala Innovation Partners. All rights reserved. | Confidential - For Qualified Investors Only</p>
        </div>
    </footer>
    
    <script>
        // Scroll Progress Bar
        window.addEventListener('scroll', () => {
            const winScroll = document.body.scrollTop || document.documentElement.scrollTop;
            const height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            const scrolled = (winScroll / height) * 100;
            document.getElementById('progressBar').style.width = scrolled + '%';
        });
        
        // Smooth Scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
        
        // Form Submission
        document.getElementById('investorForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Collect form data
            const formData = new FormData(this);
            const data = Object.fromEntries(formData);
            
            // In production, this would send to your backend
            console.log('Form submitted:', data);
            
            // Show success message
            alert('Thank you for your interest! We will send you the full investment materials within 24 hours and reach out to schedule a call.');
            
            // Reset form
            this.reset();
        });
        
        // Intersection Observer for fade-in animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);
        
        // Observe all cards and sections
        document.querySelectorAll('.portfolio-card, .advantage-card, .financial-card, .stat').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'all 0.6s ease-out';
            observer.observe(el);
        });
    </script>
</body>
</html>
