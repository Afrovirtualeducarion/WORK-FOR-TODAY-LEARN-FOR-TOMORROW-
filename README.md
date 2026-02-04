# "WORK FOR TODAY, LEARN FOR TOMORROW!"
Afro Virtual Education (AVE) addresses a critical educational gap by focusing on Ethiopians whose schooling was interrupted by migration and work constraints. By enabling high school completion, AVE restores educational opportunity, dignity, and future prospects, helping learners achieve their aspirations for higher education.
WORK FOR TODAY, LEARN FOR TOMORROW
Afro Virtual Education (AVE) addresses a critical educational gap by focusing on Ethiopians whose schooling was interrupted by migration and work constraints. By enabling high school completion, AVE restores educational opportunity, dignity, and future prospects, helping learners achieve their aspirations for higher education.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ethiopian Virtual Learning Platform</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
    }

    body {
      line-height: 1.6;
      color: #333;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    header {
      background: #2E86AB;
      color: white;
      padding: 20px 0;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      color: white;
      margin-left: 20px;
      font-weight: 600;
    }

    .hero {
      background: #2E86AB url('https://images.unsplash.com/photo-1581091215360-7c022bfa2362?auto=format&fit=crop&w=1470&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .btn {
      background: #F9A826;
      color: white;
      padding: 12px 25px;
      border-radius: 5px;
      font-weight: 600;
      transition: 0.3s;
    }

    .btn:hover {
      background: #e59400;
    }

    section {
      padding: 60px 0;
    }

    h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2rem;
      color: #2E86AB;
    }

    .value-prop {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      text-align: center;
    }

    .value-prop div {
      flex: 1 1 250px;
      margin: 20px;
      padding: 20px;
      border-radius: 8px;
      background: #f3f3f3;
    }

    .courses {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .course-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      padding: 20px;
      transition: transform 0.3s;
    }

    .course-card:hover {
      transform: translateY(-5px);
    }

    .course-card h3 {
      margin-bottom: 10px;
      color: #2E86AB;
    }

    .course-card p {
      margin-bottom: 15px;
    }

    .instructors {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .instructor-card {
      flex: 1 1 250px;
      text-align: center;
      margin: 20px;
      padding: 20px;
      border-radius: 8px;
      background: #f3f3f3;
    }

    .instructor-card img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
    }

    .testimonials {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .testimonial-card {
      flex: 1 1 250px;
      background: #f3f3f3;
      margin: 15px;
      padding: 20px;
      border-radius: 8px;
    }

    form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }

    form input, form textarea {
      padding: 12px;
      margin-bottom: 15px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 1rem;
    }

    footer {
      background: #2E86AB;
      color: white;
      text-align: center;
      padding: 20px 0;
    }

    @media(max-width:768px){
      nav {
        flex-direction: column;
      }

      .value-prop, .courses, .instructors, .testimonials {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container">
      <nav>
        <h2>Ethiopian Virtual Learning</h2>
        <div>
          <a href="#courses">Courses</a>
          <a href="#instructors">Instructors</a>
          <a href="#how-it-works">How It Works</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Empowering Ethiopian Students Abroad</h1>
      <p>Grades 7–12 Curriculum Online. Learn anywhere, anytime.</p>
      <a href="#courses" class="btn">View Courses</a>
      <a href="#contact" class="btn" style="margin-left:15px;">Enroll Today</a>
    </div>
  </section>

  <!-- Value Proposition -->
  <section>
    <div class="container">
      <h2>Why Choose Us</h2>
      <div class="value-prop">
        <div>
          <h3>Curriculum Aligned</h3>
          <p>Strictly following Ethiopian curriculum for Grades 7–12.</p>
        </div>
        <div>
          <h3>Flexible Learning</h3>
          <p>Learn at your own pace, anytime, anywhere.</p>
        </div>
        <div>
          <h3>Qualified Instructors</h3>
          <p>Experienced educators providing quality guidance online.</p>
        </div>
        <div>
          <h3>Affordable & Accessible</h3>
          <p>Designed for migrants and laborers with limited time and resources.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Courses -->
  <section id="courses">
    <div class="container">
      <h2>Courses</h2>
      <div class="courses">
        <div class="course-card">
          <h3>Grade 7 Math</h3>
          <p>Comprehensive lessons covering Ethiopian Grade 7 mathematics.</p>
          <a href="#contact" class="btn">Enroll Now</a>
        </div>
        <div class="course-card">
          <h3>Grade 8 Science</h3>
          <p>Explore key concepts in Physics, Chemistry, and Biology for Grade 8.</p>
          <a href="#contact" class="btn">Enroll Now</a>
        </div>
        <div class="course-card">
          <h3>Grade 9 English</h3>
          <p>Enhance your reading, writing, and communication skills.</p>
          <a href="#contact" class="btn">Enroll Now</a>
        </div>
        <div class="course-card">
          <h3>Grade 10 Social Studies</h3>
          <p>Understand history, geography, and civics aligned with Ethiopian curriculum.</p>
          <a href="#contact" class="btn">Enroll Now</a>
        </div>
        <div class="course-card">
          <h3>Grade 11 Math</h3>
          <p>Advanced concepts and problem-solving for higher-level learners.</p>
          <a href="#contact" class="btn">Enroll Now</a>
        </div>
        <div class="course-card">
          <h3>Grade 12 Science</h3>
          <p>Prepare for national exams with comprehensive science lessons.</p>
          <a href="#contact" class="btn">Enroll Now</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Instructors -->
  <section id="instructors">
    <div class="container">
      <h2>Our Instructors</h2>
      <div class="instructors">
        <div class="instructor-card">
          <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Instructor">
          <h3>Mesfin Lema</h3>
          <p>Mathematics Expert | Grades 7–12</p>
        </div>
        <div class="instructor-card">
          <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Instructor">
          <h3>Hanna Bekele</h3>
          <p>Science Educator | Physics & Chemistry</p>
        </div>
        <div class="instructor-card">
          <img src="https://randomuser.me/api/portraits/men/56.jpg" alt="Instructor">
          <h3>Abebe Tadesse</h3>
          <p>English & Social Studies | Grades 7–12</p>
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works -->
  <section id="how-it-works">
    <div class="container">
      <h2>How It Works</h2>
      <div class="value-prop">
        <div>
          <h3>1. Sign Up</h3>
          <p>Create your account and select your grade level.</p>
        </div>
        <div>
          <h3>2. Choose Courses</h3>
          <p>Pick the subjects you want to study.</p>
        </div>
        <div>
          <h3>3. Learn Online</h3>
          <p>Access lessons anytime from your device.</p>
        </div>
        <div>
          <h3>4. Track Progress</h3>
          <p>Complete assignments, quizzes, and earn certificates.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section>
    <div class="container">
      <h2>What Our Students Say</h2>
      <div class="testimonials">
        <div class="testimonial-card">
          <p>"This platform made it possible for me to continue my studies while working in Dubai. Highly recommended!"</p>
          <strong>- Fikadu M.</strong>
        </div>
        <div class="testimonial-card">
          <p>"Flexible, professional, and aligned with the Ethiopian curriculum. Perfect for laborers abroad."</p>
          <strong>- Sema H.</strong>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact / Signup -->
  <section id="contact">
    <div class="container">
      <h2>Get Started Today</h2>
      <form>
        <input type="text" placeholder="Full Name" required>
        <input type="email" placeholder="Email Address" required>
        <input type="text" placeholder="Country" required>
        <input type="text" placeholder="Grade (7-12)" required>
        <textarea rows="5" placeholder="Message (optional)"></textarea>
        <button type="submit" class="btn">Sign Up</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Ethiopian Virtual Learning Platform. All Rights Reserved.</p>
  </footer>

</body>
</html>

