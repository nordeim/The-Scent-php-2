Now let's craft a visually stunning and unique landing page for "The Scent." We'll aim for a premium, calming, and engaging feel, incorporating the "Wow Effect" through layout, imagery, and subtle details, while ensuring it reflects the company's mission and showcases the products.

Based on the requirements, the sample page, and the goal of a "Wow Effect," here's a plan:

1.  **Hero Section:** Full-screen or large hero image/video background with a compelling headline, short mission statement, and a clear Call-to-Action (CTA). We'll use high-quality imagery and elegant typography.
2.  **Our Philosophy/Mission:** A section explaining the brand's focus on mental/physical well-being and quality ingredients, perhaps pairing text with a relevant visual.
3.  **Featured Products:** A visually engaging grid or carousel showcasing the provided essential oil and soap images with minimal, clean text. Hover effects can add interactivity.
4.  **Discover Your Scent (Categories):** A unique visual representation of scent categories (Relaxation, Energy, etc.), potentially using icons, colors, and background textures that evoke the mood. This leads users towards exploration.
5.  **The Art of Aromatherapy (Optional Storytelling):** A section detailing the global sourcing, creative formulation process, and the relevance of aromatherapy today, reinforcing the premium aspect.
6.  **Testimonials:** Cleanly presented customer feedback to build trust.
7.  **Join Our Community (Newsletter):** An aesthetically pleasing signup form integrated into the page design.
8.  **Footer:** Standard links, contact information, social media icons, and copyright, styled consistently.

**Key "Wow" Elements:**

*   **Typography:** Using `Cormorant Garamond` for headings and `Montserrat` or `Raleway` for body text creates an elegant contrast.
*   **Color Palette:** We'll use a sophisticated palette derived from nature – deep greens, earthy tones, soft neutrals, maybe a touch of gold or copper for accents.
*   **Imagery:** High-resolution, evocative images are crucial.
*   **Layout:** Moving beyond simple stacked blocks. Using asymmetric layouts, overlapping elements (subtly), and generous whitespace.
*   **Micro-interactions:** Subtle hover effects, smooth transitions, maybe parallax scrolling on the hero image.

---

Here is the HTML (`index.html`) and CSS (`style.css`) code for the landing page.

