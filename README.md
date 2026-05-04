<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Amaar Omer | HSE Professional</title>

<!-- AOS Animation -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: white;
}

/* HERO */
header {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    text-align: center;
    background: linear-gradient(-45deg, #0f172a, #1e293b, #0f172a);
    background-size: 400% 400%;
    animation: bg 10s ease infinite;
}

@keyframes bg {
    0% {background-position: 0% 50%;}
    50% {background-position: 100% 50%;}
    100% {background-position: 0% 50%;}
}

h1 {
    font-size: 50px;
    margin: 0;
}

p {
    font-size: 18px;
    opacity: 0.8;
}

.btn {
    margin-top: 20px;
    padding: 12px 25px;
    background: #22c55e;
    color: black;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

/* SECTIONS */
.section {
    padding: 60px 20px;
    max-width: 900px;
    margin: auto;
}

h2 {
    color: #22c55e;
}

/* CARDS */
.card {
    background: #1e293b;
    padding: 20px;
    margin: 10px 0;
    border-radius: 10px;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.03);
    background: #273449;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: #0b1220;
    font-size: 14px;
    opacity: 0.7;
}
</style>
</head>

<body>

<!-- HERO -->
<header>
    <h1 data-aos="fade-up">Amaar Omer</h1>
    <p data-aos="fade-up">HSE Professional | Oil & Gas Experience | Zero Incident Record</p>
    <a class="btn" href="#">Download CV</a>
</header>

<!-- ABOUT -->
<section class="section">
    <h2 data-aos="fade-right">About Me</h2>
    <p data-aos="fade-up">
        Safety-focused professional with hands-on experience in oil & gas operations.
        Worked as Chemical Handler and Sample Catcher with a proven Zero Incident Record
        across multiple drilling projects (6 wells).
    </p>
</section>

<!-- EXPERIENCE -->
<section class="section">
    <h2 data-aos="fade-right">Experience</h2>

    <div class="card" data-aos="zoom-in">
        <h3>Chemical Handler</h3>
        <p>Handled drilling chemicals safely with strict HSE compliance.</p>
    </div>

    <div class="card" data-aos="zoom-in">
        <h3>Sample Catcher</h3>
        <p>Collected and managed drilling samples under safety procedures.</p>
    </div>

    <div class="card" data-aos="zoom-in">
        <h3>Drilling Operations Support</h3>
        <p>Participated in 6 oil wells drilling operations with zero incidents.</p>
    </div>
</section>

<!-- CERTIFICATIONS -->
<section class="section">
    <h2 data-aos="fade-right">Certifications</h2>

    <div class="card" data-aos="fade-up">OSHA 30 Construction</div>
    <div class="card" data-aos="fade-up">IOSH Managing Safely</div>
    <div class="card" data-aos="fade-up">ISO 45001 Internal Auditor</div>
    <div class="card" data-aos="fade-up">IIRSM Safety Certificates</div>
    <div class="card" data-aos="fade-up">NEBOSH IGC (In Progress)</div>
</section>

<!-- SKILLS -->
<section class="section">
    <h2 data-aos="fade-right">Skills</h2>

    <div class="card" data-aos="zoom-in">Risk Assessment</div>
    <div class="card" data-aos="zoom-in">Permit to Work System</div>
    <div class="card" data-aos="zoom-in">Incident Reporting</div>
    <div class="card" data-aos="zoom-in">Site Safety Inspections</div>
</section>

<!-- CONTACT -->
<section class="section">
    <h2 data-aos="fade-right">Contact</h2>

    <div class="card">
        Email: amaar@example.com<br>
        WhatsApp: +XXX XXX XXX<br>
        LinkedIn: linkedin.com/in/amaar-omer
    </div>
</section>

<!-- FOOTER -->
<footer>
    © 2026 Amaar Omer | HSE Portfolio
</footer>

<!-- AOS SCRIPT -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
AOS.init();
</script>

</body>
</html>
