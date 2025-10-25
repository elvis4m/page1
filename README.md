# page1<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Elevate Web Solutions</title>
  <meta name="description" content="Elevate Web Solutions builds stunning, responsive, and high-performing websites for schools, businesses, and online stores.">
  <link rel="stylesheet" href="style.css" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* Hero paragraph styling */
    .hero-highlight {
      color: #ff6f61; /* Initial color */
      transition: color 1.5s ease, transform 1s ease;
      font-size: 1.3rem; /* Larger text */
      line-height: 1.6; /* Better spacing */
    }

    .hero-highlight:hover {
      color: #ffa500; /* Hover color */
      transform: scale(1.05); /* Slight zoom on hover */
    }

    /* Automatic color fade animation */
    .hero-animate {
      animation: colorFade 5s infinite alternate;
    }

    @keyframes colorFade {
      0% { color: #ff6f61; }
      50% { color: #ff9f80; }
      100% { color: #ffa500; }
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="#hero">Elevate Web Solutions</a>
      <nav class="nav">
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact" class="btn-outline">Hire Me</a>
      </nav>
      <button class="nav-toggle" aria-label="Toggle navigation">&#9776;</button>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section id="hero" class="hero">
      <div class="container hero-grid">
        <div class="hero-content">
          <p class="hero-highlight hero-animate">
            My web design services combine creative design with smart strategy. I build responsive, SEO-friendly websites that are optimized for performance and user experience helping your brand stand out, attract visitors, and convert them into loyal customers.
          </p>
          <div class="hero-ctas">
            <br>
            <br><a href="#portfolio" class="btn-ghost">See Our Work</a>
          </div>
        </div>
        <div class="hero-media">
          <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=1200&q=80" alt="Elvis Web Designs team workspace" />
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section">
      <div class="container split">
        <div>
          <h2>About Me</h2>
          <p>Hi, I’m Elvis Asamoah, a passionate web designer and developer dedicated to creating professional, high-performing websites that help schools, brands, and entrepreneurs succeed online.
           I’ve always believed that a great website is more than just design — it’s an experience. Every project I take on starts with understanding your goals, your audience, and the message you want to share. From there, I blend creativity, strategy, and technical skill to craft a digital presence that truly represents who you are.
           Over the years, I’ve worked on a wide range of projects — from simple landing pages and portfolio sites to full-scale e-commerce stores. No matter the size or complexity, my focus remains the same: delivering clean, responsive, and results-driven websites that perform beautifully across all devices.
           <br>Here’s what you can always expect when working with me:
        </p>

          <ul>
            <li>✔ Fast and responsive designs</li>
            <li>✔ SEO and performance optimized</li>
            <li>✔ Professional maintenance & support</li>
          </ul>
          <a href="#contact" class="btn-primary">Book a Consultation</a>
        </div>
        <div>
          <div class="card-stats">
            <div><h3>50+</h3><p>Websites Delivered</p></div>
            <div><h3>100%</h3><p>Client Satisfaction</p></div>
            <div><h3>24/7</h3><p>Customer Support</p></div>
          </div>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" class="section alt">
      <div class="container">
        <h2>My Services</h2>
        <div class="services-grid">
          <article class="service-card">
            <h3>Web Design & Development</h3>
            <p>I create professional, custom-built websites tailored to your business, school, or startup. Every site I design combines modern aesthetics with functional, user-friendly layouts that engage visitors and effectively communicate your brand. My web development process ensures responsive designs that work seamlessly across all devices, from desktops to smartphones. Beyond just appearances, I focus on performance, fast loading speeds, and SEO optimization to help your website rank higher in search engines. Whether you’re launching your first site or redesigning an existing one, I craft digital experiences that not only impress visually but also drive measurable results, attract more visitors, and convert them into loyal customers.</p>
          </article>
          <article class="service-card">
            <h3>UI / UX Design</h3>
            <p>I design user interfaces that are not only visually stunning but also highly intuitive and easy to use. Every element, from buttons and menus to forms and navigation, is carefully crafted to provide a seamless experience for your visitors. I focus on understanding your audience, their behavior, and their needs, so every interaction feels natural and effortless. By combining aesthetic appeal with strategic usability, I create interfaces that guide users smoothly through your website, reduce friction, and increase engagement. The result is a digital experience that not only looks professional and modern but also drives conversions, boosts customer satisfaction, and strengthens your brand’s online presence.</p>
          </article>
          <article class="service-card">
            <h3>E-commerce Solutions</h3>
            <p>I build custom online stores designed to increase sales and enhance the shopping experience. My e-commerce solutions include everything from product listings and shopping carts to secure payment gateways and inventory management. I focus on creating a seamless user experience that encourages visitors to explore your products and make purchases. With a strong emphasis on performance and security, I ensure that your online store is not only visually appealing but also fast, reliable, and easy to navigate. Whether you’re starting a new online business or looking to improve an existing store, I provide the expertise and support you need to succeed in the competitive e-commerce landscape.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- PORTFOLIO -->
    <section id="portfolio" class="section">
      <div class="container">
        <h2>My Portfolio</h2>
        <p class="sub">A few examples of my recent work</p>
        <div class="portfolio-grid">
          <figure class="project">
            <img src="https://images.unsplash.com/photo-1596495577886-d920f1fb7238?w=1200&q=80" alt="School Website">
            <figcaption><h4>School Website</h4><p>I design modern, easy-to-navigate websites specifically for schools, educational institutions, and learning centers. Every site I create is built to provide a seamless experience for students, parents, and staff, making important information easy to find and access. Features can include online enrollment and registration forms, event calendars, news updates, class schedules, and interactive resources to enhance the learning experience. I focus on creating a visually appealing design that reflects the school’s identity while ensuring the website is fully responsive, fast-loading, and accessible across all devices. My goal is to deliver a website that not only looks professional but also streamlines administrative processes, improves communication, and engages the school community effectively.</p></figcaption>
          </figure>
          <figure class="project">
            <img src="https://images.unsplash.com/photo-1556761175-4b46a572b786?w=1200&q=80" alt="Business Website">
            <figcaption><h4>Business Website</h4><p>I create professional websites for new startups to build credibility and attract customers. My approach involves understanding the unique value proposition of each business and translating it into a compelling online presence. This includes everything from branding and design to content strategy and SEO optimization. I ensure that every website I build is not only visually appealing but also optimized for search engines, helping businesses reach their target audience effectively. With a focus on user experience and conversion optimization, I help startups establish a strong foundation for their online success.</p></figcaption>
          </figure>
          <figure class="project">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=1200&q=80" alt="Hotel Website">
            <figcaption><h4>Hotel Booking Website</h4><p>I design elegant and fully functional hotel booking websites that provide a seamless experience for guests and property managers alike. Every site I create features intuitive navigation, visually appealing layouts, and responsive design to ensure it looks great on desktops, tablets, and mobile devices. Key features can include real-time calendar integration, instant booking confirmations, secure payment processing, room availability management, and promotional offers. I focus on creating a website that not only showcases your property beautifully but also simplifies the booking process, improves customer experience, and increases reservations. My goal is to deliver a website that elevates your brand, engages visitors, and drives measurable results for your hospitality business.</p></figcaption>
          </figure>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section alt">
      <div class="container split">
        <div>
          <h2>Let's Build Your Dream Website</h2>
          <p>Ready to start your next project? Fill out the form and we’ll get back to you within 24 hours.</p>
          <form id="contact-form" method="POST" action="https://formspree.io/f/xwpwewpl">
            <label for="name">Name</label>
            <input id="name" name="name" required>
            <label for="email">Email</label>
            <input id="email" name="email" type="email" required>
            <label for="country">Country</label>
            <input id="country" name="country" required>
            <label for="number">Phone Number</label>
            <input id="number" name="number" required>
            <label for="message">Project Details</label>
            <textarea id="message" name="message" rows="5" placeholder="Tell us about your website idea..." required></textarea>
            <label for="captcha">What is 3 + 4? (Anti-robot)</label>
            <input id="captcha" name="captcha" required>
            <button type="submit" class="btn-primary">Send Message</button>
            <div id="form-response"></div>
          </form>
        </div>
        <aside>
          <div class="contact-card">
            <h3>Contact Info</h3>
            <ul>
              <li>📧 <a href="mailto:asamoahelvis550@gmail.com">asamoahelvis550@gmail.com</a></li>
              <li>📍 Canada (Remote)</li>
              <li>📞 825-365-6707</li>
            </ul>
          </div>
        </aside>
      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="site-footer">
    <div class="container footer-inner">
      <p>© <span id="year"></span> Elevate Web Solutions — All Rights Reserved</p>
    </div>
  </footer>
</body>
</html>

new file