**index.html:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Scent - Premium Aromatherapy & Natural Well-being</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Montserrat:wght@300;400;500&family=Raleway:wght@400;500;600&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- Link to CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header class="main-header">
        <div class="container header-container">
            <div class="logo">
                <a href="#">The Scent</a>
                <span>AROMATHERAPY</span>
            </div>
            <nav class="main-nav">
                <ul>
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#products">Shop</a></li>
                    <li><a href="#finder">Scent Finder</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="header-icons">
                <a href="#" aria-label="Search"><i class="fas fa-search"></i></a>
                <a href="#" aria-label="Account"><i class="fas fa-user"></i></a>
                <a href="#" aria-label="Cart"><i class="fas fa-shopping-bag"></i></a>
            </div>
             <button class="mobile-nav-toggle" aria-label="Toggle navigation">
                <i class="fas fa-bars"></i>
            </button>
        </div>
         <!-- Mobile Menu (hidden by default) -->
        <nav class="mobile-nav">
            <ul>
                <li><a href="#hero">Home</a></li>
                <li><a href="#products">Shop</a></li>
                <li><a href="#finder">Scent Finder</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                 <li><a href="#">Search</a></li>
                <li><a href="#">Account</a></li>
                <li><a href="#">Cart</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="hero-section">
            <div class="hero-background">
                <!-- Background image set in CSS -->
            </div>
            <div class="container hero-content">
                <h1>Find Your Moment of Calm</h1>
                <p>Elevate your well-being with our premium, natural aromatherapy products, crafted to restore balance and peace.</p>
                <a href="#products" class="btn btn-primary">Explore Our Collections</a>
            </div>
        </section>

        <!-- About/Mission Section -->
        <section id="about" class="about-section">
            <div class="container about-container">
                <div class="about-image">
                     <img src="https://raw.githubusercontent.com/nordeim/The-Scent/refs/heads/main/images/scent6.jpg" alt="Natural ingredients used in The Scent products">
                </div>
                <div class="about-text">
                    <h2>Rooted in Nature, Crafted with Care</h2>
                    <p>At The Scent, we believe in the power of nature to nurture mental and physical health. We meticulously source high-quality raw materials from around the globe, creating unique and harmonious aromatherapy blends. Our passion lies in crafting balanced, well-rounded products designed to help you navigate the stresses of modern life.</p>
                    <a href="#" class="btn btn-secondary">Learn Our Story</a>
                </div>
            </div>
        </section>

        <!-- Featured Products Section -->
        <section id="products" class="products-section">
            <div class="container">
                <h2>Featured Collections</h2>
                <div class="product-grid">
                    <!-- Product 1: Essential Oil -->
                    <div class="product-card">
                        <img src="https://raw.githubusercontent.com/nordeim/The-Scent/refs/heads/main/images/scent2.jpg" alt="Essential Oil Blend 1">
                        <div class="product-info">
                            <h3>Serenity Blend Oil</h3>
                            <p>Calming Lavender & Chamomile</p>
                            <a href="#" class="product-link">View Product</a>
                        </div>
                    </div>
                    <!-- Product 2: Soap -->
                    <div class="product-card">
                        <img src="https://raw.githubusercontent.com/nordeim/The-Scent/refs/heads/main/images/soap4.jpg" alt="Natural Soap 1">
                        <div class="product-info">
                            <h3>Citrus Burst Soap</h3>
                            <p>Energizing Lemon & Orange Peel</p>
                            <a href="#" class="product-link">View Product</a>
                        </div>
                    </div>
                    <!-- Product 3: Essential Oil -->
                     <div class="product-card">
                        <img src="https://raw.githubusercontent.com/nordeim/The-Scent/refs/heads/main/images/scent4.jpg" alt="Essential Oil Blend 2">
                        <div class="product-info">
                            <h3>Focus Flow Oil</h3>
                            <p>Invigorating Rosemary & Mint</p>
                            <a href="#" class="product-link">View Product</a>
                        </div>
                    </div>
                     <!-- Product 4: Soap -->
                    <div class="product-card">
                        <img src="https://raw.githubusercontent.com/nordeim/The-Scent/refs/heads/main/images/soap6.jpg" alt="Natural Soap 2">
                         <div class="product-info">
                            <h3>Woodland Retreat Soap</h3>
                            <p>Grounding Cedarwood & Pine</p>
                            <a href="#" class="product-link">View Product</a>
                        </div>
                    </div>
                </div>
                 <div class="view-all-cta">
                     <a href="#" class="btn btn-primary">Shop All Products</a>
                 </div>
            </div>
        </section>

        <!-- Scent Finder Section -->
        <section id="finder" class="finder-section">
            <div class="container">
                <h2>Discover Your Perfect Scent</h2>
                <p class="finder-subtitle">Tailor your aromatherapy experience to your mood and needs.</p>
                <div class="finder-grid">
                    <div class="finder-card">
                        <i class="fas fa-leaf finder-icon"></i>
                        <h3>Relaxation</h3>
                        <p>Calming scents to help you unwind.</p>
                    </div>
                    <div class="finder-card">
                        <i class="fas fa-bolt finder-icon"></i>
                        <h3>Energy</h3>
                        <p>Invigorating scents to boost vitality.</p>
                    </div>
                    <div class="finder-card">
                        <i class="fas fa-brain finder-icon"></i>
                        <h3>Focus</h3>
                        <p>Clarifying scents for concentration.</p>
                    </div>
                     <div class="finder-card">
                        <i class="fas fa-moon finder-icon"></i>
                        <h3>Sleep</h3>
                        <p>Soothing scents for restful nights.</p>
                    </div>
                    <div class="finder-card">
                         <i class="fas fa-balance-scale finder-icon"></i>
                        <h3>Balance</h3>
                        <p>Harmonizing scents to center your mind.</p>
                    </div>
                </div>
                <div class="finder-cta">
                    <a href="#" class="btn btn-secondary">Take the Full Scent Quiz</a>
                </div>
            </div>
        </section>

         <!-- Testimonials Section -->
        <section id="testimonials" class="testimonials-section">
            <div class="container">
                <h2>What Our Community Says</h2>
                 <div class="testimonial-grid">
                    <div class="testimonial-card">
                        <p>"The Lavender Essential Oil transformed my bedtime routine. The calming aroma helps me unwind like never before. Pure quality!"</p>
                        <span class="testimonial-author">- Sarah L., Los Angeles</span>
                         <div class="testimonial-rating">★★★★★</div>
                    </div>
                     <div class="testimonial-card">
                        <p>"I was skeptical, but the Focus Blend oil genuinely improved my concentration while working from home. It's subtle but effective."</p>
                        <span class="testimonial-author">- Michael T., Chicago</span>
                        <div class="testimonial-rating">★★★★★</div>
                    </div>
                    <div class="testimonial-card">
                         <p>"These handcrafted soaps are amazing! They smell divine, helped clear my sensitive skin, and feel so much better than store-bought."</p>
                         <span class="testimonial-author">- Emma R., Seattle</span>
                         <div class="testimonial-rating">★★★★★</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Newsletter Section -->
        <section id="newsletter" class="newsletter-section">
            <div class="container newsletter-container">
                 <h2>Join Our Community</h2>
                 <p>Subscribe for exclusive offers, aromatherapy tips, and early access to new products.</p>
                <form class="newsletter-form">
                    <input type="email" placeholder="Your email address" required>
                    <button type="submit" class="btn btn-primary">Subscribe</button>
                </form>
                 <p class="newsletter-consent">By subscribing, you agree to our Privacy Policy.</p>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer id="contact" class="main-footer">
        <div class="container footer-grid">
            <div class="footer-about">
                <h3>About The Scent</h3>
                <p>Creating premium aromatherapy products to enhance mental and physical well-being through the power of scent.</p>
                 <div class="social-icons">
                    <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                    <a href="#" aria-label="Pinterest"><i class="fab fa-pinterest"></i></a>
                </div>
            </div>
             <div class="footer-links">
                <h3>Shop</h3>
                <ul>
                    <li><a href="#">Essential Oils</a></li>
                    <li><a href="#">Natural Soaps</a></li>
                    <li><a href="#">Gift Sets</a></li>
                    <li><a href="#">New Arrivals</a></li>
                    <li><a href="#">Bestsellers</a></li>
                </ul>
            </div>
            <div class="footer-links">
                <h3>Help</h3>
                 <ul>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">FAQs</a></li>
                    <li><a href="#">Shipping & Returns</a></li>
                    <li><a href="#">Track Your Order</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                </ul>
            </div>
             <div class="footer-contact">
                 <h3>Contact Us</h3>
                <p><i class="fas fa-map-marker-alt"></i> 123 Aromatherapy Lane, Wellness City, WB 12345</p>
                <p><i class="fas fa-phone"></i> +1 (555) 123-4567</p>
                <p><i class="fas fa-envelope"></i> hello@thescent.com</p>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container">
                <p>&copy; 2025 The Scent. All rights reserved.</p>
                <!-- Add payment method icons if needed -->
                 <div class="payment-methods">
                     <span>Accepted Payments:</span>
                    <i class="fab fa-cc-visa"></i>
                    <i class="fab fa-cc-mastercard"></i>
                    <i class="fab fa-cc-paypal"></i>
                    <i class="fab fa-cc-amex"></i>
                 </div>
            </div>
        </div>
    </footer>

    <script>
        // Basic Mobile Menu Toggle
        const toggleButton = document.querySelector('.mobile-nav-toggle');
        const mobileNav = document.querySelector('.mobile-nav');
        const mainHeader = document.querySelector('.main-header');

        if (toggleButton && mobileNav && mainHeader) {
            toggleButton.addEventListener('click', () => {
                mobileNav.classList.toggle('active');
                mainHeader.classList.toggle('mobile-menu-active'); // Add class to header
                 // Change icon
                const icon = toggleButton.querySelector('i');
                if (mobileNav.classList.contains('active')) {
                    icon.classList.remove('fa-bars');
                    icon.classList.add('fa-times');
                } else {
                    icon.classList.remove('fa-times');
                    icon.classList.add('fa-bars');
                }
            });
             // Close menu when a link is clicked
            mobileNav.querySelectorAll('a').forEach(link => {
                link.addEventListener('click', () => {
                     mobileNav.classList.remove('active');
                     mainHeader.classList.remove('mobile-menu-active');
                      const icon = toggleButton.querySelector('i');
                        icon.classList.remove('fa-times');
                        icon.classList.add('fa-bars');
                });
            });
        }

         // Simple sticky header effect
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                 mainHeader.classList.add('sticky');
            } else {
                mainHeader.classList.remove('sticky');
             }
        });

    </script>

