<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayoub Elabbadi - Profil</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
            color: #333;
        }
        
        .container {
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 2.5em;
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 20px;
        }
        
        .badges {
            margin: 20px 0;
        }
        
        .badges img {
            margin-right: 10px;
        }
        
        hr {
            border: none;
            height: 2px;
            background: linear-gradient(to right, #3498db, #2ecc71);
            margin: 30px 0;
        }
        
        h2 {
            color: #2c3e50;
            font-size: 1.5em;
            margin-top: 30px;
            margin-bottom: 15px;
        }
        
        h3 {
            color: #34495e;
            font-size: 1.2em;
            margin-top: 20px;
            margin-bottom: 10px;
        }
        
        .about-section {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
        }
        
        .about-section p {
            margin: 8px 0;
        }
        
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .skill-category {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #3498db;
        }
        
        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }
        
        .tag {
            background: #e3f2fd;
            color: #1976d2;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 0.9em;
            font-family: 'Courier New', monospace;
        }
        
        .experience-item, .project-item {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin: 15px 0;
            border-left: 4px solid #2ecc71;
        }
        
        .experience-item h4, .project-item h4 {
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .soft-skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .soft-skill {
            background: #fff3e0;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            border: 2px solid #ff9800;
        }
        
        .github-stats {
            text-align: center;
            margin: 30px 0;
        }
        
        .github-stats img {
            margin: 10px;
            border-radius: 8px;
        }
        
        .contact-section {
            background: #e8f5e8;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            margin: 10px 0;
        }
        
        .contact-item a {
            color: #2c3e50;
            text-decoration: none;
            margin-left: 10px;
        }
        
        .contact-item a:hover {
            color: #3498db;
        }
        
        .quote {
            text-align: center;
            font-style: italic;
            font-size: 1.1em;
            color: #7f8c8d;
            margin: 30px 0;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 8px;
            border-left: 4px solid #9b59b6;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .skills {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>👋 Salut, je suis Ayoub Elabbadi</h1>
        <p class="subtitle">🎓 Étudiant en 5ᵉ année de cycle d'ingénieur en Génie Informatique | Passionné par le développement web, l'IA et les technologies innovantes</p>
        
        <div class="badges">
            <img src="https://img.shields.io/github/followers/ayoubelabbadi?style=social" alt="GitHub followers">
            <a href="mailto:elabbadi-ayo@upf.ac.ma">
                <img src="https://img.shields.io/badge/Email-elabbadi--ayo%40upf.ac.ma-red?style=flat-square&logo=gmail&logoColor=white" alt="Email">
            </a>
            <a href="https://www.linkedin.com/in/ayoubelabbadi">
                <img src="https://img.shields.io/badge/LinkedIn-Ayoub%20Elabbadi-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
            </a>
        </div>

        <hr>

        <h2>🧑‍💻 À propos de moi</h2>
        <div class="about-section">
            <p>🎓 Étudiant en dernière année de cycle d'ingénieur à l'Université Privée de Fès</p>
            <p>💼 Spécialisation en <strong>Développement Web</strong></p>
            <p>🧾 Projets : applications web, systèmes de gestion, plateformes e-learning, solutions IA</p>
            <p>🚀 Objectif : contribuer à des projets à fort impact technologique et innover en développement logiciel</p>
            <p>📫 Contact : <strong>elabbadi-ayo@upf.ac.ma</strong> | <strong>+212 771 844 780</strong></p>
        </div>

        <hr>

        <h2>🛠 Compétences Techniques</h2>
        <div class="skills">
            <div class="skill-category">
                <h3>💻 Langages de Programmation</h3>
                <div class="skill-tags">
                    <span class="tag">HTML</span>
                    <span class="tag">CSS</span>
                    <span class="tag">JavaScript</span>
                    <span class="tag">PHP</span>
                    <span class="tag">Python</span>
                    <span class="tag">Java</span>
                    <span class="tag">C#</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h3>🌐 Frameworks & Bibliothèques</h3>
                <div class="skill-tags">
                    <span class="tag">Laravel</span>
                    <span class="tag">React</span>
                    <span class="tag">Node.js</span>
                    <span class="tag">Express.js</span>
                    <span class="tag">Angular</span>
                    <span class="tag">Bootstrap</span>
                    <span class="tag">Spring Boot</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h3>🗃️ Bases de Données</h3>
                <div class="skill-tags">
                    <span class="tag">MySQL</span>
                    <span class="tag">MongoDB</span>
                    <span class="tag">SQL Server</span>
                    <span class="tag">SQL</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h3>⚙️ Outils & DevOps</h3>
                <div class="skill-tags">
                    <span class="tag">Git</span>
                    <span class="tag">Docker</span>
                    <span class="tag">Kubernetes</span>
                    <span class="tag">Postman</span>
                    <span class="tag">VS Code</span>
                    <span class="tag">IntelliJ IDEA</span>
                    <span class="tag">Android Studio</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h3>📊 Méthodes & Modélisation</h3>
                <div class="skill-tags">
                    <span class="tag">UML</span>
                    <span class="tag">Merise</span>
                    <span class="tag">Scrum</span>
                    <span class="tag">Agile</span>
                </div>
            </div>
        </div>

        <hr>

        <h2>💼 Expériences Professionnelles</h2>
        <div class="experience-item">
            <h4>USIM (120h) — Développement Web Full Stack</h4>
            <p>• Réalisation d'une application web de gestion des ressources humaines</p>
        </div>
        
        <div class="experience-item">
            <h4>ONDA (150h) — Développement Web Full Stack</h4>
            <p>• Développement d'une application web de gestion de maintenance aéroportuaire</p>
        </div>

        <hr>

        <h2>🚀 Projets Réalisés</h2>
        <div class="project-item">
            <p>🏫 <strong>Plateforme E-learning</strong> (Laravel + MySQL)</p>
        </div>
        <div class="project-item">
            <p>📊 <strong>Application de gestion des commandes</strong> (React + Node.js + MongoDB)</p>
        </div>
        <div class="project-item">
            <p>🤖 <strong>Système d'analyse de données</strong> (Python + Pandas)</p>
        </div>

        <hr>

        <h2>🤝 Compétences Transversales</h2>
        <div class="soft-skills">
            <div class="soft-skill">Esprit d'équipe</div>
            <div class="soft-skill">Rigueur & autonomie</div>
            <div class="soft-skill">Capacité d'analyse</div>
            <div class="soft-skill">Communication efficace</div>
        </div>

        <hr>

        <h2>📈 Statistiques GitHub</h2>
        <div class="github-stats">
            <img src="https://github-readme-stats.vercel.app/api?username=ayoubelabbadi&show_icons=true&theme=default" alt="Ayoub's GitHub Stats">
            <br>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayoubelabbadi&layout=compact" alt="Top Languages">
        </div>

        <hr>

        <h2>☕ Contact & Réseaux</h2>
        <div class="contact-section">
            <div class="contact-item">
                <span>📧</span>
                <a href="mailto:elabbadi-ayo@upf.ac.ma"><strong>Email</strong> : elabbadi-ayo@upf.ac.ma</a>
            </div>
            <div class="contact-item">
                <span>📱</span>
                <span><strong>Téléphone</strong> : +212 771 844 780</span>
            </div>
            <div class="contact-item">
                <span>💼</span>
                <a href="https://www.linkedin.com/in/ayoubelabbadi"><strong>LinkedIn</strong> : Ayoub Elabbadi</a>
            </div>
        </div>

        <hr>

        <div class="quote">
            📌 <em>"Le développement n'est pas seulement du code, c'est une vision transformée en réalité."</em>
        </div>
    </div>
</body>
</html>
