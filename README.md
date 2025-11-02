# CNCLawn-Landscape.com
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CNCLawn & Landscape</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: url('images/hero.jpg') no-repeat center center/cover;
            color: white;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }
        header h1 { font-size: 3em; margin: 0; text-shadow: 2px 2px 5px rgba(0,0,0,0.5); }
        header p { font-size: 1.2em; margin-top: 10px; text-shadow: 1px 1px 3px rgba(0,0,0,0.5); }
        .cta-button {
            display: inline-block; margin-top: 20px; padding: 12px 30px;
            background: #5cb85c; color: white; text-decoration: none;
            border-radius: 5px; font-weight: bold; transition: background 0.3s;
        }
        .cta-button:hover { background: #449d44; }
        section { padding: 60px 20px; max-width: 1000px; margin: 0 auto; }
        h2 { text-align: center; margin-bottom: 40px; color: #2d7a2d; }
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .service-item {
            background: #f4f4f4; padding: 20px; border-radius: 10px; text-align: center;
        }
        .gallery-grid {
            display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px;
        }
        .gallery-grid img { width: 100%; border-radius: 10px; }
        .contact form {
            display: flex; flex-direction: column; max-width: 500px; margin: 0 auto;
        }
        .contact input, .contact textarea {
            padding: 10px; margin-bottom: 15px; border-radius: 5px; border: 1px solid #ccc;
        }
        .contact button {
            padding: 12px; background: #2d7a2d; color: white; border: none; border-radius: 5px;
            font-weight: bold; cursor: pointer; transition: background 0.3s;
        }
        .contact button:hover { background: #1f5c1f; }
        footer { text-align: center; padding: 30px 20px; background: #f4f4f4; color: #666; }
        @media(max-width: 600px){
            header h1 { font-size: 2em; } header p { font-size: 1em; }
        }
    </style>
</head>
<body>

<header>
    <h1>We Care About Your Lawn</h1>
    <p>Family-oriented lawn care and landscaping services, founded by two brothers. We treat your lawn better than our own.</p>
    <a href="#contact" class="cta-button">Get a Free Quote</a>
</header>

<section class="about">
    <h2>Our Story</h2>
    <p>Founded by two brothers with a passion for beautiful lawns, CNCLawn & Landscape is a family-run business dedicated to giving your outdoor space the care it deserves. Professional, personal, and committed to excellence in every job.</p>
</section>

<section class="services">
    <h2>Our Services</h2>
    <div class="services-grid">
        <div class="service-item"><h3>Lawn Mowing</h3><p>Regular mowing to keep your lawn healthy and pristine.</p></div>
        <div class="service-item"><h3>Landscaping</h3><p>Custom landscaping to transform your outdoor space.</p></div>
        <div class="service-item"><h3>Maintenance</h3><p>Seasonal and ongoing maintenance for a perfect yard year-round.</p></div>
    </div>
</section>

<section class="gallery">
    <h2>Gallery</h2>
    <div class="gallery-grid">
        <img src="images/sample1.jpg" alt="Sample Work 1">
        <img src="images/sample2.jpg" alt="Sample Work 2">
        <img src="images/sample3.jpg" alt="Sample Work 3">
        <img src="images/sample4.jpg" alt="Sample Work 4">
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
    <p style="text-align:center; margin-top:15px;"><a href="mailto:info@cnlawnandlandscape.com" style="color:#2d7a2d;">Or email us directly</a></p>
</section>

<footer>
    <p>&copy; 2025 CNCLawn & Landscape. All rights reserved.</p>
</footer>

</body>
</html>
