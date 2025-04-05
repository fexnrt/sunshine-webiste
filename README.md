<!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h1 class="title"></h1>
      <p id="currentTime"></p>
      <script src="script.js"></script>
  </body>
</html><!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h1 class="title">Hello World! </h1>
      <p id="currentTime"></p>
      <script src="script.js"></script>
  </body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunshine Group</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #B3E5FC; /* Light Sky Blue */
            color: #333;
            text-align: center;
            padding: 20px;
        }

        .header {
            padding: 20px;
            background: white;
            border-radius: 15px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            max-width: 800px;
            margin: 20px auto;
        }

        .header h1 {
            font-size: 32px;
            font-weight: 600;
            color: #0288D1;
        }

        .hero {
            padding: 60px 20px;
            background: #03A9F4;
            color: white;
            border-radius: 15px;
            max-width: 900px;
            margin: 20px auto;
        }

        .hero h2 {
            font-size: 36px;
            font-weight: 600;
        }

        .hero p {
            font-size: 18px;
            margin-top: 10px;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 30px;
            background: white;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
        }

        .section-title {
            font-size: 24px;
            font-weight: 600;
            color: #0277BD;
            margin-bottom: 15px;
        }

        .info-box {
            background: #E1F5FE;
            padding: 15px;
            margin: 10px 0;
            border-radius: 10px;
            text-align: left;
        }

        .info-box ul {
            padding-left: 20px;
        }

        .contact-buttons {
            text-align: center;
            margin-top: 20px;
        }

        .whatsapp-button, .email-button {
            display: inline-block;
            padding: 12px 20px;
            font-size: 18px;
            font-weight: 600;
            border-radius: 10px;
            text-decoration: none;
            transition: 0.3s;
            margin: 10px;
        }

        .whatsapp-button {
            background-color: #29B6F6;
            color: white;
        }

        .whatsapp-button:hover {
            background-color: #0288D1;
        }

        .email-button {
            background-color: #0288D1;
            color: white;
        }

        .email-button:hover {
            background-color: #01579B;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 10px;
            font-size: 16px;
        }

        .contact-form button {
            width: 100%;
            padding: 12px;
            background-color: #0288D1;
            border: none;
            color: white;
            font-size: 18px;
            cursor: pointer;
            border-radius: 10px;
        }

        .contact-form button:hover {
            background-color: #01579B;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #0277BD;
            color: white;
            border-radius: 15px;
            margin-top: 20px;
        }

    </style>
</head>
<body>

    <div class="header">
        <h1>Sunshine Group</h1>
    </div>

    <div class="hero">
        <h2>Bright Choices, Better Living</h2>
        <p>Helping you find the perfect home with ease.</p>
    </div>

    <div class="container">
        <h2 class="section-title">Why Choose Us?</h2>

        <div class="info-box">
            <h3>🏡 Residential & Commercial Properties</h3>
            <ul>
                <li>We specialize in **buying and selling residential and commercial spaces**.</li>
                <li>Wide range of properties available **at affordable prices**.</li>
            </ul>
        </div>

        <div class="info-box">
            <h3>📜 Legal & Documentation Assistance</h3>
            <ul>
                <li>We provide **full legal guidance** to ensure a smooth property transfer.</li>
                <li>All paperwork and approvals are handled professionally.</li>
            </ul>
        </div>

        <div class="info-box">
            <h3>🔍 Property Valuation & Market Analysis</h3>
            <ul>
                <li>Get an **accurate property valuation** before making a deal.</li>
                <li>We analyze the market for the **best real estate investment opportunities**.</li>
            </ul>
        </div>

        <div class="info-box">
            <h3>📈 Investment Advisory</h3>
            <ul>
                <li>We help you **maximize your returns** with expert investment strategies.</li>
                <li>Guidance on **high-growth areas and premium locations**.</li>
            </ul>
        </div>

    </div>

    <div class="container">
        <h2 class="section-title">Real Estate Insights</h2>

        <div class="info-box">
            <h3>📌 Market Growth</h3>
            <ul>
                <li>The Indian real estate market is expected to reach **$1 Trillion by 2030**.</li>
                <li>Top cities for investment: **Mumbai, Bangalore, Hyderabad**.</li>
            </ul>
        </div>

        <div class="info-box">
            <h3>🏗️ Best Locations for Investment</h3>
            <ul>
                <li>Properties near metro stations and IT hubs have **higher appreciation**.</li>
                <li>Upcoming smart cities offer great investment opportunities.</li>
            </ul>
        </div>

        <div class="info-box">
            <h3>📜 Legal & Safety Checks</h3>
            <ul>
                <li>Ensure **RERA (Real Estate Regulatory Authority) approval** before purchasing.</li>
                <li>Verify property titles, legal clearances, and builder credibility.</li>
            </ul>
        </div>

    </div>

    <div class="container">
        <h2 class="section-title">Contact Us</h2>
        <p>📞 Call us: <strong>7755995818</strong></p>
        <p>📧 Email: <strong>sunshinegroupjs@gmail.com</strong></p>

        <div class="contact-buttons">
            <a href="https://wa.me/7755995818" target="_blank" class="whatsapp-button">
                💬 Chat on WhatsApp
            </a>
            <a href="mailto:sunshinegroupjs@gmail.com" class="email-button">
                📧 Send an Email
            </a>
        </div>

        <form class="contact-form" action="https://formsubmit.co/sunshinegroup.js@gmail.com" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

    <footer>
        © 2025 Sunshine Group | All Rights Reserved
    </footer>

</body>
</html>









