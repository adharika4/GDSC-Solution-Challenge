<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Health Awareness Sessions</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }

        header, nav, section, footer {
            margin: 20px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }

        nav li {
            float: left;
        }

        nav a {
            display: block;
            padding: 14px 16px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #66ddf5;
            color: black;
        }

        section {
            margin-bottom: 40px;
        }

        form label, form textarea, form input[type="text"], form input[type="email"], form button {
            display: block;
            margin-bottom: 10px;
        }

        button {
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }

        .session {
            border: 1px solid #9cdf54;
            padding: 10px;
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            padding: 10px;
            background-color: #77f19e;
        }
    </style>
</head>
<body>

<header>
    <h1>Health Awareness Sessions</h1>
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#sessions">Sessions</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="home">
    <h2>Welcome to Health Awareness Sessions</h2>
    <p>Empowering individuals through knowledge for a healthier life.</p>
</section>

<section id="sessions">
    <h2>Upcoming Sessions</h2>
    <div class="session">
        <h3>Session Title 1</h3>
        <p>Date: January 25, 2024</p>
        <p>Time: 3:00 PM - 5:00 PM</p>
        <p>Location: Virtual</p>
    </div>
    <div class="session">
        <h3>Session Title 2</h3>
        <p>Date: February 10, 2024</p>
        <p>Time: 2:00 PM - 4:00 PM</p>
        <p>Location: Community Center</p>
    </div>
    <!-- Add more session details as needed -->
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Our mission is to provide valuable information and resources to promote a healthier lifestyle.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 Health Awareness Sessions. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
