
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Connect | Converse | Create | Collaborate | Coexist">
  <meta name="keywords" content="cafe, networking hub, community events, Comffee Connect">
  <meta name="author" content="Comffee Connect">

  <!-- Open Graph for Social Media -->
  <meta property="og:title" content="Comffee Connect - Cafe & Networking Hub">
  <meta property="og:description" content="A Cosy Hub of Creative Ideas, Innovative Solutions, and Community.">
  <meta property="og:image" content="https://www.comffeeconnect.com/images/logo.png">
  <meta property="og:url" content="https://www.comffeeconnect.com">
  <meta property="og:type" content="website">
    <title>Comffee Connect</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="icon" type="image/png" href="https://www.comffeeconnect.com/images/logo.png">
</head>
<body>
  <!-- Header -->
  <header role="banner">
    <div class="container header-container">
      <!-- Branding: Logo and Title always on one line -->
      <div class="branding">
        <a href="#hero" aria-label="Comffee Connect Home" class="header-logo-link">
          <img src="https://raw.githubusercontent.com/CMULS/comfeeconnect/refs/heads/main/WhatsApp%20Image%202025-07-14%20at%2015.08.58_e41e5502.jpg" alt="Comffee Connect Cafe Logo" class="logo" width="50" height="50">
        </a>
        <h1>Comffee Connect</h1>
      </div>
      <!-- Navigation -->
      <nav role="navigation" aria-label="Main navigation">
        <ul>
          <li><a href="#hero" aria-current="page">HOME</a></li>
          <li><a href="#services">SERVICES</a></li>
          <li><a href="#contact">CONTACT</a></li>
        </ul>
      </nav>
    </div>
  </header>
    <!-- Spacer to push content below the fixed header -->
  <div class="header-spacer"></div>

  <!-- Hero Section -->
  <section id="hero" class="fade-in" aria-labelledby="hero-title">
    <h2 id="hero-title">What is Comffee Connect?</h2>
    <p>A Cozy Space Where Community, Creativity, and Connection Come Alive</p>
    <a href="https://wa.me/8615718899118" target="_blank" class="cta-button" rel="noopener noreferrer">Learn More</a>
  </section>
<!-- Services Section -->
  <section id="services" class="fade-in" aria-labelledby="services-title">
    <div class="container">
      <h2 id="services-title">How to Connect</h2>
      <p>Thinking of Attending a Comffee Connect Event?</p>
      <div class="services-grid">
        <div class="service-card">
          <h3>RSVP</h3>
          <p>Book your slot at the next Comffee Connect.</p>
          <a href="https://wa.me/8615718899118" target="_blank" class="cta-button" rel="noopener noreferrer">Book Here</a>
        </div>
        <div class="service-card">
          <h3>Volunteer</h3>
          <p>Help us touch more lives with Comffee Connect.</p>
          <a href="https://wa.me/8615718899118" target="_blank" class="cta-button" rel="noopener noreferrer">See How</a>
        </div>
        <div class="service-card">
          <h3>Instagram</h3>
          <p>Follow Comffee Connect on IG to stay in the loop.</p>
          <a href="https://www.instagram.com/comffeeconnect/" target="_blank" class="cta-button" rel="noopener noreferrer">Join Us</a>
        </div>
      </div>
    </div>
  </section>
    <!-- Contact Section -->
  <section id="contact" class="fade-in" aria-labelledby="contact-title">
    <div class="container">
      <h2 id="contact-title">📩 Let’s Talk</h2>
      <p>Have questions? Need help? Send a quick message.</p>
      <form id="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
        <div class="form-group">
          <label for="name">Your Name</label>
          <input type="text" id="name" name="name" placeholder="Your Name" required aria-required="true">
        </div>
        <div class="form-group">
          <label for="email">Your Email</label>
          <input type="email" id="email" name="email" placeholder="Your Email" required aria-required="true">
        </div>
        <div class="form-group">
          <label for="message">Your Message</label>
          <textarea id="message" name="message" rows="4" placeholder="Your Message" required aria-required="true"></textarea>
        </div>
        <button type="submit" class="cta-button">Send Message</button>
      </form>
    </div>
  </section>
  <!-- Footer -->
  <footer role="contentinfo">
    <div class="container">
      <p>© 2025 Comffee Connect Enterprises. All rights reserved.</p>
    </div>
  </footer>

  <script src="global.js"></script>
