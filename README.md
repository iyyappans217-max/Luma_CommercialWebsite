# Luma_CommercialWebsite

### Register Number: 212225230108
### Name: Iyyappan S
### Date: 17/11/2026
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Luma Living — thoughtfully selected products for everyday living.">
  <title>Luma Living | Shop Better, Live Brighter</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header" id="home">
    <div class="container header-inner">
      <a class="logo" href="#home" aria-label="Luma Living home">luma<span>.</span></a>
      <nav class="main-nav" aria-label="Main navigation">
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">My Account</a>
      </nav>
      <a class="header-cta" href="#products">Shop now <span aria-hidden="true">→</span></a>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-inner">
        <div class="hero-copy">
          <p class="eyebrow">DESIGNED FOR EVERYDAY</p>
          <h1>Make room for<br><span>better living.</span></h1>
          <p class="hero-description">Discover useful, beautiful essentials chosen to make your everyday moments feel a little more special.</p>
          <div class="hero-actions">
            <a class="button button-primary" href="#products">Explore collection</a>
            <a class="text-link" href="#about">Our story <span aria-hidden="true">↗</span></a>
          </div>
          <div class="hero-note"><span class="note-dot"></span> Thoughtful finds. Everyday value.</div>
        </div>
        <div class="hero-image-wrap">
          <img class="hero-image" src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=1200&q=82" alt="Warm, modern living room with carefully selected home decor">
          <div class="image-tag"><strong>Curated for you</strong><br><span>Simple things, beautifully made</span></div>
        </div>
      </div>
    </section>

    <section class="benefits">
      <div class="container benefit-row">
        <div><span class="benefit-icon">✦</span><span><strong>Thoughtful quality</strong><small>Selected with care</small></span></div>
        <div><span class="benefit-icon">↗</span><span><strong>Easy shopping</strong><small>A smooth experience</small></span></div>
        <div><span class="benefit-icon">♡</span><span><strong>Friendly support</strong><small>Here when you need us</small></span></div>
      </div>
    </section>

    <section class="section products-section" id="products">
      <div class="container">
        <div class="section-heading">
          <div><p class="eyebrow">THE COLLECTION</p><h2>Find your new favourite.</h2></div>
          <a class="text-link" href="#contact">Need a recommendation? <span aria-hidden="true">↗</span></a>
        </div>
        <div class="product-grid">
          <article class="product-card">
            <div class="product-image"><img src="https://images.unsplash.com/photo-1490312278390-ab64016e0aa9?auto=format&fit=crop&w=800&q=80" alt="Minimal ceramic table lamp" loading="lazy"><span class="product-label">BESTSELLER</span></div>
            <div class="product-info"><div><h3>Glow Table Lamp</h3><p>Warm light for calm spaces</p></div><strong>₹1,499</strong></div>
            <a class="card-link" href="#contact">Enquire now <span>→</span></a>
          </article>
          <article class="product-card">
            <div class="product-image"><img src="https://images.unsplash.com/photo-1494438639946-1ebd1d20bf85?auto=format&fit=crop&w=800&q=80" alt="Neutral home and lifestyle accessories" loading="lazy"></div>
            <div class="product-info"><div><h3>Everyday Organizer</h3><p>Keep your essentials in place</p></div><strong>₹899</strong></div>
            <a class="card-link" href="#contact">Enquire now <span>→</span></a>
          </article>
          <article class="product-card">
            <div class="product-image"><img src="https://images.unsplash.com/photo-1493663284031-b7e3aefcae8e?auto=format&fit=crop&w=800&q=80" alt="Comfortable contemporary living room" loading="lazy"></div>
            <div class="product-info"><div><h3>Comfort Cushion Set</h3><p>A softer touch for your home</p></div><strong>₹1,199</strong></div>
            <a class="card-link" href="#contact">Enquire now <span>→</span></a>
          </article>
        </div>
      </div>
    </section>

    <section class="about-section section" id="about">
      <div class="container about-layout">
        <div class="about-image"><img src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1100&q=82" alt="Bright and thoughtfully designed home interior" loading="lazy"></div>
        <div class="about-copy"><p class="eyebrow">A LITTLE ABOUT US</p><h2>Good design should feel good to live with.</h2><p>At Luma Living, we believe the things you use every day should be useful, welcoming and thoughtfully designed. We bring together practical essentials and timeless style to help you create a space that feels like you.</p><a class="button button-dark" href="#contact">Get in touch</a></div>
      </div>
    </section>

    <section class="contact-section section" id="contact">
      <div class="container contact-layout">
        <div><p class="eyebrow">WE'D LOVE TO HEAR FROM YOU</p><h2>Questions? Let's talk.</h2><p class="contact-intro">Need help choosing a product or want to know more? Send us a message.</p>
          <div class="contact-detail"><span>✉</span><div><small>Email</small><a href="mailto:hello@lumaliving.example">hello@lumaliving.example</a></div></div>
          <div class="contact-detail"><span>☎</span><div><small>Phone</small><a href="tel:+919876543210">+91 81486 29285</a></div></div>
          <div class="contact-detail"><span>⌖</span><div><small>Location</small><p>Chennai, Tamil Nadu, India</p></div></div>
        </div>
        <form class="contact-form" action="mailto:hello@lumaliving.example" method="post" enctype="text/plain">
          <label for="name">Your name</label><input id="name" name="name" type="text" placeholder="Enter your name" required>
          <label for="email">Email address</label><input id="email" name="email" type="email" placeholder="you@example.com" required>
          <label for="message">Your message</label><textarea id="message" name="message" rows="4" placeholder="How can we help?" required></textarea>
          <button class="button button-primary" type="submit">Send message <span>→</span></button>
          <small class="form-note">Demo form: submitting opens your default email application.</small>
        </form>
      </div>
    </section>

    <section class="account-section" id="account">
      <div class="container account-inner"><div><p class="eyebrow">YOUR LUMA ACCOUNT</p><h2>Make shopping feel personal.</h2><p>Sign-in features can be connected to a real account system when the website is deployed.</p></div><a class="button button-light" href="mailto:hello@lumaliving.example?subject=Account%20Enquiry">Account enquiry <span>→</span></a></div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-top">
      <div><a class="logo footer-logo" href="#home">luma<span>.</span></a><p>Thoughtful finds for everyday living.</p></div>
      <div class="social-links"><span>FOLLOW ALONG</span><a href="https://www.instagram.com/itx._.iyyappan_s" target="_blank" rel="">Instagram</a><a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer">Facebook</a><a href="https://www.pinterest.com/" target="_blank" rel="noopener noreferrer">Pinterest</a></div>
    </div>
    <div class="container footer-bottom"><span>© 2026 Luma Living. All rights reserved.</span><span>Made for everyday moments.</span></div>
  </footer>
