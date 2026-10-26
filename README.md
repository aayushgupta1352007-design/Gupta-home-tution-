# Gupta-home-tution-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gupta Home Tuition | Mathematics Classes</title>
    <meta name="description" content="Gupta Home Tuition in Jabalpur offers mathematics tuition for Classes 8 to 12 and college students, with 22 years of teaching experience.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #243047;
            background: #f5f7fb;
        }

        header {
            background: #102a56;
            color: white;
            padding: 18px 7%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 12px;
        }

        header h2 {
            font-size: 24px;
        }

        nav {
            display: flex;
            gap: 18px;
            flex-wrap: wrap;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd166;
        }

        .hero {
            padding: 85px 7%;
            text-align: center;
            color: white;
            background: linear-gradient(135deg, #102a56, #1769aa);
        }

        .hero h1 {
            font-size: clamp(32px, 5vw, 52px);
            margin-bottom: 16px;
        }

        .hero p {
            font-size: 18px;
            max-width: 700px;
            margin: 0 auto 25px;
        }

        .btn {
            display: inline-block;
            padding: 12px 22px;
            border-radius: 7px;
            text-decoration: none;
            font-weight: bold;
            margin: 5px;
            border: none;
            cursor: pointer;
            font-size: 15px;
        }

        .btn-yellow {
            background: #ffd166;
            color: #102a56;
        }

        .btn-green {
            background: #168653;
            color: white;
        }

        .btn-blue {
            background: #1769aa;
            color: white;
        }

        section {
            padding: 60px 7%;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            color: #102a56;
            margin-bottom: 12px;
        }

        .section-subtitle {
            text-align: center;
            margin: 0 auto 30px;
            max-width: 650px;
            color: #64748b;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 18px;
            margin-top: -25px;
            position: relative;
            padding: 0 7%;
        }

        .stat {
            background: white;
            text-align: center;
            padding: 24px 12px;
            border-radius: 12px;
            box-shadow: 0 5px 20px #102a5610;
        }

        .stat h3 {
            font-size: 28px;
            color: #1769aa;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 22px;
        }

        .card {
            background: white;
            padding: 26px;
            border-radius: 12px;
            box-shadow: 0 5px 20px #102a5610;
        }

        .card .emoji {
            font-size: 34px;
            margin-bottom: 10px;
        }

        .card h3 {
            color: #102a56;
            margin-bottom: 10px;
        }

        .about {
            background: white;
        }

        .about-content {
            max-width: 850px;
            margin: auto;
            text-align: center;
        }

        .about-content p {
            margin: 15px 0;
        }

        .benefits {
            list-style: none;
            max-width: 700px;
            margin: 25px auto 0;
            text-align: left;
        }

        .benefits li {
            padding: 9px 0;
        }

        .benefits li::before {
            content: "✓ ";
            color: #168653;
            font-weight: bold;
        }

        .contact {
            background: #eaf1fb;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 28px;
            max-width: 950px;
            margin: auto;
        }

        .contact-box {
            background: white;
            padding: 28px;
            border-radius: 12px;
        }

        .contact-box p {
            margin: 12px 0;
            overflow-wrap: anywhere;
        }

        form {
            display: grid;
            gap: 14px;
        }

        input, select, textarea {
            width: 100%;
            padding: 13px;
            border: 1px solid #cbd5e1;
            border-radius: 7px;
            font: inherit;
        }

        textarea {
            min-height: 110px;
            resize: vertical;
        }

        footer {
            background: #102a56;
            color: white;
            text-align: center;
            padding: 25px 7%;
        }

        footer a {
            color: #ffd166;
        }

        .mobile-bar {
            display: none;
        }

        @media (max-width: 650px) {
            header {
                justify-content: center;
                text-align: center;
            }

            nav {
                justify-content: center;
            }

            .hero {
                padding: 65px 6%;
            }

            .stats {
                grid-template-columns: 1fr;
                margin-top: 20px;
            }

            section {
                padding: 45px 6%;
            }

            .section-title {
                font-size: 27px;
            }

            body {
                padding-bottom: 65px;
            }

            .mobile-bar {
                display: flex;
                position: fixed;
                bottom: 0;
                left: 0;
                width: 100%;
                z-index: 10;
                background: white;
                padding: 8px;
                box-shadow: 0 -3px 15px #00000015;
                gap: 8px;
            }

            .mobile-bar a {
                flex: 1;
                text-align: center;
                margin: 0;
                padding: 11px 5px;
            }
        }
    </style>
</head>

<body>

<header>
    <h2>Gupta Home Tuition</h2>
    <nav>
        <a href="#home">Home</a>
        <a href="#classes">Classes</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<main>
    <section class="hero" id="home">
        <h1>Learn Mathematics with Confidence</h1>
        <p>
            Personal guidance and clear concepts for school and college
            mathematics students in Jabalpur, Madhya Pradesh.
        </p>
        <a class="btn btn-yellow" href="#classes">Explore Classes</a>
        <a class="btn btn-green"
           href="https://wa.me/919165774287"
           target="_blank" rel="noopener">
            Enquire on WhatsApp
        </a>
    </section>

    <div class="stats">
        <div class="stat">
            <h3>22+</h3>
            <p>Years of Teaching Experience</p>
        </div>
        <div class="stat">
            <h3>600+</h3>
            <p>Students Taught</p>
        </div>
        <div class="stat">
            <h3>8–12</h3>
            <p>School Classes Covered</p>
        </div>
    </div>

    <section id="classes">
        <h2 class="section-title">Our Mathematics Classes</h2>
        <p class="section-subtitle">
            Mathematics learning tailored to each student's academic level.
        </p>

        <div class="cards">
            <div class="card">
                <div class="emoji">📘</div>
                <h3>Classes 8–10</h3>
                <p>Build strong fundamentals, improve problem-solving,
                   and prepare for school examinations.</p>
            </div>

            <div class="card">
                <div class="emoji">📚</div>
                <h3>Classes 11–12</h3>
                <p>Understand important concepts, practise questions,
                   and prepare for board examinations.</p>
            </div>

            <div class="card">
                <div class="emoji">🎓</div>
                <h3>College Mathematics</h3>
                <p>Mathematics guidance for students in the first
                   two years of college.</p>
            </div>
        </div>
    </section>

    <section class="about" id="about">
        <div class="about-content">
            <h2 class="section-title">About Gupta Home Tuition</h2>
            <p>
                Welcome to Gupta Home Tuition, where students learn
                mathematics through clear explanations, regular practice,
                and individual attention.
            </p>
            <p>
                With 22 years of teaching experience and over 600 students
                taught, our aim is to help students develop confidence
                and a strong understanding of mathematics.
            </p>

            <ul class="benefits">
                <li>22 years of teaching experience</li>
                <li>Mathematics tuition for Classes 8 to 12</li>
                <li>Guidance for the first two years of college</li>
                <li>Concept-based learning and practice</li>
                <li>Support for school and college examinations</li>
            </ul>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2 class="section-title">Contact Us</h2>
        <p class="section-subtitle">
            Have a question or want to enquire about tuition?
            Send a message through WhatsApp.
        </p>

        <div class="contact-grid">
            <div class="contact-box">
                <h3>Tuition Information</h3>
                <p><strong>Institute:</strong> Gupta Home Tuition</p>
                <p><strong>Location:</strong> Jabalpur, Madhya Pradesh</p>
                <p><strong>Phone:</strong> +91 91657 74287</p>

                <a class="btn btn-blue"
                   href="tel:+919165774287">
                    Call Now
                </a>

                <a class="btn btn-green"
                   href="https://wa.me/919165774287"
                   target="_blank" rel="noopener">
                    WhatsApp
                </a>
            </div>

            <div class="contact-box">
                <h3>Enquiry Form</h3>

                <form id="enquiryForm">
                    <input type="text" id="studentName"
                           placeholder="Student's name" required>

                    <input type="tel" id="phone"
                           placeholder="Your phone number"
                           pattern="[0-9+\s-]{10,15}" required>

                    <select id="studentClass" required>
                        <option value="">Select class</option>
                        <option>Class 8</option>
                        <option>Class 9</option>
                        <option>Class 10</option>
                        <option>Class 11</option>
                        <option>Class 12</option>
                        <option>College Year 1</option>
                        <option>College Year 2</option>
                    </select>

                    <textarea id="message"
                              placeholder="Write your enquiry (optional)"></textarea>

                    <button class="btn btn-green" type="submit">
                        Send Enquiry on WhatsApp
                    </button>
                </form>
            </div>
        </div>
    </section>
</main>

<footer>
    <p><strong>Gupta Home Tuition</strong></p>
    <p>Mathematics Tuition | Jabalpur, Madhya Pradesh</p>
    <p>Phone: +91 91657 74287</p>
    <p>© <span id="year"></span> Gupta Home Tuition. All rights reserved.</p>
</footer>

<div class="mobile-bar">
    <a class="btn btn-blue" href="tel:+919165774287">📞 Call</a>
    <a class="btn btn-green"
       href="https://wa.me/919165774287"
       target="_blank" rel="noopener">WhatsApp</a>
</div>

<script>
    document.getElementById("year").textContent =
        new Date().getFullYear();

    document.getElementById("enquiryForm").addEventListener(
        "submit",
        function(event) {
            event.preventDefault();

            const name = document.getElementById("studentName").value.trim();
            const phone = document.getElementById("phone").value.trim();
            const studentClass =
                document.getElementById("studentClass").value;
            const message =
                document.getElementById("message").value.trim();

            const text =
                "Hello Gupta Home Tuition!%0A%0A" +
                "Student Name: " + encodeURIComponent(name) + "%0A" +
                "Phone: " + encodeURIComponent(phone) + "%0A" +
                "Class: " + encodeURIComponent(studentClass) + "%0A" +
                "Enquiry: " + encodeURIComponent(message);

            window.open(
                "https://wa.me/919165774287?text=" + text,
                "_blank"
            );
        }
    );
</script>

</body>
</html>
