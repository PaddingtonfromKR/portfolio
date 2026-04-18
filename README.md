[index.html](https://github.com/user-attachments/files/26855242/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jihye Kim - Professional Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-brand">Jihye Kim</div>
            <ul class="nav-menu">
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1 class="hero-title">Jihye Kim</h1>
            <p class="hero-subtitle">Your Professional Title Here</p>
            <p class="hero-description">Brief tagline about yourself - what you do and what makes you unique</p>
            <div class="hero-buttons">
                <a href="#contact" class="btn btn-primary">Get in Touch</a>
                <a href="https://www.linkedin.com/in/jihye-kim-kr/" target="_blank" class="btn btn-secondary">LinkedIn</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <p>
                    Write a compelling introduction about yourself here. Include your background, 
                    what drives you professionally, and what you're passionate about. This is your 
                    chance to make a strong first impression.
                </p>
                <p>
                    Add another paragraph highlighting your unique value proposition, career goals, 
                    or what sets you apart in your field.
                </p>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="section section-alt">
        <div class="container">
            <h2 class="section-title">Professional Experience</h2>
            
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">Job Title</h3>
                        <p class="experience-company">Company Name</p>
                    </div>
                    <p class="experience-date">Month Year - Present</p>
                </div>
                <ul class="experience-description">
                    <li>Key achievement or responsibility #1</li>
                    <li>Key achievement or responsibility #2</li>
                    <li>Key achievement or responsibility #3</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">Previous Job Title</h3>
                        <p class="experience-company">Previous Company Name</p>
                    </div>
                    <p class="experience-date">Month Year - Month Year</p>
                </div>
                <ul class="experience-description">
                    <li>Key achievement or responsibility #1</li>
                    <li>Key achievement or responsibility #2</li>
                    <li>Key achievement or responsibility #3</li>
                </ul>
            </div>

            <!-- Add more experience items as needed -->
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="section">
        <div class="container">
            <h2 class="section-title">Education</h2>
            
            <div class="education-item">
                <div class="education-header">
                    <div>
                        <h3 class="education-degree">Degree Name</h3>
                        <p class="education-school">University Name</p>
                    </div>
                    <p class="education-date">Graduation Year</p>
                </div>
                <p class="education-details">Relevant coursework, honors, or additional details</p>
            </div>

            <!-- Add more education items as needed -->
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section section-alt">
        <div class="container">
            <h2 class="section-title">Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3 class="skill-category-title">Technical Skills</h3>
                    <ul class="skill-list">
                        <li>Skill 1</li>
                        <li>Skill 2</li>
                        <li>Skill 3</li>
                        <li>Skill 4</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3 class="skill-category-title">Professional Skills</h3>
                    <ul class="skill-list">
                        <li>Skill 1</li>
                        <li>Skill 2</li>
                        <li>Skill 3</li>
                        <li>Skill 4</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3 class="skill-category-title">Languages</h3>
                    <ul class="skill-list">
                        <li>English - Fluent</li>
                        <li>Korean - Native</li>
                        <li>Add more languages</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2 class="section-title">Get in Touch</h2>
            <div class="contact-content">
                <p class="contact-intro">I'm always open to new opportunities and connections. Feel free to reach out!</p>
                <div class="contact-links">
                    <a href="mailto:your.email@example.com" class="contact-link">
                        <span class="contact-icon">✉</span>
                        your.email@example.com
                    </a>
                    <a href="https://www.linkedin.com/in/jihye-kim-kr/" target="_blank" class="contact-link">
                        <span class="contact-icon">in</span>
                        LinkedIn Profile
                    </a>
                    <a href="https://github.com/yourusername" target="_blank" class="contact-link">
                        <span class="contact-icon">{ }</span>
                        GitHub Profile
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Jihye Kim. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
[style.css](https://github.com/user-attachments/files/26855246/style.css)
[script.js](https://github.com/user-attachments/files/26855250/script.js)
// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Navbar background change on scroll
window.addEventListener('scroll', function() {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.style.boxShadow = '0 4px 12px rgba(0, 0, 0, 0.15)';
    } else {
        navbar.style.boxShadow = '0 2px 4px rgba(0, 0, 0, 0.1)';
    }
});

// Add animation to sections when they come into view
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver(function(entries) {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);

// Observe all sections
document.querySelectorAll('.section').forEach(section => {
    section.style.opacity = '0';
    section.style.transform = 'translateY(20px)';
    section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(section);
});
