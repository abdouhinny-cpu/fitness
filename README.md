<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>[Your Name] — Certified Personal Trainer | Strength & Weight Loss</title>
  <meta name="description" content="Certified personal trainer specializing in strength training, weight loss and functional fitness. Online & in-person coaching. Book a free consultation." />
  <meta name="keywords" content="personal trainer, fitness coach, online training, weight loss, strength training, nutrition plans" />

  <!-- Open Graph -->
  <meta property="og:title" content="[Your Name] — Certified Personal Trainer" />
  <meta property="og:description" content="Transform with personalized strength training and nutrition plans. Book a free consultation." />
  <meta property="og:type" content="website" />
  <!-- Replace with your image URL -->
  <meta property="og:image" content="/assets/og-image.jpg" />

  <!-- Basic styling (mobile-first) -->
  <style>
    :root{
      --bg:#000;
      --fg:#fff;
      --muted:#e6e6e6;
      --accent:#00B4FF;
      --maxw:1100px;
      --radius:14px;
      --card-pad:18px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:var(--bg);color:var(--fg);}
    a{color:var(--accent);text-decoration:none}
    img{max-width:100%;height:auto;border-radius:8px}
    .container{width:calc(100% - 32px);max-width:var(--maxw);margin:0 auto}

    header{padding:18px 0;position:sticky;top:0;backdrop-filter: blur(6px);background:rgba(0,0,0,0.55);z-index:40}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .logo{font-weight:700;letter-spacing:0.6px}
    nav ul{display:flex;gap:14px;align-items:center;list-style:none;padding:0;margin:0}
    .btn{background:var(--accent);color:#000;padding:10px 14px;border-radius:10px;font-weight:600}

    /* Hero */
    .hero{padding:48px 0 30px}
    .hero-grid{display:grid;grid-template-columns:1fr;gap:22px;align-items:center}
    .hero h1{font-size:clamp(26px,6vw,44px);margin:0 0 8px;line-height:1.02}
    .lead{color:var(--muted);font-size:15px;margin-bottom:14px}
    .hero-cta{display:flex;gap:10px;flex-wrap:wrap}

    /* About + Services */
    section{padding:28px 0}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:var(--card-pad);border-radius:var(--radius);}
    .two-col{display:grid;grid-template-columns:1fr;gap:18px}
    .services-grid{display:grid;grid-template-columns:1fr;gap:12px}

    /* Pricing */
    .pricing{display:grid;grid-template-columns:1fr;gap:12px}
    .price-card{border-radius:12px;padding:16px;background:rgba(255,255,255,0.03)}

    /* Testimonials */
    .testis{display:grid;grid-template-columns:1fr;gap:12px}
    .testimonial{padding:14px;border-radius:12px;background:rgba(255,255,255,0.02)}

    /* Contact */
    form{display:grid;gap:10px}
    input,textarea,select{padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.06);background:transparent;color:var(--fg)}
    label{font-size:13px;color:var(--muted)}

    footer{padding:24px 0;color:var(--muted);font-size:14px}

    /* Responsive for wide screens */
    @media(min-width:800px){
      .hero-grid{grid-template-columns:1fr 420px}
      .two-col{grid-template-columns:1fr 420px}
      .services-grid{grid-template-columns:repeat(2,1fr)}
      .pricing{grid-template-columns:repeat(3,1fr)}
      .testis{grid-template-columns:repeat(2,1fr)}
    }

    /* Accessibility */
    .sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}

    /* small helper */
    .muted{color:var(--muted)}
    .center{text-align:center}
  </style>

  <!-- Schema (basic LocalBusiness) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"LocalBusiness",
    "name":"[Your Name or Brand]",
    "description":"Certified personal trainer specializing in strength training, weight loss and functional fitness.",
    "url":"https://yourdomain.com",
    "telephone":"+XX-XXXX-XXXX",
    "sameAs":["https://instagram.com/yourhandle"]
  }
  </script>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="logo">[Your Name]</div>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#pricing">Pricing</a></li>
          <li><a href="#testimonials">Testimonials</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a class="btn" href="#contact">Book a Free Consultation</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- HERO -->
    <section class="hero" id="home">
      <div class="hero-grid">
        <div>
          <h1>Become Stronger. Lose Weight. Feel Unstoppable.</h1>
          <p class="lead">I’m <strong>[Your Name]</strong>, a certified personal trainer blending evidence-based strength training with practical nutrition — online & in-person coaching.</p>
          <div class="hero-cta">
            <a class="btn" href="#contact">Book a Free Consultation</a>
            <a href="#pricing" class="muted">See Packages</a>
          </div>

          <ul style="margin-top:16px;display:flex;gap:10px;flex-wrap:wrap;list-style:none;padding:0">
            <li class="muted">Flexible scheduling</li>
            <li class="muted">Proven results</li>
            <li class="muted">Online & In-person</li>
          </ul>
        </div>

        <div class="card center">
          <!-- Replace with your hero image -->
          <img src="/assets/coach-hero.jpg" alt="[Your Name] coaching client" style="border-radius:12px;object-fit:cover;height:320px;width:100%"/>
          <p class="muted" style="margin-top:12px">15-minute free consultation · No commitment</p>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about">
      <div class="two-col" style="gap:18px">
        <div class="card">
          <h2>About [Your Name]</h2>
          <p class="muted">Certified Fitness Coach · Specialist in strength training, weight loss & functional fitness · [X+] years experience</p>
          <p>I’m [Your Name] — a certified personal trainer (e.g., NASM, ACE). I create measurable, sustainable programs that prioritize form, consistency and progressive overload. I work with beginners and athletes to achieve real results with busy schedules.</p>

          <h3>Certifications</h3>
          <ul>
            <li>[Certification 1]</li>
            <li>[Certification 2]</li>
            <li>CPR / First Aid</li>
          </ul>
        </div>

        <aside class="card">
          <img src="/assets/about-photo.jpg" alt="[Your Name] training" style="height:300px;object-fit:cover;width:100%"/>
        </aside>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services">
      <h2>Services I Offer</h2>
      <p class="muted">Custom programs built around your goals, schedule, and experience level.</p>

      <div class="services-grid" style="margin-top:12px">
        <div class="card">
          <h3>1-on-1 Personal Training</h3>
          <p>Personalized in-person sessions focused on strength, form, and measurable progress. 30–60 min sessions.</p>
          <p><a class="btn" href="#contact">Book a Free Consultation</a></p>
        </div>

        <div class="card">
          <h3>Online Coaching</h3>
          <p>Structured weekly programming, progress tracking, and video technique feedback for remote clients.</p>
          <p><a href="#contact">Get Started</a></p>
        </div>

        <div class="card">
          <h3>Group Sessions</h3>
          <p>High-energy small group training that combines coaching with community accountability.</p>
          <p><a href="#contact">Join a Class</a></p>
        </div>

        <div class="card">
          <h3>Nutrition Plans & Coaching</h3>
          <p>Sustainable meal plans with habit-based coaching for long-term results.</p>
          <p><a href="#contact">Request a Nutrition Plan</a></p>
        </div>
      </div>
    </section>

    <!-- PRICING -->
    <section id="pricing">
      <h2>Packages & Pricing</h2>
      <p class="muted">Transparent packages to match different goals and budgets. Contact for custom plans.</p>

      <div class="pricing" style="margin-top:12px">
        <div class="price-card">
          <h3>Starter — $99 / week</h3>
          <p>1 virtual check-in / week, customized workout program, basic nutrition guide.</p>
          <p><a class="btn" href="#contact">Book Starter</a></p>
        </div>

        <div class="price-card">
          <h3>Performance — $199 / week</h3>
          <p>2x sessions per week, weekly review, video form checks, detailed nutrition plan.</p>
          <p><a class="btn" href="#contact">Book Performance</a></p>
        </div>

        <div class="price-card">
          <h3>Transformation — $349 / week</h3>
          <p>3x sessions/week + unlimited messaging, advanced nutrition, monthly check-ins.</p>
          <p><a class="btn" href="#contact">Book Transformation</a></p>
        </div>
      </div>

      <p style="margin-top:12px" class="muted">Prices shown are examples — replace with your local currency or <a href="#contact">Get a Quote</a>.</p>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonials">
      <h2>Client Success Stories</h2>
      <p class="muted">Real people. Real results. Photos used with client permission.</p>

      <div class="testis" style="margin-top:12px">
        <div class="testimonial">
          <blockquote>“In three months I dropped two dress sizes and finally enjoy the gym. The workouts are challenging but doable — best investment I’ve made.”</blockquote>
          <p class="muted">— Maria G., Lost 20 lbs</p>
        </div>

        <div class="testimonial">
          <blockquote>“I gained strength and confidence. The weekly check-ins kept me on track.”</blockquote>
          <p class="muted">— Adam S., +30% strength gains</p>
        </div>
      </div>

      <div style="margin-top:12px" class="card">
        <h3>Before / After Gallery</h3>
        <div style="display:grid;grid-template-columns:repeat(2,1fr);gap:8px;margin-top:8px">
          <img src="/assets/before1.jpg" alt="Before client 1" />
          <img src="/assets/after1.jpg" alt="After client 1" />
        </div>
      </div>
    </section>

    <!-- HOW IT WORKS -->
    <section id="how">
      <h2>How It Works</h2>
      <ol class="muted">
        <li>Book a Free Consultation — 15-minute call to set goals.</li>
        <li>Get a Tailored Plan — personalized workouts & nutrition.</li>
        <li>Progress & Adjust — weekly check-ins and updates.</li>
      </ol>
    </section>

    <!-- CONTACT & CALENDLY -->
    <section id="contact">
      <h2>Ready to Start?</h2>
      <div class="two-col">
        <div class="card">
          <form onsubmit="handleForm(event)">
            <label for="name">Name</label>
            <input id="name" name="name" required />

            <label for="email">Email</label>
            <input id="email" name="email" type="email" required />

            <label for="phone">Phone (optional)</label>
            <input id="phone" name="phone" />

            <label for="goal">Goal</label>
            <select id="goal" name="goal">
              <option>Weight loss</option>
              <option>Strength</option>
              <option>General fitness</option>
              <option>Custom</option>
            </select>

            <label for="msg">Message</label>
            <textarea id="msg" name="message" rows="4"></textarea>

            <button class="btn" type="submit">Send & Book</button>
            <p class="muted" style="margin-top:8px">Or book instantly using the scheduler on the right.</p>
          </form>
        </div>

        <aside class="card">
          <h3 class="center">Book a 15-min Free Consultation</h3>
          <p class="muted center">Instant scheduling via Calendly — replace the URL below with your Calendly link.</p>

          <!-- Calendly widget: paste your Calendly URL in data-url -->
          <div id="calendly-wrap" style="min-height:420px">
            <iframe src="https://calendly.com/yourname/15min?embed_domain=example.com&embed_type=Inline" width="100%" height="420" frameborder="0"></iframe>
          </div>
        </aside>
      </div>
    </section>

    <!-- SOCIAL -->
    <section>
      <h2>Follow the journey</h2>
      <p class="muted">Daily workouts, client wins, recipes, and behind-the-scenes.</p>
      <div style="display:flex;gap:10px;margin-top:8px">
        <a href="https://instagram.com/yourhandle" target="_blank" rel="noopener">Instagram</a>
        <a href="https://facebook.com/yourhandle" target="_blank" rel="noopener">Facebook</a>
        <a href="https://youtube.com/yourhandle" target="_blank" rel="noopener">YouTube</a>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© <span id="year"></span> [Your Name]. All rights reserved.</div>
        <div class="muted">Contact: <a href="mailto:hello@yourdomain.com">hello@yourdomain.com</a> · +XX-XXXX-XXXX</div>
      </div>
    </div>
  </footer>

  <script>
    // tiny client-side form handler: opens mailto (replace with Formspree or server if you want full backend)
    function handleForm(e){
      e.preventDefault();
      const name = document.getElementById('name').value;
      const email = document.getElementById('email').value;
      const phone = document.getElementById('phone').value;
      const goal = document.getElementById('goal').value;
      const msg = document.getElementById('msg').value;

      // Construct email content
      const subject = encodeURIComponent('New website inquiry from '+name);
      const body = encodeURIComponent('Name: '+name+'\nEmail: '+email+'\nPhone: '+phone+'\nGoal: '+goal+'\nMessage: '+msg);
      // fallback: open mail client
      window.location.href = 'mailto:hello@yourdomain.com?subject='+subject+'&body='+body;
    }

    // set current year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