</body>
</html>
```

**style.css:**

```css
/* --- Base Styles & Variables --- */
:root {
    --font-heading: 'Cormorant Garamond', serif;
    --font-body: 'Montserrat', sans-serif;
    --font-accent: 'Raleway', sans-serif;

    --color-primary: #1A4D5A; /* Deep Teal */
    --color-secondary: #A0C1B1; /* Soft Mint Green */
    --color-accent: #D4A76A; /* Muted Gold/Ochre */
    --color-background: #F8F5F2; /* Warm Off-White */
    --color-text: #333333; /* Dark Grey */
    --color-text-light: #FFFFFF;
    --color-border: #e0e0e0;

    --container-width: 1200px;
    --spacing-unit: 1rem; /* Approx 16px */

    --transition-speed: 0.3s;
}

*, *::before, *::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
    font-size: 100%; /* Base font size (usually 16px) */
}

body {
    font-family: var(--font-body);
    color: var(--color-text);
    background-color: var(--color-background);
    line-height: 1.7;
    overflow-x: hidden; /* Prevent horizontal scroll */
}

h1, h2, h3, h4, h5, h6 {
    font-family: var(--font-heading);
    font-weight: 600;
    color: var(--color-primary);
    margin-bottom: calc(var(--spacing-unit) * 1);
    line-height: 1.2;
}

