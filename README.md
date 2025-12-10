<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wahid AC Service</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif;}
        body {background:#f4f9ff; color:#333;}
        header {background:#0077b6; color:white; padding:20px 0; position:sticky; top:0; z-index:1000;}
        header .container {display:flex; justify-content:space-between; align-items:center; max-width:1200px; margin:auto; padding:0 20px;}
        header h1 {font-size:28px;}
        header nav a {color:white; margin-left:20px; text-decoration:none; font-weight:600;}
        header nav a:hover {text-decoration:underline;}

        .hero {background:#00b4d8; color:white; text-align:center; padding:100px 20px; background-image: url('https://images.unsplash.com/photo-1610396773161-7a6b1f7b9b7a?auto=format&fit=crop&w=1350&q=80'); background-size:cover; background-position:center;}
        .hero h2 {font-size:48px; margin-bottom:20px; text-shadow:2px 2px 4px #000;}
        .hero p {font-size:20px; margin-bottom:30px;}
        .hero .btn {background:#0077b6; color:white; padding:15px 30px; font-size:18px; text-decoration:none; border-radius:5px;}
        .hero .btn:hover {background:#023e8a;}

        .container {max-width:1200px; margin:auto; padding:50px 20px;}
        .services {display:flex; flex-wrap:wrap; gap:20px; justify-content:center;}
        .service-box {background:white; flex:1 1 250px; padding:30px; text-align:center; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1);}
        .service-box i {font-size:50px; color:#00b4d8; margin-bottom:20px;}
        .service-box h3 {font-size:24px; margin-bottom:15px;}
        .service-box p {font-size:16px; color:#555;}

        .about, .testimonials, .contact {text-align:center; margin-bottom:50px;}
        .about h2, .testimonials h2, .contact h2 {font-size:36px; margin-bottom:30px; color:#0077b6;}
        .about p, .testimonials p {font-size:18px; color:#555; max-width:800px; margin:auto;}

        .testimonial-box {background:white; padding:20px; margin:10px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1);}
        .testimonial-box p {font-style:italic; color:#0077b6;}

        .contact form {max-width:600px; margin:auto; display:flex; flex-direction:column; gap:15px;}
        .contact input, .contact textarea {padding:15px; border-radius:5px; border:1px solid #ccc; font-size:16px;}
        .contact button {padding:15px; background:#0077b6; color:white; border:none; font-size:18px; border-radius:5px; cursor:pointer;}
        .contact button:hover {background:#023e8a;}

        footer {background:#0077b6; color:white; text-align:center; padding:20px 0;}
        footer a {color:white; text-decoration:none;}
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container">
            <h1>❄️ Wahid AC Service</h1>
            <nav>
                <a href="#services">Services</a>
                <a href="#about">About</a>
                <a href="#testimonials">Testimonials</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Aapka AC Kharaab? Hum Hai Yahan!</h2>
        <p>Fast & Reliable AC Service in Mumbra | Call Now: 9792864761</p>
        <a href="#contact" class="btn">Book Service Now</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="container">
        <h2 style="text-align:center; margin-bottom:50px; color:#0077b6;">Our Services</h2>
        <div class="services">
            <div class="service-box">
                <i class="fas fa-tools"></i>
                <h3>AC Repair</h3>
                <p>Quick and efficient AC repair with genuine parts.</p>
            </div>
            <div class="service-box">
                <i class="fas fa-wind"></i>
                <h3>Gas Charging</h3>
                <p>Refill AC gas for better cooling and performance.</p>
            </div>
            <div class="service-box">
                <i class="fas fa-cogs"></i>
                <h3>PCB Work</h3>
                <p>Expert PCB repair and replacement for all AC models.</p>
            </div>
            <div class="service-box">
                <i class="fas fa-home"></i>
                <h3>AC Installation</h3>
                <p>Professional AC installation with safety and precision.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about container">
        <h2>Why Choose Wahid AC Service?</h2>
        <p>We provide fast, reliable, and affordable AC services in Mumbra. Experienced technicians, genuine parts, and customer satisfaction are our priority!</p>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="testimonials container">
        <h2>Happy Customers</h2>
        <div class="testimonial-box">
            <p>"Comforts company ne mera AC ek din me repair kar diya! - Ramesh K."</p>
        </div>
        <div class="testimonial-box">
            <p>"Fast and professional service, highly recommend! - Sita P."</p>
        </div>
    </section>

    <!-- Contact Form -->
    <section id="contact" class="contact container">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="tel" placeholder="Phone Number" required>
            <textarea placeholder="Message" rows="5" required></textarea>
            <button type="submit">Request Service</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>📞 Call Now: 9792864761 | 📍 Mumbra, Maharashtra</p>
        <p>© 2025 Wahid AC Service</p>
    </footer>

</body>
</html>
