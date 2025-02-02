<template>
    <div class="landing-container">
      <!-- Hero Section -->
      <section class="hero">
        <div class="hero-content">
          <h1>Welcome to <span class="highlight">fbusiness</span></h1>
          <p>Your one-stop solution for business growth & success.</p>
          <NuxtLink to="/contact" class="cta-button">Get Started</NuxtLink>
        </div>
      </section>
  
      <!-- Features Section -->
      <section class="features">
        <div class="feature">
          <h2>🚀 Fast & Reliable</h2>
          <p>Our platform ensures high-speed performance and reliability.</p>
        </div>
        <div class="feature">
          <h2>💡 Smart Solutions</h2>
          <p>We provide AI-powered tools to boost your business efficiency.</p>
        </div>
        <div class="feature">
          <h2>📞 24/7 Support</h2>
          <p>Our team is available anytime to assist you.</p>
        </div>
      </section>
  
      <!-- Footer Section -->
      <footer class="footer">
        <p>© 2025 fbusiness. All Rights Reserved.</p>
      </footer>
    </div>
  </template>
  
  <style scoped>
  /* Global Styles */
  .landing-container {
    font-family: 'Poppins', sans-serif;
    text-align: center;
  }
  
  /* Hero Section */
  .hero {
    background: linear-gradient(135deg, #ff416c, #ff4b2b);
    color: white;
    padding: 100px 20px;
  }
  
  .hero-content h1 {
    font-size: 3rem;
    font-weight: bold;
    margin-bottom: 10px;
  }
  
  .hero-content .highlight {
    color: #ffd700;
  }
  
  .hero-content p {
    font-size: 1.2rem;
    margin-bottom: 20px;
  }
  
  .cta-button {
    display: inline-block;
    padding: 12px 25px;
    background: white;
    color: #ff4b2b;
    font-weight: bold;
    text-decoration: none;
    border-radius: 8px;
    transition: 0.3s;
  }
  
  .cta-button:hover {
    background: #ffd700;
    color: black;
  }
  
  /* Features Section */
  .features {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 50px auto;
    max-width: 900px;
  }
  
  .feature {
    background: #f8f8f8;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    flex: 1;
  }
  
  .feature h2 {
    color: #ff4b2b;
    font-size: 1.5rem;
  }
  
  .feature p {
    color: #555;
  }
  
  /* Footer */
  .footer {
    margin-top: 50px;
    padding: 20px;
    background: #222;
    color: white;
  }
  </style>
  