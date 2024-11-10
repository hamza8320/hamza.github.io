<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Agency</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1><p style="color:brown;">Welcome to Travel Agency By Hamza</p></h1>
        <img src="Travell.jpg" alt="Passport Size" width="600" height="200">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#calculator">Trip Cost Calculator</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Your Adventure Awaits!</h2>
            <p>Explore the world with us. Find the best travel packages tailored just for you.</p>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We are a leading travel agency with years of experience in providing unforgettable travel experiences.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <p>We offer a variety of travel services, including flight bookings, hotel reservations, and guided tours.</p>
        </section>

        <section id="calculator">
            <h2>Trip Cost Calculator</h2>
            <form id="costCalculator">
                <label for="destination">Destination:</label>
                <input type="text" id="destination" required>
                
                <label for="days">Number of Days:</label>
                <input type="number" id="days" required>
                
                <label for="budget">Budget per Day:</label>
                <input type="number" id="budget" required>
                
                <button type="submit">Calculate Cost</button>
            </form>
            <div id="result"></div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Travel Agency. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