h1 { font-size: clamp(2.5rem, 5vw, 4rem); }
h2 { font-size: clamp(1.8rem, 4vw, 2.8rem); }
h3 { font-size: clamp(1.3rem, 3vw, 1.8rem); }

p {
    margin-bottom: calc(var(--spacing-unit) * 1);
    max-width: 70ch; /* Improve readability */
}

a {
    color: var(--color-primary);
    text-decoration: none;
    transition: color var(--transition-speed) ease;
}

a:hover, a:focus {
    color: var(--color-accent);
}

img {
    max-width: 100%;
    height: auto;
    display: block;
}

ul {
    list-style: none;
}

.container {
    width: 90%;
    max-width: var(--container-width);
    margin: 0 auto;
    padding: 0 var(--spacing-unit);
}

/* --- Buttons --- */
.btn {
    display: inline-block;
    font-family: var(--font-accent);
    font-weight: 500;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    padding: calc(var(--spacing-unit) * 0.8) calc(var(--spacing-unit) * 2);
    border-radius: 50px; /* Pill shape */
    cursor: pointer;
    transition: background-color var(--transition-speed) ease, color var(--transition-speed) ease, transform var(--transition-speed) ease;
    border: 2px solid transparent;
}

.btn-primary {
    background-color: var(--color-primary);
    color: var(--color-text-light);
    border-color: var(--color-primary);
}

.btn-primary:hover, .btn-primary:focus {
    background-color: var(--color-accent);
    border-color: var(--color-accent);
    color: var(--color-text-light);
    transform: translateY(-2px);
}

.btn-secondary {
    background-color: transparent;
    color: var(--color-primary);
    border-color: var(--color-primary);
}

.btn-secondary:hover, .btn-secondary:focus {
    background-color: var(--color-primary);
    color: var(--color-text-light);
     transform: translateY(-2px);
}

/* --- Header --- */
.main-header {
    position: absolute; /* Overlay on hero */
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    padding: calc(var(--spacing-unit) * 1.5) 0;
    background: transparent;
    transition: background-color var(--transition-speed) ease, box-shadow var(--transition-speed) ease, padding var(--transition-speed) ease;
}
.main-header.sticky {
     position: fixed;
     background-color: rgba(255, 255, 255, 0.95); /* Slightly transparent white */
     box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
     padding: calc(var(--spacing-unit) * 0.8) 0;
}
.main-header.sticky .logo a,
.main-header.sticky .main-nav a,
.main-header.sticky .header-icons a,
.main-header.sticky .mobile-nav-toggle {
    color: var(--color-primary);
}
.main-header.sticky .logo span {
    color: var(--color-text);
}
.main-header.sticky .main-nav a:hover,
.main-header.sticky .header-icons a:hover {
    color: var(--color-accent);
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo a {
    font-family: var(--font-heading);
    font-size: 1.8rem;
    font-weight: 700;
    color: var(--color-text-light); /* White for hero overlay */
    text-transform: uppercase;
    letter-spacing: 1px;
}
.logo span {
    display: block;
    font-family: var(--font-accent);
    font-size: 0.6rem;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--color-text-light); /* White for hero overlay */
    margin-top: -5px;
    opacity: 0.8;
}