</body>
</html>

```

style.css
```
/* Luma Living — commercial website using CSS Flexbox */
:root {
  --ink: #202923;
  --muted: #69736c;
  --cream: #f6f5ef;
  --paper: #fffefa;
  --green: #526b57;
  --green-dark: #344b3a;
  --line: #e7e8df;
  --serif: Georgia, "Times New Roman", serif;
  --sans: Arial, Helvetica, sans-serif;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body { margin: 0; color: var(--ink); background: var(--paper); font-family: var(--sans); line-height: 1.6; }
img { display: block; width: 100%; }
a { color: inherit; text-decoration: none; }
.container { width: min(1120px, calc(100% - 48px)); margin: 0 auto; }
.site-header { background: rgba(255,254,250,.96); border-bottom: 1px solid var(--line); position: sticky; top: 0; z-index: 10; }
.header-inner { min-height: 76px; display: flex; align-items: center; justify-content: space-between; gap: 28px; }
.logo { font-family: var(--serif); font-size: 2rem; font-weight: 700; letter-spacing: -2px; }
.logo span { color: #91a47e; }
.main-nav { display: flex; align-items: center; justify-content: center; gap: 27px; }
.main-nav a { color: #505b53; font-size: .88rem; transition: color .25s ease; }
.main-nav a:hover, .text-link:hover, .card-link:hover { color: #91a47e; }
.header-cta { border: 1px solid #cbd3c8; border-radius: 30px; padding: 10px 17px; font-size: .86rem; transition: background .25s, color .25s; white-space: nowrap; }
.header-cta:hover { background: var(--green-dark); color: white; }
.hero { background: var(--cream); padding: 72px 0 78px; }
.hero-inner { display: flex; align-items: center; justify-content: space-between; gap: 58px; }
.hero-copy { flex: 1 1 44%; }
.eyebrow { color: var(--green); font-size: .7rem; font-weight: 700; letter-spacing: 2px; margin: 0 0 15px; }
h1, h2, h3, p { margin-top: 0; }
h1, h2 { font-family: var(--serif); font-weight: 500; letter-spacing: -1.5px; line-height: 1.12; }
h1 { font-size: clamp(3rem, 6vw, 5rem); margin-bottom: 22px; }
h1 span { color: var(--green); font-style: italic; }
.hero-description { max-width: 440px; color: var(--muted); font-size: 1rem; line-height: 1.8; }
.hero-actions { display: flex; align-items: center; gap: 25px; margin-top: 30px; }
.button { display: inline-flex; align-items: center; justify-content: center; gap: 12px; border: 0; border-radius: 3px; padding: 14px 21px; font: inherit; font-size: .88rem; cursor: pointer; transition: transform .25s, background .25s, box-shadow .25s; }
.button:hover { transform: translateY(-3px); box-shadow: 0 8px 20px #263b2b20; }
.button-primary { background: var(--green); color: white; }
.button-primary:hover { background: var(--green-dark); }
.button-dark { background: var(--ink); color: white; margin-top: 12px; }
.button-light { background: #fffefa; color: var(--ink); }
.text-link { font-size: .88rem; font-weight: 600; transition: color .25s; }
.hero-note { margin-top: 45px; color: var(--muted); font-size: .78rem; }
.note-dot { display: inline-block; width: 8px; height: 8px; background: #91a47e; border-radius: 50%; margin-right: 8px; }
.hero-image-wrap { flex: 1 1 52%; position: relative; }
.hero-image { height: 450px; object-fit: cover; border-radius: 3px; }
.image-tag { position: absolute; bottom: 22px; left: -24px; background: var(--paper); padding: 15px 20px; box-shadow: 0 8px 25px #00000012; font-size: .82rem; }
.image-tag span { color: var(--muted); font-size: .72rem; }
.benefits { border-bottom: 1px solid var(--line); }
.benefit-row { display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 25px 0; }
.benefit-row > div { display: flex; align-items: center; gap: 13px; }
.benefit-icon { display: grid; place-items: center; width: 38px; height: 38px; border: 1px solid #dce2d8; border-radius: 50%; color: var(--green); font-size: 1.1rem; }
.benefit-row strong, .benefit-row small { display: block; }
.benefit-row strong { font-size: .83rem; }
.benefit-row small { color: var(--muted); font-size: .73rem; }
.section { padding: 88px 0; }
.section-heading { display: flex; justify-content: space-between; align-items: end; gap: 20px; margin-bottom: 32px; }
h2 { font-size: clamp(2.1rem, 4vw, 3.1rem); margin-bottom: 0; }
.section-heading .text-link { padding-bottom: 7px; }
.product-grid { display: flex; gap: 24px; }
.product-card { flex: 1 1 0; min-width: 0; }
.product-image { position: relative; overflow: hidden; background: var(--cream); }
.product-image img { height: 270px; object-fit: cover; transition: transform .5s ease; }
.product-card:hover .product-image img { transform: scale(1.045); }
.product-label { position: absolute; top: 14px; left: 14px; background: #fffefa; padding: 6px 9px; font-size: .62rem; letter-spacing: 1px; }
.product-info { display: flex; justify-content: space-between; gap: 10px; align-items: start; padding: 17px 0 8px; }
.product-info h3 { font-family: var(--serif); font-size: 1.25rem; font-weight: 500; margin-bottom: 4px; }
.product-info p { color: var(--muted); font-size: .78rem; margin: 0; }
.product-info > strong { font-size: .88rem; white-space: nowrap; padding-top: 4px; }
.card-link { display: flex; justify-content: space-between; border-top: 1px solid var(--line); padding: 12px 0; font-size: .8rem; font-weight: 600; transition: color .25s; }
.about-section { background: var(--cream); }
.about-layout { display: flex; align-items: center; gap: 70px; }
.about-image { flex: 1 1 52%; }
.about-image img { height: 390px; object-fit: cover; }
.about-copy { flex: 1 1 48%; }
.about-copy h2 { max-width: 470px; margin-bottom: 20px; }
.about-copy > p:not(.eyebrow) { max-width: 470px; color: var(--muted); line-height: 1.85; }
.contact-layout { display: flex; justify-content: space-between; gap: 70px; }
.contact-layout > div { flex: 1 1 50%; }
.contact-layout h2 { margin-bottom: 15px; }
.contact-intro { color: var(--muted); max-width: 400px; }
.contact-detail { display: flex; align-items: center; gap: 15px; margin-top: 22px; }
.contact-detail > span { display: grid; place-items: center; width: 38px; height: 38px; border-radius: 50%; background: var(--cream); color: var(--green); }
.contact-detail small { display: block; color: var(--muted); font-size: .7rem; }
.contact-detail a, .contact-detail p { font-size: .88rem; margin: 0; }
.contact-form { flex: 1 1 44%; display: flex; flex-direction: column; padding: 27px; background: var(--cream); }
.contact-form label { font-size: .78rem; font-weight: 700; margin: 0 0 7px; }
.contact-form input, .contact-form textarea { width: 100%; border: 1px solid #dfe2d9; background: var(--paper); padding: 12px; margin-bottom: 17px; font: inherit; font-size: .85rem; outline: none; resize: vertical; }
.contact-form input:focus, .contact-form textarea:focus { border-color: var(--green); box-shadow: 0 0 0 2px #526b5715; }
.contact-form button { align-self: flex-start; }
.form-note { color: var(--muted); margin-top: 12px; font-size: .68rem; }
.account-section { background: var(--green-dark); color: white; padding: 48px 0; }
.account-inner { display: flex; align-items: center; justify-content: space-between; gap: 30px; }
.account-section .eyebrow { color: #c6d4bd; }
.account-section h2 { font-size: 2.1rem; margin-bottom: 9px; }
.account-section p:not(.eyebrow) { color: #d6dfd4; margin-bottom: 0; font-size: .86rem; }
.site-footer { background: #202923; color: white; padding: 40px 0 18px; }
.footer-top { display: flex; align-items: center; justify-content: space-between; gap: 25px; padding-bottom: 32px; }
.footer-logo { display: inline-block; }
.footer-top p { color: #bdc7bd; font-size: .8rem; margin: 5px 0 0; }
.social-links { display: flex; align-items: center; gap: 20px; }
.social-links span { color: #aab7aa; font-size: .65rem; letter-spacing: 1.4px; }
.social-links a { font-size: .8rem; transition: color .2s; }
.social-links a:hover { color: #b7c9a9; }
.footer-bottom { display: flex; justify-content: space-between; gap: 20px; border-top: 1px solid #ffffff25; padding-top: 17px; color: #aab7aa; font-size: .7rem; }
@media (max-width: 850px) {
  .header-inner { flex-wrap: wrap; padding: 14px 0; }
  .main-nav { order: 3; width: 100%; justify-content: space-between; gap: 12px; }
  .hero-inner, .about-layout, .contact-layout { gap: 35px; }
  .hero-image { height: 380px; }
  .product-grid { gap: 16px; }
  .product-image img { height: 220px; }
}
@media (max-width: 620px) {
  .container { width: min(100% - 32px, 480px); }
  .header-inner { gap: 12px; }
  .logo { font-size: 1.7rem; }
  .header-cta { padding: 8px 11px; font-size: .76rem; }
  .main-nav { overflow-x: auto; justify-content: flex-start; gap: 20px; padding: 7px 0 2px; }
  .main-nav a { white-space: nowrap; font-size: .78rem; }
  .hero { padding: 50px 0 58px; }
  .hero-inner, .about-layout, .contact-layout { flex-direction: column; align-items: stretch; }
  h1 { font-size: 3.35rem; }
  .hero-image { height: 300px; }
  .image-tag { left: 10px; }
  .benefit-row { flex-wrap: wrap; justify-content: flex-start; }
  .benefit-row > div { flex: 1 1 42%; }
  .section { padding: 62px 0; }
  .section-heading { align-items: flex-start; flex-direction: column; }
  .product-grid { flex-direction: column; gap: 30px; }
  .product-image img { height: 290px; }
  .about-image img { height: 280px; }
  .contact-form { padding: 20px; }
  .account-inner, .footer-top, .footer-bottom { align-items: flex-start; flex-direction: column; }
  .social-links { flex-wrap: wrap; gap: 15px; }
}

```
## OUTPUT
<img width="1535" height="769" alt="OutputImage" src="https://github.com/user-attachments/assets/f7316063-9ba9-4d43-a9ba-21df57f6cced" />
<img width="1531" height="771" alt="OutputImage1" src="https://github.com/user-attachments/assets/3560bcbc-9006-497d-bf4e-1d9edcd67a77" />
<img width="1535" height="774" alt="OutputImage2" src="https://github.com/user-attachments/assets/e93b37d0-9a10-4faf-a547-3668139e581d" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
