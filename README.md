<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Иванова Анастасия - Личная страница</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header Styles */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid white;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .tagline {
            font-size: 1.2em;
            opacity: 0.9;
        }

        /* Navigation */
        nav {
            background: #333;
            padding: 15px 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #667eea;
        }

        /* Section Styles */
        section {
            padding: 60px 0;
            background: white;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        h2 {
            color: #333;
            margin-bottom: 30px;
            text-align: center;
            font-size: 2em;
        }

        /* About Section */
        .about-content {
            display: flex;
            align-items: center;
            gap: 40px;
        }

        .about-text {
            flex: 1;
        }

        /* Skills Section */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .skill-category {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }

        .skill-category h3 {
            margin-bottom: 15px;
            color: #333;
        }

        .skill-category ul {
            list-style: none;
        }

        .skill-category li {
            margin-bottom: 8px;
            padding-left: 20px;
            position: relative;
        }

        .skill-category li:before {
            content: "▸";
            position: absolute;
            left: 0;
            color: #667eea;
        }

        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .project-card {
            background: #f8f9fa;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-image {
            height: 200px;
            background: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3em;
            color: #666;
        }

        .project-content {
            padding: 20px;
        }

        .project-links {
            margin-top: 15px;
        }

        .btn {
            display: inline-block;
            padding: 8px 16px;
            background: #667eea;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            margin-right: 10px;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #5a6fd8;
        }

        /* Contact Section */
        .contact-info {
            text-align: center;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .contact-links a {
            color: #333;
            text-decoration: none;
            transition: color 0.3s;
        }

        .contact-links a:hover {
            color: #667eea;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 40px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 10px 0;
            }

            .about-content {
                flex-direction: column;
                text-align: center;
            }

            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <!-- Замените src на ссылку на ваше реальное фото -->
            <img src="https://via.placeholder.com/150" alt="Мое фото" class="profile-img">
            <h1>Иван Петров</h1>
            <p class="tagline">Веб-разработчик | Python-программист</p>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">Обо мне</a></li>
                <li><a href="#skills">Навыки</a></li>
                <li><a href="#projects">Проекты</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Content -->
    <div class="container">
        <!-- About Section -->
        <section id="about">
            <h2>Обо мне</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Привет! Я веб-разработчик с passion к созданию красивых и функциональных веб-приложений. Имею опыт работы с современными технологиями и постоянно учусь новому.</p>
                    <br>
                    <p>В настоящее время специализируюсь на frontend-разработке, но также интересуюсь backend и мобильной разработкой. Люлю решать сложные задачи и создавать продукты, которые делают жизнь людей лучше.</p>
                    <br>
                    <p>В свободное время участвую в open-source проектах, читаю техническую литературу и занимаюсь спортом.</p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2>Мои навыки</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Frontend</h3>
                    <ul>
                        <li>HTML5/CSS3</li>
                        <li>JavaScript/TypeScript</li>
                        <li>React/Vue.js</li>
                        <li>Responsive Design</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Backend</h3>
                    <ul>
                        <li>Python/Django</li>
                        <li>Node.js/Express</li>
                        <li>REST API</li>
                        <li>Базы данных</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Инструменты</h3>
                    <ul>
                        <li>Git/GitHub</li>
                        <li>Docker</li>
                        <li>Webpack</li>
                        <li>VS Code</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>Мои проекты</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">📱</div>
                    <div class="project-content">
                        <h3>Мобильное приложение</h3>
                        <p>Приложение для управления задачами с синхронизацией в облаке.</p>
                        <div class="project-links">
                            <a href="#" class="btn">Демо</a>
                            <a href="#" class="btn">Код</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">🌐</div>
                    <div class="project-content">
                        <h3>Веб-платформа</h3>
                        <p>Социальная платформа для обмена знаниями между разработчиками.</p>
                        <div class="project-links">
                            <a href="#" class="btn">Демо</a>
                            <a href="#" class="btn">Код</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">🛠️</div>
                    <div class="project-content">
                        <h3>Библиотека компонентов</h3>
                        <p>UI-библиотека с reusable компонентами для React.</p>
                        <div class="project-links">
                            <a href="#" class="btn">Демо</a>
                            <a href="#" class="btn">Код</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Контакты</h2>
            <div class="contact-info">
                <p>Свяжитесь со мной для сотрудничества или просто поздоровайтесь!</p>
                <div class="contact-links">
                    <a href="mailto:your.email@example.com">📧 Email</a>
                    <a href="https://github.com/yourusername">💻 GitHub</a>
                    <a href="https://linkedin.com/in/yourprofile">💼 LinkedIn</a>
                    <a href="https://t.me/yourusername">✈️ Telegram</a>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© 2024 Иван Петров. Все права защищены.</p>
            <p>Сделано с ❤️ и GitHub Pages</p>
        </div>
    </footer>

    <script>
        // Плавная прокрутка для навигации
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
            });
        });

        // Анимация появления элементов при скролле
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Применяем анимацию к секциям
        document.querySelectorAll('section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(20px)';
            section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
            observer.observe(section);
        });
    </script>
</body>
</html>