.main-nav ul {
    display: flex;
    gap: calc(var(--spacing-unit) * 2);
}

.main-nav a {
    font-family: var(--font-accent);
    font-weight: 500;
    color: var(--color-text-light); /* White for hero overlay */
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 5px 0;
    position: relative;
}
/* Underline effect */
.main-nav a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    background-color: var(--color-accent);
    transition: width var(--transition-speed) ease;
}
.main-nav a:hover::after, .main-nav a:focus::after {
    width: 100%;
}


.header-icons {
    display: flex;
    gap: calc(var(--spacing-unit) * 1.5);
}

.header-icons a {
    color: var(--color-text-light); /* White for hero overlay */
    font-size: 1.2rem;
}

.mobile-nav-toggle {
    display: none; /* Hidden on desktop */
    background: none;
    border: none;
    color: var(--color-text-light); /* White for hero overlay */
    font-size: 1.5rem;
    cursor: pointer;
    z-index: 1001; /* Above mobile nav */
}

.mobile-nav {
    display: none; /* Hidden by default */
    position: absolute;
    top: 100%; /* Position below header */
    left: 0;
    width: 100%;
    background-color: rgba(255, 255, 255, 0.98); /* Match sticky header */
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    padding: var(--spacing-unit);
    max-height: 0;
    overflow: hidden;
     transition: max-height 0.5s ease-out;
}
.mobile-nav.active {
     display: block; /* Show when active */
     max-height: 500px; /* Adjust as needed */
}
.main-header.mobile-menu-active {
     background-color: rgba(255, 255, 255, 0.98); /* Ensure bg when mobile menu is open */
}
.main-header.mobile-menu-active .logo a,
.main-header.mobile-menu-active .logo span,
.main-header.mobile-menu-active .mobile-nav-toggle {
    color: var(--color-primary); /* Darken elements when mobile menu is open */
}


.mobile-nav ul {
    display: flex;
    flex-direction: column;
    gap: var(--spacing-unit);
}

.mobile-nav a {
    display: block;
    padding: calc(var(--spacing-unit) * 0.5);
    color: var(--color-primary);
    font-family: var(--font-accent);
    text-transform: uppercase;
    text-align: center;
    font-size: 1.1rem;
    transition: background-color var(--transition-speed) ease;
}
.mobile-nav a:hover, .mobile-nav a:focus {
     background-color: var(--color-secondary);
     color: var(--color-primary);
}


/* --- Hero Section --- */
.hero-section {
    position: relative;
    height: 100vh; /* Full viewport height */
    min-height: 600px; /* Minimum height */
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    overflow: hidden; /* Ensure pseudo-elements don't overflow */
    color: var(--color-text-light);
}

.hero-background {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('https://raw.githubusercontent.com/nordeim/The-Scent/refs/heads/main/images/scent5.jpg'); /* Replace with your best hero image */
    background-size: cover;
    background-position: center center;
    background-attachment: fixed; /* Parallax effect */
    z-index: -2;
    animation: zoomInOut 25s infinite alternate ease-in-out; /* Subtle zoom */
}

/* Dark overlay for text contrast */
.hero-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.4); /* Adjust darkness */
    z-index: -1;
}

.hero-content {
    position: relative; /* Ensure content is above overlay */
    z-index: 1;
    max-width: 800px;
    animation: fadeIn 1.5s ease-out;
}

