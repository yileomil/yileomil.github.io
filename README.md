<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }

        /* Layout */
        .cv-container {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            display: grid;
            grid-template-columns: 280px 1fr;
            gap: 30px;
        }

        /* Sidebar Styles */
        .sidebar {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto 20px;
            display: block;
            background-color: #ddd;
        }

        /* Main Content Styles */
        .main-content {
            padding: 20px;
        }

        /* Typography */
        h1 {
            color: #2c3e50;
            margin-bottom: 10px;
        }

        h2 {
            color: #3498db;
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
            margin: 20px 0 15px 0;
        }

        h3 {
            color: #2c3e50;
            margin: 15px 0 5px 0;
        }

        /* Contact Info */
        .contact-info p {
            margin-bottom: 8px;
        }

        /* Skills */
        .skills-list {
            list-style: none;
        }

        .skills-list li {
            background-color: #e9ecef;
            padding: 5px 10px;
            margin: 5px 0;
            border-radius: 15px;
            display: inline-block;
            margin-right: 5px;
        }

        /* Experience and Education */
        .experience-item, .education-item {
            margin-bottom: 20px;
        }

        .period {
            color: #666;
            font-style: italic;
            margin-bottom: 8px;
        }

        ul {
            padding-left: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .cv-container {
                grid-template-columns: 1fr;
            }

            .sidebar {
                order: -1;
            }
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <!-- Sidebar -->
        <div class="sidebar">
            <img class="profile-img" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNkYAAAAAYAAjCB0C8AAAAASUVORK5CYII=" alt="Profile">
            
            <div class="contact-info">
                <h2>Contact</h2>
                <p>📧 your.email@example.com</p>
                <p>📱 (123) 456-7890</p>
                <p>📍 City, Country</p>
                <p>🔗 linkedin.com/in/yourprofile</p>
            </div>

            <div class="skills-section">
                <h2>Skills</h2>
                <ul class="skills-list">
                    <li>HTML/CSS</li>
                    <li>JavaScript</li>
                    <li>Python</li>
                    <li>React</li>
                    <li>Node.js</li>
                    <li>Git</li>
                </ul>
            </div>

            <div class="languages-section">
                <h2>Languages</h2>
                <ul class="skills-list">
                    <li>English (Native)</li>
                    <li>Spanish (Fluent)</li>
                </ul>
            </div>
        </div>

        <!-- Main Content -->
        <div class="main-content">
            <h1>Your Name</h1>
            <p style="color: #666; margin-bottom: 20px;">Software Developer</p>

            <section>
                <h2>Professional Summary</h2>
                <p>Detail-oriented software developer with X years of experience in full-stack development. Passionate about creating efficient, scalable solutions and learning new technologies.</p>
            </section>

            <section>
                <h2>Work Experience</h2>
                
                <div class="experience-item">
                    <h3>Senior Software Developer</h3>
                    <p class="period">Company Name | 2020 - Present</p>
                    <ul>
                        <li>Led development of key features resulting in 40% increase in user engagement</li>
                        <li>Managed team of 5 developers and implemented agile methodologies</li>
                        <li>Optimized application performance reducing load time by 60%</li>
                    </ul>
                </div>

                <div class="experience-item">
                    <h3>Software Developer</h3>
                    <p class="period">Previous Company | 2018 - 2020</p>
                    <ul>
                        <li>Developed and maintained multiple web applications</li>
                        <li>Collaborated with UX team to implement responsive designs</li>
                        <li>Implemented automated testing reducing bugs by 30%</li>
                    </ul>
                </div>
            </section>

            <section>
                <h2>Education</h2>
                <div class="education-item">
                    <h3>Bachelor of Science in Computer Science</h3>
                    <p class="period">University Name | 2014 - 2018</p>
                    <p>Major: Computer Science</p>
                    <p>GPA: 3.8/4.0</p>
                </div>
            </section>

            <section>
                <h2>Projects</h2>
                <div class="experience-item">
                    <h3>Project Name</h3>
                    <p>Built a full-stack web application using React and Node.js. Implemented user authentication, real-time updates, and responsive design.</p>
                </div>
            </section>
        </div>
    </div>
</body>
</html>
