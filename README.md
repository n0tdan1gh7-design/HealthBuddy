<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HealthBuddy | Healthcare Made Accessible</title>

<style>
:root {
    --navy: #183B56;
    --ocean: #5B9DB8;
    --sky: #B9DCEB;
    --seafoam: #D5EAE5;
    --sand: #F3EBDD;
    --white: #FFFFFF;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: var(--white);
    color: var(--navy);
    line-height: 1.7;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 22px 8%;
    background: white;
    border-bottom: 1px solid var(--seafoam);
}

.logo {
    font-size: 26px;
    font-weight: bold;
    color: var(--navy);
}

.logo span {
    color: var(--ocean);
}

nav a {
    text-decoration: none;
    color: var(--navy);
    margin-left: 25px;
    font-size: 14px;
}

nav a:hover {
    color: var(--ocean);
}

.hero {
    background: linear-gradient(135deg, #D5EAE5, #B9DCEB);
    text-align: center;
    padding: 110px 20px;
}

.hero h1 {
    font-size: 52px;
    margin-bottom: 15px;
}

.hero p {
    max-width: 650px;
    margin: auto;
    font-size: 18px;
}

.btn {
    display: inline-block;
    margin-top: 28px;
    padding: 13px 28px;
    background: var(--navy);
    color: white;
    text-decoration: none;
    border-radius: 30px;
    transition: 0.3s;
}

.btn:hover {
    background: var(--ocean);
}

section {
    padding: 75px 10%;
}

.section-title {
    text-align: center;
    font-size: 32px;
    margin-bottom: 25px;
}

.mission {
    text-align: center;
    max-width: 850px;
    margin: auto;
}

.problem {
    background: var(--sand);
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    margin-top: 35px;
}

.card {
    background: white;
    padding: 28px;
    border-radius: 14px;
    border: 1px solid var(--seafoam);
}

.card h3 {
    color: var(--ocean);
    margin-bottom: 12px;
}

.solutions {
    background: #F8FBFC;
}

.resources {
    background: var(--seafoam);
    text-align: center;
}

footer {
    background: var(--navy);
    color: white;
    text-align: center;
    padding: 30px;
}

footer p {
    font-size: 13px;
    opacity: 0.8;
}

@media (max-width: 650px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        margin: 0 8px;
        font-size: 12px;
    }

    .hero h1 {
        font-size: 36px;
    }

    section {
        padding: 55px 7%;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">Health<span>Buddy</span></div>

    <nav>
        <a href="#home">Home</a>
        <a href="#mission">Mission</a>
        <a href="#problem">Problem</a>
        <a href="#solutions">Solutions</a>
        <a href="#resources">Resources</a>
    </nav>
</header>

<div class="hero" id="home">
    <h1>Healthcare Made Accessible.</h1>

    <p>
        Helping immigrant families understand healthcare,
        overcome language barriers, and navigate medical
        services with confidence.
    </p>

    <a href="#solutions" class="btn">Explore HealthBuddy</a>
</div>

<section id="mission">
    <h2 class="section-title">Our Mission</h2>

    <div class="mission">
        <p>
            To help make healthcare and health literacy accessible
            by empowering immigrant families with the linguistic
            tools, foundational knowledge, and navigational
            confidence required to successfully interact with
            the medical system.
        </p>
        <br>
        <p>
            We aim to bridge the information gap between new
            immigrant populations and complex healthcare
            infrastructure, ensuring equitable, transparent,
            and culturally competent medical care.
        </p>
    </div>
</section>

<section class="problem" id="problem">
    <h2 class="section-title">Understanding the Problem</h2>

    <div class="cards">
        <div class="card">
            <h3>Language Barriers</h3>
            <p>
                Limited access to understandable medical
                documentation in native languages can
                create communication difficulties.
            </p>
        </div>

        <div class="card">
            <h3>Administrative Complexity</h3>
            <p>
                Health insurance policies, deductibles,
                co-pays, and medical terminology can
                be confusing to navigate.
            </p>
        </div>

        <div class="card">
            <h3>Healthcare Navigation</h3>
            <p>
                Families may need additional guidance
                understanding how to access and navigate
                available healthcare services.
            </p>
        </div>
    </div>
</section>

<section class="solutions" id="solutions">
    <h2 class="section-title">Our Solutions</h2>

    <div class="cards">
        <div class="card">
            <h3>Multilingual Guides</h3>
            <p>
                Free translated educational materials
                covering fundamental healthcare topics
                across multiple languages.
            </p>
        </div>

        <div class="card">
            <h3>Health Literacy Tools</h3>
            <p>
                Interactive bite-sized vocabulary modules
                designed to simplify clinical terminology.
            </p>
        </div>

        <div class="card">
            <h3>Healthcare Starter Kits</h3>
            <p>
                Practical family resources including
                symptom trackers and emergency
                contact organizers.
            </p>
        </div>
    </div>
</section>

<section class="resources" id="resources">
    <h2 class="section-title">Start Your Healthcare Journey</h2>

    <p>
        Better healthcare understanding starts with
        accessible information and education.
    </p>

    <a href="mailto:info@healthbuddy.org" class="btn">
        Contact HealthBuddy
    </a>
</section>

<footer>
    <h3>HealthBuddy</h3>
    <p>Making healthcare easier to understand for everyone.</p>

    <p>
        © 2026 HealthBuddy Corporation.
        All Rights Reserved.
    </p>

    <p>
        Unauthorized reproduction or distribution
        of website content is prohibited.
    </p>
</footer>


</body>
</html>
