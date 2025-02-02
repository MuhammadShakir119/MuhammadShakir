<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IPTV Smart Service</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>IPTV Smart Service</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to IPTV Smart Service</h2>
            <p>Your gateway to endless entertainment. Stream live TV, movies, and more!</p>
            <button onclick="learnMore()">Learn More</button>
        </div>
    </section>

    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-list">
            <div class="service-item">
                <h3>Live TV</h3>
                <p>Watch your favorite channels live.</p>
            </div>
            <div class="service-item">
                <h3>Movies & Shows</h3>
                <p>Access thousands of movies and TV shows on demand.</p>
            </div>
            <div class="service-item">
                <h3>Multi-Device Support</h3>
                <p>Stream on your TV, phone, or tablet.</p>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing">
        <h2>Pricing Plans</h2>
        <div class="pricing-plans">
            <div class="plan">
                <h3>Basic</h3>
                <p>$10/month</p>
                <ul>
                    <li>100+ Channels</li>
                    <li>1 Device</li>
                </ul>
                <button>Subscribe</button>
            </div>
            <div class="plan">
                <h3>Premium</h3>
                <p>$20/month</p>
                <ul>
                    <li>300+ Channels</li>
                    <li>3 Devices</li>
                </ul>
                <button>Subscribe</button>
            </div>
            <div class="plan">
                <h3>Ultimate</h3>
                <p>$30/month</p>
                <ul>
                    <li>500+ Channels</li>
                    <li>5 Devices</li>
                </ul>
                <button>Subscribe</button>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <textarea id="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 IPTV Smart Service. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
