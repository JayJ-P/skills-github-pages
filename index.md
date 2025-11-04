---
title: Welcome to my blog
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Your Biography — Portfolio</title>

    <link rel="stylesheet" href="styles.css" />
    <link rel="icon" href="favicon.png" />

</head>
<body>
    <button id="skip-link" class="skip-link">Skip to content</button>

    <header class="site-header">
        <div class="header-inner">
            <a class="brand" href="#intro">Your Name</a>

            <nav class="top-nav" aria-label="Main navigation">
                <button id="menu-toggle" class="menu-toggle" aria-expanded="false" aria-controls="primary-nav" aria-label="Toggle menu">
                    ☰
                </button>
                <ul id="primary-nav" class="nav-list">
                    <li><a href="#intro">Home</a></li>
                    <li><a href="#bio">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>

            <div class="header-actions">
                <button id="dark-toggle" class="btn icon-btn" aria-pressed="false" title="Toggle dark mode">🌙</button>
                <a class="btn" href="resume.pdf" download="YourName_Resume.pdf" aria-label="Download resume">Download Resume</a>
            </div>
        </div>
    </header>

    <div class="container">
        <!-- Sidebar (desktop) -->
        <aside class="sidebar" aria-label="Profile sidebar">
            <img src="1.webp" alt="Profile picture" class="profile-pic" />
            <h1 class="name">Your Name</h1>
            <p class="tagline">Developer • Designer • Problem Solver</p>

            <nav class="sidebar-nav" aria-label="Sidebar navigation">
                <ul>
                    <li><a href="#intro">Introduction</a></li>
                    <li><a href="#bio">Full Bio</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>

            <div class="social">
                <a href="#" aria-label="LinkedIn profile">LinkedIn</a>
                <a href="#" aria-label="GitHub profile">GitHub</a>
                <a href="#" aria-label="Twitter profile">Twitter</a>
            </div>
        </aside>

        <!-- Main content -->
        <main id="content" class="main-content" tabindex="-1">
            <section id="intro" class="panel reveal">
                <h2>Introduction</h2>
                <p>Hello — I'm <strong>Your Name</strong>. I build web apps, design interfaces, and solve technical problems. This is a short intro to explain who I am and what I do.</p>
            </section>

            <section id="bio" class="panel reveal">
                <h2>Full Bio</h2>

                <h3>Early Life</h3>
                <p>I grew up in ... Describe your upbringing, influences, and early interests.</p>

                <h3>Education</h3>
                <p>Degrees, institutions, notable coursework or projects.</p>

                <h3>Career</h3>
                <p>Roles, companies, major projects and outcomes. Use bullets for clarity:</p>
                <ul>
                    <li>Role — company (year–year): short achievement</li>
                    <li>Role — company (year–year): short achievement</li>
                </ul>

                <h3>Skills & Expertise</h3>
                <p>Summary of what you know and what you're learning.</p>
            </section>

            <section id="projects" class="panel reveal">
                <h2>Projects</h2>
                <div class="project-list">
                    <article class="project-item">
                        <h3>Project Title 1</h3>
                        <p>Short description. Tech: HTML, CSS, JS</p>
                        <p><a href="#" class="project-link">View project</a></p>
                    </article>

                    <article class="project-item">
                        <h3>Project Title 2</h3>
                        <p>Short description. Tech: React, Node</p>
                        <p><a href="#" class="project-link">View project</a></p>
                    </article>

                    <article class="project-item">
                        <h3>Project Title 3</h3>
                        <p>Short description. Tech: Python, Data</p>
                        <p><a href="#" class="project-link">View project</a></p>
                    </article>
                </div>
            </section>

            <section id="skills" class="panel reveal">
                <h2>Skills</h2>
                <div class="skills-grid">
                    <div class="skill">
                        <div class="skill-head"><span>JavaScript</span><span class="skill-value">85%</span></div>
                        <div class="progress"><div class="progress-bar" data-value="85"></div></div>
                    </div>
                    <div class="skill">
                        <div class="skill-head"><span>HTML & CSS</span><span class="skill-value">90%</span></div>
                        <div class="progress"><div class="progress-bar" data-value="90"></div></div>
                    </div>
                    <div class="skill">
                        <div class="skill-head"><span>React</span><span class="skill-value">75%</span></div>
                        <div class="progress"><div class="progress-bar" data-value="75"></div></div>
                    </div>
                </div>
            </section>

            <section id="testimonials" class="panel reveal">
                <h2>Testimonials</h2>
                <div class="carousel" aria-roledescription="carousel">
                    <button class="carousel-btn prev" aria-label="Previous testimonial">‹</button>
                    <div class="carousel-track">
                        <blockquote class="testimonial">
                            <p>"Great to work with — delivered ahead of schedule."</p>
                            <footer>— Client A</footer>
                        </blockquote>
                        <blockquote class="testimonial">
                            <p>"Excellent problem solving and clean code."</p>
                            <footer>— Client B</footer>
                        </blockquote>
                        <blockquote class="testimonial">
                            <p>"Very communicative and detail-oriented."</p>
                            <footer>— Client C</footer>
                        </blockquote>
                    </div>
                    <button class="carousel-btn next" aria-label="Next testimonial">›</button>
                </div>
            </section>

            <section id="contact" class="panel reveal">
                <h2>Contact</h2>

                <div class="contact-grid">
                    <div class="contact-details">
                        <p>Email: <a href="mailto:you@example.com">you@example.com</a></p>
                        <p>Phone: <a href="tel:+1234567890">+1 234 567 890</a></p>
                        <p>Location: City, Country</p>
                        <p>Social: <a href="#">LinkedIn</a> • <a href="#">GitHub</a></p>
                    </div>

                    <form id="contact-form" class="contact-form" novalidate action="https://formspree.io/f/meopbror" method="POST">
                        <label>
                            <span>Name</span>
                            <input type="text" name="name" id="name" required minlength="2" />
                        </label>

                        <label>
                            <span>Email</span>
                            <input type="email" name="email" id="email" required />
                        </label>

                        <label>
                            <span>Message</span>
                            <textarea name="message" id="message" rows="6" required minlength="10"></textarea>
                        </label>

                        <div class="form-actions">
                            <button type="submit" class="btn">Send</button>
                            <button type="button" id="mailto-fallback" class="btn ghost">Open Email</button>
                        </div>

                        <p id="form-status" class="form-status" role="status" aria-live="polite"></p>
                    </form>
                </div>
            </section>

            <footer id="site-footer" class="footer panel">
                <p>&copy; <span id="year"></span> Your Name — All rights reserved.</p>
                <p><a href="#privacy">Privacy Policy</a> • <a href="#terms">Terms</a></p>
            </footer>
        </main>
    </div>

    <script src="script.js" defer></script>
</body>
</html>
