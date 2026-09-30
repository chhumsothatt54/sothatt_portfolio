<script setup>
</script>

<template>
  <header id="header" class="fixed-top">
    <nav class="navbar navbar-expand-lg navbar-dark"
      style="background: linear-gradient(90deg, #040b14 0%, #0a192f 100%); box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
      <div class="container">
        <a class="navbar-brand fw-bold" href="#"
          style="font-family: 'Outfit', sans-serif; font-size: 24px; color: #fff;">Chhum Sothatt</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto align-items-lg-center">
            <li class="nav-item"><a href="#hero" class="nav-link scrollto active">Home</a></li>
            <li class="nav-item"><a href="#about" class="nav-link scrollto">About</a></li>
            <li class="nav-item"><a href="#skills" class="nav-link scrollto">Skills</a></li>
            <li class="nav-item"><a href="#resume" class="nav-link scrollto">Resume</a></li>
            <li class="nav-item"><a href="#portfolio" class="nav-link scrollto">Projects</a></li>
            <!-- <li class="nav-item"><a href="#services" class="nav-link scrollto">Reference</a></li> -->
          </ul>

        </div>
      </div>
    </nav>
  </header>
  
  <section id="hero" class="d-flex align-items-center" style="min-height: 100vh;">
    <div class="container hero-container position-relative z-2">
      <div class="row align-items-center justify-content-between">
        <div class="col-lg-6 order-2 order-lg-1 d-flex flex-column justify-content-center text-center text-lg-start">
          <h1>Chhum Sothatt</h1>
          <p>I'm <span>Information Technology Student</span></p>
          <div class="social-links ms-lg-4 mt-3 mt-lg-0 d-flex gap-2">
            <a href="https://t.me/csothatt" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="Telegram"><i class="bi bi-telegram fs-2"></i></a>
            <a href="https://www.facebook.com/share/1EpBWRbDwH/?mibextid=wwXIfr" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="Facebook"><i class="bi bi-facebook fs-2"></i></a>
            <a href="https://github.com/chhumsothatt54" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="GitHub"><i class="bi bi-github fs-2"></i></a>
            <a href="https://vercel.com/chhumsothatt" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="Vercel"><i class="bi bi-caret-up-fill fs-2"></i></a>
          </div>
          <div class="mt-4">
            <a href="#about" class="btn btn-outline-light rounded-pill px-4 py-2 me-3">About Me</a>
            <a href="#portfolio" class="btn btn-primary rounded-pill px-4 py-2" style="background-color: var(--accent-teal); border: none;">Github Me</a>
          </div>
        </div>
        <div class="col-lg-5 order-1 order-lg-2 text-center mb-4 mb-lg-0">
          <img src="../assets/image/me-removebg-preview.png" class="img-fluid rounded-3 shadow-lg border border-4 hero-img" style="border-color: rgba(20, 184, 166, 0.5) !important;" alt="Chhum Sothatt">
        </div>
      </div>
    </div>
  </section>

  <main id="main">
    <!-- About Section -->
    <section id="about" class="about" style="background-color: #f8fafc; padding: 100px 0;">
      <div class="container">
        <div class="section-title text-center mb-5 pb-3">
          <h2 class="d-inline-block position-relative pb-2" style="font-weight: 800; font-size: 40px; color: #0f172a;">
            About Me
            <span style="position: absolute; width: 60%; height: 4px; background: var(--accent-teal); bottom: 0; left: 20%; border-radius: 2px;"></span>
          </h2>
          <p class="text-muted mt-3 px-lg-5 mx-lg-5" style="font-size: 1.1rem; line-height: 1.8;">
            Seeking an internship opportunity to apply and further develop my web development skills. Hands-on
            experience building web applications using Laravel, PHP, Node.js, Express.js, Vue.js, and MySQL. Familiar
            with RESTful APIs, database design, CRUD operations, authentication, and frontend-backend integration.
          </p>
        </div>

        <div class="row align-items-center g-5">
          <div class="col-lg-5 position-relative text-center">
            <div class="position-absolute top-50 start-50 translate-middle w-100 h-100" style="background: linear-gradient(45deg, rgba(20,184,166,0.15), rgba(20,184,166,0.05)); border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%; z-index: 0; filter: blur(20px);"></div>
            <img src="../assets/image/me-removebg-preview.png" class="img-fluid rounded-4 position-relative z-1" alt="Chhum Sothatt"
              style="box-shadow: -15px 15px 0px rgba(20,184,166,0.2); max-width: 80%;">
          </div>
          <div class="col-lg-7 content ps-lg-5">
            <h3 class="fw-bold mb-3" style="color: #0f172a; font-size: 32px;">Aspiring Web Developer & IT Student</h3>
            <p class="fst-italic text-muted mb-4 fs-5">
              Passionate about building highly performant and beautiful web applications that provide a seamless user experience.
            </p>
            
            <div class="glass-card p-4 mb-4 border-0 shadow-sm bg-white rounded-4" style="transition: transform 0.3s ease;">
              <div class="row g-4">
                <div class="col-md-6">
                  <div class="d-flex align-items-center p-2 rounded-3 hover-effect">
                    <div class="icon-box-small me-3 d-flex align-items-center justify-content-center rounded-circle" style="width: 50px; height: 50px; background: rgba(20,184,166,0.1);">
                      <i class="bi bi-telephone-fill text-teal" style="font-size: 22px;"></i>
                    </div>
                    <div>
                      <span class="d-block text-muted small fw-semibold text-uppercase tracking-wider">Phone</span>
                      <span class="text-dark fw-bold fs-6">069 871 704 / 071 822 3195</span>
                    </div>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="d-flex align-items-center p-2 rounded-3 hover-effect">
                    <div class="icon-box-small me-3 d-flex align-items-center justify-content-center rounded-circle" style="width: 50px; height: 50px; background: rgba(20,184,166,0.1);">
                      <i class="bi bi-geo-alt-fill text-teal" style="font-size: 22px;"></i>
                    </div>
                    <div>
                      <span class="d-block text-muted small fw-semibold text-uppercase tracking-wider">Location</span>
                      <span class="text-dark fw-bold fs-6">Russey Keo, Phnom Penh</span>
                    </div>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="d-flex align-items-center p-2 rounded-3 hover-effect">
                    <div class="icon-box-small me-3 d-flex align-items-center justify-content-center rounded-circle" style="width: 50px; height: 50px; background: rgba(20,184,166,0.1);">
                      <i class="bi bi-envelope-fill text-teal" style="font-size: 22px;"></i>
                    </div>
                    <div>
                      <span class="d-block text-muted small fw-semibold text-uppercase tracking-wider">Email</span>
                      <a href="mailto:chhumsothatt54@gmail.com" class="text-dark fw-bold fs-6 text-decoration-none">chhumsothatt54@gmail.com</a>
                    </div>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="d-flex align-items-center p-2 rounded-3 hover-effect">
                    <div class="icon-box-small me-3 d-flex align-items-center justify-content-center rounded-circle" style="width: 50px; height: 50px; background: rgba(20,184,166,0.1);">
                      <i class="bi bi-laptop text-teal" style="font-size: 22px;"></i>
                    </div>
                    <div>
                      <span class="d-block text-muted small fw-semibold text-uppercase tracking-wider">Freelance</span>
                      <span class="text-dark fw-bold fs-6">Available</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills section-bg" style="background-color: #f5f8fd; padding: 100px 0;">
      <div class="container">
        <div class="section-title text-center mb-5 pb-3">
          <h2 class="d-inline-block position-relative pb-2" style="font-weight: 800; font-size: 40px; color: #0f172a;">
            Skills
            <span style="position: absolute; width: 60%; height: 4px; background: var(--accent-teal); bottom: 0; left: 20%; border-radius: 2px;"></span>
          </h2>
          <p class="text-muted mt-3" style="font-size: 1.1rem;">Here are some of the technologies I have worked with recently.</p>
        </div>

        <div class="skills-content">
          <!-- Backend -->
          <h4 class="mb-4 fw-bold text-center" style="color: #173b6c;">Backend</h4>
          <div class="row g-4 mb-5 justify-content-center">
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/php.jpg" alt="PHP"
                  class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">PHP</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/laravel.jpg"
                  alt="Laravel" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Laravel</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/node.jpg"
                  alt="Node.js" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Node.js</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/express.jpg"
                  alt="Express.js" class="img-fluid mb-3" style="height: 50px; mix-blend-mode: darken;">
                <h6 class="mb-0 fw-bold text-dark">Express.js</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/rest.jpg"
                  alt="REST APIs" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">REST APIs</h6>
              </div>
            </div>
          </div>

          <!-- Frontend -->
          <h4 class="mb-4 fw-bold text-center" style="color: #173b6c;">Frontend</h4>
          <div class="row g-4 mb-5 justify-content-center">
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/html.jpg" alt="HTML"
                  class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">HTML</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/css.jpg" alt="CSS"
                  class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">CSS</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg"
                  alt="Bootstrap 5" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Bootstrap 5</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/js.jpg"
                  alt="JavaScript" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">JavaScript</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/vue.jpg"
                  alt="Vue.js" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Vue.js</h6>
              </div>
            </div>
          </div>

          <!-- Database -->
          <h4 class="mb-4 fw-bold text-center" style="color: #173b6c;">Database</h4>
          <div class="row g-4 mb-5 justify-content-center">
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/mysql.jpg"
                  alt="MySQL" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">MySQL</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/postgresql.jpg"
                  alt="PostgreSQL" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">PostgreSQL</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/sql.jpg"
                  alt="SQL" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">SQL</h6>
              </div>
            </div>
          </div>

          <!-- Tools -->
          <h4 class="mb-4 fw-bold text-center" style="color: #173b6c;">Tools</h4>
          <div class="row g-4 justify-content-center">
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/github.jpg"
                  alt="GitHub" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">GitHub</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/vercel.jpg"
                  alt="Vercel" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Vercel</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/postman.jpg"
                  alt="Postman" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Postman</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/vs.jpg"
                  alt="VS Code" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">VS Code</h6>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-2">
              <div class="skill-card text-center p-4">
                <img src="../assets/image/drawio.jpg"
                  alt="Draw.io" class="img-fluid mb-3" style="height: 50px;">
                <h6 class="mb-0 fw-bold text-dark">Draw.io</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="resume">
      <div class="container">
        <div class="section-title">
          <h2>Resume</h2>
          <p>A summary of my education and project experience.</p>
        </div>

        <div class="row">
          <div class="col-lg-6">
            <h3 class="resume-title">Education</h3>
            <div class="resume-item">
              <div class="d-flex align-items-center mb-2">
                <img src="../assets/image/ntti.jpg" alt="NTTI" class="rounded me-3 shadow-sm" style="width: 50px; height: 50px; object-fit: contain; background: #fff; padding: 2px;">
                <h4 class="mb-0" style="margin-bottom: 0 !important;">Information Technology</h4>
              </div>
              <h5>2023 - 2026 (Year 4)</h5>
              <p><em>National Technical Training Institute (NTTI)</em></p>
              <p>Studying Information Technology with a focus on web development and software engineering principles.</p>
            </div>
            <div class="resume-item">
              <div class="d-flex align-items-center mb-2">
                <img src="../assets/image/ant.jpg" alt="ANT" class="rounded me-3 shadow-sm" style="width: 50px; height: 50px; object-fit: contain; background: #fff; padding: 2px;">
                <h4 class="mb-0" style="margin-bottom: 0 !important;">100% Scholarship Program — MPTC & CBRD Fund</h4>
              </div>
              <h5>2025 - 2026</h5>
              <p><em>ANT TECHNOLOGY TRAINING CENTER</em></p>
              <p>Awarded a full scholarship to advance skills in software development and technology.</p>
            </div>
            <div class="resume-item">
              <div class="d-flex align-items-center mb-2">
                <img src="../assets/image/etec-center.jpg" alt="ETEC" class="rounded me-3 shadow-sm" style="width: 50px; height: 50px; object-fit: contain; background: #fff; padding: 2px;">
                <h4 class="mb-0" style="margin-bottom: 0 !important;">100% Scholarship Program</h4>
              </div>
              <h5>2026</h5>
              <p><em>ETEC CENTER</em></p>
              <p>Awarded a full scholarship for specialized technology training.</p>
            </div>
          </div>
          <div class="col-lg-6">
            <h3 class="resume-title">Project Experience</h3>
            <div class="resume-item">
              <h4>Hotel Booking Management System</h4>
              <h5>2026</h5>
              <p><em>Laravel, Vue.js, PostgreSQL</em></p>
              <ul>
                <li>Built RESTful APIs using Laravel for users, hotels, rooms, bookings, payments, and reviews.</li>
                <li>Developed responsive frontend interfaces using Vue.js 3 and Composition API.</li>
                <li>Implemented authentication and role-based access for Admin, Hotel Manager, and Customer.</li>
                <li>Designed relational database structures and integrated the frontend with backend APIs.</li>
              </ul>
            </div>
            <div class="resume-item">
              <h4>Sabay Tour Website</h4>
              <h5>2025</h5>
              <p><em>HTML, CSS, Bootstrap 5</em></p>
              <ul>
                <li>Created user-friendly layouts for displaying tour information.</li>
                <li>Used HTML, CSS, Bootstrap to create highly responsive designs.</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- My Projects Section -->
    <section id="portfolio" class="portfolio section-bg" style="background-color: #f5f8fd;">
      <div class="container">
        <div class="section-title">
          <h2>My Projects</h2>
          <p>Some of the projects I have been working on.</p>
        </div>

        <div class="row portfolio-container g-4">
          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/admin_hotel.png"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Hotel Booking System api</h4>
                <p class="text-muted small mb-3 flex-grow-1">php , laravel 12 , Postgresql</p>
                <a href="https://github.com/chhumsothatt54/HotelBookingManagementSystem_api" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/hotel_booking.png"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Hotel Booking System frontend</h4>
                <p class="text-muted small mb-3 flex-grow-1">Html , Css , Bootstrap 5 , Vue (composition api)</p>
                <a href="https://github.com/chhumsothatt54/HotelManagementSystem_frontend" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/cinema_booking.png"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Cinema Ticket Booking System</h4>
                <p class="text-muted small mb-3 flex-grow-1">Html , Css , Bootstrap 5 , Jquery , Php , Mysql</p>
                <a href="https://github.com/chhumsothatt54/TEAM4-Cinema-Ticket-Booking-System" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/vue_ecommerce.png"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Vue Ecommerce</h4>
                <p class="text-muted small mb-3 flex-grow-1">Html , Css , Bootstrap 5 , Vue (composition api)</p>
                <a href="https://github.com/chhumsothatt54/Vue-Ecommerce" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/mini_project.png"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Mini Project</h4>
                <p class="text-muted small mb-3 flex-grow-1">Html , Css , Bootstrap 5 , Javascipt</p>
                <a href="https://github.com/chhumsothatt54/Mini_Project" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/sabay_tour.png"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Sabay Tour Website</h4>
                <p class="text-muted small mb-3 flex-grow-1">HTML , Css, Bootstrap 5</p>
                <a href="https://github.com/chhumsothatt54/Travel_Tour" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/node_api.jpg"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Crud Product api</h4>
                <p class="text-muted small mb-3 flex-grow-1">Node js , Express js</p>
                <a href="https://github.com/chhumsothatt54/crud-product-node" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/laravel_api.jpg"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Crud Product api</h4>
                <p class="text-muted small mb-3 flex-grow-1">Php , Laravel</p>
                <a href="https://github.com/chhumsothatt54/crud-product-laravel" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap d-flex flex-column h-100">
              <img src="../assets/image/webapp.jpg"
                class="img-fluid" alt="">
              <div class="mt-3 d-flex flex-column flex-grow-1">
                <h4 class="fs-5 fw-bold">Mini Web App</h4>
                <p class="text-muted small mb-3 flex-grow-1">Html , Css , Bootstrap 5 , Php</p>
                <a href="https://github.com/chhumsothatt54/pr_admin" target="_blank" class="btn btn-sm btn-github rounded-pill px-3 shadow-sm" style="width: max-content;">
                  <i class="bi bi-github me-1"></i> View GitHub
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- Modern Footer -->
  <footer id="footer" class="footer position-relative pt-5 pb-4 mt-auto" style="background: linear-gradient(180deg, #0a192f 0%, #040b14 100%);">
    <div class="container border-top border-secondary pt-4">
      <div class="row align-items-center justify-content-between">
        <div class="col-md-4 text-center text-md-start mb-4 mb-md-0">
          <h3 class="fw-bold text-white mb-2" style="font-family: 'Outfit', sans-serif;">Chhum Sothatt</h3>
          <p class="text-white-50 small mb-0">Information Technology Student & Aspiring Web Developer</p>
        </div>
        
        <div class="col-md-4 text-center mb-4 mb-md-0">
          <div class="social-links d-flex justify-content-center gap-3">
            <a href="https://t.me/csothatt" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="Telegram"><i class="bi bi-telegram fs-2"></i></a>
            <a href="https://www.facebook.com/share/1EpBWRbDwH/?mibextid=wwXIfr" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="Facebook"><i class="bi bi-facebook fs-2"></i></a>
            <a href="https://github.com/chhumsothatt54" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="GitHub"><i class="bi bi-github fs-2"></i></a>
            <a href="https://vercel.com/chhumsothatt" target="_blank" class="text-white bg-secondary bg-opacity-25 rounded-circle d-flex align-items-center justify-content-center" style="width: 40px; height: 40px;" title="Vercel"><i class="bi bi-caret-up-fill fs-2"></i></a>
          </div>
        </div>
        
        <div class="col-md-4 text-center text-md-end">
          <p class="mb-0 text-white-50 small">
            &copy; <strong><span>2026</span></strong>. All Rights Reserved.
          </p>
          <p class="mb-0 text-white-50 small mt-1">
            Built by <span class="fw-bold" style="color: var(--accent-teal);">Chhum Sothatt</span>
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer-social:hover {
  background-color: var(--accent-teal) !important;
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(20, 184, 166, 0.3);
}
.social-links a:hover {
  background-color: var(--accent-teal) !important;
  color: #fff !important;
}

.nav-link {
  color: rgba(255, 255, 255, 0.75) !important;
  font-weight: 500;
  padding: 10px 15px !important;
  transition: 0.3s;
}

.nav-link:hover,
.nav-link.active {
  color: var(--accent-teal) !important;
}
</style>
