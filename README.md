# SANAD-WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SANAD - Coming Soon</title>

    <style>
        :root{
            --bg:#ffffff;
            --primary:#0a2a43;
            --accent:#1e88a8;
            --muted:#6d8aa3;
            --card:#f7fbfd;
        }
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: var(--bg);
            color: var(--primary);
            display: flex;
            justify-content: center;
            align-items: flex-start;
            flex-direction: column;
            min-height: 100vh;
            padding: 40px 20px;
        }

        .container{
            width:100%;
            max-width:980px;
            margin: 0 auto;
        }

        header{ text-align:center; padding:30px 0; }
        .logo { width:220px; margin-bottom:12px; }
        h1 { font-size:44px; margin:6px 0; letter-spacing:1px; }
        .tag { font-size:18px; color:var(--accent); margin-top:6px; }

        .card{ background:var(--card); border-radius:14px; padding:22px; box-shadow:0 6px 18px rgba(10,42,67,0.06); margin-top:20px; }
        .features ul{ list-style:none; padding:0; margin:0; }
        .features li{ padding:10px 0; font-size:18px; }

        h2{ color:var(--primary); font-size:28px; margin:0 0 12px 0; }
        p{ color:var(--accent); font-size:16px; }

        .cta{ text-align:center; margin:26px 0; }
        .btn{ display:inline-block; padding:12px 26px; background:var(--primary); color:white; border-radius:10px; text-decoration:none; font-size:18px; }

        .two-col{ display:flex; gap:18px; flex-wrap:wrap; }
        .col{ flex:1 1 320px; }

        footer{ text-align:center; color:var(--muted); font-size:14px; margin-top:28px; }

        @media (max-width:520px){ h1{ font-size:34px } }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="logo.png" alt="SANAD Logo" class="logo">
            <h1>SANAD</h1>
            <div class="tag">Our smartwatch app is coming soon. Stay tuned.</div>
        </header>

        <main>
            <!-- Intro card (keeps original simple message) -->
            <section class="card">
                <p style="margin:0; font-size:16px;">SANAD is an on-watch application that runs on your smartwatch to continuously monitor heart activity and motion to detect seizures and abnormal heart-rate events. It is designed to provide immediate alarms and clear on-watch instructions so users and caregivers can act quickly.</p>
            </section>

            <!-- Features & Why side-by-side -->
            <section class="two-col" style="margin-top:18px;">
                <div class="col card features">
                    <h2>App Features</h2>
                    <ul style="margin-top:12px;">
                        <li>🔵✓   — detects abnormal heart activity.</li>
                        <li>🔵✓   — uses motion and vitals analysis to identify seizure events.</li>
                        <li>🔵✓   — immediately notifies trusted contacts when a critical event is detected.</li>
                        <li>🔵✓   — shows clear, step-by-step guidance for what to do during a seizure.</li>
                    </ul>
                </div>

                <div class="col card">
                    <h2>Why Choose SANAD?</h2>
                    <ul style="margin-top:12px; list-style:none; padding:0;">
                        <li style="padding:8px 0;">🔵✓   — runs in the background without needing your phone.</li>
                        <li style="padding:8px 0;">🔵✓   — reduces response time by notifying caregivers instantly.</li>
                        <li style="padding:8px 0;">🔵✓   — practical instructions reduce uncertainty during emergencies.</li>
                        <li style="padding:8px 0;">🔵✓   — works locally on-device to preserve personal data.</li>
                    </ul>
                </div>
            </section>

            <!-- How It Works -->
            <section class="card" style="margin-top:18px;">
                <h2>How It Works</h2>
                <ul style="list-style:none; color:var(--primary); font-size:16px; line-height:1.7; padding:0;">
                    <li>🔵✓  SANAD runs quietly in the background.</li>
                    <li>🔵✓  Heart rate and motion signals are analyzed in real time.</li>
                    <li>🔵✓  If seizure-like patterns or abnormal heart activity are identified, the app triggers an alarm.</li>
                    <li>🔵✓  The watch sounds a loud alarm and displays on-watch step-by-step instructions for immediate care.</li>
                    <li>🔵✓  If the user does not cancel the alarm, selected caregivers receive an alert with location information.</li>
                </ul>
            </section>

            <!-- Testimonials -->
            <section class="card" style="margin-top:18px;">
                <h2>What People Are Saying</h2>
                <p style="font-style:italic; margin:10px 0;">“SANAD gave us peace of mind. The automatic alerts helped us respond within seconds.” — Caregiver</p>
                <p style="font-style:italic; margin:10px 0;">“Finally, an app that provides clear steps to follow during a seizure.” — User</p>
            </section>

            <!-- Call to action -->
            <section class="cta">
                <a href="#" class="btn">Get Notified</a>
            </section>

        </main>

        <footer>
            © 2025 SANAD. All Rights Reserved.
        </footer>
    </div>
</body>
</html>

         

         
