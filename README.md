<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV DJAFARALY SHANE - Développeur Front-End</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Georgia', serif;
            line-height: 1.5;
            color: #333;
        }
        
        .container {
            display: flex;
            max-width: 1400px;
            margin: 0 auto;
            min-height: 100vh;
        }
        
        .left-column {
            background-color: #384952;
            color: #fff;
            width: 334px;
            padding: 0;
            flex-shrink: 0;
        }
        
        .right-column {
            background-color: #f8f8f8;
            flex: 1;
            padding: 45px 55px;
        }
        
        .profile-section {
            text-align: center;
            padding: 40px 30px 35px;
        }
        
        .profile-photo {
            width: 190px;
            height: 190px;
            border-radius: 50%;
            background-color: #2a3740;
            margin: 0 auto 35px;
            overflow: hidden;
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="%23555"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>');
            background-size: 100px;
            background-position: center;
            background-repeat: no-repeat;
        }
        
        .name h1 {
            font-size: 26px;
            font-weight: 400;
            letter-spacing: 4px;
            margin-bottom: 12px;
            font-family: 'Georgia', serif;
        }
        
        .job-title {
            font-size: 13.5px;
            font-weight: 300;
            letter-spacing: 2px;
            line-height: 1.6;
        }
        
        .left-content {
            padding: 0 30px 40px;
        }
        
        .section {
            margin-bottom: 42px;
        }
        
        .section-title {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 22px;
            font-size: 14px;
            font-weight: 400;
            letter-spacing: 2.5px;
            text-transform: uppercase;
        }
        
        .section-icon {
            width: 26px;
            height: 26px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 16px;
            background-color: #4a5960;
            border-radius: 50%;
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: 13px;
            margin-bottom: 16px;
            font-size: 12.5px;
            line-height: 1.4;
        }
        
        .contact-icon {
            width: 34px;
            height: 34px;
            background-color: #4a5960;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            font-size: 15px;
        }
        
        .skill-item {
            margin-bottom: 20px;
        }
        
        .skill-name {
            font-size: 12.5px;
            margin-bottom: 9px;
            font-weight: 300;
        }
        
        .skill-bar {
            width: 100%;
            height: 5px;
            background-color: #2a3740;
            border-radius: 2.5px;
            overflow: hidden;
        }
        
        .skill-progress {
            height: 100%;
            background: linear-gradient(90deg, #689f38, #8bc34a);
            border-radius: 2.5px;
        }
        
        .atout-item {
            display: flex;
            align-items: flex-start;
            gap: 11px;
            margin-bottom: 17px;
            font-size: 12.5px;
            line-height: 1.5;
        }
        
        .check-icon {
            width: 26px;
            height: 26px;
            background-color: #689f38;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            margin-top: 1px;
        }
        
        .check-icon svg {
            width: 14px;
            height: 14px;
        }
        
        .language-section {
            display: flex;
            gap: 35px;
            margin-top: 18px;
        }
        
        .language-item {
            text-align: center;
            flex: 1;
        }
        
        .flag {
            width: 80px;
            height: 50px;
            margin: 0 auto 12px;
            border-radius: 3px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        
        .flag img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .language-name {
            font-size: 10px;
            text-transform: uppercase;
            letter-spacing: 0.8px;
            line-height: 1.5;
        }
        
        .right-section {
            margin-bottom: 50px;
        }
        
        .right-section-title {
            display: flex;
            align-items: center;
            gap: 18px;
            margin-bottom: 28px;
            font-size: 22px;
            font-weight: 400;
            letter-spacing: 3px;
            text-transform: uppercase;
        }
        
        .section-icon-right {
            width: 55px;
            height: 55px;
            background-color: #384952;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 26px;
            color: #fff;
            flex-shrink: 0;
        }
        
        .section-icon-right svg {
            width: 28px;
            height: 28px;
        }
        
        .experience-item {
            margin-bottom: 32px;
        }
        
        .exp-title {
            font-size: 15px;
            font-weight: 700;
            text-transform: uppercase;
            border-bottom: 2px solid #2a2a2a;
            padding-bottom: 6px;
            margin-bottom: 14px;
            display: inline-block;
        }
        
        .exp-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 14px;
            gap: 20px;
        }
        
        .company {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 13px;
            font-weight: 600;
        }
        
        .company-icon {
            font-size: 16px;
            color: #689f38;
        }
        
        .company-icon svg {
            width: 16px;
            height: 16px;
        }
        
        .date {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 12px;
            color: #555;
            white-space: nowrap;
        }
        
        .date-icon {
            font-size: 14px;
            color: #c62828;
        }
        
        .date-icon svg {
            width: 14px;
            height: 14px;
        }
        
        .project-name {
            font-weight: 700;
            text-decoration: underline;
            margin-bottom: 10px;
            font-size: 13px;
        }
        
        .description {
            font-size: 12.5px;
            line-height: 1.65;
            margin-bottom: 10px;
            text-align: justify;
        }
        
        .tech-stack {
            font-size: 12.5px;
            font-weight: 600;
            line-height: 1.5;
        }
        
        .experience-list {
            list-style: none;
            padding-left: 0;
        }
        
        .experience-list li {
            font-size: 12.5px;
            line-height: 1.65;
            margin-bottom: 8px;
            padding-left: 18px;
            position: relative;
            text-align: justify;
        }
        
        .experience-list li:before {
            content: "-";
            position: absolute;
            left: 0;
            font-weight: 600;
        }
        
        .formation-item {
            margin-bottom: 28px;
        }
        
        .formation-title {
            font-size: 14px;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .school {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 13px;
            font-weight: 600;
        }
        
        .school-name {
            font-style: italic;
            text-decoration: underline;
            margin-left: 26px;
            font-size: 12.5px;
        }
        
        .formation-details {
            margin-left: 26px;
            font-size: 12.5px;
            line-height: 1.65;
        }
        
        .formation-details > div {
            margin-bottom: 3px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-column">
            <div class="profile-section">
                <div class="profile-photo"></div>
                
                <div class="name">
                    <h1>DJAFARALY SHANE</h1>
                </div>
                <div class="job-title">DÉVELOPPEUR FRONT-END<br>CONFIRMÉ</div>
            </div>
            
            <div class="left-content">
                <div class="section">
                    <div class="section-title">
                        <span class="section-icon">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="white">
                                <path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/>
                            </svg>
                        </span>
                        CONTACTS
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg width="14" height="14" viewBox="0 0 24 24" fill="white">
                                <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
                            </svg>
                        </div>
                        <span>93120 La Courneuve</span>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg width="14" height="14" viewBox="0 0 24 24" fill="white">
                                <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
                            </svg>
                        </div>
                        <span>shane.djaf@gmail.com</span>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg width="14" height="14" viewBox="0 0 24 24" fill="white">
                                <path d="M20 6h-4V4c0-1.11-.89-2-2-2h-4c-1.11 0-2 .89-2 2v2H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2zm-6 0h-4V4h4v2z"/>
                            </svg>
                        </div>
                        <span></span>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg width="14" height="14" viewBox="0 0 24 24" fill="white">
                                <path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"/>
                            </svg>
                        </div>
                        <span>Disponible de suite</span>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg width="14" height="14" viewBox="0 0 24 24" fill="white">
                                <path d="M9 3L5 6.99h3V14h2V6.99h3L9 3zm7 14.01V10h-2v7.01h-3L15 21l4-3.99h-3z"/>
                            </svg>
                        </div>
                        <span>8 ans d'expérience professionnelle</span>
                    </div>
                </div>
                
                <div class="section">
                    <div class="section-title">
                        <span class="section-icon">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="white">
                                <path d="M9 16.2L4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4L9 16.2z"/>
                            </svg>
                        </span>
                        MES COMPÉTENCES
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">HTML - CSS - JavaScript</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">TypeScript</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">VueJS</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">ReactJS</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">NodeJS</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">PHP - SQL</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-name">Git - Gitlab - Jira - Figma</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 100%"></div>
                        </div>
                    </div>
                </div>
                
                <div class="section">
                    <div class="section-title">
                        <span class="section-icon">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="white">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>
                            </svg>
                        </span>
                        MES ATOUTS
                    </div>
                    <div class="atout-item">
                        <div class="check-icon">
                            <svg viewBox="0 0 24 24" fill="white">
                                <path d="M9 16.2L4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4L9 16.2z"/>
                            </svg>
                        </div>
                        <span>Adaptabilité, capacité à travailler sur des sujets divers</span>
                    </div>
                    <div class="atout-item">
                        <div class="check-icon">
                            <svg viewBox="0 0 24 24" fill="white">
                                <path d="M9 16.2L4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4L9 16.2z"/>
                            </svg>
                        </div>
                        <span>Compréhension des besoins utilisateurs<br>Création d'un cahier des charges</span>
                    </div>
                    <div class="atout-item">
                        <div class="check-icon">
                            <svg viewBox="0 0 24 24" fill="white">
                                <path d="M9 16.2L4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4L9 16.2z"/>
                            </svg>
                        </div>
                        <span>Méthode Agile</span>
                    </div>
                    <div class="atout-item">
                        <div class="check-icon">
                            <svg viewBox="0 0 24 24" fill="white">
                                <path d="M9 16.2L4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4L9 16.2z"/>
                            </svg>
                        </div>
                        <span>Curieux, rigoureux et organisé</span>
                    </div>
                </div>
                
                <div class="section">
                    <div class="section-title">
                        <span class="section-icon">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="white">
                                <path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zm6.93 6h-2.95c-.32-1.25-.78-2.45-1.38-3.56 1.84.63 3.37 1.91 4.33 3.56zM12 4.04c.83 1.2 1.48 2.53 1.91 3.96h-3.82c.43-1.43 1.08-2.76 1.91-3.96zM4.26 14C4.1 13.36 4 12.69 4 12s.1-1.36.26-2h3.38c-.08.66-.14 1.32-.14 2 0 .68.06 1.34.14 2H4.26zm.82 2h2.95c.32 1.25.78 2.45 1.38 3.56-1.84-.63-3.37-1.9-4.33-3.56zm2.95-8H5.08c.96-1.66 2.49-2.93 4.33-3.56C8.81 5.55 8.35 6.75 8.03 8zM12 19.96c-.83-1.2-1.48-2.53-1.91-3.96h3.82c-.43 1.43-1.08 2.76-1.91 3.96zM14.34 14H9.66c-.09-.66-.16-1.32-.16-2 0-.68.07-1.35.16-2h4.68c.09.65.16 1.32.16 2 0 .68-.07 1.34-.16 2zm.25 5.56c.6-1.11 1.06-2.31 1.38-3.56h2.95c-.96 1.65-2.49 2.93-4.33 3.56zM16.36 14c.08-.66.14-1.32.14-2 0-.68-.06-1.34-.14-2h3.38c.16.64.26 1.31.26 2s-.1 1.36-.26 2h-3.38z"/>
                            </svg>
                        </span>
                        LINGUISTIQUE
                    </div>
                    <div class="language-section">
                        <div class="language-item">
                            <div class="flag">
                                <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 60 30'%3E%3CclipPath id='a'%3E%3Cpath d='M0 0v30h60V0z'/%3E%3C/clipPath%3E%3CclipPath id='b'%3E%3Cpath d='M30 15h30v15zv15H0zH0V0zV0h30z'/%3E%3C/clipPath%3E%3Cg clip-path='url(%23a)'%3E%3Cpath d='M0 0v30h60V0z' fill='%23012169'/%3E%3Cpath d='M0 0l60 30m0-30L0 30' stroke='%23fff' stroke-width='6'/%3E%3Cpath d='M0 0l60 30m0-30L0 30' clip-path='url(%23b)' stroke='%23C8102E' stroke-width='4'/%3E%3Cpath d='M30 0v30M0 15h60' stroke='%23fff' stroke-width='10'/%3E%3Cpath d='M30 0v30M0 15h60' stroke='%23C8102E' stroke-width='6'/%3E%3C/g%3E%3C/svg%3E" alt="UK Flag">
                            </div>
                            <div class="language-name">Anglais<br>Débutant</div>
                        </div>
                        <div class="language-item">
                            <div class="flag">
                                <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'%3E%3Cpath fill='%23002395' d='M0 0h900v600H0z'/%3E%3Cpath fill='%23ED2939' d='M0 0h900L0 600z'/%3E%3Cpath fill='%23FFCE00' d='M0 0l900 600H0z'/%3E%3Cpath fill='%23002395' d='M0 600V0l900 600z'/%3E%3Cpath fill='%23ED2939' d='M450 300l-150 100 57-162L207 138h185L450 0l58 138h185L543 238l57 162z'/%3E%3C/svg%3E" alt="Reunion Flag">
                            </div>
                            <div class="language-name">Créole Réunionnais<br>Débutant</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="right-column">
            <div class="right-section">
                <div class="right-section-title">
                    <span class="section-icon-right">
                        <svg viewBox="0 0 24 24" fill="white">
                            <path d="M20 6h-4V4c0-1.11-.89-2-2-2h-4c-1.11 0-2 .89-2 2v2H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2zm-6 0h-4V4h4v2z"/>
                        </svg>
                    </span>
                    EXPÉRIENCES PROFESSIONNELLES
                </div>
                
                <div class="experience-item">
                    <div class="exp-title">DÉVELOPPEUR FRONT-END</div>
                    <div class="exp-header">
                        <div class="company">
                            <span class="company-icon">
                                <svg viewBox="0 0 24 24" fill="#689f38">
                                    <path d="M12 7V3H2v18h20V7H12zM6 19H4v-2h2v2zm0-4H4v-2h2v2zm0-4H4V9h2v2zm0-4H4V5h2v2zm4 12H8v-2h2v2zm0-4H8v-2h2v2zm0-4H8V9h2v2zm0-4H8V5h2v2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8v10zm-2-8h-2v2h2v-2zm0 4h-2v2h2v-2z"/>
                                </svg>
                            </span>
                            <span>Prométhée Earth Intelligence</span>
                        </div>
                        <div class="date">
                            <span class="date-icon">
                                <svg viewBox="0 0 24 24" fill="#c62828">
                                    <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                                </svg>
                            </span>
                            <span>Juillet 2022 - Aujourd'hui (3 ans)</span>
                        </div>
                    </div>
                    
                    <div class="project-name">Projet EOP</div>
                    <div class="description">
                        Développement d'une plateforme digitale permettant l'exploitation des données géospatiales en les fusionnant et les corrélant avec des données multi-sources sans connaissance spécifique du monde du spatial, le but étant de faciliter et démocratiser l'accès et la compréhension des données géospatiales.
                    </div>
                    <div class="tech-stack">
                        VueJS 3 - TypeScript - MapBox GL JS / Maplibre - Cypress - Pinia - Vuetify<br>- DayJS - TurfJS - D3JS - Proj4JS
                    </div>
                    
                    <div class="project-name" style="margin-top: 16px;">Projet CarbonTracker</div>
                    <div class="description">
                        Développement d'une plateforme permettant de calculer l'émission de CO2 via des capteurs sur une période définie
                    </div>
                    <div class="tech-stack">
                        ReactJS - TypeScript - MapBox GL JS - chartJS
                    </div>
                </div>
                
                <div class="experience-item">
                    <div class="exp-title">DÉVELOPPEUR FRONT-END</div>
                    <div class="exp-header">
                        <div class="company">
                            <span class="company-icon">
                                <svg viewBox="0 0 24 24" fill="#689f38">
                                    <path d="M12 7V3H2v18h20V7H12zM6 19H4v-2h2v2zm0-4H4v-2h2v2zm0-4H4V9h2v2zm0-4H4V5h2v2zm4 12H8v-2h2v2zm0-4H8v-2h2v2zm0-4H8V9h2v2zm0-4H8V5h2v2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8v10zm-2-8h-2v2h2v-2zm0 4h-2v2h2v-2z"/>
                                </svg>
                            </span>
                            <span>KIZOA</span>
                        </div>
                        <div class="date">
                            <span class="date-icon">
                                <svg viewBox="0 0 24 24" fill="#c62828">
                                    <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                                </svg>
                            </span>
                            <span>Février 2017 - Janvier 2022 (5 ans)</span>
                        </div>
                    </div>
                    
                    <ul class="experience-list">
                        <li>Développement d'une WebApp <strong>Typescript</strong> permettant aux clients de créer leur film avec une multitude d'outils (musique - transition - gif - logo)</li>
                        <li>Maintenance, amélioration et ajout de nouvelles pages sur le site web</li>
                        <li>Maintenance de plusieurs plateforme : Marketing / Newsletter / Support / Stats <strong>(PHP / jQuery / SASS)</strong></li>
                        <li>Maintenance et correctifs de bugs de la plateforme</li>
                        <li>Analyse des besoins utilisateurs et création d'un cahier des charges techniques</li>
                        <li>Maintenance du <strong>Desktop</strong> de la plateforme sous <strong>Electron</strong></li>
                        <li>Analyse des données de trafic, amélioration du <strong>référencement</strong></li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="exp-title">ASSISTANT INFORMATIQUE</div>
                    <div class="exp-header">
                        <div class="company">
                            <span class="company-icon">
                                <svg viewBox="0 0 24 24" fill="#689f38">
                                    <path d="M12 7V3H2v18h20V7H12zM6 19H4v-2h2v2zm0-4H4v-2h2v2zm0-4H4V9h2v2zm0-4H4V5h2v2zm4 12H8v-2h2v2zm0-4H8v-2h2v2zm0-4H8V9h2v2zm0-4H8V5h2v2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8v10zm-2-8h-2v2h2v-2zm0 4h-2v2h2v-2z"/>
                                </svg>
                            </span>
                            <span>Conseil Général de la Réunion</span>
                        </div>
                        <div class="date">
                            <span class="date-icon">
                                <svg viewBox="0 0 24 24" fill="#c62828">
                                    <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                                </svg>
                            </span>
                            <span>Aout 2014 - Novembre 2014 (4 mois)</span>
                        </div>
                    </div>
                    
                    <ul class="experience-list">
                        <li>Analyse des besoins utilisateurs et création d'un cahier des charges techniques</li>
                        <li>S'approprier une base de données déjà établie</li>
                        <li>Création d'un <strong>serveur Web avec L.A.M.P.</strong> et mise en œuvre des règles de sécurités.</li>
                        <li><strong>Développement d'une application</strong> pour Smartphone et tablette, à partir d'un site web existant</li>
                    </ul>
                </div>
            </div>
            
            <div class="right-section">
                <div class="right-section-title">
                    <span class="section-icon-right">
                        <svg viewBox="0 0 24 24" fill="white">
                            <path d="M5 13.18v4L12 21l7-3.82v-4L12 17l-7-3.82zM12 3L1 9l11 6 9-4.91V17h2V9L12 3z"/>
                        </svg>
                    </span>
                    FORMATION
                </div>
                
                <div class="formation-item">
                    <div class="formation-title">Architecte logiciel, développeur d'applications</div>
                    <div class="exp-header">
                        <div class="school">
                            <span class="company-icon">
                                <svg viewBox="0 0 24 24" fill="#689f38">
                                    <path d="M12 7V3H2v18h20V7H12zM6 19H4v-2h2v2zm0-4H4v-2h2v2zm0-4H4V9h2v2zm0-4H4V5h2v2zm4 12H8v-2h2v2zm0-4H8v-2h2v2zm0-4H8V9h2v2zm0-4H8V5h2v2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8v10zm-2-8h-2v2h2v-2zm0 4h-2v2h2v-2z"/>
                                </svg>
                            </span>
                            <span>ETNA</span>
                        </div>
                        <div class="date">
                            <span class="date-icon">
                                <svg viewBox="0 0 24 24" fill="#c62828">
                                    <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                                </svg>
                            </span>
                            <span>Octobre 2015 - Février 2016</span>
                        </div>
                    </div>
                    <div class="school-name">InsTRit - Domaine de l'immobilier</div>
                    <div class="formation-details">
                        <div>- Création de widget, utilisation des données du gouvernement via L'INSEE (Js -<br>&nbsp;&nbsp;Leaflet)</div>
                    </div>
                    <div class="school-name" style="margin-top: 8px;">Maincare - Domaine Médical</div>
                    <div class="formation-details">
                        <div>- Repérer et calculer la surface d'une plaie à l'aide d'une photo (Canvas / js)</div>
                    </div>
                </div>
                
                <div class="formation-item">
                    <div class="formation-title">Expert en Technologies de l'Information</div>
                    <div class="exp-header">
                        <div class="school">
                            <span class="company-icon">
                                <svg viewBox="0 0 24 24" fill="#689f38">
                                    <path d="M12 7V3H2v18h20V7H12zM6 19H4v-2h2v2zm0-4H4v-2h2v2zm0-4H4V9h2v2zm0-4H4V5h2v2zm4 12H8v-2h2v2zm0-4H8v-2h2v2zm0-4H8V9h2v2zm0-4H8V5h2v2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8v10zm-2-8h-2v2h2v-2zm0 4h-2v2h2v-2z"/>
                                </svg>
                            </span>
                            <span>Epitech</span>
                        </div>
                        <div class="date">
                            <span class="date-icon">
                                <svg viewBox="0 0 24 24" fill="#c62828">
                                    <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                                </svg>
                            </span>
                            <span>Septembre 2013 - Juillet 2015</span>
                        </div>
                    </div>
                    <div class="formation-details">
                        <div>Apprentissage du <strong>langage C</strong></div>
                        <div>Travail et configuration sur environnement linux / Unix.</div>
                        <div>Langage <strong>C++</strong>, librairie graphique <strong>(SDL – SFML)</strong> et approfondissement du C</div>
                        <div>Administrateur système</div>
                    </div>
                </div>
                
                <div class="formation-item">
                    <div class="formation-title">BAC STG - Sciences et Technologies de la Gestion - option comptabilité et finances<br>d'entreprise</div>
                    <div class="exp-header">
                        <div class="school">
                            <span class="company-icon">
                                <svg viewBox="0 0 24 24" fill="#689f38">
                                    <path d="M12 7V3H2v18h20V7H12zM6 19H4v-2h2v2zm0-4H4v-2h2v2zm0-4H4V9h2v2zm0-4H4V5h2v2zm4 12H8v-2h2v2zm0-4H8v-2h2v2zm0-4H8V9h2v2zm0-4H8V5h2v2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8v10zm-2-8h-2v2h2v-2zm0 4h-2v2h2v-2z"/>
                                </svg>
                            </span>
                            <span>Lycée Sarda Garriga, St André de la Réunion</span>
                        </div>
                        <div class="date">
                            <span class="date-icon">
                                <svg viewBox="0 0 24 24" fill="#c62828">
                                    <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                                </svg>
                            </span>
                            <span>Juillet 2012</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
