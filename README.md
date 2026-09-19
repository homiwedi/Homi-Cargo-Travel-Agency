<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homi Cargo & Travel | Asmara & World Wide</title>
    <style>
        :root {
            --primary: #0056b3; /* Deep Blue */
            --secondary: #ff9f43; /* Orange/Gold for accents */
            --dark: #2c3e50;
            --light: #f4f7f6;
            --white: #ffffff;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }
        /* Navigation */
        nav {
            background-color: var(--white);
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary);
            text-decoration: none;
        }
        .nav-links a {
            margin-left: 20px;
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
        }
        .btn-nav {
            background-color: var(--primary);
            color: white !important;
            padding: 8px 15px;
            border-radius: 5px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 86, 179, 0.8), rgba(0, 86, 179, 0.8)), url('https://images.unsplash.com/photo-1578575437130-527eed3abbec?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
        }
        .cta-button {
            margin-top: 20px;
            background-color: var(--secondary);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: 0.3s;
        }
        .cta-button:hover {
            transform: scale(1.05);
        }

        /* Services Grid */
        .section-title {
            text-align: center;
            margin: 50px 0 20px;
            color: var(--primary);
        }
        .services-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px 5%;
            max-width: 1200px;
            margin: 0 auto;
        }
        .service-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            text-align: center;
            border-top: 5px solid var(--primary);
        }
        .price-tag {
            font-size: 2rem;
            font-weight: bold;
            color: var(--secondary);
            margin: 10px 0;
        }
        
        /* Contact & Drop Zone */
        .contact-section {
            background-color: var(--dark);
            color: white;
            padding: 50px 5%;
            margin-top: 50px;
        }
        .form-container {
            max-width: 600px;
            margin: 0 auto;
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 10px;
        }
        input, textarea, select {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            box-sizing: border-box;
        }
        button.submit-btn {
            width: 100%;
            background-color: var(--secondary);
            color: white;
            border: none;
            padding: 15px;
            font-size: 1.1rem;
            cursor: pointer;
            border-radius: 5px;
            font-weight: bold;
        }
        button.submit-btn:hover {
            background-color: #e68a2d;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1a252f;
            color: #aaa;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            nav { flex-direction: column; gap: 10px; }
            .nav-links { margin-top: 10px; }
            .nav-links a { margin: 0 10px; }
        }
    </style>
</head>
<body>

<!-- NAVIGATION -->
<nav>
    <a href="#" class="logo">HOMI CARGO & TRAVEL</a>
    <div class="nav-links">
        <a href="#services">Services</a>
        <a href="#prices">Prices</a>
        <a href="booking.html">Book Flights/Tours</a>
        <a href="#contact" class="btn-nav">Contact Us</a>
    </div>
</nav>

<!-- HERO SECTION -->
<section class="hero">
    <h1>Fast Shipping to Asmara & Worldwide</h1>
    <p>Cheap Flight Tickets • Luxury Tours • Secure Cargo Delivery</p>
    <a href="#contact" class="cta-button">Get a Quote Now</a>
</section>

<!-- SERVICES & PRICES -->
<h2 id="services" class="section-title">Our Premium Services</h2>
<div class="services-container">
    
    <!-- Cargo Service -->
    <div class="service-card">
        <h3>✈️ Air Cargo</h3>
        <p>Direct flights to Asmara, Eritrea and major global hubs.</p>
        <div class="price-tag">$5 / Kg</div>
        <p><small>Flat rate for standard parcels. Documents & Heavy machinery available.</small></p>
    </div>

    <!-- Travel Service -->
    <div class="service-card">
        <h3>🌍 Global Tours</h3>
        <p>Kampala City Tours, Safari Packages, and International Holidays.</p>
        <div class="price-tag">From $200</div>
        <p><small>All-inclusive guides, hotels, and transport included.</small></p>
    </div>

    <!-- Ticketing Service -->
    <div class="service-card">
        <h3>🎫 Cheap Tickets</h3>
        <p>We find the lowest fares for Uganda, Eritrea, Europe, and Asia.</p>
        <div class="price-tag">Best Price Guarantee</div>
        <p><small>Contact us for personalized flight quotes.</small></p>
    </div>

</div>

<!-- CONTACT & DROP ZONE FORM -->
<section id="contact" class="contact-section">
    <h2 style="text-align:center; color:white;">Send Files & Get Quotes</h2>
    <p style="text-align:center; margin-bottom: 30px;">Upload your cargo manifest, passport copies, or just ask a question.</p>
    
    <div class="form-container">
        <!-- NETLIFY FORM CODE STARTS HERE -->
        <form name="cargo-contact" method="POST" data-netlify="true" enctype="multipart/form-data">
            <input type="hidden" name="form-name" value="cargo-contact">
            
            <label>Name:</label>
            <input type="text" name="name" placeholder="Your Full Name" required>
            
            <label>Email Address:</label>
            <input type="email" name="email" placeholder="your@email.com" required>
            
            <label>Phone Number (WhatsApp/SMS):</label>
            <input type="tel" name="phone" placeholder="+256... or +291..." required>
            
            <label>Service Needed:</label>
            <select name="service">
                <option value="cargo">Cargo ($5/kg)</option>
                <option value="flight">Flight Ticket</option>
                <option value="tour">Tour Package</option>
                <option value="other">Other Inquiry</option>
            </select>

            <label>Message / Details:</label>
            <textarea name="message" rows="4" placeholder="Where are you sending to? What dates?" required></textarea>
            
            <label>Attach Document/Image (Optional):</label>
            <input type="file" name="attachment">

            <button type="submit" class="submit-btn">Submit Request 🚀</button>
        </form>
        <!-- NETLIFY FORM CODE ENDS HERE -->
    </div>
</section>

<footer>
    &copy; 2026 Homi Cargo & Travel Agency.<br>
    Serving Kampala, Asmara, and the World.<br>
    Email: info@homitravel.com | Phone: +256 700 000 000
</footer>

</body>
</html>