.hero-content h1 {
    color: var(--color-text-light);
    font-weight: 700;
    margin-bottom: calc(var(--spacing-unit) * 1);
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: calc(var(--spacing-unit) * 2);
    opacity: 0.9;
     max-width: 60ch;
     margin-left: auto;
     margin-right: auto;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

@keyframes zoomInOut {
     from { transform: scale(1); }
    to { transform: scale(1.05); }
}

/* --- Generic Section Styling --- */
section {
    padding: calc(var(--spacing-unit) * 5) 0;
}
section:nth-child(odd) { /* Alternate background for visual separation */
    background-color: #fff; /* Slightly different from body bg */
}
section h2 {
    text-align: center;
    margin-bottom: calc(var(--spacing-unit) * 3);
}

/* --- About Section --- */
.about-section {
    background-color: #fff; /* White background */
}
.about-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: calc(var(--spacing-unit) * 4);
    align-items: center;
}
.about-image img {
    border-radius: 8px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    transition: transform var(--transition-speed) ease;
}
.about-image img:hover {
    transform: scale(1.03);
}
.about-text h2 {
    text-align: left;
}
.about-text p {
    margin-bottom: calc(var(--spacing-unit) * 2);
}

/* --- Products Section --- */
.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: calc(var(--spacing-unit) * 2.5);
}
.product-card {
    background-color: #fff;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
    transition: transform var(--transition-speed) ease, box-shadow var(--transition-speed) ease;
    position: relative;
}
.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
}
.product-card img {
    width: 100%;
    height: 250px; /* Fixed height */
    object-fit: cover; /* Cover the area */
    transition: opacity var(--transition-speed) ease;
}
.product-card:hover img {
    opacity: 0.85;
}
.product-info {
    padding: calc(var(--spacing-unit) * 1.5);
    text-align: center;
}
.product-info h3 {
    margin-bottom: calc(var(--spacing-unit) * 0.5);
    font-size: 1.3rem;
}
.product-info p {
    font-size: 0.9rem;
    color: #666;
    margin-bottom: calc(var(--spacing-unit) * 1);
}
.product-link {
    font-family: var(--font-accent);
    font-weight: 500;
    color: var(--color-accent);
    text-transform: uppercase;
    font-size: 0.85rem;
    letter-spacing: 0.5px;
    position: relative;
     padding-bottom: 3px;
}
.product-link::after {
    content: '';
    position: absolute;
    width: 0;
    height: 1px;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    background-color: var(--color-accent);
    transition: width var(--transition-speed) ease;
}
.product-card:hover .product-link::after {
    width: 50%;
}
.view-all-cta {
    text-align: center;
    margin-top: calc(var(--spacing-unit) * 3);
}


/* --- Scent Finder Section --- */
.finder-section {
    background-color: var(--color-secondary); /* Use the soft green */
    color: var(--color-primary); /* Dark text on light bg */
}
.finder-section h2 {
     color: var(--color-primary);
}
.finder-subtitle {
     text-align: center;
     margin-top: calc(var(--spacing-unit) * -2); /* Pull up closer to title */
     margin-bottom: calc(var(--spacing-unit) * 3);
     opacity: 0.9;
}

.finder-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: calc(var(--spacing-unit) * 2);
}
.finder-card {
    background-color: rgba(255, 255, 255, 0.5); /* Semi-transparent white */
    padding: calc(var(--spacing-unit) * 2) calc(var(--spacing-unit) * 1.5);
    border-radius: 8px;
    text-align: center;
    transition: background-color var(--transition-speed) ease, transform var(--transition-speed) ease;
    cursor: pointer;
}
.finder-card:hover {
    background-color: rgba(255, 255, 255, 0.8);
    transform: translateY(-5px);
}
.finder-icon {
    font-size: 2.5rem;
    color: var(--color-primary);
    margin-bottom: var(--spacing-unit);
    display: block;
}
.finder-card h3 {
    font-size: 1.2rem;
     margin-bottom: calc(var(--spacing-unit) * 0.5);
}
.finder-card p {
     font-size: 0.9rem;
     line-height: 1.5;
     color: var(--color-text);
     margin-bottom: 0;
}
.finder-cta {
    text-align: center;
    margin-top: calc(var(--spacing-unit) * 3);
}
.finder-cta .btn-secondary {
     border-color: var(--color-primary); /* Ensure border matches text color */
}
.finder-cta .btn-secondary:hover {
    background-color: var(--color-primary);
    color: var(--color-text-light);
}

