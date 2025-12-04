<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Paul Abiodun - Enhanced CV</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
    :root {
        --bg: #ffffff;
        --sidebar: #eef2f3;
        --text: #333;
        --accent: #0fb9b1; /* teal */
        --muted: #6c7a86;
    }

    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: var(--bg);
        color: var(--text);
        display: flex;
        min-height: 100vh;
    }

    .sidebar {
        width: 280px;
        background: var(--sidebar);
        padding: 25px;
        display: flex;
        flex-direction: column;
        gap: 20px;
    }

    .sidebar h2 {
        margin-top: 0;
        color: var(--accent);
    }

    .sidebar .info p {
        margin: 6px 0;
        font-size: 14px;
    }

    .icon {
        color: var(--accent);
        margin-right: 8px;
    }

    .main {
        flex: 1;
        padding: 35px 40px;
    }

    h1 {
        margin: 0 0 5px;
        font-size: 32px;
        color: var(--accent);
    }

    h3 {
        margin-top: 35px;
        border-left: 4px solid var(--accent);
        padding-left: 10px;
    }

    ul {
        padding-left: 20px;
        line-height: 1.6;
    }

    .badge {
        background: rgba(255,255,255,0.1);
        padding: 6px 10px;
        border-radius: 6px;
        margin: 5px;
        display: inline-block;
        font-size: 13px;
    }

    @media (max-width: 768px) {
        body {
            flex-direction: column;
        }
        .sidebar {
            width: 100%;
        }
    }
</style>
</head>
<body>

<div class="sidebar" style="background:#f4f6f7;color:#333;">
    <img src="profile.png" alt="Profile Photo" style="width:120px;height:120px;border-radius:10px;object-fit:cover;margin-bottom:20px;">
    <h2>Contact</h2>
    <div class="info">
        <p><i class="fa-solid fa-user icon"></i>Paul Abiodun</p>
        <p><i class="fa-solid fa-location-dot icon"></i>Nottingham, UK</p>
        <p><i class="fa-solid fa-phone icon"></i>+44 (0) 772 150 2616</p>
        <p><i class="fa-solid fa-envelope icon"></i>paulaxcity@yahoo.com</p>
    </div>

    <h2>Skills</h2>
    <div>
        <span class="badge">Technical Proficiency</span>
        <span class="badge">Customer Service</span><br>
        <span class="badge">Problem Solving</span>
        <span class="badge">Documentation</span><br>
        <span class="badge">Teamwork</span>
        <span class="badge">Adaptability</span><br>
        <span class="badge">IT Security Awareness</span><br>
        <span class="badge">Attention to Detail</span>
    </div>

    <h2>Additional</h2>
    <p><i class="fa-solid fa-id-card icon"></i>Full UK Driving Licence</p>
    <p><i class="fa-solid fa-gamepad icon"></i>Travelling & Gaming</p>
</div>

<div class="main">
    <h1>Paul Abiodun</h1>
    <p><strong>IT Support Specialist</strong></p>

    <h3>About Me</h3>
    <p>Dedicated and customer-focused IT Support Specialist with over 10 years of experience providing technical assistance across diverse environments. Skilled in diagnosing and resolving hardware, software, and network issues. Adept at communicating technical information clearly and collaborating with teams. Committed to continuous learning and improving IT service delivery.</p>

    <h3>Work Experience</h3>

    <h4>IT Support Specialist — Instiq Professional Services (UBA & Premium Trust Bank)</h4>
    <p><em>Apr 2021 – Present | Lagos & UK</em></p>
    <ul>
        <li>Deliver first-line technical support via phone, email, and in person.</li>
        <li>Troubleshoot and resolve hardware, software, and network issues.</li>
        <li>Install and maintain desktops, printers, and IT equipment.</li>
        <li>Manage Active Directory accounts and permissions.</li>
        <li>Monitor servers, networks, and security infrastructure.</li>
        <li>Conduct updates, backups, and system health checks.</li>
        <li>Provide documentation, training, and user guidance.</li>
        <li>Primary contact for application issues & service requests.</li>
        <li>Technical Support & App Testing for UBA Core Banking Apps.</li>
    </ul>

    <h4>IT Support Engineer — Polaris Bank Ltd</h4>
    <p><em>Aug 2011 – Mar 2021 | Lagos, Nigeria</em></p>
    <ul>
        <li>Provided first-line technical support to banking staff.</li>
        <li>Installed and configured IT hardware and software.</li>
        <li>Monitored systems for security, compliance, and performance.</li>
        <li>Coordinated with vendors for upgrades and technical fixes.</li>
        <li>Documented configurations and support tickets.</li>
        <li>Trained staff in cybersecurity best practices.</li>
        <li>Supported disaster recovery processes.</li>
    </ul>

    <h3>Education</h3>
    <ul>
        <li><strong>B.Sc. Computer Science</strong> — ESPAM Formation University, Benin (2020)</li>
        <li><strong>OND Computer Engineering</strong> — Federal Polytechnic Ede, Osun (2008)</li>
    </ul>

    <h3>Certifications</h3>
    <ul>
        <li>Microsoft Azure Fundamentals — Microsoft (2023)</li>
    </ul>
</div>

</body>
</html>
