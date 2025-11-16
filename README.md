# SANAD-WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sanad – Early Seizure Detection App</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: #f8fbff;
        color: #1a2a3a;
    }
    header.hero {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 60px;
        background: linear-gradient(#e4f4ff, #f9fcff);
    }
    .hero-content h1 {
        font-size: 64px;
        font-weight: 700;
    }
    .logo {
        width: 130px;
        margin-bottom: 10px;
    }
    .tagline {
        font-size: 22px;
        margin-bottom: 20px;
    }
    .btn-download {
        background: #00a7c7;
        padding: 14px 26px;
        color: white;
        text-decoration: none;
        font-size: 18px;
        border-radius: 12px;
        font-weight: 600;
    }
    section {
        padding: 60px;
    }
    h2 {
        font-size: 36px;
        margin-bottom: 20px;
    }
    ul, ol {
        font-size: 18px;
        line-height: 1.8;
    }
    #contact form input,
    #contact form textarea {
        width: 100%;
        margin-bottom: 15px;
        padding: 12px;
        border-radius: 8px;
        border: 1px solid #cbd9e7;
        font-size: 16px;
    }
    #contact button {
        padding: 12px 24px;
        background: #008bb0;
        border: none;
        color: white;
        font-size: 18px;
        border-radius: 10px;
    }
    footer {
        text-align: center;
        padding: 20px;
        background: #dff4ff;
        margin-top: 40px;
        font-size: 16px;
    }
    .hero-image img {
        width: 350px;
    }
</style>
</head>
<body>

<header class="hero">
    <div class="hero-content">
        <img src="logo.png" alt="Sanad Logo" class="logo">
        <h1>Sanad</h1>
        <p class="tagline">Early seizure detection. Real-time voice alerts.</p>
        <a href="#" class="btn-download">Download (Coming Soon)</a>
    </div>
    <div class="hero-image">
        <img src="smartwatch-phone.png" alt="Sanad App on Smartwatch and Phone">
    </div>
</header>

<section id="how-it-works">
    <h2>How It Works</h2>
    <ul>
        <li>Detects heart‑rate patterns before a seizure</li>
        <li>Sends sound + voice alarms</li>
        <li>Gives step-by-step instructions to helpers</li>
        <li>Warns the user early</li>
    </ul>
</section>

<section id="features">
    <h2>Features</h2>
    <ul>
        <li>Smartwatch detection</li>
        <li>Real-time voice alerts</li>
        <li>Emergency guidance instructions</li>
        <li>Safe, private, simple to use</li>
    </ul>
</section>

<section id="families">
    <h2>For Families & Caregivers</h2>
    <p>Sanad helps those around the person act fast and effectively:</p>
    <ol>
        <li>Attention! Someone is about to have a seizure.</li>
        <li>Stay calm and keep others calm.</li>
        <li>Clear the area around them to prevent injury.</li>
        <li>Gently guide them to sit or lie down if safe.</li>
        <li>Do not hold them down or restrain them.</li>
        <li>Check for nearby hazards (sharp objects, corners).</li>
        <li>Call for medical help if necessary.</li>
    </ol>
    <p>Early detection saves lives that are often lost due to unawareness.</p>
</section>

<section id="about">
    <h2>About Sanad</h2>
    <p>Sanad’s mission is to support people who experience seizures and provide peace of mind to families and caregivers. Our technology monitors heart-rate patterns to detect seizures before they happen, giving everyone time to react safely.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:support@sanadapp.com">support@sanadapp.com</a></p>
    <form>
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
        <button type="submit">Send</button>
    </form>
</section>

<footer>
    <p>© 2025 Sanad App. All rights reserved.</p>
</footer>

</body>
</html>