</body>
</html>
<style>
    * {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  scroll-behavior: smooth;
}

/* Body & HTML: Combined Background Image and Color */
body,
html {
  font-family: "Inter", sans-serif;
  background: url("https://raw.githubusercontent.com/engineeredbytio/altbg/2d6ad2af5666b6e0437ba1d9dd02eb1562bb1eb4/tiosyncedthis.png")
    no-repeat center center fixed;
  background-size: cover;
  background-color: #121212; /* Dark mode base fallback */
  color: #fff;
  line-height: 1.6;
}
.header-spacer {
  height: 120px; /* Adjust to match the header height */
}

/* ========== Headings ========== */
h1,
h2,
h3 {
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 1px;
  text-align: center;
}
h1 {
  font-size: 2.5rem;
  white-space: nowrap; /* Keep title on one line */
}
h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}
h3 {
  font-size: 1.2rem;
  margin-bottom: 15px;
}
/* ========== Container (Glassmorphism Style) ========== */
.container {
  width: 90%;
  max-width: 1200px;
  margin: 20px auto;
  background: rgba(255, 255, 255, 0.08);
  padding: 40px;
  border-radius: 15px;
  backdrop-filter: blur(12px);
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.6);
}
/* ========== Header ========== */
header {
  position: fixed;
  width: 100%;
  background: rgba(0, 0, 0, 0.5);
  padding: 10px 0;
  backdrop-filter: blur(8px);
  transition: background 0.3s ease-in-out;
  z-index: 1000;
}
.header-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 90%;
  margin: 0 auto;
  flex-wrap: wrap; /* Allows navigation to drop if needed */
} 
/* Branding: Logo and Title stay together */
.branding {
  display: flex;
  align-items: center;
  white-space: nowrap;
}
.branding h1 {
  margin-left: 10px;
}
/* Logo */
.logo {
  width: 50px;
  height: auto;
  transition: transform 0.3s ease-in-out;
}
.logo:hover {
  transform: scale(1.05);
}
/* Navigation */
nav ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-end;
}nav ul li {
  margin-left: 20px;
}
nav ul li a {
  color: #ffffff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease-in-out;
  position: relative;
}
nav ul li a:hover {
  color: #1db954;
} 
/* ========== Hero Section ========== */
#hero {
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  background: radial-gradient(
    circle,
    rgba(18, 18, 18, 1) 0%,
    rgba(0, 0, 0, 1) 100%
  );
}
#hero p {
  font-size: 1.3rem;
  max-width: 800px;
  margin-bottom: 30px;
  opacity: 0.9;
  line-height: 1.8;
}
/* ========== Buttons (Spotify + Manus Fusion) ========== */
button,
.cta-button,
.social-button {
  display: inline-block;
  background: linear-gradient(135deg, #1db954, #18a345);
  color: #000;
  padding: 12px 28px;
  font-size: 1rem;
  font-weight: bold;
  text-transform: uppercase;
  text-decoration: none;
  border-radius: 10px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  min-width: 160px;
  text-align: center;
  border: none;
  cursor: pointer;
}
/* Hover Effect */
button:hover,
.cta-button:hover,
.social-button:hover {
  transform: scale(1.1);
  box-shadow: 0 6px 15px rgba(29, 185, 84, 0.4);
}
/* AI Button (Bigger & More Noticeable) */
#hero .cta-button {
  font-size: 1.3rem;
  padding: 18px 40px;
  min-width: 220px;
  background: linear-gradient(135deg, #ffffff, #dddddd);
  color: #000;
} 
/* ========== Services Section (Spotify-Style Cards) ========== */
#services {
  padding: 100px 0;
  text-align: center;
}
.services-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 30px;
}