/* --- Testimonials Section --- */
.testimonials-section {
    background-color: #fff;
}
.testimonial-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: calc(var(--spacing-unit) * 2);
}
.testimonial-card {
    background-color: var(--color-background); /* Use the warm off-white */
    padding: calc(var(--spacing-unit) * 2);
    border-radius: 8px;
    border-left: 5px solid var(--color-secondary); /* Accent border */
    box-shadow: 0 4px 10px rgba(0,0,0,0.03);
}
.testimonial-card p {
    font-style: italic;
    margin-bottom: var(--spacing-unit);
    color: #555;
}
.testimonial-author {
    display: block;
    font-weight: 500;
    color: var(--color-primary);
    margin-bottom: calc(var(--spacing-unit) * 0.5);
}
.testimonial-rating {
    color: var(--color-accent);
    font-size: 1.1rem;
}

/* --- Newsletter Section --- */
.newsletter-section {
     background-color: var(--color-primary);
     color: var(--color-text-light);
     padding: calc(var(--spacing-unit) * 4) 0;
}
.newsletter-section h2 {
    color: var(--color-text-light);
}
.newsletter-container {
     text-align: center;
     max-width: 700px;
}
.newsletter-container p {
    opacity: 0.9;
    margin-bottom: calc(var(--spacing-unit) * 1.5);
}
.newsletter-form {
    display: flex;
    justify-content: center;
    gap: var(--spacing-unit);
    margin-bottom: var(--spacing-unit);
    flex-wrap: wrap; /* Wrap on smaller screens */
}
.newsletter-form input[type="email"] {
    padding: calc(var(--spacing-unit) * 0.8);
    border: 1px solid var(--color-secondary);
    border-radius: 50px;
    font-family: var(--font-body);
    min-width: 300px;
    flex-grow: 1; /* Take available space */
}
.newsletter-form .btn {
    background-color: var(--color-accent);
    color: var(--color-primary);
    border-color: var(--color-accent);
}
.newsletter-form .btn:hover {
    background-color: var(--color-secondary);
    border-color: var(--color-secondary);
    color: var(--color-primary);
}
.newsletter-consent {
    font-size: 0.8rem;
    opacity: 0.7;
    margin-bottom: 0;
}
.newsletter-consent a {
    color: var(--color-secondary);
    text-decoration: underline;
}
.newsletter-consent a:hover {
    color: var(--color-text-light);
}

/* --- Footer --- */
.main-footer {
    background-color: #2f3d41; /* Darker shade */
    color: #ccc;
    padding-top: calc(var(--spacing-unit) * 4);
    font-size: 0.9rem;
}
.footer-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: calc(var(--spacing-unit) * 3);
    margin-bottom: calc(var(--spacing-unit) * 3);
}
.footer-about h3, .footer-links h3, .footer-contact h3 {
    font-family: var(--font-accent);
    color: var(--color-text-light);
    font-weight: 600;
    margin-bottom: calc(var(--spacing-unit) * 1.2);
    font-size: 1.1rem;
}
.footer-about p {
    line-height: 1.6;
    margin-bottom: var(--spacing-unit);
}
.social-icons {
    display: flex;
    gap: var(--spacing-unit);
}
.social-icons a {
    color: #ccc;
    font-size: 1.2rem;
    transition: color var(--transition-speed) ease, transform var(--transition-speed) ease;
}
.social-icons a:hover {
    color: var(--color-accent);
    transform: scale(1.1);
}

.footer-links ul li {
    margin-bottom: calc(var(--spacing-unit) * 0.5);
}
.footer-links a {
    color: #ccc;
}
.footer-links a:hover {
    color: var(--color-text-light);
    text-decoration: underline;
}
.footer-contact p {
    margin-bottom: calc(var(--spacing-unit) * 0.6);
    display: flex;
    align-items: center;
    gap: calc(var(--spacing-unit) * 0.5);
}
.footer-contact i {
    color: var(--color-secondary);
    width: 16px; /* Align icons */
    text-align: center;
}

.footer-bottom {
    background-color: #222b2e; /* Even darker */
    padding: calc(var(--spacing-unit) * 1.5) 0;
    margin-top: calc(var(--spacing-unit) * 2);
}
.footer-bottom .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap; /* Wrap on small screens */
    gap: var(--spacing-unit);
    font-size: 0.85rem;
}
.payment-methods {
    display: flex;
    align-items: center;
    gap: calc(var(--spacing-unit) * 0.8);
}
.payment-methods span {
     margin-right: calc(var(--spacing-unit) * 0.5);
}
.payment-methods i {
    font-size: 1.8rem;
    color: #aaa;
}


