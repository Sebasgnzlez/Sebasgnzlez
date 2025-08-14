<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sebastián González Sevillano - Full Stack Developer | Portfolio Profesional</title>
    
    <!-- SEO Meta Tags -->
    <meta name="description" content="Portfolio profesional de Sebastián González Sevillano, Full Stack Developer especializado en Java, Flutter, C#, y desarrollo web. Experiencia en desarrollo multiplataforma y soluciones innovadoras.">
    <meta name="keywords" content="Sebastián González Sevillano, Full Stack Developer, Desarrollo Web, Flutter, Java, C#, PHP, SQL, HTML5, CSS3, JavaScript, Desarrollo Multiplataforma">
    <meta name="author" content="Sebastián González Sevillano">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:type" content="website">
    <meta property="og:title" content="Sebastián González Sevillano - Full Stack Developer">
    <meta property="og:description" content="Portfolio profesional de Sebastián González Sevillano, Full Stack Developer especializado en desarrollo multiplataforma y soluciones web innovadoras.">
    <meta property="og:image" content="foto.jpg">
    <meta property="og:url" content="https://sebasgnzlez.dev">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@sebasgnzlezz">
    <meta name="twitter:title" content="Sebastián González Sevillano - Full Stack Developer">
    <meta name="twitter:description" content="Portfolio profesional de Sebastián González Sevillano, Full Stack Developer especializado en desarrollo multiplataforma y soluciones web innovadoras.">
    <meta name="twitter:image" content="foto.jpg">
    
    <!-- Favicon -->
    <link rel="icon" type="image/png" href="favicon.ico">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://sebasgnzlez.dev">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    
    <!-- Structured Data / Schema.org -->
    <script type="application/ld+json">
    {
        "@context": "http://schema.org",
        "@type": "Person",
        "name": "Sebastián González Sevillano",
        "jobTitle": "Full Stack Developer",
        "image": "foto.jpg",
        "url": "https://sebasgnzlez.dev",
        "sameAs": [
            "https://www.linkedin.com/in/sebasgnzlez",
            "https://x.com/sebasgnzlezz"
        ],
        "skills": [
            "Java",
            "C++",
            "C#",
            "Kotlin",
            "Flutter",
            "PHP",
            "SQL",
            "HTML5",
            "CSS3",
            "JavaScript"
        ]
    }
    </script>
    
    <!-- Preload Critical Resources -->
    <link rel="preload" href="foto.jpg" as="image">
    <link rel="preload" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" as="style">
    
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }

        /* Header styles */
        .profile-header {
            display: flex;
            align-items: center;
            gap: 2rem;
            padding: 2rem;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #0366d6;
        }

        .profile-info h1 {
            color: #2f363d;
            margin-bottom: 0.5rem;
        }

        .profile-info h2 {
            color: #586069;
            font-weight: 400;
        }

        /* Section styles */
        section {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        h2.section-title {
            color: #0366d6;
            margin-bottom: 1.5rem;
            border-bottom: 2px solid #e1e4e8;
            padding-bottom: 0.5rem;
        }

        /* Skills section */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .skill-badge {
            background-color: #e1e4e8;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            transition: transform 0.2s;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .skill-badge i {
            font-size: 1.1rem;
        }

        .skill-badge:hover {
            transform: translateY(-2px);
            background-color: #0366d6;
            color: white;
        }

        /* Interests section */
        .interests-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .interest-card {
            background-color: #f8f9fa;
            border-radius: 8px;
            padding: 1.5rem;
            text-align: center;
            transition: transform 0.2s;
        }

        .interest-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .interest-icon {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .interest-title {
            color: #0366d6;
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        .interest-description {
            color: #586069;
            font-size: 0.9rem;
        }

        /* Stats section */
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }

        .stats-card {
            max-width: 100%;
            height: auto;
        }

        /* Footer styles */
        footer {
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 2rem;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .contact-link {
            color: #0366d6;
            text-decoration: none;
            transition: color 0.2s;
        }

        .contact-link:hover {
            color: #044289;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .profile-header {
                flex-direction: column;
                text-align: center;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }

            .stats-container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <main itemscope itemtype="http://schema.org/Person">
    <!-- Header Section -->
    <header class="profile-header" role="banner">
        <img src="foto.jpg" 
             alt="Sebastián González Sevillano - Full Stack Developer" 
             class="profile-image"
             itemprop="image"
             loading="eager"
             width="150"
             height="150">
        <div class="profile-info">
            <h1 itemprop="name">Sebastián González Sevillano</h1>
            <h2 itemprop="jobTitle">Full Stack Developer | Apasionado por la tecnología y la innovación</h2>
        </div>
    </header>

    <!-- About Section -->
    <section aria-labelledby="about-heading">
        <h2 id="about-heading" class="section-title">Sobre mí</h2>
        <p itemprop="description">
            Desarrollador de software con formación en sistemas microinformáticos y desarrollo de aplicaciones
            multiplataforma. Apasionado por la tecnología, el aprendizaje continuo y la resolución eficiente de problemas.
            Me adapto con facilidad a nuevos entornos y disfruto trabajando en equipo para crear soluciones funcionales,
            escalables y de calidad. Comprometido, proactivo y orientado a resultados, con el objetivo de aportar valor real
            en cada proyecto.
        </p>
    </section>

    <!-- Skills Section -->
    <section>
        <h2 class="section-title">Skills</h2>
        <!-- Programming Languages -->
        <div class="skills-container">
            <div class="skill-badge">
                <i class="fab fa-java"></i> Java
            </div>
            <div class="skill-badge">
                <i class="fab fa-cuttlefish"></i> C++
            </div>
            <div class="skill-badge">
                <i class="fab fa-microsoft"></i> C#
            </div>
            <div class="skill-badge">
                <i class="fab fa-android"></i> Kotlin
            </div>
            <div class="skill-badge">
                <i class="fas fa-mobile-alt"></i> Flutter
            </div>
            <div class="skill-badge">
                <i class="fab fa-php"></i> PHP
            </div>
            <div class="skill-badge">
                <i class="fas fa-database"></i> SQL
            </div>
            <div class="skill-badge">
                <i class="fab fa-html5"></i> HTML5
            </div>
            <div class="skill-badge">
                <i class="fab fa-css3-alt"></i> CSS3
            </div>
            <div class="skill-badge">
                <i class="fab fa-js"></i> JavaScript
            </div>
        </div>
    </section>

    <!-- Interests & Professional Goals Section -->
    <section>
        <h2 class="section-title">Intereses y Objetivos Profesionales</h2>
        <div class="interests-grid">
            <div class="interest-card">
                <div class="interest-icon"><i class="fas fa-rocket"></i></div>
                <h3 class="interest-title">Objetivos Profesionales</h3>
                <p class="interest-description">
                    Aspiro a especializarme en desarrollo Full Stack y arquitectura de software.
                    Comprometido con la excelencia técnica y las mejores prácticas de desarrollo.
                </p>
            </div>
            <div class="interest-card">
                <div class="interest-icon"><i class="fas fa-code-branch"></i></div>
                <h3 class="interest-title">Áreas de Especialización</h3>
                <p class="interest-description">
                    Desarrollo multiplataforma con Flutter, aplicaciones web modernas y
                    sistemas backend robustos. Experiencia en integración de APIs y bases de datos.
                </p>
            </div>
            <div class="interest-card">
                <div class="interest-icon"><i class="fas fa-brain"></i></div>
                <h3 class="interest-title">Intereses Tecnológicos</h3>
                <p class="interest-description">
                    Apasionado por las nuevas tecnologías, la inteligencia artificial y 
                    el desarrollo de soluciones innovadoras que impacten positivamente.
                </p>
            </div>
            <div class="interest-card">
                <div class="interest-icon"><i class="fas fa-users"></i></div>
                <h3 class="interest-title">Trabajo en Equipo</h3>
                <p class="interest-description">
                    Creo en la colaboración efectiva, la comunicación clara y el aprendizaje 
                    continuo como pilares fundamentales del desarrollo de software.
                </p>
            </div>
        </div>
    </section>

    <!-- Próximos Proyectos Section -->
    <section>
        <h2 class="section-title">Próximos Proyectos</h2>
        <div class="projects-grid">
            <div class="project-card">
                <div class="project-icon">
                    <i class="fas fa-rocket"></i>
                </div>
                <h3 class="project-title">En Desarrollo</h3>
                <p class="project-tech">Portfolio Personal</p>
                <p class="project-description">
                    Actualmente trabajando en mi portfolio personal para mostrar 
                    mis habilidades y futuros proyectos. Utilizando tecnologías 
                    modernas y mejores prácticas de desarrollo.
                </p>
            </div>
            <div class="project-card">
                <div class="project-icon">
                    <i class="fas fa-lightbulb"></i>
                </div>
                <h3 class="project-title">Próximamente</h3>
                <p class="project-tech">Aplicación Móvil con Flutter</p>
                <p class="project-description">
                    Planificando el desarrollo de una aplicación móvil 
                    multiplataforma utilizando Flutter y Firebase. Enfocada en 
                    proporcionar una experiencia de usuario excepcional.
                </p>
            </div>
            <div class="project-card">
                <div class="project-icon">
                    <i class="fas fa-code"></i>
                </div>
                <h3 class="project-title">Aprendizaje Continuo</h3>
                <p class="project-tech">Desarrollo Web Full Stack</p>
                <p class="project-description">
                    Profundizando en el desarrollo web moderno con JavaScript, 
                    frameworks actuales y buenas prácticas de desarrollo. 
                    Proximamente proyectos utilizando estas tecnologías.
                </p>
            </div>
        </div>
    </section>

    <style>
        /* Proyectos Destacados styles */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 1rem 0;
        }

        .project-card {
            background-color: #f8f9fa;
            border-radius: 10px;
            padding: 1.5rem;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .project-icon {
            font-size: 2rem;
            color: #0366d6;
            margin-bottom: 1rem;
        }

        .project-title {
            color: #24292e;
            font-size: 1.25rem;
            margin-bottom: 0.5rem;
        }

        .project-tech {
            color: #0366d6;
            font-size: 0.9rem;
            margin-bottom: 1rem;
            font-weight: 500;
        }

        .project-description {
            color: #586069;
            font-size: 0.95rem;
            line-height: 1.5;
        }
    </style>

    <!-- Footer / Contact Section -->
    <footer>
        <!-- TIP: Replace with your social links -->
        <a href="https://www.linkedin.com/in/sebasgnzlez" class="contact-link">💼 LinkedIn</a>
        <a href="https://x.com/sebasgnzlezz" class="contact-link">🐦 Twitter</a>
        <a href="#" class="contact-link" style="cursor: default; opacity: 0.7;">🌐 Portfolio (En desarrollo)</a>
    </footer>
</body>
</html>

