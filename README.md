<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SkillSync - Task Allocation System</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.0/font/bootstrap-icons.css">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">
        <i class="bi bi-diagram-3-fill me-2"></i>SkillSync
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#how-it-works">How It Works</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#testimonials">Testimonials</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
          <li class="nav-item ms-lg-3">
            <a class="btn btn-primary" href="#">Get Started</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero-section py-5 mt-5">
    <div class="container py-5">
      <div class="row align-items-center">
        <div class="col-lg-6">
          <h1 class="display-4 fw-bold mb-4">Optimize Your Team's Potential</h1>
          <p class="lead mb-4">SkillSync intelligently matches tasks with your team members' skills, ensuring optimal productivity and job satisfaction.</p>
          <div class="d-flex gap-3">
            <a href="#" class="btn btn-primary btn-lg px-4">Start Free Trial</a>
            <a href="#" class="btn btn-outline-primary btn-lg px-4">Learn More</a>
          </div>
        </div>
        <div class="col-lg-6 d-none d-lg-block">
          <img src="assets/hero-image.svg" alt="Task Allocation Dashboard" class="img-fluid">
        </div>
      </div>
    </div>
  </section>

  <!-- Features Carousel -->
  <section id="features" class="py-5 bg-light">
    <div class="container py-5">
      <div class="text-center mb-5">
        <h2 class="fw-bold">Key Features</h2>
        <p class="lead text-muted">Discover how SkillSync transforms your workflow</p>
      </div>
      
      <div id="featuresCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#featuresCarousel" data-bs-slide-to="0" class="active"></button>
          <button type="button" data-bs-target="#featuresCarousel" data-bs-slide-to="1"></button>
          <button type="button" data-bs-target="#featuresCarousel" data-bs-slide-to="2"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row justify-content-center">
              <div class="col-md-4 mb-4">
                <div class="card h-100 border-0 shadow-sm">
                  <div class="card-body text-center p-4">
                    <div class="icon-box bg-primary bg-gradient text-white rounded-circle mx-auto mb-4">
                      <i class="bi bi-people-fill fs-3"></i>
                    </div>
                    <h5 class="card-title">Skill-Based Allocation</h5>
                    <p class="card-text">Automatically assign tasks to team members based on their skills and availability.</p>
                  </div>
                </div>
              </div>
              <div class="col-md-4 mb-4">
                <div class="card h-100 border-0 shadow-sm">
                  <div class="card-body text-center p-4">
                    <div class="icon-box bg-success bg-gradient text-white rounded-circle mx-auto mb-4">
                      <i class="bi bi-graph-up fs-3"></i>
                    </div>
                    <h5 class="card-title">Performance Analytics</h5>
                    <p class="card-text">Track team productivity with comprehensive reports and real-time dashboards.</p>
                  </div>
                </div>
              </div>
              <div class="col-md-4 mb-4">
                <div class="card h-100 border-0 shadow-sm">
                  <div class="card-body text-center p-4">
                    <div class="icon-box bg-info bg-gradient text-white rounded-circle mx-auto mb-4">
                      <i class="bi bi-bell-fill fs-3"></i>
                    </div>
                    <h5 class="card-title">Real-Time Notifications</h5>
                    <p class="card-text">Stay updated with instant alerts for new assignments and task updates.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row justify-content-center">
              <div class="col-md-4 mb-4">
                <div class="card h-100 border-0 shadow-sm">
                  <div class="card-body text-center p-4">
                    <div class="icon-box bg-warning bg-gradient text-white rounded-circle mx-auto mb-4">
                      <i class="bi bi-tools fs-3"></i>
                    </div>
                    <h5 class="card-title">Skill Management</h5>
                    <p class="card-text">Easily define and update required skills for your organization's needs.</p>
                  </div>
                </div>
              </div>
              <div class="col-md-4 mb-4">
                <div class="card h-100 border-0 shadow-sm">
                  <div class="card-body text-center p-4">
                    <div class="icon-box bg-danger bg-gradient text-white rounded-circle mx-auto mb-4">
                      <i class="bi bi-kanban-fill fs-3"></i>
                    </div>
                    <h5 class="card-title">Task Workflow</h5>
                    <p class="card-text">Create, modify, and track tasks through their complete lifecycle.</p>
                  </div>
                </div>
              </div>
              <div class="col-md-4 mb-4">
                <div class="card h-100 border-0 shadow-sm">
                  <div class="card-body text-center p-4">
                    <div class="icon-box bg-secondary bg-gradient text-white rounded-circle mx-auto mb-4">
                      <i class="bi bi-shield-lock fs-3"></i>
                    </div>
                    <h5 class="card-title">Role-Based Access</h5>
                    <p class="card-text">Secure system with different permission levels for admins, managers, and team members.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#featuresCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#featuresCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section id="how-it-works" class="py-5">
    <div class="container py-5">
      <div class="text-center mb-5">
        <h2 class="fw-bold">How SkillSync Works</h2>
        <p class="lead text-muted">Simple steps to optimize your team's productivity</p>
      </div>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card border-0 h-100">
            <div class="card-body text-center p-4">
              <div class="step-number bg-primary bg-gradient text-white rounded-circle mx-auto mb-4">1</div>
              <h5 class="card-title">Define Skills</h5>
              <p class="card-text">Managers create and maintain a catalog of skills required for various tasks.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0 h-100">
            <div class="card-body text-center p-4">
              <div class="step-number bg-success bg-gradient text-white rounded-circle mx-auto mb-4">2</div>
              <h5 class="card-title">Create Tasks</h5>
              <p class="card-text">Assign tasks with required skills, deadlines, and priority levels.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card border-0 h-100">
            <div class="card-body text-center p-4">
              <div class="step-number bg-info bg-gradient text-white rounded-circle mx-auto mb-4">3</div>
              <h5 class="card-title">Automatic Allocation</h5>
              <p class="card-text">System matches tasks with qualified team members based on skills and availability.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="py-5 bg-light">
    <div class="container py-5">
      <div class="text-center mb-5">
        <h2 class="fw-bold">What Our Clients Say</h2>
        <p class="lead text-muted">Trusted by teams worldwide</p>
      </div>
      <div class="row">
        <div class="col-lg-4 mb-4">
          <div class="card h-100 border-0 shadow-sm">
            <div class="card-body p-4">
              <div class="d-flex mb-3">
                <img src="assets/testimonial1.jpg" class="rounded-circle me-3" width="60" height="60" alt="Client">
                <div>
                  <h6 class="mb-0">Sarah Johnson</h6>
                  <small class="text-muted">CTO, TechSolutions Inc.</small>
                </div>
              </div>
              <p class="card-text">"SkillSync reduced our task assignment time by 70% and improved team satisfaction by matching people with work they excel at."</p>
              <div class="text-warning">
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mb-4">
          <div class="card h-100 border-0 shadow-sm">
            <div class="card-body p-4">
              <div class="d-flex mb-3">
                <img src="assets/testimonial2.jpg" class="rounded-circle me-3" width="60" height="60" alt="Client">
                <div>
                  <h6 class="mb-0">Michael Chen</h6>
                  <small class="text-muted">Project Manager, GlobalSoft</small>
                </div>
              </div>
              <p class="card-text">"The reporting features give us incredible visibility into team performance and help identify skill gaps for training."</p>
              <div class="text-warning">
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-half"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mb-4">
          <div class="card h-100 border-0 shadow-sm">
            <div class="card-body p-4">
              <div class="d-flex mb-3">
                <img src="assets/testimonial3.jpg" class="rounded-circle me-3" width="60" height="60" alt="Client">
                <div>
                  <h6 class="mb-0">David Wilson</h6>
                  <small class="text-muted">Team Lead, CreativeMinds</small>
                </div>
              </div>
              <p class="card-text">"Our developers love being able to opt for tasks that match their interests and skills. It's boosted morale and productivity."</p>
              <div class="text-warning">
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
                <i class="bi bi-star-fill"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="py-5 bg-primary text-white">
    <div class="container py-5 text-center">
      <h2 class="fw-bold mb-4">Ready to Transform Your Team's Productivity?</h2>
      <p class="lead mb-5">Join thousands of teams who are already optimizing their workflow with SkillSync</p>
      <a href="#" class="btn btn-light btn-lg px-5 me-3">Start Free Trial</a>
      <a href="#" class="btn btn-outline-light btn-lg px-5">Schedule Demo</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-5 mb-5 mb-lg-0">
          <h2 class="fw-bold mb-4">Get In Touch</h2>
          <p class="lead mb-4">Have questions about SkillSync? We'd love to hear from you.</p>
          <div class="d-flex mb-3">
            <i class="bi bi-geo-alt-fill text-primary fs-4 me-3"></i>
            <div>
              <h5 class="mb-0">Address</h5>
              <p class="mb-0">123 Productivity Lane, Suite 456<br>Tech City, TC 12345</p>
            </div>
          </div>
          <div class="d-flex mb-3">
            <i class="bi bi-telephone-fill text-primary fs-4 me-3"></i>
            <div>
              <h5 class="mb-0">Phone</h5>
              <p class="mb-0">+1 (555) 123-4567</p>
            </div>
          </div>
          <div class="d-flex">
            <i class="bi bi-envelope-fill text-primary fs-4 me-3"></i>
            <div>
              <h5 class="mb-0">Email</h5>
              <p class="mb-0">info@skillsync.com</p>
            </div>
          </div>
        </div>
        <div class="col-lg-7">
          <div class="card border-0 shadow-sm">
            <div class="card-body p-5">
              <h3 class="fw-bold mb-4">Send Us a Message</h3>
              <form>
                <div class="row g-3">
                  <div class="col-md-6">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" required>
                  </div>
                  <div class="col-md-6">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" required>
                  </div>
                  <div class="col-12">
                    <label for="subject" class="form-label">Subject</label>
                    <input type="text" class="form-control" id="subject" required>
                  </div>
                  <div class="col-12">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="5" required></textarea>
                  </div>
                  <div class="col-12">
                    <button type="submit" class="btn btn-primary px-4 py-2">Send Message</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white py-5">
    <div class="container py-4">
      <div class="row g-4">
        <div class="col-lg-4">
          <h5 class="fw-bold mb-3"><i class="bi bi-diagram-3-fill me-2"></i>SkillSync</h5>
          <p>Optimizing team productivity through intelligent skill-based task allocation.</p>
          <div class="d-flex gap-3">
            <a href="#" class="text-white"><i class="bi bi-facebook fs-4"></i></a>
            <a href="#" class="text-white"><i class="bi bi-twitter fs-4"></i></a>
            <a href="#" class="text-white"><i class="bi bi-linkedin fs-4"></i></a>
            <a href="#" class="text-white"><i class="bi bi-instagram fs-4"></i></a>
          </div>
        </div>
        <div class="col-lg-2 col-md-4">
          <h5 class="fw-bold mb-3">Quick Links</h5>
          <ul class="list-unstyled">
            <li class="mb-2"><a href="#home" class="text-white text-decoration-none">Home</a></li>
            <li class="mb-2"><a href="#features" class="text-white text-decoration-none">Features</a></li>
            <li class="mb-2"><a href="#how-it-works" class="text-white text-decoration-none">How It Works</a></li>
            <li class="mb-2"><a href="#testimonials" class="text-white text-decoration-none">Testimonials</a></li>
            <li class="mb-2"><a href="#contact" class="text-white text-decoration-none">Contact</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-4">
          <h5 class="fw-bold mb-3">Resources</h5>
          <ul class="list-unstyled">
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">Documentation</a></li>
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">API Reference</a></li>
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">Help Center</a></li>
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">Community Forum</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-4">
          <h5 class="fw-bold mb-3">Legal</h5>
          <ul class="list-unstyled">
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">Privacy Policy</a></li>
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">Terms of Service</a></li>
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">Cookie Policy</a></li>
            <li class="mb-2"><a href="#" class="text-white text-decoration-none">GDPR Compliance</a></li>
          </ul>
        </div>
      </div>
      <hr class="my-4">
      <div class="row">
        <div class="col-md-6 text-center text-md-start">
          <p class="mb-0">&copy; 2023 SkillSync. All rights reserved.</p>
        </div>
        <div class="col-md-6 text-center text-md-end">
          <p class="mb-0">Designed with <i class="bi bi-heart-fill text-danger"></i> for productive teams</p>
        </div>
      </div>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>







css properties



/* Custom CSS for SkillSync Landing Page */

/* General Styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  scroll-behavior: smooth;
}

/* Hero Section */
.hero-section {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
}

/* Icon Boxes */
.icon-box {
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Step Numbers */
.step-number {
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
  font-weight: bold;
}

/* Navbar Scroll Effect */
.navbar {
  transition: all 0.3s ease;
}

.navbar.scrolled {
  background-color: #343a40 !important;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

/* Card Hover Effect */
.card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1) !important;
}

/* Carousel Controls */
.carousel-control-prev, .carousel-control-next {
  width: 5%;
}

/* Gradient Backgrounds */
.bg-gradient-primary {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

.bg-gradient-success {
  background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
}

.bg-gradient-info {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
}

.bg-gradient-warning {
  background: linear-gradient(135deg, #f6d365 0%, #fda085 100%);
}

.bg-gradient-danger {
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}

.bg-gradient-secondary {
  background: linear-gradient(135deg, #868f96 0%, #596164 100%);
}

/* Responsive Adjustments */
@media (max-width: 768px) {
  .hero-section {
    text-align: center;
    padding-top: 100px;
  }
  
  .display-4 {
    font-size: 2.5rem;
  }
}
