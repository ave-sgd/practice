<header>
<div>
<h1>Мирзаева Согдиана Руслановна</h1>
<p>Специалист по веб-разработке и дизайну</p>
</div>
</header><nav>
<div>
<ul>
<li><a href="#about">О профессии</a></li>
<li><a href="#skills">Навыки</a></li>
<li><a href="#contact">Контакты</a></li>
</ul>
</div>
</nav>
<section>
<div>
<h2>О профессии</h2>
<p>Веб-разработка и дизайн &mdash; это сфера, где технические навыки встречаются с творчеством. Я создаю современные, интуитивно понятные интерфейсы, уделяя внимание как функциональности, так и эстетике.</p>
<p>Моя цель &mdash; делать digital-продукты, которые решают задачи пользователей и при этом выглядят стильно.</p>
</div>
</section>
<section>
<div>
<h2>Мои навыки</h2>
<div>
<div>
<h3>Веб-разработка</h3>
<p>HTML5, CSS3, JavaScript, адаптивная верстка</p>
</div>
<div>
<h3>Веб-дизайн</h3>
<p>UI/UX проектирование, создание макетов, работа с Figma</p>
</div>
<div>
<div>
<h2>Контакты</h2>
<div>
<p>l.seydoux@yandex.ru</p>
<p>+7 (XXX) XXX-XX-XX</p>
</div>
</div>
</div>
</div>
</div>
</section>
<footer>
<div>
<p>&copy; 2025 Мирзаева С.Р. | Веб-разработчик и дизайнер</p>
</div>
</footer>

/* Общие стили */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
    background-color: #f8fafc;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
}

/* Цветовая схема */
:root {
    --primary-blue: #1e3a8a;
    --secondary-blue: #3b82f6;
    --light-blue: #93c5fd;
    --white: #ffffff;
}

/* Шапка */
header {
    background: linear-gradient(135deg, var(--primary-blue), var(--secondary-blue));
    color: var(--white);
    text-align: center;
    padding: 80px 0;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 15px;
    font-weight: 700;
}

header p {
    font-size: 1.3rem;
    opacity: 0.9;
}

/* Навигация */
nav {
    background: var(--primary-blue);
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

nav ul {
    display: flex;
    list-style: none;
    justify-content: center;
    padding: 15px 0;
}

nav li {
    margin: 0 20px;
}

nav a {
    color: var(--white);
    text-decoration: none;
    font-weight: 500;
    font-size: 1.1rem;
    padding: 8px 0;
    position: relative;
    transition: 0.3s;
}

nav a:after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: 0;
    left: 0;
    background-color: var(--light-blue);
    transition: width 0.3s;
}

nav a:hover:after {
    width: 100%;
}

/* Секции */
.section {
    padding: 80px 0;
}

.section h2 {
    text-align: center;
    margin-bottom: 50px;
    font-size: 2.2rem;
    color: var(--primary-blue);
    position: relative;
}

.section h2:after {
    content: '';
    display: block;
    width: 80px;
    height: 3px;
    background: var(--secondary-blue);
    margin: 15px auto 0;
}

/* Навыки */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

.skill {
    text-align: center;
    padding: 40px 30px;
    background: var(--white);
    border-radius: 8px;
    transition: all 0.3s ease;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
    border: 1px solid rgba(59, 130, 246, 0.2);
}

.skill:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(59, 130, 246, 0.1);
}

.skill i {
    font-size: 3.5rem;
    color: var(--secondary-blue);
    margin-bottom: 25px;
}

.skill h3 {
    font-size: 1.4rem;
    margin-bottom: 15px;
    color: var(--primary-blue);
}

.skill p {
    color: #64748b;
}

/* Контакты */
.contact-info {
    text-align: center;
    margin-bottom: 50px;
}

.contact-info p {
    margin: 15px 0;
    font-size: 1.2rem;
    color: var(--primary-blue);
}

.contact-info i {
    margin-right: 12px;
    color: var(--secondary-blue);
    width: 20px;
}

.social-links {
    margin-top: 30px;
}

.social-links a {
    color: var(--primary-blue);
    font-size: 1.8rem;
    margin: 0 15px;
    transition: 0.3s;
    display: inline-block;
}

.social-links a:hover {
    color: var(--secondary-blue);
    transform: translateY(-5px);
}

.contact-form {
    max-width: 600px;
    margin: 0 auto;
    background: var(--white);
    padding: 40px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
    border: 1px solid rgba(59, 130, 246, 0.2);
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 15px;
    margin-bottom: 20px;
    border: 1px solid rgba(59, 130, 246, 0.3);
    border-radius: 6px;
    font-size: 1rem;
    transition: 0.3s;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--secondary-blue);
    box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2);
}

.contact-form textarea {
    height: 150px;
    resize: vertical;
}

.contact-form button {
    background: var(--secondary-blue);
    color: var(--white);
    border: none;
    padding: 15px 30px;
    font-size: 1.1rem;
    cursor: pointer;
    border-radius: 6px;
    transition: 0.3s;
    width: 100%;
    font-weight: 500;
}

.contact-form button:hover {
    background: var(--primary-blue);
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(30, 58, 138, 0.2);
}

/* Подвал */
footer {
    background: var(--primary-blue);
    color: var(--white);
    text-align: center;
    padding: 25px 0;
    font-size: 1rem;
}

/* Адаптивность */
@media (max-width: 768px) {
    header {
        padding: 60px 0;
    }
    
    header h1 {
        font-size: 2rem;
    }
    
    header p {
        font-size: 1.1rem;
    }
    
    nav ul {
        flex-direction: column;
        align-items: center;
        padding: 10px 0;
    }
    
    nav li {
        margin: 8px 0;
    }
    
    .section {
        padding: 60px 0;
    }
    
    .skills-grid {
        grid-template-columns: 1fr;
    }
    
    .contact-form {
        padding: 30px 20px;
    }
}
