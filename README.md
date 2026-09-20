<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Your Trip - Homi Cargo & Travel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
        }
        nav {
            background-color: #0056b3;
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            color: white;
            font-weight: bold;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .back-link {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
        }
        h1 {
            color: #0056b3;
            text-align: center;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        /* Using simple colors if images fail to load */
        .img-kampala { background-color: #ff9f43; } 
        .img-asmera { background-color: #00a8e8; }
        .img-flight { background-color: #6c5ce7; }
        
        .card-body {
            padding: 20px;
        }
        .card-title {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 10px;
            color: #0056b3;
        }
        .card-price {
            color: #ff9f43;
            font-weight: bold;
            font-size: 1.1rem;
            margin-bottom: 15px;
            display: block;
        }
        .btn-book {
            display: inline-block;
            background-color: #0056b3;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 50px;
            background: #eee;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<nav>
    <a href="index.html" class="logo">HOMI CARGO & TRAVEL</a>
    <a href="index.html" class="back-link">&larr; Back to Home</a>
</nav>

<div class="container">
    <h1>Explore Destinations & Deals</h1>
    <p style="text-align:center;">Special offers for Kampala, Asmara, and International Routes.</p>

    <div class="grid">
        <!-- Item 1: Kampala Tour -->
        <div class="card">
            <div class="card-img img-kampala"></div>
            <div class="card-body">
                <div class="card-title">Kampala City Tour</div>
                <p>Experience the vibrant culture of Uganda's capital. Includes Lake Victoria views and local markets.</p>
                <span class="card-price">$150 / Person</span>
                <a href="index.html#contact" class="btn-book">Book This Tour</a>
            </div>
        </div>

        <!-- Item 2: Asmara Heritage -->
        <div class="card">
            <div class="card-img img-asmera"></div>
            <div class="card-body">
                <div class="card-title">Asmara Heritage Walk</div>
                <p>Discover the Italian modernist architecture of Eritrea's beautiful capital city.</p>
                <span class="card-price">$200 / Person</span>
                <a href="index.html#contact" class="btn-book">Book This Tour</a>
            </div>
        </div>

        <!-- Item 3: Flight Deal -->
        <div class="card">
            <div class="card-img img-flight"></div>
            <div class="card-body">
                <div class="card-title">Uganda ➔ Middle East</div>
                <p>Discounted economy class tickets. Limited seats available for next month departures.</p>
                <span class="card-price">From $450 Roundtrip</span>
                <a href="index.html#contact" class="btn-book">Check Availability</a>
            </div>
        </div>
    </div>
</div>

<footer>
    Need custom pricing? Call us directly!<br>
    <strong>+256 700 000 000</strong>
</footer>

</body>
</html>            border-top: 5px solid var(--primary);
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
