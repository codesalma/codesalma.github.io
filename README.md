!DOCTYPE html>
<html lang="en">
<head>
    <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Salma Adhikari — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --muted:#94a3b8;
      --accent:#06b6d4; /* teal-ish */
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;padding:0;
      font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background:linear-gradient(180deg,#041025 0%, #071528 60%);
      color:#e6eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
    }
    .container{max-width:1100px;margin:36px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:800;color:#041025}
    nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-weight:600}
    nav a:hover{color:var(--accent)}

    .hero{display:grid;grid-template-columns:1fr 400px;gap:28px;margin-top:28px;align-items:center}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:var(--radius);padding:28px;box-shadow:0 8px 30px rgba(2,6,23,0.6);}
    .title{font-size:28px;font-weight:700;margin:0}
    .subtitle{color:var(--muted);margin-top:6px}

    .about p{color:var(--muted);margin:12px 0}
    .info-grid{display:flex;gap:12px;flex-wrap:wrap;margin-top:12px}
    .pill{background:var(--glass);padding:8px 12px;border-radius:999px;color:var(--muted);font-weight:600}

    .right-card{padding:20px;text-align:center}
    .avatar{width:120px;height:120px;border-radius:16px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:inline-flex;align-items:center;justify-content:center;font-size:36px;font-weight:800;color:#041025}
    .socials{margin-top:14px}
    .socials a{margin:0 8px;color:var(--muted);text-decoration:none}
    .socials a:hover{color:var(--accent)}

    .sections{margin-top:26px;display:grid;grid-template-columns:1fr 340px;gap:24px}
    .projects .project{display:flex;gap:12px;align-items:flex-start;padding:14px;border-radius:12px;background:rgba(255,255,255,0.02);margin-bottom:12px}
    .project .dot{width:10px;height:10px;border-radius:3px;background:var(--accent);margin-top:6px}
    .project h4{margin:0;font-size:16px}
    .project p{margin:6px 0;color:var(--muted);font-size:14px}

    .tiktok-embed{border-radius:12px;overflow:hidden;padding:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02))}
    .contact-form label{display:block;margin-bottom:6px;font-weight:600}
    .contact-form input,.contact-form textarea{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit;resize:vertical}
    .row{display:flex;gap:12px}
    .row .col{flex:1}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:10px 16px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#7c3aed);color:#041025;border:none;font-weight:700;cursor:pointer}
    .muted{color:var(--muted);font-size:13px}

    footer{text-align:center;margin:40px 0;color:var(--muted)}

    /* Responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      .sections{grid-template-columns:1fr}
      nav a{display:none}
    }

    /* form error styles */
    .error{border-color:#ff6b6b!important}
    .error-msg{color:#ffb4b4;font-size:13px;margin-top:6px}

    /* subtle animation */
    .float{animation:floaty 6s ease-in-out infinite}
    @keyframes floaty{0%{transform:translateY(0)}50%{transform:translateY(-8px)}100%{transform:translateY(0)}}

  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">SA</div>
        <div>
          <div style="font-weight:800">salma Adhikari</div>
          <div style="font-size:13px;color:var(--muted)">Student · Computer Science · Content creator (TikTok)</div>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#tiktok">TikTok</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div class=" card-right card">
        <img src="images/Myphoto.jpg"
            alt="Salma Adhikari"
            style="width:100%;border-radius:var(--radius);object-fit:cover;max-height:300px;box-shadow:0 4px 20px rgba(0,0,0,0.3);"

        <h1 class="title">Hi — I'm <span style="background:linear-gradient(90deg,var(--accent),#7c3aed);-webkit-background-clip:text;background-clip:text;color:transparent;">Salma Adhikari</span></h1>
        <div class="subtitle">Computer Science student passionate about coding, problem solving, and creating fun short-form content on TikTok.</div>

        <div class="about" id="about">
          <p class="muted">I study Computer Science and enjoy building web projects, small tools, and short-form video content. I love experimenting with UI, storytelling, and editing on mobile for TikTok.</p>

          <div class="info-grid">
            <div class="pill"><i class="fas fa-map-marker-alt me-2"></i> Bharatpur -9, Chitwan</div>
            <div class="pill"><i class="fas fa-phone me-2"></i> <span id="phone">9845211377</span></div>
            <div class="pill"><i class="fas fa-envelope me-2"></i> <a href="mailto:salmadhkr@gmail.com" style="color:var(--accent);text-decoration:none">salmadhkr@gmail.com</a></div>
          </div>

          <div style="margin-top:18px">
            <strong>Family</strong>
            <p class="muted" style="margin:6px 0">Mother: Sita Adhikari · Father: Shiva Adhikari</p>
          </div>

          <div style="margin-top:8px">
            <strong>Interests</strong>
            <p class="muted" style="margin:6px 0">Web development, algorithms, mobile video creation, storytelling for social media.</p>
          </div>
        </div>

        <div style="margin-top:18px;display:flex;gap:10px;align-items:center">
          <a class="btn" href="#contact"><i class="fas fa-paper-plane"></i> Get in touch</a>
          <a class="btn" href="#projects" style="background:transparent;color:var(--accent);border:1px solid rgba(255,255,255,0.06)"><i class="fas fa-folder-open"></i> View projects</a>
        </div>

      </div>

      <aside class="card right-card float">
        <div class="avatar">SA</div>
        <h3 style="margin-top:12px;margin-bottom:6px">Salma Adhikari</h3>
        <div class="muted">Student of Computer Science</div>

        <div class="socials" style="margin-top:14px">
          <a href="https://facebook.com/" target="_blank" aria-label="Facebook"><i class="fab fa-facebook fa-lg"></i></a>
          <a href="https://instagram.com/" target="_blank" aria-label="Instagram"><i class="fab fa-instagram fa-lg"></i></a>
          <a href="https://tiktok.com/" target="_blank" aria-label="Tiktok"><i class="fab fa-tiktok fa-lg"></i></a>
        </div>

        <div style="margin-top:16px" class="muted">Click phone to copy</div>
      </aside>
    </section>

    <section class="sections">
      <main>
        <div class="card projects" id="projects">
          <h3 style="margin-top:0">Selected Projects</h3>
          <div class="project">
            <div class="dot"></div>
            <div>
              <h4>Portfolio Website</h4>
              <p class="muted">A modern responsive portfolio (this site). Built with HTML, CSS and small JS for interactivity.</p>
            </div>
          </div>

          <div class="project">
            <div class="dot"></div>
            <div>
              <h4>TikTok Content Series</h4>
              <p class="muted">Short-form video series about coding tips and day-in-life of a CS student.</p>
            </div>
          </div>

          <div class="project">
            <div class="dot"></div>
            <div>
              <h4>Mini Web Tools</h4>
              <p class="muted">Small utilities like a study timer, note-taker and simple quiz app.</p>
            </div>
          </div>

        </div>

        <div class="card tiktok-embed" id="tiktok">
          <h3 style="margin-top:0">TikTok</h3>
          <p class="muted">I create short, engaging clips about coding, life at university, and quick editing tips.</p>

          <!-- NOTE: Replace `your_tiktok_username` with your actual username to embed real posts -->
          <div style="margin-top:12px;display:flex;gap:12px;flex-wrap:wrap">
            <div style="flex:1;min-width:220px">
              <a href="https://www.tiktok.com/@your_tiktok_username" target="_blank" style="color:var(--accent);text-decoration:none">@your_tiktok_username</a>
              <p class="muted" style="margin-top:6px">Click to view on TikTok</p>
            </div>
            <div style="min-width:220px;flex:1">
              <!-- example embed placeholder -->
              <div style="border-radius:8px;padding:12px;background:rgba(255,255,255,0.02);text-align:center;">
                <div style="font-weight:700">Sample clip</div>
                <div class="muted" style="margin-top:8px">Replace with an embedded TikTok or screenshot of your most popular video.</div>
              </div>
            </div>
          </div>
        </div>

      </main>

      <aside>
        <div class="card contact-form" id="contact">
          <h3 style="margin-top:0">Contact Me</h3>
          <p class="muted">Have a question, collaboration idea, or want me to create a TikTok for your product? Send a message!</p>

          <form id="contactForm" novalidate>
            <div class="row">
              <div class="col">
                <label for="name">Your name</label>
                <input id="name" name="name" type="text" placeholder="Salma" required minlength="2" />
                <div class="error-msg" id="err-name" style="display:none"></div>
              </div>
              <div class="col">
                <label for="phoneInput">Phone</label>
                <input id="phoneInput" name="phone" type="tel" placeholder="9845xxxxxx" pattern="^[9][78][0-9]{8}$" />
                <div class="error-msg" id="err-phone" style="display:none"></div>
              </div>
            </div>

            <div style="margin-top:10px">
              <label for="email">Email</label>
              <input id="email" name="email" type="email" placeholder="you@example.com" required />
              <div class="error-msg" id="err-email" style="display:none"></div>
            </div>

            <div style="margin-top:10px">
              <label for="message">Message</label>
              <textarea id="message" name="message" rows="5" placeholder="Hi Salma, I want to collaborate..." required minlength="10"></textarea>
              <div class="error-msg" id="err-message" style="display:none"></div>
            </div>

            <div style="margin-top:12px;display:flex;gap:10px;align-items:center">
              <button type="submit" class="btn"><i class="fas fa-paper-plane"></i> Send message</button>
              <div class="muted" id="formStatus">We’ll email you back — usually within a few days.</div>
            </div>
          </form>

          <hr style="border:none;border-top:1px solid rgba(255,255,255,0.03);margin:14px 0">
          <div class="muted" style="font-size:13px">Or email: <a href="mailto:salmadhkr@gmail.com" style="color:var(--accent);text-decoration:none">salmadhkr@gmail.com</a></div>
        </div>

        <div style="height:18px"></div>

        <div class="card" style="padding:16px">
          <h4 style="margin:0">Quick info</h4>
          <p class="muted" style="margin-top:8px">Mother: Sita Adhikari<br>Father: Shiva Adhikari</p>
        </div>
      </aside>
    </section>

    <footer>
      <div class="muted">© <span id="year"></span> Salma Adhikari — Built with ❤️</div>
    </footer>

  </div>

  <script>
    // fill year
    document.getElementById('year').textContent = new Date().getFullYear();

    // click phone to copy
    document.getElementById('phone').addEventListener('click', function(){
      navigator.clipboard.writeText(this.textContent).then(()=>{
        alert('Phone number copied to clipboard');
      }).catch(()=>{});
    });

    // Simple form validation + submit (no real backend):
    const form = document.getElementById('contactForm');
    const status = document.getElementById('formStatus');

    function showErr(id,msg){
      const el = document.getElementById(id);
      el.style.display = 'block';
      el.textContent = msg;
    }
    function hideErr(id){
      const el = document.getElementById(id);
      el.style.display = 'none';
      el.textContent = '';
    }

    form.addEventListener('submit', async function(e){
      e.preventDefault();

      // reset
      ['err-name','err-email','err-message','err-phone'].forEach(hideErr);
      ['name','email','message','phoneInput'].forEach(id=>document.getElementById(id).classList.remove('error'));

      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const phone = document.getElementById('phoneInput').value.trim();
      const message = document.getElementById('message').value.trim();

      let hasError = false;
      if(name.length < 2){ showErr('err-name','Please enter your name (2+ characters)'); document.getElementById('name').classList.add('error'); hasError = true; }
      // basic email check
      if(!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)){ showErr('err-email','Please enter a valid email'); document.getElementById('email').classList.add('error'); hasError = true; }
      if(message.length < 10){ showErr('err-message','Message should be at least 10 characters'); document.getElementById('message').classList.add('error'); hasError = true; }
      // optional phone validation for Nepali numbers (starts with 98/97 then 8 more digits)
      if(phone && !/^[9][78][0-9]{8}$/.test(phone)){ showErr('err-phone','If provided, enter a valid Nepali mobile number like 98xxxxxxxx'); document.getElementById('phoneInput').classList.add('error'); hasError = true; }

      if(hasError) return;

      // show sending
      status.textContent = 'Sending...';

      // Example: send to a server endpoint.
      // Replace `YOUR_ENDPOINT_URL` with your server or a form endpoint (e.g. Formspree, Netlify Forms)
      const endpoint = 'YOUR_ENDPOINT_URL';
      const payload = {name,email,phone,message,source:'portfolio-site'};

      try{
        if(endpoint === 'YOUR_ENDPOINT_URL'){
          // No backend configured — simulate success and provide mailto fallback
          status.textContent = 'No backend configured. Opening your email app as a fallback.';

          const mailto = `mailto:salmadhkr@gmail.com?subject=${encodeURIComponent('Message from portfolio: '+name)}&body=${encodeURIComponent('Name: '+name+'\nEmail: '+email+'\nPhone: '+phone+'\n\nMessage:\n'+message)}`;
          window.location.href = mailto;
          setTimeout(()=>{ status.textContent = 'Draft opened in your email app. Thank you!'; },1000);

        } else {
          const res = await fetch(endpoint,{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify(payload)});
          if(res.ok){ status.textContent = 'Message sent — thanks!'; form.reset(); } else { throw new Error('network'); }
        }
      }catch(err){
        status.textContent = 'Could not send message. You can email: salmadhkr@gmail.com';
      }

    });
  </script>
</body>
</html>

-
