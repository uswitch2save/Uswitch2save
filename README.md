<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>uSwitch2Save - Save on Utilities & Payment Solutions</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to CSS file -->
</head>
<body>
    <section id="hero" class="hero-section">
        <div class="hero-content">
            <a href="#get-quote" class="cta-button">Get a Quote Now</a>
        </div>
    </section>

    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>We help individuals and businesses save money on utilities and upgrade their payment solutions.</p>
    </section>

    <section id="services" class="services-section">
        <h2>Our Services</h2>
        <ul>
            <li>Utility Bill Savings</li>
            <li>Card Payment Solutions</li>
            <li>Business Insurance Advice</li>
        </ul>
    </section>

    <section id="get-quote" class="quote-section">
        <h2>Get a Quote Now</h2>
        <p>Interested in saving money? Get a personalized quote today!</p>
        <form id="quoteForm">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <button type="submit" class="cta-button">Submit</button>
        </form>
    </section>

    <section id="consultant" class="consultant-section">
        <h2>Become a Consultant</h2>
        <p>Join uSwitch2Save and start earning by helping businesses and individuals save on their utilities.</p>
        <form id="consultantForm">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <button type="submit" class="cta-button">Apply Now</button>
        </form>
    </section>

    <script>
        document.getElementById('quoteForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Quote request submitted! We will contact you soon.');
        });

        document.getElementById('consultantForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Consultant application submitted! We will review and get in touch.');
        });
    </script>
</body>
</html>
