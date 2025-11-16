# SANAD-WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SANAD | Early Seizure Detection</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
:root {
    --primary:#0A6CFF;
    --secondary:#0E3B85;
    --light:#FFFFFF;
    --bg:#F7FAFF;
    --text-dark:#1B1B1B;
    --text-muted:#5A5A5A;
}

body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: var(--bg);
    color: var(--text-dark);
    line-height: 1.6;
}

/* Header */
header {
    text-align: center;
    padding: 25px;
    background: var(--light);
    border-bottom: 1px solid #dfe8ff;
}
header img {
    width: 130px;
    display: block;
    margin: 0 auto 8px;
}
header h1 {
    font-size: 26px;
    font-weight: 700;
    color: var(--primary);
}

/* Hero */
.hero {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(to bottom right, #0a6cff, #0E3B85);
    color: var(--light);
}
.hero h2 {
    font-size: 46px;
    font-weight: 700;
}
.hero p {
    font-size: 20px;
    margin-bottom: 25px;
}
.btn {
    background: var(--light);
    color: var(--primary);
    font-weight: 600;
    padding: 14px 26px;
    border-radius: 30px;
    text-decoration: none;
    transition: .3s;
}
.btn:hover {
    background: var(--secondary);
    color: var(--light);
}

/* Sections */
.section {
    max-width: 1100px;
    margin: 60px auto;
    padding: 35px;
    background: var(--light);
    border-radius: 18px;
    box-shadow: 0 8px 18px rgba(0,0,0,0.05);
}
.section h3 {
    text-align: center;
    margin-bottom: 20px;
    font-size: 30px;
    font-weight: 700;
    color: var(--primary);
}

/* Grid */
.grid {
    display: grid;
    gap: 22px;
}
@media (min-width:750px){
    .grid-2 { grid-template-columns: repeat(2,1fr); }
    .grid-3 { grid-template-columns: repeat(3,1fr); }
}

.card {
    background: var(--bg);
    padding: 20px;
    border-radius: 16px;
    text-align: center;
    border: 1px solid #e1ebff;
}
.card h4 { color: var(--secondary); font-weight: 600; }

/* Contact */
.contact input, .contact textarea {
    width: 100%;
    padding: 14px;
    border-radius: 10px;
    border: 1px solid #cfdfff;
    margin-bottom: 12px;
}
.contact button {
    width: 100%;
    background: var(--primary);
    border: none;
    padding: 14px;
    border-radius: 10px;
    color: var(--light);
    font-size: 17px;
    cursor: pointer;
    transition:.3s;
}
.contact button:hover { background: var(--secondary); }

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: var(--primary);
    color: var(--light);
    margin-top: 50px;
}
</style>
</head>
<body>

<header>
    <img src="logo.png" alt="Sanad Logo">
    <h1>SANAD</h1>
    <small>Seizure Alert • Protection • Peace of Mind</small>
</header>

<section class="hero">
    <h2>Protecting Lives Through Smart Seizure Detection</h2>
    <p>AI-powered wearables that monitor and notify caregivers instantly during seizures.</p>
    <a href="#contact" class="btn">Request Early Access</a>
</section>

<div class="section">
    <h3>Mission & Vision</h3>
    <p><strong>Mission:</strong> To provide reliable early seizure detection for patients and caregivers through advanced wearable technology.</p>
    <p><strong>Vision:</strong> A world where no seizure goes unnoticed, ensuring safety, response, and peace of mind.</p>
</div>

<div class="section">
    <h3>Product Overview</h3>
    <div class="grid grid-2">
        <div>
            <p>SANAD is a small, comfortable wearable device connected to a mobile app. It continuously monitors seizure-related biomarkers, movement patterns, and emergency thresholds using machine learning to trigger instant alerts to family members and healthcare providers.</p>
        </div>
        <div>
            <ul>
                <li>✔ Real-time monitoring</li>
                <li>✔ Smart mobile alert system</li>
                <li>✔ Cloud-based medical analytics</li>
                <li>✔ Lightweight & child-friendly</li>
            </ul>
        </div>
    </div>
</div>

<div class="section">
    <h3>Key Features</h3>
    <div class="grid grid-3">
        <div class="card"><h4>24/7 Monitoring</h4><p>Continuous detection with medical-grade accuracy.</p></div>
        <div class="card"><h4>Emergency Alerts</h4><p>Instant notifications sent to caregivers, parents & doctors.</p></div>
        <div class="card"><h4>AI-Driven Analytics</h4><p>Personalized seizure prediction learning and tracking.</p></div>
    </div>
</div>

<div class="section">
    <h3>Team</h3>
    <div class="grid grid-3">
        <div class="card"><h4>Biomedical Engineers</h4><p>Device research & biosignal integration</p></div>
        <div class="card"><h4>AI & Software Developers</h4><p>Algorithm design and mobile app development</p></div>
        <div class="card"><h4>Medical Advisors</h4><p>Neurologists and clinical professionals</p></div>
    </div>
</div>

<div class="section" id="contact">
    <h3>Contact Us</h3>
    <form class="contact">
        <input type="text" placeholder="Full Name" required>
        <input type="email" placeholder="Email Address" required>
        <textarea placeholder="Message"></textarea>
        <button type="submit">Submit</button>
    </form>
</div>

<footer>
    © 2025 SANAD | All Rights Reserved
</footer>

</body>
</html>
