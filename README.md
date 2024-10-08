<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        .container {
            width: 90%;
            margin: 0 auto;
            padding: 20px 0;
        }
        section {
            margin: 30px 0;
        }
        h2 {
            color: #007bff;
            font-size: 28px;
            margin-bottom: 10px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 10px 0;
            display: flex;
            align-items: center;
        }
        ul li i {
            font-size: 24px;
            color: #007bff;
            margin-right: 10px;
        }
        .icon {
            width: 40px;
            height: 40px;
            background-color: #007bff;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            font-size: 20px;
        }
        .service img {
            width: 100px;
            margin-right: 15px;
            border-radius: 10px;
            animation: float 3s infinite ease-in-out;
        }
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        .service {
            display: flex;
            align-items: center;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Professional Page</h1>
</header>

<div class="container">

    <!-- Education Section -->
    <section id="education">
        <h2><span class="icon">🎓</span> Education</h2>
        <p>Bachelor of Computer Science in Sana'a University.</p>
        <h3>Security Courses:</h3>
        <ul>
            <li><i class="icon">🔐</i>Course in protecting systems from intrusions.</li>
            <li><i class="icon">🛡️</i>Course in attack techniques and cyber penetration.</li>
        </ul>
        <h3>Technical Courses:</h3>
        <ul>
            <li><i class="icon">💻</i>Course in Systems analysis and design.</li>
            <li><i class="icon">📝</i>Course in the digital content industry.</li>
            <li><i class="icon">🎨</i>Course in design professions.</li>
        </ul>
        <h3>Management Courses:</h3>
        <ul>
            <li><i class="icon">🚀</i>Course in entrepreneurship.</li>
            <li><i class="icon">📊</i>Course in accounting.</li>
            <li><i class="icon">📢</i>Course in e-marketing.</li>
            <li><i class="icon">📑</i>Course in the business model.</li>
            <li><i class="icon">🎤</i>Course in Training of Trainers.</li>
        </ul>
    </section>

    <!-- Experience Section -->
    <section id="experience">
        <h2><span class="icon">💼</span> Experience</h2>
        <ul>
            <li><i class="icon">👨‍💻</i>Head of Technical Analysts Group for Public Works Projects (PWP).</li>
            <li><i class="icon">🛠️</i>Member of the Advanced Accounting and Administrative System Development Team.</li>
            <li><i class="icon">📈</i>Member of the Project Management and Technical Support System Development Team.</li>
            <li><i class="icon">🛒</i>Head of a team of developers: Contracting, Sales, and Purchasing System (S.P.E PRO).</li>
            <li><i class="icon">🛤️</i>Head of Technical Analysts Group of the Road Maintenance Fund (RMF-IU).</li>
            <li><i class="icon">🛣️</i>Head of Technical Analyst Group for the Rural Access Program Central Management Office (RAPCMO).</li>
            <li><i class="icon">🏢</i>Head of a team of designers and developers for the Chartered Accountants System - Ministry of Trade and Industry - Yemen.</li>
            <li><i class="icon">⚙️</i>ERPNEXT systems consultant.</li>
            <li><i class="icon">💻</i>Service provider at the ICT Department – NRC.</li>
            <li><i class="icon">🖥️</i>Works exhibition: <a href="https://github.com/alsanhani" target="_blank">github.com/alsanhani</a>.</li>
        </ul>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2><span class="icon">🛠️</span> Skills</h2>
        <ul>
            <li><i class="icon">🌐</i>Web development: Bootstrap(HTML-CSS)- ASP.NET- frappe.</li>
            <li><i class="icon">📱</i>Mobile programming: JAVA.</li>
            <li><i class="icon">👨‍💻</i>Programming languages: C++-C#- PHP – PYTHON.</li>
            <li><i class="icon">📊</i>Analyzing and mining various data (Data Analysis).</li>
            <li><i class="icon">💾</i>Database management: MYSQL-SQLSERVER.</li>
            <li><i class="icon">🗂️</i>Version control systems: Git.</li>
            <li><i class="icon">🔧</i>Network management (Internal-External).</li>
            <li><i class="icon">📦</i>System backups and disaster recovery management.</li>
        </ul>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2><span class="icon">🛎️</span> My Services</h2>
        <div class="service">
            <img src="https://via.placeholder.com/100" alt="Accounting System">
            <p>Accounting System</p>
        </div>
        <div class="service">
            <img src="https://via.placeholder.com/100" alt="Human Resources System">
            <p>Human Resources System</p>
        </div>
        <div class="service">
            <img src="https://via.placeholder.com/100" alt="Warehouse System">
            <p>Warehouse System</p>
        </div>
        <!-- Add more services as needed -->
    </section>

</div>

</body>
</html>
