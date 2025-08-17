// --- DICTIONNAIRE DE TRADUCTIONS (AMÉLIORÉES) ---
        const translations = {
            fr: {
                nav_home: "Accueil", nav_about: "À propos", nav_projects: "Projets", nav_skills: "Compétences", nav_watch: "Veille", nav_contact: "Contact",
                hero_greeting: "Bonjour, je suis", hero_subtitle: "Étudiant en BTS SIO option SISR au lycee Melkior-Garré, en Guyane.", hero_typed: ["Aboikonie Joel", " un futur Administrateur Réseaux"],
                hero_cta1: "Découvrir mes projets", hero_cta2: "Me contacter",
                about_title: "À propos de moi", about_p1: "Né et ayant grandi en Guyane, un territoire tourné vers l'avenir, j'ai développé très tôt une fascination pour la technologie qui nous connecte au monde. Le BTS SIO SISR a été pour moi le moyen de transformer cette passion en expertise : comprendre, déployer et protéger la colonne vertébrale de toute organisation moderne.", about_p2: "Je vise un poste d'administrateur systèmes et réseaux, avec une spécialisation en cybersécurité. Mon but est d'assurer la robustesse et l'intégrité des infrastructures, un défi crucial pour toutes les entreprises à l'ère du numérique.",
                projects_title: "Mes Projets", projects_year2: "Deuxième Année", project2_title: "Infrastructure Active Directory", project2_desc: "Simulation de la création d'un réseau d'entreprise avec gestion centralisée des utilisateurs et des politiques de sécurité.", projects_year1: "Première Année", project1_title: "Service de Supervision Réseau", project1_desc: "Mise en place d'une solution de monitoring (Zabbix) pour surveiller l'état de santé d'un parc de serveurs Linux et Windows.", projects_doc: "Voir la documentation", projects_video: "Voir la vidéo",
                skills_title: "Mes Compétences", skills_cat1: "Systèmes d'Exploitation", skills_cat2: "Réseaux", skills_cat3: "Virtualisation",
                watch_title: "Veille Technologique", watch_topic1_title: "Cloud Hybride", watch_topic1_desc: "Combinaison d'infrastructures locales et de services cloud (AWS, Azure).", watch_topic2_title: "Infrastructure as Code", watch_topic2_desc: "Automatisation du déploiement avec des outils comme Terraform et Ansible.", watch_topic3_title: "Cybersécurité Défensive", watch_topic3_desc: "Évolution des EDR et du Zero Trust Network Access (ZTNA).",
                contact_title: "Contact", contact_intro: "Un projet ? Une question ? N'hésitez pas à me contacter. Je serais ravi d'échanger avec vous."
            },
            en: {
                nav_home: "Home", nav_about: "About", nav_projects: "Projects", nav_skills: "Skills", nav_watch: "Tech Watch", nav_contact: "Contact",
                hero_greeting: "Hello, I am", hero_subtitle: "A student in BTS SIO, SISR option, at Melkior-Garré high school in French Guiana.", hero_typed: ["Aboikonie Joel", "a future Network Administrator"],
                hero_cta1: "Discover my projects", hero_cta2: "Contact me",
                about_title: "About Me", about_p1: "Born and raised in French Guiana, a forward-looking territory, I developed an early fascination for the technology that connects us to the world. The BTS SIO SISR program has been my way of turning this passion into expertise: understanding, deploying, and protecting the backbone of any modern organization.", about_p2: "I am aiming for a position as a Systems and Network Administrator, with a specialization in cybersecurity. My goal is to ensure the robustness and integrity of infrastructures, a crucial challenge for all companies in the digital age.",
                projects_title: "My Projects", projects_year2: "Second Year", project2_title: "Active Directory Infrastructure", project2_desc: "A simulation of creating a corporate network with centralized user management and security policies.", projects_year1: "First Year", project1_title: "Network Monitoring Service", project1_desc: "Implementation of a monitoring solution (Zabbix) to oversee the health of a fleet of Linux and Windows servers.", projects_doc: "View documentation", projects_video: "Watch video",
                skills_title: "My Skills", skills_cat1: "Operating Systems", skills_cat2: "Networking", skills_cat3: "Virtualization",
                watch_title: "Technological Watch", watch_topic1_title: "Hybrid Cloud", watch_topic1_desc: "Combining on-premise infrastructure with cloud services (AWS, Azure).", watch_topic2_title: "Infrastructure as Code", watch_topic2_desc: "Automating deployment with tools like Terraform and Ansible.", watch_topic3_title: "Defensive Cybersecurity", watch_topic3_desc: "The evolution of EDR and Zero Trust Network Access (ZTNA).",
                contact_title: "Contact", contact_intro: "Have a project or a question? Feel free to contact me. I would be delighted to connect with you."
            },
            pt: {
                nav_home: "Início", nav_about: "Sobre mim", nav_projects: "Projetos", nav_skills: "Competências", nav_watch: "Vigilância", nav_contact: "Contato",
                hero_greeting: "Olá, eu sou", hero_subtitle: "Estudante do BTS SIO, opção SISR, na escola Melkior-Garré, na Guiana Francesa.", hero_typed: ["Aboikonie Joel", "um futuro Administrador de Redes"],
                hero_cta1: "Descubra meus projetos", hero_cta2: "Entre em contato",
                about_title: "Sobre Mim", about_p1: "Nascido e criado na Guiana Francesa, um território voltado para o futuro, desenvolvi desde cedo um fascínio pela tecnologia que nos conecta ao mundo. O BTS SIO SISR foi a minha forma de transformar essa paixão em perícia: compreender, implementar e proteger a espinha dorsal de qualquer organização moderna.", about_p2: "Meu objetivo é uma posição como Administrador de Sistemas e Redes, com especialização em cibersegurança. Minha meta é garantir a robustez e a integridade das infraestruturas, um desafio crucial para todas as empresas na era digital.",
                projects_title: "Meus Projetos", projects_year2: "Segundo Ano", project2_title: "Infraestrutura Active Directory", project2_desc: "Simulação da criação de uma rede corporativa com gestão centralizada de utilizadores e políticas de segurança.", projects_year1: "Primeiro Ano", project1_title: "Serviço de Monitoramento de Rede", project1_desc: "Implementação de uma solução de monitoramento (Zabbix) para supervisionar a saúde de um parque de servidores Linux e Windows.", projects_doc: "Ver documentação", projects_video: "Ver vídeo",
                skills_title: "Minhas Competências", skills_cat1: "Sistemas Operacionais", skills_cat2: "Redes", skills_cat3: "Virtualização",
                watch_title: "Vigilância Tecnológica", watch_topic1_title: "Nuvem Híbrida", watch_topic1_desc: "Combinação de infraestrutura local com serviços na nuvem (AWS, Azure).", watch_topic2_title: "Infraestrutura como Código", watch_topic2_desc: "Automação da implementação com ferramentas como Terraform e Ansible.", watch_topic3_title: "Cibersegurança Defensiva", watch_topic3_desc: "A evolução do EDR e do Acesso à Rede Zero Trust (ZTNA).",
                contact_title: "Contato", contact_intro: "Tem um projeto ou uma pergunta? Fique à vontade para me contatar. Terei o maior prazer em conversar com você."
            },
            nl: {
                nav_home: "Home", nav_about: "Over mij", nav_projects: "Projecten", nav_skills: "Vaardigheden", nav_watch: "Tech Watch", nav_contact: "Contact",
                hero_greeting: "Hallo, ik ben", hero_subtitle: "Student BTS SIO, optie SISR, aan het Melkior-Garré lyceum in Frans-Guyana.", hero_typed: ["Aboikonie Joel", "een toekomstig Netwerkbeheerder"],
                hero_cta1: "Ontdek mijn projecten", hero_cta2: "Neem contact op",
                about_title: "Over Mij", about_p1: "Geboren en getogen in Frans-Guyana, een toekomstgericht gebied, ontwikkelde ik al vroeg een fascinatie voor de technologie die ons met de wereld verbindt. De BTS SIO SISR was voor mij de manier om deze passie om te zetten in expertise: het begrijpen, implementeren en beschermen van de ruggengraat van elke moderne organisatie.", about_p2: "Ik streef naar een functie als Systeem- en Netwerkbeheerder, met een specialisatie in cybersecurity. Mijn doel is de robuustheid en integriteit van infrastructuren te waarborgen, een cruciale uitdaging voor alle bedrijven in het digitale tijdperk.",
                projects_title: "Mijn Projecten", projects_year2: "Tweede Jaar", project2_title: "Active Directory Infrastructuur", project2_desc: "Simulatie van het opzetten van een bedrijfsnetwerk met gecentraliseerd gebruikersbeheer en beveiligingsbeleid.", projects_year1: "Eerste Jaar", project1_title: "Netwerkmonitoringdienst", project1_desc: "Implementatie van een monitoringoplossing (Zabbix) om de gezondheid van een vloot Linux- en Windows-servers te bewaken.", projects_doc: "Bekijk documentatie", projects_video: "Bekijk video",
                skills_title: "Mijn Vaardigheden", skills_cat1: "Besturingssystemen", skills_cat2: "Netwerken", skills_cat3: "Virtualisatie",
                watch_title: "Technologische Watch", watch_topic1_title: "Hybride Cloud", watch_topic1_desc: "Combinatie van on-premise infrastructuur met clouddiensten (AWS, Azure).", watch_topic2_title: "Infrastructuur als Code", watch_topic2_desc: "Automatisering van de implementatie met tools zoals Terraform en Ansible.", watch_topic3_title: "Defensieve Cybersecurity", watch_topic3_desc: "De evolutie van EDR en Zero Trust Network Access (ZTNA).",
                contact_title: "Contact", contact_intro: "Heeft u een project of een vraag? Neem gerust contact met mij op. Ik ga graag met u in gesprek."
            }
        };
        
        let currentLanguage = 'fr';
        let typeInterval;

        function changeLanguage(lang) {
            currentLanguage = lang;
            document.documentElement.lang = lang;
            const elements = document.querySelectorAll('[data-lang]');
            elements.forEach(el => {
                const key = el.getAttribute('data-lang');
                if (translations[lang] && translations[lang][key] && el.id !== 'typed-text') {
                    el.innerHTML = translations[lang][key];
                }
            });
            initTypingEffect();
        }

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.1 });

        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(page => page.classList.remove('active'));
            const activePage = document.getElementById(pageId);
            activePage.classList.add('active');
            document.querySelectorAll('.nav-link').forEach(link => {
                link.classList.toggle('active', link.getAttribute('data-page') === pageId);
            });
            activePage.querySelectorAll('.reveal').forEach(el => observer.observe(el));
            window.scrollTo(0, 0);

            if (pageId === 'about') {
                initConstellation();
            }
        }
        
        function initTypingEffect() {
            clearTimeout(typeInterval);
            const typedTextSpan = document.getElementById('typed-text');
            if (!typedTextSpan) return;
            const textArray = translations[currentLanguage].hero_typed;
            let textArrayIndex = 0;
            let charIndex = 0;
            typedTextSpan.textContent = '';
            function type() {
                if (charIndex < textArray[textArrayIndex].length) {
                    typedTextSpan.textContent += textArray[textArrayIndex].charAt(charIndex++);
                    typeInterval = setTimeout(type, 120);
                } else {
                    typeInterval = setTimeout(erase, 2000);
                }
            }
            function erase() {
                if (charIndex > 0) {
                    typedTextSpan.textContent = textArray[textArrayIndex].substring(0, --charIndex);
                    typeInterval = setTimeout(erase, 80);
                } else {
                    textArrayIndex = (textArrayIndex + 1) % textArray.length;
                    typeInterval = setTimeout(type, 500);
                }
            }
            setTimeout(type, 500);
        }

        function initThreeJS() {
            const container = document.getElementById('canvas-container');
            if (!container) return;
            // NOUVELLE ANIMATION 3D : PLEXUS DE PARTICULES
            const scene = new THREE.Scene();
            const camera = new THREE.PerspectiveCamera(75, container.clientWidth / container.clientHeight, 0.1, 1000);
            camera.position.z = 15;
            const renderer = new THREE.WebGLRenderer({ alpha: true, antialias: true });
            renderer.setSize(container.clientWidth, container.clientHeight);
            renderer.setPixelRatio(window.devicePixelRatio);
            container.appendChild(renderer.domElement);

            const pointsGeometry = new THREE.BufferGeometry();
            const numPoints = 150;
            const positions = new Float32Array(numPoints * 3);
            const velocities = [];

            for (let i = 0; i < numPoints; i++) {
                positions[i * 3] = (Math.random() - 0.5) * 30;
                positions[i * 3 + 1] = (Math.random() - 0.5) * 30;
                positions[i * 3 + 2] = (Math.random() - 0.5) * 30;
                velocities.push(new THREE.Vector3((Math.random() - 0.5) * 0.02, (Math.random() - 0.5) * 0.02, (Math.random() - 0.5) * 0.02));
            }
            pointsGeometry.setAttribute('position', new THREE.BufferAttribute(positions, 3));
            const pointsMaterial = new THREE.PointsMaterial({ color: 0x64ffda, size: 0.1 }); // Cyan
            const points = new THREE.Points(pointsGeometry, pointsMaterial);
            scene.add(points);

            const linesGeometry = new THREE.BufferGeometry();
            const linePositions = new Float32Array(numPoints * numPoints * 6);
            linesGeometry.setAttribute('position', new THREE.BufferAttribute(linePositions, 3));
            const linesMaterial = new THREE.LineBasicMaterial({ color: 0x64ffda, transparent: true, opacity: 0.1 }); // Cyan
            const lines = new THREE.LineSegments(linesGeometry, linesMaterial);
            scene.add(lines);

            let mouse = new THREE.Vector2();
            document.addEventListener('mousemove', (e) => {
                mouse.x = (e.clientX / window.innerWidth) * 2 - 1;
                mouse.y = - (e.clientY / window.innerHeight) * 2 + 1;
            });

            function animate() {
                requestAnimationFrame(animate);
                const positions = points.geometry.attributes.position.array;
                const linePositions = lines.geometry.attributes.position.array;
                let lineIndex = 0;

                for (let i = 0; i < numPoints; i++) {
                    positions[i * 3] += velocities[i].x;
                    positions[i * 3 + 1] += velocities[i].y;
                    positions[i * 3 + 2] += velocities[i].z;

                    if (positions[i * 3 + 1] < -15 || positions[i * 3 + 1] > 15) velocities[i].y *= -1;
                    if (positions[i * 3] < -15 || positions[i * 3] > 15) velocities[i].x *= -1;
                    if (positions[i * 3 + 2] < -15 || positions[i * 3 + 2] > 15) velocities[i].z *= -1;

                    for (let j = i + 1; j < numPoints; j++) {
                        const dx = positions[i * 3] - positions[j * 3];
                        const dy = positions[i * 3 + 1] - positions[j * 3 + 1];
                        const dz = positions[i * 3 + 2] - positions[j * 3 + 2];
                        const dist = Math.sqrt(dx * dx + dy * dy + dz * dz);

                        if (dist < 3) {
                            linePositions[lineIndex++] = positions[i * 3];
                            linePositions[lineIndex++] = positions[i * 3 + 1];
                            linePositions[lineIndex++] = positions[i * 3 + 2];
                            linePositions[lineIndex++] = positions[j * 3];
                            linePositions[lineIndex++] = positions[j * 3 + 1];
                            linePositions[lineIndex++] = positions[j * 3 + 2];
                        }
                    }
                }
                lines.geometry.setDrawRange(0, lineIndex / 3);
                lines.geometry.attributes.position.needsUpdate = true;
                points.geometry.attributes.position.needsUpdate = true;

                camera.position.x += (mouse.x * 5 - camera.position.x) * 0.03;
                camera.position.y += (-mouse.y * 5 - camera.position.y) * 0.03;
                camera.lookAt(scene.position);

                renderer.render(scene, camera);
            }
            animate();
        }

        // --- SCRIPT POUR LA CONSTELLATION ---
        function initConstellation() {
            const canvas = document.getElementById('about-bg');
            if (!canvas || canvas.dataset.initialized) return;
            canvas.dataset.initialized = true;

            const ctx = canvas.getContext('2d');
            let parent = canvas.parentElement;
            canvas.width = parent.clientWidth;
            canvas.height = parent.clientHeight;

            let dots = [];
            for(let i = 0; i < 50; i++){
                dots.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height,
                    vx: Math.random() * 0.5 - 0.25,
                    vy: Math.random() * 0.5 - 0.25,
                    radius: Math.random() * 1.5 + 1
                });
            }

            function draw(){
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                ctx.fillStyle = 'rgba(100, 255, 218, 0.5)'; // Cyan
                dots.forEach(dot => {
                    ctx.beginPath();
                    ctx.arc(dot.x, dot.y, dot.radius, 0, Math.PI * 2);
                    ctx.fill();
                });

                ctx.beginPath();
                for(let i = 0; i < dots.length; i++){
                    for(let j = i; j < dots.length; j++){
                        let dist = Math.sqrt(Math.pow(dots[i].x - dots[j].x, 2) + Math.pow(dots[i].y - dots[j].y, 2));
                        if(dist < 150){
                            ctx.moveTo(dots[i].x, dots[i].y);
                            ctx.lineTo(dots[j].x, dots[j].y);
                        }
                    }
                }
                ctx.lineWidth = 0.5;
                ctx.strokeStyle = 'rgba(100, 255, 218, 0.2)'; // Cyan
                ctx.stroke();
            }

            function update(){
                dots.forEach(dot => {
                    dot.x += dot.vx;
                    dot.y += dot.vy;

                    if(dot.x < 0 || dot.x > canvas.width) dot.vx *= -1;
                    if(dot.y < 0 || dot.y > canvas.height) dot.vy *= -1;
                });
            }

            function loop(){
                draw();
                update();
                requestAnimationFrame(loop);
            }
            loop();
        }

        document.addEventListener('DOMContentLoaded', () => {
            feather.replace();
            showPage('home');
            changeLanguage(currentLanguage);
            
            if (document.getElementById('home').classList.contains('active')) {
                initThreeJS();
            }

            const cursorDot = document.getElementById('cursor-dot');
            const cursorTrailer = document.getElementById('cursor-trailer');
            
            window.addEventListener('mousemove', e => {
                cursorDot.style.transform = `translate(${e.clientX}px, ${e.clientY}px)`;
                cursorTrailer.style.transform = `translate(${e.clientX}px, ${e.clientY}px)`;
            });

            const interactiveElements = document.querySelectorAll('a, button');
            interactiveElements.forEach(el => {
                el.addEventListener('mouseenter', () => cursorTrailer.classList.add('grow'));
                el.addEventListener('mouseleave', () => cursorTrailer.classList.remove('grow'));
            });

            const profileContainer = document.getElementById('profile-pic-container');
            if (profileContainer) {
                profileContainer.addEventListener('mousemove', e => {
                    const rect = profileContainer.getBoundingClientRect();
                    const x = e.clientX - rect.left;
                    const y = e.clientY - rect.top;
                    profileContainer.style.setProperty('--mouse-x', `${x}px`);
                    profileContainer.style.setProperty('--mouse-y', `${y}px`);
                });
            }
        });