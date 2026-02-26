<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Florussel F. Gallibot | Full-Stack Developer</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>
:root {
    --bg: #0f172a;
    --card: rgba(255,255,255,0.08);
    --text: #ffffff;
    --accent: #38bdf8;
}

body.light {
    --bg: #f1f5f9;
    --card: rgba(255,255,255,0.7);
    --text: #0f172a;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    background: var(--bg);
    color: var(--text);
    transition: 0.4s ease;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 40px 20px;
}

header {
    text-align: center;
    padding: 80px 20px 40px;
    animation: fadeIn 1s ease-in-out;
}

header img {
    width: 170px;
    border-radius: 50%;
    border: 4px solid var(--accent);
    box-shadow: 0 0 30px rgba(56,189,248,0.5);
    margin-bottom: 20px;
}

h1 {
    font-size: 2.5rem;
    font-weight: 800;
}

.subtitle {
    font-weight: 400;
    margin-top: 10px;
    opacity: 0.8;
}

.toggle-btn {
    position: fixed;
    top: 20px;
    right: 20px;
    padding: 8px 15px;
    border-radius: 20px;
    border: none;
    background: var(--accent);
    cursor: pointer;
    font-weight: 600;
}

.card {
    backdrop-filter: blur(20px);
    background: var(--card);
    border-radius: 15px;
    padding: 30px;
    margin: 25px 0;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-6px);
}

.section-title {
    font-size: 1.5rem;
    margin-bottom: 15px;
    font-weight: 700;
}

.skills span {
    display: inline-block;
    background: var(--accent);
    color: #000;
    padding: 6px 12px;
    border-radius: 20px;
    margin: 5px;
    font-size: 0.85rem;
    font-weight: 600;
}

.buttons {
    margin-top: 20px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    border-radius: 25px;
    margin: 5px;
    font-weight: 600;
    text-decoration: none;
    transition: 0.3s;
}

.primary {
    background: var(--accent);
    color: #000;
}

.secondary {
    border: 2px solid var(--accent);
    color: var(--accent);
}

.btn:hover {
    transform: scale(1.05);
}

.github-stats {
    text-align: center;
}

footer {
    text-align: center;
    padding: 30px;
    opacity: 0.6;
}

@keyframes fadeIn {
    from {opacity:0; transform: translateY(-20px);}
    to {opacity:1; transform: translateY(0);}
}

@media(max-width:768px){
    h1 {font-size:2rem;}
}
</style>
</head>

<body>

<button class="toggle-btn" onclick="toggleMode()">Toggle Mode</button>

<header>
    <img src="YOUR_IMGUR_DIRECT_LINK.jpg" alt="Florussel Gallibot">
    <h1>Florussel F. Gallibot</h1>
    <p class="subtitle">Full-Stack Developer | React • Next.js • Django • Web Scraping Architect</p>

    <div class="buttons">
        <a href="YOUR_RESUME_LINK.pdf" class="btn primary" target="_blank">Download Resume</a>
        <a href="https://github.com/jrgallibot" class="btn secondary" target="_blank">GitHub Profile</a>
    </div>
</header>

<div class="container">

<div class="card">
    <div class="section-title">Professional Summary</div>
    Experienced full-stack software developer specializing in React, Next.js, Django, and scalable web architectures. 
    Proven expertise in production-grade systems, automation pipelines, and enterprise-level scraping infrastructure.
</div>

<div class="card">
    <div class="section-title">Technical Expertise</div>
    <div class="skills">
        <span>React</span>
        <span>Next.js</span>
        <span>TypeScript</span>
        <span>Django</span>
        <span>Python</span>
        <span>Web Scraping</span>
        <span>Puppeteer</span>
        <span>Selenium</span>
        <span>Redux Toolkit</span>
        <span>AWS</span>
        <span>API Integration</span>
    </div>
</div>

<div class="card">
    <div class="section-title">Highlighted Projects</div>
    <strong>AchieveAI</strong> – Project management system with real-time dashboards.<br><br>
    <strong>Odoo Helpdesk Integration</strong> – React frontend integrated with Odoo workflows.<br><br>
    <strong>Caraga IRIS Recruitment System</strong> – Government hiring portal with real-time applicant tracking.<br>
</div>

<div class="card github-stats">
    <div class="section-title">GitHub Statistics</div>
    <img src="https://github-readme-stats.vercel.app/api?username=jrgallibot&show_icons=true&theme=tokyonight" width="100%">
    <br><br>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=jrgallibot&theme=tokyonight" width="100%">
</div>

</div>

<footer>
© 2026 Florussel F. Gallibot | Building scalable systems with precision
</footer>

<script>
function toggleMode(){
    document.body.classList.toggle("light");
}
</script>

</body>
</html>