/* --- Responsive Design --- */

/* Tablets and smaller desktops */
@media (max-width: 992px) {
    .header-container {
        padding: 0 calc(var(--spacing-unit) * 1.5); /* More padding on smaller screens */
    }
     .main-nav {
        display: none; /* Hide desktop nav */
    }
    .header-icons {
        display: none; /* Hide icons or move to mobile menu */
    }
    .mobile-nav-toggle {
        display: block; /* Show hamburger */
    }
    .about-container {
        grid-template-columns: 1fr; /* Stack elements */
        text-align: center;
    }
     .about-image {
         margin-bottom: calc(var(--spacing-unit) * 2);
         order: -1; /* Move image above text */
     }
    .about-text h2 {
         text-align: center;
    }
    .footer-grid {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Adjust columns */
    }
}

/* Mobile phones */
@media (max-width: 576px) {
    h1 { font-size: 2rem; }
    h2 { font-size: 1.6rem; }
    h3 { font-size: 1.2rem; }

    .hero-section {
        min-height: 500px;
    }
     .hero-content p {
        font-size: 1rem;
    }
     .btn {
         padding: calc(var(--spacing-unit) * 0.7) calc(var(--spacing-unit) * 1.5);
         font-size: 0.9rem;
    }

     section {
        padding: calc(var(--spacing-unit) * 3) 0;
    }
     section h2 {
        margin-bottom: calc(var(--spacing-unit) * 2);
    }

    .product-grid {
        grid-template-columns: 1fr; /* Single column */
        gap: calc(var(--spacing-unit) * 1.5);
    }
     .finder-grid {
        grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); /* Allow smaller cards */
        gap: var(--spacing-unit);
    }
    .finder-card {
        padding: calc(var(--spacing-unit) * 1.5) var(--spacing-unit);
    }
     .testimonial-grid {
         grid-template-columns: 1fr;
     }
    .newsletter-form {
        flex-direction: column; /* Stack form elements */
        align-items: stretch; /* Full width */
    }
     .newsletter-form input[type="email"] {
         min-width: auto;
         width: 100%;
    }
    .newsletter-form .btn {
         width: 100%;
    }

    .footer-grid {
        grid-template-columns: 1fr; /* Single column */
        text-align: center;
    }
     .footer-about p, .footer-contact p {
         justify-content: center;
     }
     .social-icons {
        justify-content: center;
        margin-top: var(--spacing-unit);
    }
    .footer-bottom .container {
        flex-direction: column;
        text-align: center;
    }
    .payment-methods {
        margin-top: var(--spacing-unit);
    }

}
```

**How to Use:**

1.  Save the HTML code as `index.html`.
2.  Save the CSS code as `style.css` in the same folder as `index.html`.
3.  Open `index.html` in your web browser.

**Further Enhancements for "Wow":**

1.  **Animations on Scroll:** Use a small JavaScript library (like AOS - Animate On Scroll or Intersection Observer API) to make elements fade or slide in as the user scrolls down the page.
2.  **Interactive Scent Finder:** Develop the "Take the Full Scent Quiz" button to lead to an actual interactive quiz page.
3.  **Hero Video:** Replace the hero background image with a calming, high-quality background video loop (nature, flowing liquids, etc.). Ensure it's optimized for web use.
4.  **Parallax Depth:** Implement more advanced parallax effects where different layers move at different speeds for a greater sense of depth.
5.  **Product Image Carousel:** If you have many featured products, use a subtle carousel/slider instead of a static grid.
6.  **Custom Icons:** Instead of Font Awesome for the finder section, create custom SVG icons that perfectly match the brand aesthetic.
7.  **Load Optimization:** Ensure images are optimized (correct format like WebP, appropriate size) for faster loading.

This design provides a strong foundation that is visually appealing, unique compared to the sample, reflects the brand's mission, and incorporates elements designed to create a premium "Wow Effect." Remember to replace placeholder links (`#`) with actual page URLs as you build out the rest of the site.
