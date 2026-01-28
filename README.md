<!DOCTYPE html>
<html>
<head>
    <style>
        /* Smooth scrolling for navigation links */
        html { scroll-behavior: smooth; }
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 0; }
        .content-container { padding: 20px; max-width: 900px; margin: auto; }
        /* Add space at the top so fixed header doesn't cover content */
        .main-body { padding-top: 120px; } 
        summary { cursor: pointer; font-size: 1.1em; margin-top: 10px; }
    </style>
</head>
<body>

<div style="position: fixed; top: 0; left: 0; width: 100%; background-color: #ffffff; z-index: 1000; padding: 10px 0; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
    <div style="display: flex; gap: 8px; justify-content: center; flex-wrap: wrap; padding: 0 10px;">
        <a href="#contact" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Contact</a>
        <a href="#education" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Education</a>
        <a href="#work-experience" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Work</a>
        <a href="#organizational-experience" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Leadership</a>
        <a href="#achievements" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Awards</a>
        <a href="#projects" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Projects</a>
        <a href="#certifications" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Certificates</a>
        <a href="#technical-skills" style="text-decoration: none; padding: 8px 12px; background-color: #6c757d; color: white; border-radius: 5px; font-size: 13px;">Skills</a>
    </div>
</div>

<div class="main-body content-container">

    <section id="contact">
        <h2>Contact</h2>
        <ul>
            <li><strong>Email:</strong> <a href="mailto:kbasar.bq@gmail.com">kbasar.bq@gmail.com</a></li>
            <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/md-khairul-basar-b19282247/">Md. Khairul Basar</a></li>
            <li><strong>WhatsApp:</strong> <a href="https://wa.me/+8801822887922/">+880 1822 887922</a></li>
        </ul>
    </section>

    <hr>

    <section id="education">
        <h2>Education</h2>
        <ul>
            <li><strong>B.Sc., Industrial & Production Engineering (IPE)</strong><br>
                Shahjalal University of Science and Technology (SUST)<br>
                (Feb 2020 - Aug 2025) | CGPA: <strong>3.45/4.00</strong> (Up to 7th sem)</li>
            <li><strong>HSC</strong>, Sunflower School and College, Saidpur | GPA: 4.92/5.00</li>
        </ul>
    </section>

    <hr>

    <section id="work-experience">
        <h2>Work Experience</h2>
        <details>
            <summary><strong>Internship — Walton Hi-Tech Industries PLC (May 2025)</strong></summary>
            <ul>
                <li>Gained hands-on experience in the Refrigerator Manufacturing Unit.</li>
                <li>Worked on VSM, SMV, SAM, Line balancing, 5S, Kanban, and OEE.</li>
            </ul>
        </details>
        <details>
            <summary><strong>Remote Employee @ Industrial 3D Solutions (Dec 2024 - June 2025)</strong></summary>
            <ul>
                <li>Created custom Excel tools and automated VBA functions.</li>
                <li>Coordinated laboratory product supply to universities.</li>
            </ul>
        </details>
    </section>

    <hr>

    <section id="organizational-experience">
        <h2>Organizational Experience</h2>
        <details>
            <summary><strong>Leader, Cultural Team, IKSS (2024 - 2025)</strong></summary>
            <p>Led event planning and execution, fostering teamwork and engagement.</p>
        </details>
        <details>
            <summary><strong>Executive Member, OBAT Canada Saidpur Branch (2020 - 2021)</strong></summary>
            <p>Developed professional communication skills and executed multiple programs.</p>
        </details>
    </section>

    <hr>

    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <li>Awarded a 60% scholarship for the <strong>ISCEA Prize Case Competition 2024</strong></li>
            <li>Finalist in <strong>IPE Case Quest 1.0</strong></li>
        </ul>
    </section>

    <hr>

    <section id="projects">
        <h2>Projects</h2>
        <details>
            <summary><strong>Pre-Assembly Line Analysis (Walton Hi-Tech)</strong></summary>
            <ul>
                <li>Conducted Time Study and Motion Analysis.</li>
                <li>Improved line efficiency using line balancing techniques.</li>
            </ul>
        </details>
        <details>
            <summary><strong>ML for Task Prediction & Optimization (Gurobi)</strong></summary>
            <ul>
                <li>Developed ML models to estimate task times.</li>
                <li>Optimized workflow using Gurobi Python API.</li>
            </ul>
        </details>
        <details>
            <summary><strong>Traffic Simulation at LamaBazar Intersection</strong></summary>
            <ul>
                <li>Arena simulation model for traffic optimization.</li>
                <li>Proposed lanes reduced waiting time by 50–60%.</li>
            </ul>
        </details>
    </section>

    <hr>

    <section id="certifications">
        <h2>Certifications</h2>
        <details>
            <summary><strong>Excel/VBA for Creative Problem Solving</strong> (CU Boulder)</summary>
            <p>Specialization covering UDFs, iteration, and user forms.</p>
        </details>
        <details>
            <summary><strong>Six Sigma White Belt</strong> (CSSC)</summary>
            <p>Demonstrated proficiency in Six Sigma curriculum. Cert: kWGBvKBpyw</p>
        </details>
    </section>

    <hr>

    <section id="technical-skills">
        <h2>Technical Skills</h2>
        <ul>
            <li><strong>Data Science:</strong> Python (NumPy, Pandas, Scikit-learn, PyTorch)</li>
            <li><strong>Analytics:</strong> Excel VBA, Power BI, Tableau</li>
            <li><strong>Modeling:</strong> Arena Simulation, AutoCAD</li>
        </ul>
    </section>

    <hr>

    <section id="industrial-training">
        <h2>Industrial Training</h2>
        <ul>
            <li><strong>BITAC, Dhaka:</strong> Manufacturing processes (12 days)</li>
            <li><strong>Khadim Ceramics:</strong> Industrial ceramic processes (1 day)</li>
        </ul>
    </section>

    <hr>

    <section id="interests">
        <h2>Interests</h2>
        <p>Poetry, Chess, Reading, Travelling</p>
    </section>

</div>

</body>
</html>