.service-card {
  background: rgba(255, 255, 255, 0.1);
  padding: 30px;
  border-radius: 12px;
  width: 320px;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.service-card h3 {
  font-size: 1rem;
  margin-bottom: 10px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.service-card p {
  font-size: 0.9rem;
  margin-bottom: 15px;
  line-height: 1.4;
  color: #ccc;
}
/* Hover Effect */
.service-card:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 20px rgba(255, 255, 255, 0.1);
}

/* ========== Contact Section ========== */
#contact {
  padding: 100px 0;
  text-align: center;
}

#contact h2 {
  margin-bottom: 30px;
  font-size: 1.8rem;
}

/* Form Group Spacing */
.form-group {
  margin-bottom: 20px;
  text-align: left;
}

/* Input Fields */
input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 14px;
  margin-top: 10px;
  border: none;
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.1);
  color: #ffffff;
  font-size: 1rem;
  outline: none;
} 
/* Textarea (Larger Input Box) */
textarea {
  min-height: 120px;
  resize: vertical;
}

/* Submit Button */
button[type="submit"] {
  width: 100%;
  padding: 14px;
  margin-top: 20px;
  background: linear-gradient(135deg, #1db954, #18a345);
  color: #000;
  font-size: 1rem;
  font-weight: bold;
  border-radius: 8px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
button[type="submit"]:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 12px rgba(29, 185, 84, 0.5);
}

/* Social Media Spacing */
.social-media {
  margin-top: 40px;
  display: flex;
  justify-content: center;
  gap: 15px;
}
/* Social Media Buttons */
.social-button {
  background: #1db954;
  min-width: 160px;
  padding: 12px 24px;
}

/* Responsive Fix for Mobile */
@media (max-width: 768px) {
  .services-grid {
    flex-direction: column;
    align-items: center;
  }
  .social-media {
    flex-direction: column;
    align-items: center;
  }

  .social-button {
    width: 80%;
    margin-bottom: 10px;
  }
}
/* ========== Footer ========== */
footer {
  background: rgba(18, 18, 18, 0.9);
  padding: 30px 0;
  text-align: center;
}

footer p {
  font-size: 0.9rem;
  color: #ccc;
}
/* ========== Animations ========== */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeIn 0.6s ease-out forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
/* ========== Responsive Design ========== */
@media (max-width: 768px) {
  .header-spacer {
    height: 60px;
  }

  .header-container {
    flex-direction: column;
    align-items: center;
  }

  nav ul {
    flex-direction: column;
    align-items: center;
    margin-top: 10px;
  }
 nav ul li {
    margin: 5px 0;
  }

  .services-grid {
    grid-template-columns: 1fr;
  }

  #hero,
  #services,
  #contact {
    padding: 60px 20px;
  }

  #hero .cta-button {
    padding: 14px 30px;
    min-width: 180px;
  }
}

@media (max-width: 600px) {
  h1 {
    font-size: clamp(1.5rem, 4vw, 2rem);
  }

  h2 {
    font-size: clamp(1.2rem, 3vw, 1.5rem);
  }

  h3 {
    font-size: clamp(0.9rem, 2.5vw, 1rem);
  }

  .container {
    padding: 20px;
  }

  .logo {
    width: 40px;
  }
} 

</style>
<script>
  console.log("Global JS loaded.");

 Fade-in effect for sections using IntersectionObserver
document.addEventListener("DOMContentLoaded", function () {
  const faders = document.querySelectorAll(".fade-in");

  const appearOptions = {
    threshold: 0.2,
    rootMargin: "0px 0px -50px 0px"
  };

  const appearOnScroll = new IntersectionObserver(function (entries, observer) {
    entries.forEach((entry) => {
      if (!entry.isIntersecting) return;
      entry.target.classList.add("appear");
      observer.unobserve(entry.target);
    });
  }, appearOptions);

  faders.forEach((fader) => {
    appearOnScroll.observe(fader);
  });
});
</script>
