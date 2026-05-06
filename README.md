<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prashant Textile</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f5f7fa;
}

/* Header */
header {
    background: #0d6efd;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 50px 20px;
    background: url('https://images.unsplash.com/photo-1581578731548-c64695cc6952') no-repeat center/cover;
    color: white;
}

.hero h2 {
    font-size: 30px;
    margin-bottom: 10px;
}

.btn {
    display: inline-block;
    margin: 10px;
    padding: 10px 20px;
    background: #ff9800;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.whatsapp {
    background: #25D366;
}

/* Products */
.products {
    padding: 40px 20px;
    text-align: center;
}

.products h2 {
    margin-bottom: 20px;
}

.card {
    display: inline-block;
    width: 250px;
    margin: 15px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

.card h3 {
    margin: 10px 0;
}

/* Bulk Section */
.bulk {
    background: #e3f2fd;
    padding: 40px 20px;
    text-align: center;
}

.bulk form {
    max-width: 400px;
    margin: auto;
}

.bulk input, .bulk textarea {
    width: 100%;
    padding: 10px;
    margin: 8px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
}

.bulk button {
    background: #0d6efd;
    color: white;
    border: none;
    padding: 10px;
    width: 100%;
    border-radius: 5px;
}

/* About */
.about {
    padding: 30px;
    text-align: center;
}

/* Contact */
.contact {
    background: #212529;
    color: white;
    padding: 20px;
    text-align: center;
}

/* Footer */
footer {
    background: #000;
    color: white;
    text-align: center;
    padding: 10px;
}
</style>

</head>

<body>

<header>
    <h1>Prashant Textile</h1>
    <p>Trusted Manufacturer of Quality Towels & Napkins</p>
</header>

<section class="hero">
    <h2>Premium Cotton & Polyester Towels</h2>
    <p>Supplying for Homes & Businesses</p>
    <a href="tel:7219426993" class="btn">Call Now</a>
    <a href="https://wa.me/917219426993" class="btn whatsapp">WhatsApp Us</a>
</section>

<section class="products">
    <h2>Our Products</h2>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1604335399105-a0c585fd81a0">
        <h3>Bath Towels</h3>
        <p>Soft cotton towels | ₹200 - ₹500</p>
        <a href="https://wa.me/917219426993" class="btn">Enquire</a>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1583847268964-b28dc8f51f92">
        <h3>Hand Towels</h3>
        <p>Durable & absorbent</p>
        <a href="https://wa.me/917219426993" class="btn">Enquire</a>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1582735689369-4fe89db7114c">
        <h3>Kitchen Napkins</h3>
        <p>Strong & reusable</p>
        <a href="https://wa.me/917219426993" class="btn">Enquire</a>
    </div>

</section>

<section class="bulk">
    <h2>Bulk Orders Available</h2>
    <p>We supply to hotels, retailers & businesses</p>

    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="tel" placeholder="Phone Number" required>
        <textarea placeholder="Your Requirement"></textarea>
        <button type="submit">Get Quote</button>
    </form>
</section>

<section class="about">
    <h2>About Us</h2>
    <p>Located in MIDC, Solapur, we manufacture high-quality towels and napkins using cotton and polyester.</p>
    <p><strong>The product you can trust</strong></p>
</section>

<section class="contact">
    <h2>Contact Us</h2>
    <p>📞 7219426993</p>
    <p>📍 MIDC, Solapur</p>
</section>

<footer>
    <p>© 2026 Prashant Textile</p>
</footer>

</body>
</html>
