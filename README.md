# SANAD-WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>SANAD - Early Seizure Detection</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
    :root {
        --primary: #0A2A43;
        --secondary: #1e88a8;
        --accent: #1abc9c;
        --light: #ffffff;
        --gray: #6d8aa3;
        --bg: #f6faff;
    }

    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: var(--bg);
        color: var(--primary);
        line-height: 1.6;
    }

    header {
        text-align: center;
        padding: 40px 20px;
    }

    header img {
        width: 160px;
        margin-bottom: 10px;
    }

    .hero {
        text-align: center;
        padding: 40px 20px 60px;
    }

    .hero h1 {
        font-size: 48px;
        font-weight: 700;
        color: var(--primary);
    }

    .hero p {
        font-size: 20px;
        color: var(--secondary);
        margin-bottom: 20px;
    }

    .btn {
        background: var(--primary);
        color: var(--light);
        padding: 14px 28px;
        border-radius: 30px;
        display: inline-block;
        font-weight: 600;
        text-decoration: none;
        transition: 0.3s ease-in-out;
    }

    .btn:hover {
        background: var(--secondary);
    }

    .section {
        max-width: 1100px;
        margin: 60px auto;
        padding: 30px 25px;
        background: var(--light);
        border-radius: 18px;
        box-shadow: 0 8px 18px rgba(0, 0, 0, 0.07);
    }

    h2 {
        text-align: center;
        font-weight: 700;
        margin-bottom: 25px;
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
        gap: 20px;
        text-align: center;
    }

    .card {
        background: var(--bg);
        padding: 20px;
        border-radius: 16px;
        font-weight: 500;
        color: var(--primary);
        border-left: 5px solid var(--accent);
        min-height: 120px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    ul.instructions li {
        margin: 10px 0;
        color: var(--secondary);
    }

    footer {
        text-align: center;
        padding: 25px;
        color: var(--gray);
        font-size: 14px;
    }

    /* Mobile */
    @media(max-width: 600px) {
        .hero h1 { font-size: 32px; }
        .hero p { font-size: 18px; }
    }
</style>
</head>

<body>

<header>
    <img src="logo.png" alt="SANAD Logo">
</header>

<section class="hero">
    <h1>SANAD</h1>
    <p>Early Seizure Detection • Real-Time Voice Alerts</p>
    <a href="#" class="btn">Download (Coming Soon)</a>
</section>

<section class="section">
    <h2>How It Works</h2>
    <div class="grid">
        <div class="card">Detects abnormal heart-rate patterns before a seizure</div>
        <div class="card">Sends alarm + spoken voice alert</div>
        <div class="card">Gives step-by-step emergency guidance</div>
        <div class="card">Warns the user early to prepare safely</div>
    </div>
</section>

<section class="section">
    <h2>Features</h2>
    <div class="grid">
        <div class="card">Smartwatch + mobile integration</div>
        <div class="card">AI-powered real-time alerts</div>
        <div class="card">Clear emergency voice instructions</div>
        <div class="card">Safe • Private • Easy to use</div>
    </div>
</section>

<section class="section">
    <h2>For Families & Caregivers</h2>
    <ul class="instructions">
        <li>“Attention! Someone is about to have a seizure.”</li>
        <li>“Stay calm and keep others calm.”</li>
        <li>“Clear the area to prevent injury.”</li>
        <li>“Help the person lie or sit safely if possible.”</li>
        <li>“Do not hold or restrict movement.”</li>
        <li>“Remove hazards such as sharp objects.”</li>
        <li>“Call medical help if needed.”</li>
    </ul>
</section>

<section class="section">
    <h2>About Sanad</h2>
    <p style="text-align:center; max-width:850px; margin:auto; color:var(--secondary); font-size:17px;">
        Our mission is to protect and support individuals living with seizure disorders by using
        advanced biometric technology. Sanad analyzes heart-rate signals to detect early
        pre-seizure patterns and alerts both the user and nearby people in real time.
    </p>
</section>

<section class="section">
    <h2>Contact Us</h2>
    <p style="text-align:center; margin-bottom:10px;">📩 support@sanadapp.com</p>
    <form style="text-align:center;">
        <input type="email" placeholder="Enter your email" required
        style="padding:10px; width:260px; border-radius:8px; border:1px solid var(--gray);">
        <button class="btn" style="border:none; margin-left:8px;">Send</button>
    </form>
</section>

<footer>
    © 2025 SANAD — All Rights Reserved
</footer>

</body>
</html>

