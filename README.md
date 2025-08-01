<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Unions Marriage Bureau</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #fafbfc;
            font-family: 'Segoe UI', Arial, sans-serif;
            color: #222;
        }
        .page-header {
            background: #9c3161;
            color: #fff;
            padding: 16px 0;
            text-align: center;
        }
        .banner {
            width: 100%;
            max-height: 300px;
            object-fit: cover;
            display: block;
        }
        .center-panel {
            max-width: 1000px;
            margin: 30px auto 0 auto;
            background: #fff;
            border-radius: 9px;
            box-shadow: 0 2px 10px #d7d5d7;
            padding: 24px;
            text-align: center;
        }
        h1 {
            margin-bottom: 5px;
            letter-spacing: 2px;
        }
        .subheading {
            font-size: 1.1em;
            color: #6e2c50;
            margin-bottom: 24px;
        }
        .services-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin: 30px 0;
        }
        .service-card {
            background: #d8cdd4;
            border-radius: 7px;
            padding: 16px;
            width: 230px;
            box-shadow: 0 1px 4px #e9e1e8;
            text-align: center;
        }
        .service-card img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 12px;
        }
        .contact-section {
            margin-top: 40px;
            padding: 22px;
            background: #f7f3f8;
            border-radius: 9px;
        }
        .contact-section h2 {
            color: #9c3161;
        }
        .contact-form {
            display: grid;
            gap: 10px;
            max-width: 400px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            padding: 8px;
            border: 1px solid #c1adc1;
            border-radius: 4px;
        }
        .contact-form button {
            background: #9c3161;
            color: #fff;
            border: none;
            padding: 11px;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }
        .contact-form button:hover {
            background: #791f44;
        }
        .footer {
            background: #9c3161;
            color: #fff;
            text-align: center;
            margin-top: 32px;
            padding: 16px 0;
        }
        @media (max-width: 700px) {
            .center-panel, .contact-section {
                padding: 12px;
            }
            .services-grid {
                flex-direction: column;
                gap: 14px;
            }
        }
    </style>
</head>
<body>
    <header class="page-header">
        <h1>Happy Unions Marriage Bureau</h1>
        <div class="subheading">Connecting Hearts, Creating Families</div>
    </header>
    <img src="c:\Users\URK23CS1083\Downloads\1234refghbnm.jpg" alt="Marriage Banner" class="banner">
    <div class="center-panel">
        <h2>Welcome to Our Marriage Bureau</h2>
        <p>
            We specialize in introducing the perfect matches for a happy and meaningful life together. With extensive experience and a focus on personal attention, our team ensures confidentiality, security, and satisfaction in every union.
        </p>

        <div class="services-grid">
            <div class="service-card">
                <img src="https://img.icons8.com/color/96/000000/conference-call.png" alt="Marriage Counseling">
                <div><b>Personalized Matchmaking</b></div>
                <small>For all cultures & communities</small>
            </div>
            <div class="service-card">
                <img src="https://img.icons8.com/color/96/000000/couple-man-woman.png" alt="Verified Profiles">
                <div><b>Verified Profiles</b></div>
                <small>100% privacy & background checks</small>
            </div>
            <div class="service-card">
                <img src="https://img.icons8.com/color/96/000000/gift--v2.png" alt="Events & Gatherings">
                <div><b>Events & Gatherings</b></div>
                <small>Regular meetups and mixers</small>
            </div>
            <div class="service-card">
                <img src="https://img.icons8.com/color/96/000000/consultation.png" alt="Relationship Guidance">
                <div><b>Relationship Guidance</b></div>
                <small>Counseling by experienced advisors</small>
            </div>
        </div>
 <div class="contact-section" id="contact">
            <h2>Contact & Inquiry</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Email Address" required>
                <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
                <button type="submit">Send Inquiry</button>
            </form>
        </div>
    </div>
       
    <div class="footer">
        &copy; 2025 Happy Unions Marriage Bureau. All Rights Reserved.
    </div>
</body>
</html>
