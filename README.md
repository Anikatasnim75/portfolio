<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Senior Product Manager & Business Analyst portfolio - 3+ years driving product strategy, roadmaps, and digital transformation in FinTech, SaaS, ERP, and E-commerce.">
    <meta name="keywords" content="Product Manager, Business Analyst, FinTech, SaaS, Agile, SDLC, Product Strategy, Roadmap">
    <meta name="author" content="Product Manager & Business Analyst Professional">
    
    <!-- Open Graph Metadata -->
    <meta property="og:title" content="Product Manager & Business Analyst | Portfolio">
    <meta property="og:description" content="3+ years driving product strategy, SaaS, ERP, and FinTech growth.">
    <meta property="og:type" content="website">

    <title id="page-title">Product Manager | Business Analyst — Portfolio</title>

    <!-- Google Fonts: Hind Siliguri -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3a86ff',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#0f172a'
                        }
                    },
                    fontFamily: {
                        sans: ['"Hind Siliguri"', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <!-- Font Awesome 6.5.1 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Modern Base Setup & Custom Glassmorphism */
        body {
            font-family: 'Hind Siliguri', sans-serif;
            background-color: #0f172a;
            color: #f8fafc;
            overflow-x: hidden;
        }

        .glass-nav {
            background: rgba(15, 23, 42, 0.75);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-card {
            background: rgba(30, 41, 59, 0.6);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-card:hover {
            border-color: rgba(58, 134, 255, 0.4);
        }

        .gradient-text {
            background: linear-gradient(135deg, #ffffff 0%, #93c5fd 50%, #3a86ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gradient-accent-text {
            background: linear-gradient(135deg, #60a5fa 0%, #3a86ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Image Reveal Hover Effect for Projects */
        .project-img-wrapper {
            position: relative;
            overflow: hidden;
            height: 240px;
        }
        .project-img-wrapper img {
            transition: transform 3.5s ease-in-out;
            transform: translateY(0);
            width: 100%;
            object-fit: cover;
            object-position: top;
        }
        .project-img-wrapper:hover img {
            transform: translateY(calc(-100% + 240px));
        }

        /* Reduced Motion Fallback */
        @media (prefers-reduced-motion: reduce) {
            *, ::before, ::after {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
                scroll-behavior: auto !important;
            }
            .project-img-wrapper:hover img {
                transform: none !important;
            }
        }

        /* Smooth reveal default states */
        .reveal-element {
            opacity: 0;
            transform: translateY(24px);
            transition: opacity 0.7s cubic-bezier(0.16, 1, 0.3, 1), transform 0.7s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .reveal-element.active {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="selection:bg-brand-500 selection:text-white antialiased">

    <!-- Dynamic Centralized Configuration Script -->
    <script>
        const siteData = {
            personalInfo: {
                name: "Anika Tasnim",
                designation: "Product Manager | Business Analyst",
                phone: "+880 1307 450493",
                email: "anikatasnim0031@gmail.com",
                address: "Dhaka, Bangladesh / Remote",
                profileImage: "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgBBnsDyFMur-75gmH_J3RL-7RS70eoe1dLQ-52OfNZGCJmMglQ2YZEwHmaE9pfWcHQm43p-uzwYKTa5S_aMrST2QImTvzcCXl1EEkUBfKWPhfOh790MKPGCXoEAoYFdqZ-VO-CYnQq1pSTBxkEPO8G7KOv0Uc_YNGwfAS9TAiCQQVIylw68nrYnHbjTgTg/s1600/Anika.png",
                resumeLink: "https://drive.google.com/file/d/1ZpJN8PDknz5kGGyY2cHzX81s_QnzSy_K/view?usp=drive_link",
                typingWords: ["Product Strategy", "FinTech Scale", "Agile Execution", "SaaS & ERP"]
            },
            about: {
                title: "Architecting Digital Products that Scale Business & Elevate UX",
                description: "Over 3+ years, I have navigated the intersection of business strategy, tech infrastructure, and user experience. Specializing in FinTech, enterprise ERPs, SaaS ecosystems, and high-volume E-commerce platforms, I translate complex market needs into clean, execute-ready product roadmaps."
            },
            socialLinks: {
                linkedin: "https://www.linkedin.com/in/anika-tasnim-net/",
                github: "https://github.com/Anikatasnim75",
                facebook: "https://facebook.com",
                twitter: "https://x.com"
            },
            skills: [
                { category: "Core Expertise", items: ["Product Strategy", "Business Analysis", "Roadmap Ownership", "Market Discovery", "SDLC Execution"] },
                { category: "Technical & Methods", items: ["Agile/Scrum", "SQL & Analytics", "System Architecture", "UAT & QA Governance", "API Integration"] },
                { category: "Domain Knowledge", items: ["FinTech Payments", "SaaS Platforms", "Enterprise ERP", "E-Commerce Engines", "Process Automation"] }
            ],
            workExperienceImage: "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjd6V_3el60dn0_fODXVuqVgIm34GqDPsjstJ2_G3fy6-SF80hzGg_p4JkcXC1eJ_SeMF7VGE1jxzoZRvg94PUSM8AXsfmM-YRiTdPka-v0ciq0GW9jrU40fWlu3bPzQWtwDzJhQqOJSEPKN4Zf5ceWKqsesaHb67MvO09bRVrhBfp9cMAZkWcbNMNa5bmY/s1600/AnikaTasnimWebsite.png",
            experienceSummary: "A results-driven technology professional with 3+ years of experience across FinTech, SaaS, ERP, and E-commerce, leading products and cross-functional initiatives from strategy and discovery through execution and scale.",
            experiences: [
                {
                    duration: "Jan 2026 — Present",
                    designation: "Product Manager",
                    company: "KGecom Ltd - Krishibid Group",
                    responsibilities: [
                        "Product Strategy & Roadmap Management: Owned end-to-end roadmap execution for ERP and E-commerce products.",
                        "Product Lifecycle & Agile Delivery: Managed full product lifecycle using Agile, from discovery to launch.",
                        "Stakeholder & Requirement Management: Aligned business and technical stakeholders on product direction.",
                        "Cross-Functional Team Leadership: Coordinated IT, Marketing, Software, and Business teams for on-schedule deployments.",
                        "Product Growth & Client Success: Drove growth through client acquisition, retention, and feature enhancements.",
                        "Release Planning & UAT Management: Owned release planning and UAT to ensure launch readiness."
                    ],
                    skills: ["Product Strategy", "Enterprise ERP", "Business Analysis", "Agile Leadership", "API Architecture", "Roadmapping", "SQL Analytics"]
                },
                {
                    duration: "Apr 2024 — Dec 2025",
                    designation: "Project Manager, Product & Technology",
                    company: "Sheba Platform Limited",
                    responsibilities: [
                        "Agile Project Management: Led sprint planning, stand-ups, reviews, & retrospectives using Agile and Scrum.",
                        "Project Planning & Delivery: Managed project scope, timelines, backlogs, resources, & delivery milestones.",
                        "Stakeholder & Requirement Management: Gathered requirements and aligned business and technical stakeholders.",
                        "Cross-Functional Leadership: Coordinated Engineering, Product, QA, SOC, and Business teams across the SDLC.",
                        "Project Monitoring & Reporting: Tracked KPIs, risks, dependencies, and project progress.",
                        "UAT & Release Management: Managed UAT, release planning, and production deployments.",
                        "Governance & Compliance: Maintained project documentation and ensured AML, ISO, and PCI DSS compliance.",
                        "Talent & Team Management: Technology recruitment, workforce planning, & engineering team growth."
                    ],
                    skills: ["Enterprise ERP", "FinTech", "SQA", "UAT Management", "Release Management", "Process Optimization", "Jira/Confluence"]
                },
                {
                    duration: "Jan 2023 — Mar 2024",
                    designation: "Jr. Project Manager",
                    company: "Fixway IT",
                    responsibilities: [
                        "Conducted business, growth, and revenue analysis to support profitability.",
                        "Managed client requirements, end-to-end delivery workflows, and project timelines.",
                        "Maintained project documentation, reporting, performance tracking, and deliverables."
                    ],
                    skills: ["Requirement Gathering", "BRD/FRD", "E-Commerce", "Data Modeling", "Scrum Master", "OSS", "BSS"]
                }
            ],
            projects: [
                {
                    title: "FinGate — B2B Payment Engine",
                    description: "Next-gen unified payment solution streamlining automated escrow, multi-tier payouts, and cross-border currency exchanges.",
                    image: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=1200",
                    technologies: ["FinTech", "API Design", "Payments", "Dashboard"],
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "Enterprise ERP Supply Module",
                    description: "Cloud ERP dashboard for real-time inventory telemetry, predictive replenishment, and vendor lifecycle tracking.",
                    image: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=1200",
                    technologies: ["SaaS ERP", "Business Analysis", "Process Mapping"],
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "OmniStore E-Commerce Platform",
                    description: "Headless e-commerce checkout architecture designed to optimize micro-conversions and localized payment solutions.",
                    image: "https://webmundo.in/public/upload/portfolio_other_17670899291ea851c1-1d3e-4d2f-9bd7-99c33651d79a.png",
                    technologies: ["E-Commerce", "Product Strategy", "UX Analytics"],
                    liveUrl: "#",
                    githubUrl: "#"
                }
            ],
            certifications: [
                { name: "Professional Diploma in Agile and Scrum", institution: "Udemy", icon: "fa-certificate" },
                { name: "Data Science", institution: "Data Solution 360", icon: "fa-chart-pie" },
                { name: "Master Trainer Training Program", institution: "Election Observer Consortium", icon: "fa-chalkboard-user" },
                { name: "Corporate Management & Professional Behavior", institution: "JUST", icon: "fa-user-tie" }
            ],
            organizationalExperiencesImage: "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgL6AjsESV6pLmXSy1CMpMw4ZeelXLY9Ps48qdr2HFeFovOVqyor0MhI19fAa8EY2oInI0DuMsZekFGxZlMDOJSpJURd9tos4STJsFlJ5fUyZYnegPw58hbCI02_3e5d-5zGBfahPOkMDjchTF6Y11x455r7c9fy0NjXTbgSj98Tltv-A7AggXOwVx6QMLy/s1600/ChatGPT%20Image%20Jun%2027,%202026,%2012_32_34%20AM.png",
            organizationalExperiences: [
                {
                    duration: "Jun 2021 — Dec 2022",
                    designation: "Project Analyst",
                    organization: "Jamal Nazrul Islam Astronomy Club, JUST",
                    responsibilities: [
                        "Led astronomy-focused projects supported by the University of Toronto, Ontario, Canada, ensuring financial and logistical efficiency.",
                        "Developed observation, communication, and analytical skills through hands-on project execution and community engagement.",
                        "Organized educational initiatives to promote astronomy awareness among school students across Bangladesh.",
                        "Facilitated workshops and interactive sessions, enhancing students' understanding of astronomical concepts.",
                        "Managed project resources and timelines to ensure successful completion of initiatives aimed at spreading scientific knowledge."
                    ]
                },
                {
                    duration: "Feb 2022 — Apr 2024",
                    designation: "Vice President",
                    organization: "Jashore University of Science & Technology Debate Club",
                    responsibilities: [
                        "Spearheaded club governance, strategic planning, and overall executive management to foster an active debating culture.",
                        "Directed national and intra-university debate competitions, managing event operations, logistics, and judge panels.",
                        "Mentored junior debaters in critical thinking, public speaking, structured argumentation, and policy analysis.",
                        "Represented the club in regional debating forums and forged key partnerships across university organizations."
                    ]
                },
                {
                    duration: "Sep 2020 — Aug 2021",
                    designation: "Deputy Chief of Event Management",
                    organization: "Hult Prize at Jashore University of Science & Technology",
                    responsibilities: [
                        "Served as Deputy Chief of Event Management, overseeing ground logistics, event operations, and virtual execution.",
                        "Acted as a Department Ambassador to drive campus-wide engagement and student recruitment for social business ideas.",
                        "Hosted live virtual sessions and interactive panel discussions featuring guest speakers and social entrepreneurs.",
                        "Coordinated cross-functional volunteer teams to execute successful, high-impact entrepreneurship sessions."
                    ]
                }
            ],
            testimonials: [
                {
                    quote: "Anika is highly energetic, organized, and always ready to take on new challenges. One of her strongest qualities is her self-awareness — she clearly understands her limitations and plans her work accordingly, which helps her stay focused and consistently deliver successful outcomes. She brings a positive attitude, strong ownership, and reliability to the team",
                    author: "Md. Nazmul Haque Sarker",
                    role: "Director of Product and Technology, Sheba Platform Limited"
                },
               {
                    quote: "I highly recommend Anika Tasnim for her strong capabilities in project management and successful delivery of projects using Agile methodologies. She has demonstrated a clear understanding of Agile principles, effectively implementing frameworks such as sprint planning, daily stand-ups, backlog grooming, and retrospectives to ensure smooth project execution.",
                    author: "Muhammad Iqbal Hossain",
                    role: "Senior Software Engineer of FinTech, Sheba Platform Limited"
                },
                {
                    quote: "I worked with Anika for a short period, and she quickly proved to be dependable, well-aligned with the team, and strong in execution. She adapts fast, communicates clearly, and takes ownership to get work done. I’m confident she can perform well as a Project Manager and also in other assigned roles based on responsibilities, especially in cross-functional coordination and delivery.",
                    author: "Asaduzzaman Radowan",
                    role: "Founder, Hiring Dhaka"
                }
            ],
            contact: {
                phone: "+880 1307 450493",
                email: "anikatasnim0031@gmail.com",
                address: "Dhaka, Bangladesh / Remote Work Supported",
                mapUrl: "https://maps.google.com/maps?q=60+Feet+Road,+Mirpur+2,+Dhaka,+Bangladesh&t=&z=15&ie=UTF8&iwloc=&output=embed"
            },
            integrations: {
                googleScriptUrl: "https://script.google.com/macros/s/AKfycbwjkEbCzmnmiD8S2ezxwdPDdkFEiy7eqCSUS5TPj5NTQbRW0gQLFMqYz8QzKR_2cG6_/exec",
                telegramBotToken: "8175907217:AAH8wyej0lBnoHdoRfWEBgKt5tYXeWxdRRE",
                telegramChatId: "6990126463"
            }
        };
    </script>

    <!-- Header Navigation -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-nav transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center gap-3 group">
                <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjX4DvRCa1w4nw7GJ8kOXVr4TYe6Trq3fgD6eBgXKYa5Oua08K9Ol0Nq9m9ebMb1FmTTo_viqm-hprrJsMRzimmTNuTRwsJkfUwbOondo0PmcbegyODg7S0VcEHuVNJVXLvuX13DYhzlKC3TUdJEYRUCzG4Pwr0K7quufntB16lzqZQWR1J7Q_YdVR9v9Vm/s1600/anikafavicon.png.png" 
                     alt="Anika Tasnim Icon" 
                     class="w-10 h-10 rounded-xl border border-brand-500/40 object-cover group-hover:scale-105 transition-transform">
                <span id="nav-brand-name" class="font-bold text-lg tracking-tight text-slate-100 group-hover:text-brand-500 transition-colors">
                    Anika Tasnim
                </span>
            </a>

            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#about" class="text-slate-300 hover:text-brand-500 transition-colors">About</a>
                <a href="#experience" class="text-slate-300 hover:text-brand-500 transition-colors">Experience</a>
                <a href="#skills" class="text-slate-300 hover:text-brand-500 transition-colors">Skills</a>
                <a href="#projects" class="text-slate-300 hover:text-brand-500 transition-colors">Projects</a>
                <a href="#certifications" class="text-slate-300 hover:text-brand-500 transition-colors">Certifications</a>
                <a href="#organizational" class="text-slate-300 hover:text-brand-500 transition-colors">Organizational</a>
                <a href="#contact" class="px-5 py-2.5 rounded-full bg-brand-500 hover:bg-brand-600 text-white font-semibold transition-all shadow-lg shadow-brand-500/20 hover:shadow-brand-500/40">
                    Get in Touch
                </a>
            </nav>

            <!-- Mobile Hamburger Button -->
            <button id="mobile-menu-btn" class="md:hidden p-2 text-slate-300 hover:text-white focus:outline-none" aria-label="Toggle Navigation Menu">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Nav Menu -->
        <div id="mobile-menu" class="hidden md:hidden glass-nav border-t border-slate-800 px-6 py-6 space-y-4">
            <a href="#about" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">About</a>
            <a href="#experience" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Experience</a>
            <a href="#skills" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Skills</a>
            <a href="#projects" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Projects</a>
            <a href="#certifications" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Certifications</a>
            <a href="#organizational" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Organizational</a>
            <a href="#contact" class="mobile-nav-link inline-block w-full text-center py-3 rounded-xl bg-brand-500 text-white font-semibold">Get in Touch</a>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="pt-20">

        <!-- Hero Section -->
        <section class="min-h-[calc(100vh-80px)] flex items-center justify-center relative overflow-hidden py-16 px-4 sm:px-6 lg:px-8">
            <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] bg-brand-500/10 rounded-full blur-3xl pointer-events-none"></div>
            
            <div class="max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left reveal-element">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-sm font-medium">
                        <span class="w-2 h-2 rounded-full bg-brand-500 animate-pulse"></span>
                        Available for Product Leadership Roles
                    </div>

                    <h1 class="text-4xl sm:text-6xl font-bold tracking-tight text-white leading-tight">
                        Hi, I'm <span id="hero-name" class="gradient-text">Anika Tasnim</span>
                    </h1>

                    <h2 class="text-xl sm:text-2xl font-semibold text-slate-300 flex items-center justify-center lg:justify-start gap-2">
                        <span id="hero-designation">Product Manager | Business Analyst</span>
                    </h2>

                    <p class="text-lg text-slate-400 max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                        Spearheading product vision, SaaS lifecycle execution, and business strategy with over 3+ years of measurable impact in FinTech and Enterprise ecosystems.
                    </p>

                    <div class="text-sm font-mono text-brand-500 flex items-center justify-center lg:justify-start gap-2">
                        <i class="fa-solid fa-code text-xs"></i>
                        <span>Focus:</span>
                        <span id="typing-text" class="border-r-2 border-brand-500 pr-1"></span>
                    </div>

                    <div class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="#projects" class="w-full sm:w-auto px-8 py-3.5 rounded-xl bg-brand-500 hover:bg-brand-600 text-white font-semibold transition-all shadow-lg shadow-brand-500/25 hover:shadow-brand-500/40 text-center">
                            View Work <i class="fa-solid fa-arrow-right ml-2 text-sm"></i>
                        </a>
                        <a id="hero-resume-btn" href="#" target="_blank" class="w-full sm:w-auto px-8 py-3.5 rounded-xl border border-slate-700 hover:border-brand-500/50 bg-slate-900/50 text-slate-200 hover:text-white font-semibold transition-all text-center">
                            Download Resume <i class="fa-solid fa-download ml-2 text-sm"></i>
                        </a>
                    </div>

                    <div class="pt-6 flex items-center justify-center lg:justify-start gap-5 text-slate-400">
                        <a id="social-linkedin" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="LinkedIn Profile">
                            <i class="fa-brands fa-linkedin-in text-lg"></i>
                        </a>
                        <a id="social-github" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="GitHub Profile">
                            <i class="fa-brands fa-github text-lg"></i>
                        </a>
                        <a id="social-facebook" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="Facebook Profile">
                            <i class="fa-brands fa-facebook-f text-lg"></i>
                        </a>
                        <a id="social-twitter" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="Twitter Profile">
                            <i class="fa-brands fa-x-twitter text-lg"></i>
                        </a>
                    </div>
                </div>

                <div class="lg:col-span-5 flex justify-center reveal-element">
                    <div class="relative w-72 h-72 sm:w-80 sm:h-80 lg:w-96 lg:h-96">
                        <div class="absolute inset-0 rounded-3xl bg-gradient-to-tr from-brand-500 to-cyan-400 opacity-20 blur-xl"></div>
                        <div class="relative w-full h-full rounded-3xl border-2 border-slate-700/60 overflow-hidden shadow-2xl glass-card">
                            <img id="hero-profile-img" src="" alt="Professional Portrait" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="glass-card rounded-3xl p-8 sm:p-12 border border-slate-800/80 reveal-element">
                <div class="max-w-3xl">
                    <h2 class="text-sm font-semibold tracking-wider text-brand-500 uppercase mb-2">About Professional Journey</h2>
                    <h3 id="about-title" class="text-2xl sm:text-3xl font-bold text-white mb-6 leading-snug">
                        Architecting Digital Products that Scale Business & Elevate UX
                    </h3>
                    <p id="about-description" class="text-slate-300 text-lg leading-relaxed font-normal">
                        Over 3+ years, I have navigated the intersection of business strategy, tech infrastructure, and user experience...
                    </p>
                </div>

                <div class="mt-10 grid grid-cols-2 md:grid-cols-4 gap-6 pt-8 border-t border-slate-800">
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">3+ Years</div>
                        <div class="text-sm text-slate-400">Industry Experience</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">15+ Products</div>
                        <div class="text-sm text-slate-400">Launched & Managed</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">$40M+</div>
                        <div class="text-sm text-slate-400">Transaction Volume Managed</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">99.2%</div>
                        <div class="text-sm text-slate-400">UAT Satisfaction</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Work Experience Section -->
        <section id="experience" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="mb-12 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Work Experience</h2>
                <p id="experience-summary" class="mt-4 text-slate-400 text-lg max-w-3xl leading-relaxed">
                    <!-- Dynamic Experience Summary -->
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element">
                    <div class="sticky top-28">
                        <div class="relative group rounded-3xl overflow-hidden border border-slate-800 bg-slate-900 shadow-2xl">
                            <img id="experience-portrait-img" src="" alt="Work Experience Portrait" class="w-full h-[450px] lg:h-[550px] object-cover transition-transform duration-700 group-hover:scale-105">
                            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 via-transparent to-transparent"></div>
                            <div class="absolute bottom-6 left-6 right-6">
                                <span class="px-3 py-1 rounded-full bg-brand-500/20 text-brand-500 text-xs font-semibold border border-brand-500/30">
                                    Career Trajectory
                                </span>
                                <h4 class="text-xl font-bold text-white mt-2">End-to-End Ownership</h4>
                                <p class="text-sm text-slate-300">From concept discovery to operational excellence.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 space-y-10 reveal-element">
                    <div id="experience-container" class="relative pl-6 sm:pl-8 border-l-2 border-slate-800 space-y-12">
                        <!-- Dynamic Experience Cards Injected Here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-16 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white">Skills & Strategic Competencies</h2>
                <p class="text-slate-400 mt-3">A holistic breakdown of product management, analytical methods, and tech domains.</p>
            </div>

            <div id="skills-container" class="grid grid-cols-1 md:grid-cols-3 gap-8 reveal-element">
                <!-- Dynamic Skills Categories -->
            </div>
        </section>

        <!-- Projects / Portfolio Section -->
        <section id="projects" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 reveal-element">
                <div>
                    <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Featured Projects</h2>
                    <p class="text-slate-400 mt-2">Selected products and platform initiatives led across FinTech, ERP, and SaaS.</p>
                </div>
            </div>

            <div id="projects-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Dynamic Project Cards Injected Here -->
            </div>
        </section>

        <!-- Professional Trainings & Certifications Section -->
        <section id="certifications" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-16 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white">Professional Trainings & Certifications</h2>
                <p class="text-slate-400 mt-3">Continuous learning programs and credentials acquired to build industry expertise.</p>
            </div>

            <div id="certifications-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 reveal-element">
                <!-- Dynamic Certification Cards -->
            </div>
        </section>

        <!-- Organizational Experience Section -->
        <section id="organizational" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="mb-12 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Organizational Experience</h2>
                <p class="mt-4 text-slate-400 text-lg max-w-3xl leading-relaxed">
                    Leadership roles, event operations, and community initiatives across university and global organizations.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element">
                    <div class="sticky top-28">
                        <div class="relative group rounded-3xl overflow-hidden border border-slate-800 bg-slate-900 shadow-2xl">
                            <img id="org-experience-portrait-img" src="" alt="Organizational Leadership Portrait" class="w-full h-[450px] lg:h-[550px] object-cover transition-transform duration-700 group-hover:scale-105">
                            <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 via-transparent to-transparent"></div>
                            <div class="absolute bottom-6 left-6 right-6">
                                <span class="px-3 py-1 rounded-full bg-brand-500/20 text-brand-500 text-xs font-semibold border border-brand-500/30">
                                    Community & Leadership
                                </span>
                                <h4 class="text-xl font-bold text-white mt-2">Impact & Engagement</h4>
                                <p class="text-sm text-slate-300">Building communities and driving youth leadership programs.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 space-y-10 reveal-element">
                    <div id="org-experience-container" class="relative pl-6 sm:pl-8 border-l-2 border-slate-800 space-y-12">
                        <!-- Dynamic Organizational Experience Cards Injected Here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="glass-card rounded-3xl p-8 sm:p-12 border border-slate-800/80 reveal-element">
                <h2 class="text-2xl font-bold text-white mb-8 text-center">Stakeholder Endorsements</h2>
                <div id="testimonials-container" class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <!-- Dynamic Testimonials -->
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element space-y-6">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Let's Connect</h2>
                    <p class="text-slate-400 text-lg">
                        Have a strategic product position, enterprise project initiative, or consulting inquiry? Drop a message.
                    </p>

                    <div class="space-y-4 pt-4">
                        <div class="flex items-center gap-4 p-4 rounded-2xl glass-card">
                            <div class="w-12 h-12 rounded-xl bg-brand-500/10 text-brand-500 flex items-center justify-center text-xl">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold">Email</div>
                                <a id="contact-email" href="" class="text-white hover:text-brand-500 font-medium"></a>
                            </div>
                        </div>

                        <!-- LinkedIn Contact Item replacing Phone -->
                        <div class="flex items-center gap-4 p-4 rounded-2xl glass-card">
                            <div class="w-12 h-12 rounded-xl bg-brand-500/10 text-brand-500 flex items-center justify-center text-xl">
                                <i class="fa-brands fa-linkedin-in"></i>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold">LinkedIn</div>
                                <a id="contact-linkedin" href="" target="_blank" class="text-white hover:text-brand-500 font-medium">Anika Tasnim</a>
                            </div>
                        </div>

                        <div class="flex items-center gap-4 p-4 rounded-2xl glass-card">
                            <div class="w-12 h-12 rounded-xl bg-brand-500/10 text-brand-500 flex items-center justify-center text-xl">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold">Location</div>
                                <span id="contact-address" class="text-white font-medium"></span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 reveal-element">
                    <form id="contact-form" class="glass-card rounded-3xl p-8 border border-slate-800 space-y-6">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label for="form-name" class="block text-sm font-medium text-slate-300 mb-2">Full Name</label>
                                <input type="text" id="form-name" required class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="John Doe">
                            </div>
                            <div>
                                <label for="form-phone" class="block text-sm font-medium text-slate-300 mb-2">Phone Number</label>
                                <input type="tel" id="form-phone" class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="+1 (555) 000-0000">
                            </div>
                        </div>

                        <div>
                            <label for="form-email" class="block text-sm font-medium text-slate-300 mb-2">Email Address</label>
                            <input type="email" id="form-email" required class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="john@example.com">
                        </div>

                        <div>
                            <label for="form-message" class="block text-sm font-medium text-slate-300 mb-2">Message</label>
                            <textarea id="form-message" rows="4" required class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="Describe project or inquiry details..."></textarea>
                        </div>

                        <button type="submit" id="form-submit-btn" class="w-full py-4 rounded-xl bg-brand-500 hover:bg-brand-600 text-white font-semibold transition-all shadow-lg shadow-brand-500/20 hover:shadow-brand-500/40 flex items-center justify-center gap-2">
                            <span>Send Message</span>
                            <i class="fa-solid fa-paper-plane text-sm"></i>
                        </button>
                        <div id="form-status" class="text-sm text-center hidden"></div>
                    </form>
                </div>
            </div>
        </section>

        <!-- Google Map Section -->
        <section class="py-12 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="rounded-3xl overflow-hidden glass-card p-3 border border-slate-800/80 reveal-element shadow-2xl">
                <iframe id="google-map" class="w-full h-80 rounded-2xl border-0" loading="lazy" allowfullscreen></iframe>
            </div>
        </section>

    </main>

    <!-- Footer Section -->
    <footer class="border-t border-slate-800/80 bg-slate-950 py-12 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
            <div>
                <span id="footer-name" class="font-bold text-lg text-white">Anika Tasnim</span>
                <p id="footer-designation" class="text-sm text-slate-400">Product Manager | Business Analyst</p>
            </div>
            <div class="text-sm text-slate-500 text-center md:text-right">
                © <span id="current-year"></span> <span id="footer-copyright-name">Anika Tasnim</span>. All Rights Reserved.
            </div>
        </div>
    </footer>

    <!-- Rendering & Logic Engine -->
    <script>
        document.addEventListener("DOMContentLoaded", () => {
            
            // 1. Populate Personal & Contact Info
            document.getElementById("page-title").innerText = `${siteData.personalInfo.name} — ${siteData.personalInfo.designation}`;
            document.getElementById("nav-brand-name").innerText = siteData.personalInfo.name;
            document.getElementById("hero-name").innerText = siteData.personalInfo.name;
            document.getElementById("hero-designation").innerText = siteData.personalInfo.designation;
            document.getElementById("hero-profile-img").src = siteData.personalInfo.profileImage;
            document.getElementById("hero-resume-btn").href = siteData.personalInfo.resumeLink;
            
            // Social Links
            document.getElementById("social-linkedin").href = siteData.socialLinks.linkedin;
            document.getElementById("social-github").href = siteData.socialLinks.github;
            document.getElementById("social-facebook").href = siteData.socialLinks.facebook;
            document.getElementById("social-twitter").href = siteData.socialLinks.twitter;

            // About Section
            document.getElementById("about-title").innerText = siteData.about.title;
            document.getElementById("about-description").innerText = siteData.about.description;

            // Contact Info
            document.getElementById("contact-email").innerText = siteData.contact.email;
            document.getElementById("contact-email").href = `mailto:${siteData.contact.email}`;
            
            // Dynamic binding for LinkedIn contact element
            const contactLinkedin = document.getElementById("contact-linkedin");
            contactLinkedin.innerText = siteData.personalInfo.name;
            contactLinkedin.href = siteData.socialLinks.linkedin;
            
            document.getElementById("contact-address").innerText = siteData.contact.address;
            document.getElementById("google-map").src = siteData.contact.mapUrl;

            // Footer Info
            document.getElementById("footer-name").innerText = siteData.personalInfo.name;
            document.getElementById("footer-designation").innerText = siteData.personalInfo.designation;
            document.getElementById("footer-copyright-name").innerText = siteData.personalInfo.name;
            document.getElementById("current-year").innerText = new Date().getFullYear();

            // 2. Typing Effect for Hero Subtext
            const typingContainer = document.getElementById("typing-text");
            const words = siteData.personalInfo.typingWords || ["Product Strategy", "Agile Execution"];
            let wordIdx = 0, charIdx = 0, isDeleting = false;

            function typeEffect() {
                const currentWord = words[wordIdx];
                if (isDeleting) {
                    typingContainer.innerText = currentWord.substring(0, charIdx - 1);
                    charIdx--;
                } else {
                    typingContainer.innerText = currentWord.substring(0, charIdx + 1);
                    charIdx++;
                }

                let speed = isDeleting ? 40 : 80;
                if (!isDeleting && charIdx === currentWord.length) {
                    speed = 2000;
                    isDeleting = true;
                } else if (isDeleting && charIdx === 0) {
                    isDeleting = false;
                    wordIdx = (wordIdx + 1) % words.length;
                    speed = 400;
                }
                setTimeout(typeEffect, speed);
            }
            typeEffect();

            // 3. Render Work Experience Section (Dynamic)
            document.getElementById("experience-summary").innerText = siteData.experienceSummary;
            document.getElementById("experience-portrait-img").src = siteData.workExperienceImage;

            const expContainer = document.getElementById("experience-container");
            expContainer.innerHTML = siteData.experiences.map(exp => `
                <div class="relative group">
                    <span class="absolute -left-[31px] sm:-left-[39px] top-1.5 w-4 h-4 rounded-full bg-slate-900 border-2 border-brand-500 group-hover:scale-125 transition-transform"></span>

                    <div class="flex flex-wrap items-center gap-3 mb-2">
                        <span class="px-3 py-1 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-xs font-semibold">
                            ${exp.duration}
                        </span>
                        <span class="text-slate-400 text-sm font-medium">${exp.company}</span>
                    </div>

                    <h3 class="text-xl font-bold text-white mb-4">${exp.designation}</h3>

                    <ul class="space-y-2.5 mb-6 text-slate-300 text-sm leading-relaxed">
                        ${exp.responsibilities.map(r => `
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-caret-right text-brand-500 text-xs mt-1"></i>
                                <span>${r}</span>
                            </li>
                        `).join('')}
                    </ul>

                    <div class="space-y-2">
                        <div class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Key Skills Applied</div>
                        <div class="flex flex-wrap gap-2">
                            ${exp.skills.map(s => `
                                <span class="px-3 py-1 rounded-lg text-xs font-medium bg-slate-900/80 border border-slate-800 text-slate-300 hover:border-brand-500/40 hover:text-white transition-all">
                                    ${s}
                                </span>
                            `).join('')}
                        </div>
                    </div>
                </div>
            `).join('');

            // 4. Render Skills Section
            const skillsContainer = document.getElementById("skills-container");
            skillsContainer.innerHTML = siteData.skills.map(cat => `
                <div class="glass-card rounded-2xl p-6 border border-slate-800/80">
                    <h3 class="text-lg font-bold text-white mb-4 pb-3 border-b border-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-brand-500 text-sm"></i>
                        ${cat.category}
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        ${cat.items.map(skill => `
                            <span class="px-3 py-1.5 rounded-lg text-xs font-medium bg-slate-900/60 border border-slate-800 text-slate-300 hover:border-brand-500/30 transition-colors">
                                ${skill}
                            </span>
                        `).join('')}
                    </div>
                </div>
            `).join('');

            // 5. Render Projects Section with Image Reveal Scroll
            const projectsContainer = document.getElementById("projects-container");
            projectsContainer.innerHTML = siteData.projects.map(proj => `
                <div class="glass-card rounded-2xl overflow-hidden border border-slate-800/80 flex flex-col justify-between group hover:border-brand-500/30 transition-all reveal-element">
                    <div>
                        <div class="project-img-wrapper bg-slate-900">
                            <img src="${proj.image}" alt="${proj.title}">
                        </div>

                        <div class="p-6 space-y-3">
                            <h3 class="text-xl font-bold text-white group-hover:text-brand-500 transition-colors">${proj.title}</h3>
                            <p class="text-sm text-slate-400 leading-relaxed">${proj.description}</p>
                            
                            <div class="flex flex-wrap gap-1.5 pt-2">
                                ${proj.technologies.map(t => `
                                    <span class="px-2.5 py-0.5 rounded-md text-[11px] font-medium bg-brand-500/10 text-brand-500">
                                        ${t}
                                    </span>
                                `).join('')}
                            </div>
                        </div>
                    </div>

                    <div class="p-6 pt-0 flex items-center gap-4">
                        <a href="${proj.liveUrl}" class="text-xs font-semibold text-white hover:text-brand-500 flex items-center gap-1.5 transition-colors">
                            <span>Live Preview</span>
                            <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                        </a>
                        <a href="${proj.githubUrl}" class="text-xs font-semibold text-slate-400 hover:text-white flex items-center gap-1.5 transition-colors">
                            <span>Details</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            `).join('');

            // 6. Render Professional Trainings & Certifications Section
            const certsContainer = document.getElementById("certifications-container");
            certsContainer.innerHTML = siteData.certifications.map(cert => `
                <div class="glass-card rounded-2xl p-6 border border-slate-800/80 flex flex-col justify-between group hover:border-brand-500/40 transition-all">
                    <div>
                        <div class="w-10 h-10 rounded-xl bg-brand-500/10 border border-brand-500/20 text-brand-500 flex items-center justify-center text-lg mb-4 group-hover:scale-110 transition-transform">
                            <i class="fa-solid ${cert.icon}"></i>
                        </div>
                        <h3 class="text-base font-bold text-white group-hover:text-brand-500 transition-colors mb-2">${cert.name}</h3>
                    </div>
                    <div class="pt-4 border-t border-slate-800/60 flex items-center justify-between text-xs text-slate-400">
                        <span>Institution</span>
                        <span class="font-semibold text-slate-200">${cert.institution}</span>
                    </div>
                </div>
            `).join('');

            // 7. Render Organizational Experience Section
            document.getElementById("org-experience-portrait-img").src = siteData.organizationalExperiencesImage;

            const orgContainer = document.getElementById("org-experience-container");
            orgContainer.innerHTML = siteData.organizationalExperiences.map(org => `
                <div class="relative group">
                    <span class="absolute -left-[31px] sm:-left-[39px] top-1.5 w-4 h-4 rounded-full bg-slate-900 border-2 border-brand-500 group-hover:scale-125 transition-transform"></span>

                    <div class="flex flex-wrap items-center gap-3 mb-2">
                        <span class="px-3 py-1 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-xs font-semibold">
                            ${org.duration}
                        </span>
                        <span class="text-slate-400 text-sm font-medium">${org.organization}</span>
                    </div>

                    <h3 class="text-xl font-bold text-white mb-4">${org.designation}</h3>

                    <ul class="space-y-2.5 text-slate-300 text-sm leading-relaxed">
                        ${org.responsibilities.map(r => `
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-square-check text-brand-500 text-xs mt-1"></i>
                                <span>${r}</span>
                            </li>
                        `).join('')}
                    </ul>
                </div>
            `).join('');

            // 8. Render Testimonials
            const testContainer = document.getElementById("testimonials-container");
            testContainer.innerHTML = siteData.testimonials.map(t => `
                <div class="space-y-4">
                    <i class="fa-solid fa-quote-left text-2xl text-brand-500/40"></i>
                    <p class="text-slate-300 text-base italic leading-relaxed">"${t.quote}"</p>
                    <div>
                        <div class="font-bold text-white text-sm">${t.author}</div>
                        <div class="text-xs text-slate-400">${t.role}</div>
                    </div>
                </div>
            `).join('');

            // 9. Mobile Menu Toggle
            const mobileMenuBtn = document.getElementById("mobile-menu-btn");
            const mobileMenu = document.getElementById("mobile-menu");
            mobileMenuBtn.addEventListener("click", () => {
                mobileMenu.classList.toggle("hidden");
            });

            document.querySelectorAll(".mobile-nav-link").forEach(link => {
                link.addEventListener("click", () => mobileMenu.classList.add("hidden"));
            });

            // 10. Scroll Reveal Observer
            const observerOptions = { threshold: 0.1, rootMargin: "0px 0px -50px 0px" };
            const revealObserver = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add("active");
                        observer.unobserve(entry.target);
                    }
                });
            }, observerOptions);

            document.querySelectorAll(".reveal-element").forEach(el => revealObserver.observe(el));

            // 11. Contact Form Submission Handling
            const contactForm = document.getElementById("contact-form");
            const formSubmitBtn = document.getElementById("form-submit-btn");
            const formStatus = document.getElementById("form-status");

            contactForm.addEventListener("submit", async (e) => {
                e.preventDefault();
                
                const name = document.getElementById("form-name").value.trim();
                const phone = document.getElementById("form-phone").value.trim();
                const email = document.getElementById("form-email").value.trim();
                const message = document.getElementById("form-message").value.trim();

                formSubmitBtn.disabled = true;
                formSubmitBtn.innerHTML = `<i class="fa-solid fa-spinner animate-spin"></i> Sending...`;
                formStatus.classList.add("hidden");

                try {
                    if (siteData.integrations.googleScriptUrl) {
                        const formData = new URLSearchParams();
                        formData.append("name", name);
                        formData.append("phone", phone);
                        formData.append("email", email);
                        formData.append("message", message);

                        fetch(siteData.integrations.googleScriptUrl, {
                            method: "POST",
                            mode: "no-cors",
                            headers: { "Content-Type": "application/x-www-form-urlencoded" },
                            body: formData.toString()
                        });
                    }

                    if (siteData.integrations.telegramBotToken && siteData.integrations.telegramChatId) {
                        const tgText = `📬 *New Portfolio Inquiry*\n\n*Name:* ${name}\n*Phone:* ${phone}\n*Email:* ${email}\n*Message:* ${message}`;
                        await fetch(`https://api.telegram.org/bot${siteData.integrations.telegramBotToken}/sendMessage`, {
                            method: "POST",
                            headers: { "Content-Type": "application/json" },
                            body: JSON.stringify({
                                chat_id: siteData.integrations.telegramChatId,
                                text: tgText,
                                parse_mode: "Markdown"
                            })
                        });
                    }

                    formStatus.innerText = "Thank you! Your message has been received successfully.";
                    formStatus.className = "text-sm text-center text-emerald-400 font-medium block";
                    contactForm.reset();
                } catch (err) {
                    console.error(err);
                    formStatus.innerText = "Form submitted! Thank you.";
                    formStatus.className = "text-sm text-center text-emerald-400 font-medium block";
                    contactForm.reset();
                } finally {
                    formSubmitBtn.disabled = false;
                    formSubmitBtn.innerHTML = `<span>Send Message</span><i class="fa-solid fa-paper-plane text-sm"></i>`;
                }
            });
        });
    </script>
</body>
</html>
