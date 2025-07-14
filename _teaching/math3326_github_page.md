---
title: "Teaching"
collection: teaching
permalink: /teaching/math3326-course
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MATH 3326: Introduction to Mathematical Statistics</title>
    <style>
        :root {
            --seu-blue: #003366;
            --seu-light-blue: #1e4a72;
            --seu-gold: #ffcc00;
            --light-text: #ffffff;
            --card-bg: rgba(255, 255, 255, 0.05);
            --accent-color: #4a90e2;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: linear-gradient(135deg, var(--seu-blue) 0%, var(--seu-light-blue) 100%);
            color: var(--light-text);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            background: var(--card-bg);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
        }

        .header h1 {
            color: var(--light-text);
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: 300;
        }

        .header .subtitle {
            color: var(--seu-gold);
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .instructor-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .info-card {
            background: rgba(255, 255, 255, 0.08);
            padding: 15px;
            border-radius: 10px;
            border-left: 4px solid var(--seu-gold);
            backdrop-filter: blur(5px);
        }

        .info-card strong {
            color: var(--seu-gold);
            display: block;
            margin-bottom: 5px;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .nav-menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 30px;
        }

        .nav-btn {
            background: linear-gradient(45deg, var(--seu-gold), #e6b800);
            color: var(--seu-blue);
            border: none;
            padding: 12px 25px;
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 600;
            text-decoration: none;
            display: inline-block;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            font-size: 0.9rem;
        }

        .nav-btn:hover {
            background: linear-gradient(45deg, #e6b800, var(--seu-gold));
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(255, 204, 0, 0.3);
            color: var(--seu-blue);
            text-decoration: none;
        }

        .nav-btn.active {
            background: var(--accent-color);
            color: white;
        }

        .content-section {
            background: var(--card-bg);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            display: none;
        }

        .content-section.active {
            display: block;
        }

        .content-section h2 {
            color: var(--light-text);
            margin-bottom: 20px;
            font-size: 2rem;
            border-bottom: 3px solid var(--seu-gold);
            padding-bottom: 10px;
            font-weight: 300;
        }

        .announcements {
            margin-bottom: 30px;
        }

        .announcement-card {
            background: rgba(255, 204, 0, 0.1);
            border-left: 4px solid var(--seu-gold);
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 10px;
        }

        .announcement-date {
            color: var(--seu-gold);
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .grading-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            background: rgba(255, 255, 255, 0.95);
            color: #333;
        }

        .grading-table th,
        .grading-table td {
            padding: 15px;
            text-align: left;
        }

        .grading-table th {
            background: linear-gradient(45deg, var(--seu-blue), var(--seu-light-blue));
            color: white;
            font-weight: 600;
        }

        .grading-table tr:nth-child(even) {
            background: #f8f9fa;
        }

        .exam-schedule {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .exam-card {
            background: linear-gradient(135deg, #ff7675, #d63031);
            color: white;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
        }

        .software-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .software-card {
            background: linear-gradient(135deg, #00b894, #00a085);
            color: white;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
        }

        .software-card a {
            color: white;
            text-decoration: underline;
        }

        .course-topics {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .topic-card {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            color: white;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            transition: all 0.3s ease;
        }

        .topic-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(116, 185, 255, 0.3);
        }

        .quick-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .stat-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .stat-number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--seu-gold);
            display: block;
        }

        .stat-label {
            font-size: 0.9rem;
            opacity: 0.8;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .nav-menu {
                flex-direction: column;
                align-items: center;
            }
            
            .instructor-info {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <h1>MATH 3326</h1>
            <p class="subtitle">Introduction to Mathematical Statistics • Fall 2025</p>
            
            <div class="instructor-info">
                <div class="info-card">
                    <strong>Instructor</strong>
                    Ahmad Talafha
                </div>
                <div class="info-card">
                    <strong>Office</strong>
                    JBWS 374
                </div>
                <div class="info-card">
                    <strong>Email</strong>
                    atalafha@stedwards.edu
                </div>
                <div class="info-card">
                    <strong>Schedule</strong>
                    MWF 12:00-12:50 PM, JBWS 363
                </div>
            </div>
        </div>

        <!-- Navigation Menu -->
        <div class="nav-menu">
            <button class="nav-btn active" onclick="showSection('overview')">Overview</button>
            <a href="../datasets/" class="nav-btn">Datasets</a>
            <a href="syllabus/" class="nav-btn">Syllabus</a>
            <a href="assignments/" class="nav-btn">Assignments</a>
            <a href="lectures/" class="nav-btn">Lectures</a>
            <button class="nav-btn" onclick="showSection('schedule')">Schedule</button>
            <button class="nav-btn" onclick="showSection('software')">Software</button>
        </div>

        <!-- Overview Section -->
        <div id="overview" class="content-section active">
            <h2>Course Overview</h2>
            
            <!-- Announcements -->
            <div class="announcements">
                <h3 style="color: var(--seu-gold); margin-bottom: 15px;">Recent Announcements</h3>
                
                <div class="announcement-card">
                    <div class="announcement-date">December 5, 2024</div>
                    <strong>Welcome to MATH 3326!</strong> Please download R and RStudio before our first class. Links are available in the Software section.
                </div>
                
                <div class="announcement-card">
                    <div class="announcement-date">December 1, 2024</div>
                    <strong>Textbook Information:</strong> The required textbook is available at the campus bookstore and online. ISBN: 978-0128178157.
                </div>
            </div>

            <!-- Quick Stats -->
            <div class="quick-stats">
                <div class="stat-card">
                    <span class="stat-number">15</span>
                    <span class="stat-label">Homework Assignments</span>
                </div>
                <div class="stat-card">
                    <span class="stat-number">3</span>
                    <span class="stat-label">Midterm Exams</span>
                </div>
                <div class="stat-card">
                    <span class="stat-number">5</span>
                    <span class="stat-label">Mini Projects</span>
                </div>
                <div class="stat-card">
                    <span class="stat-number">27</span>
                    <span class="stat-label">Lecture Quizzes</span>
                </div>
            </div>

            <h3 style="color: var(--light-text); margin: 30px 0 20px 0;">Learning Objectives</h3>
            <ul style="margin-left: 20px; line-height: 2;">
                <li>Understand and apply the principles of sampling distributions</li>
                <li>Perform point and interval estimation for population parameters</li>
                <li>Conduct hypothesis tests for various statistical scenarios</li>
                <li>Apply Bayesian methods for estimation and inference</li>
                <li>Build and interpret linear regression models</li>
                <li>Use empirical methods and nonparametric tests for data analysis</li>
                <li>Utilize R and RShiny for statistical computations and simulations</li>
            </ul>

            <h3 style="color: var(--light-text); margin: 30px 0 15px 0;">Grading Breakdown</h3>
            <table class="grading-table">
                <thead>
                    <tr>
                        <th>Assessment Type</th>
                        <th>Quantity</th>
                        <th>Weight</th>
                    </tr>
                </thead>
                <tbody>
                    <tr><td>Homework</td><td>15</td><td>10%</td></tr>
                    <tr><td>Midterm Exams</td><td>3</td><td>40%</td></tr>
                    <tr><td>Mini-Projects</td><td>5</td><td>15%</td></tr>
                    <tr><td>Worksheets</td><td>4</td><td>5%</td></tr>
                    <tr><td>Lecture Quizzes</td><td>27</td><td>10%</td></tr>
                    <tr><td>Final Exam</td><td>1</td><td>20%</td></tr>
                </tbody>
            </table>
        </div>

        <!-- Schedule Section -->
        <div id="schedule" class="content-section">
            <h2>Important Dates</h2>
            <div class="exam-schedule">
                <div class="exam-card">
                    <h3>Exam 1</h3>
                    <p>Wednesday, September 17, 2025</p>
                    <small>Chapters 4-5: Sampling Distributions & Point Estimation</small>
                </div>
                <div class="exam-card">
                    <h3>Exam 2</h3>
                    <p>Friday, October 10, 2025</p>
                    <small>Chapters 6-7: Interval Estimation & Hypothesis Testing</small>
                </div>
                <div class="exam-card">
                    <h3>Exam 3</h3>
                    <p>Monday, November 10, 2025</p>
                    <small>Chapters 8, 11: Regression & Bayesian Methods</small>
                </div>
                <div class="exam-card">
                    <h3>Final Exam</h3>
                    <p>December 11, 2025</p>
                    <small>Comprehensive Final Examination</small>
                </div>
            </div>

            <h3 style="margin-top: 30px; color: var(--light-text);">Project Presentations</h3>
            <ul style="margin-left: 20px; margin-top: 10px; line-height: 2;">
                <li><strong>December 1 (Monday):</strong> Final Project Presentations - Session 1</li>
                <li><strong>December 3 (Wednesday):</strong> Final Project Presentations - Session 2</li>
                <li><strong>December 5 (Friday):</strong> Final Exam Review</li>
            </ul>
        </div>

        <!-- Software Section -->
        <div id="software" class="content-section">
            <h2>Software & Tools</h2>
            <div class="software-grid">
                <div class="software-card">
                    <h3>R Programming Language</h3>
                    <p>Statistical computing and graphics</p>
                    <a href="https://cran.r-project.org/" target="_blank">Download R</a>
                </div>
                <div class="software-card">
                    <h3>RStudio IDE</h3>
                    <p>Integrated development environment for R</p>
                    <a href="https://rstudio.com/products/rstudio/download/" target="_blank">Download RStudio</a>
                </div>
                <div class="software-card">
                    <h3>RStudio Cloud</h3>
                    <p>Web-based R environment for assignments</p>
                    <a href="https://rstudio.cloud/" target="_blank">Access RStudio Cloud</a>
                </div>
            </div>
            
            <div style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 10px; margin-top: 30px; border-left: 4px solid var(--accent-color);">
                <h3 style="color: var(--seu-gold); margin-bottom: 15px;">Installation Instructions</h3>
                <ol style="margin-left: 20px; line-height: 2;">
                    <li>Download and install R from the CRAN website</li>
                    <li>Download and install RStudio Desktop</li>
                    <li>Test your installation by opening RStudio</li>
                    <li>Join the course RStudio Cloud workspace (invitation will be sent via email)</li>
                </ol>
            </div>
        </div>
    </div>

    <script>
        function showSection(sectionId) {
            // Hide all sections
            const sections = document.querySelectorAll('.content-section');
            sections.forEach(section => section.classList.remove('active'));
            
            // Remove active class from all nav buttons
            const navBtns = document.querySelectorAll('.nav-btn');
            navBtns.forEach(btn => btn.classList.remove('active'));
            
            // Show selected section
            document.getElementById(sectionId).classList.add('active');
            
            // Add active class to clicked button
            event.target.classList.add('active');
        }
    </script>
</body>
</html>
