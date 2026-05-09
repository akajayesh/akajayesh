<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jay.dev | Full Stack Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap" rel="stylesheet" />
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        background: '#0D1117',
                        surface: '#0A0A0A',
                        'surface-dim': '#131313',
                        primary: '#9966CC',
                        secondary: '#d5bbff',
                        'on-surface': '#e5e2e1',
                        'on-surface-variant': '#94A3B8',
                        outline: '#30363D'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #0D1117; color: #e5e2e1; scroll-behavior: smooth; }
        .bento-card {
            background-color: #0A0A0A;
            border: 1px solid #30363D;
            transition: all 0.3s ease;
        }
        .bento-card:hover {
            border-color: #9966CC;
            box-shadow: 0 0 15px rgba(153, 102, 204, 0.1);
        }
        .stats-card {
            background-color: #131313;
            border: 1px solid #30363D;
        }
        .blur-nav {
            backdrop-filter: blur(12px);
            background-color: rgba(13, 17, 23, 0.8);
            border-bottom: 1px solid #30363D;
        }
    </style>
</head>
<body class="antialiased min-h-screen font-sans selection:bg-primary/30">

<nav class="fixed top-0 w-full z-50 blur-nav transition-all">
    <div class="max-w-5xl mx-auto px-6 h-20 flex items-center justify-between">
        <a href="#" class="font-display font-bold text-xl tracking-tight text-white">Jay.dev</a>
        <div class="hidden md:flex items-center space-x-8">
            <a href="#projects" class="text-on-surface-variant hover:text-white text-sm font-mono tracking-widest uppercase transition-colors">Projects</a>
            <a href="#stack" class="text-on-surface-variant hover:text-white text-sm font-mono tracking-widest uppercase transition-colors">Stack</a>
            <a href="#stats" class="text-on-surface-variant hover:text-white text-sm font-mono tracking-widest uppercase transition-colors">Stats</a>
            <a href="https://my-portfolio-theta-henna-16.vercel.app" target="_blank" class="bg-primary text-white px-5 py-2 rounded-md font-mono text-sm tracking-wide hover:bg-primary/90 transition-colors">Resume</a>
        </div>
    </div>
</nav>

<main class="max-w-4xl mx-auto px-6 pt-32 pb-24 space-y-32">
    
    <!-- Hero Section -->
    <section class="space-y-6 pt-12 animate-fade-in-up">
        <div class="inline-flex items-center space-x-2 px-3 py-1.5 rounded-full border border-outline bg-surface-dim">
            <span class="w-2 h-2 rounded-full bg-primary animate-pulse"></span>
            <span class="text-xs font-mono tracking-widest text-primary uppercase">Available for work</span>
        </div>
        
        <h1 class="font-display text-5xl md:text-6xl font-bold leading-tight">
            Hello World <span class="text-primary inline-block hover:-rotate-12 transition-transform">👨‍💻</span>, I'm <span class="text-primary">Jay</span>
        </h1>
        
        <p class="font-mono text-secondary text-sm md:text-base tracking-widest uppercase mb-1">
            IT Engineer • Full Stack Engineer • Backend Engineer
        </p>
        <p class="font-mono text-secondary text-sm md:text-base tracking-widest uppercase pt-0 mt-0">
            AI Engineer • Software Engineer • Software Tester
        </p>
        
        <p class="text-on-surface-variant max-w-2xl text-lg leading-relaxed pt-2">
            I specialize in building robust backend systems and AI-driven applications. My focus lies in creating scalable software through modern frameworks like Django and React, ensuring quality through rigorous software testing and automated pipelines. Currently focused on internship growth and production-grade deployments.
        </p>
        
        <div class="flex flex-wrap gap-4 pt-6">
            <a href="mailto:jayeshsutar312@gmail.com" class="inline-flex items-center justify-center space-x-2 bg-primary text-white px-6 py-3 rounded-lg font-mono text-sm hover:ring-2 hover:ring-primary/50 transition-all shadow-[0_0_15px_rgba(153,102,204,0.3)]">
                <span>Let's Connect</span>
                <span class="material-symbols-outlined text-sm">arrow_forward</span>
            </a>
            <a href="https://github.com/akajayesh" target="_blank" class="inline-flex items-center justify-center space-x-2 px-6 py-3 rounded-lg font-mono text-sm border border-outline hover:bg-surface transition-colors">
                <span>View GitHub</span>
            </a>
        </div>
    </section>

    <!-- Tech Stack -->
    <section id="stack" class="space-y-8">
        <h2 class="font-display text-2xl font-semibold flex items-center space-x-3">
            <span class="material-symbols-outlined text-primary">layers</span>
            <span>Core Technical Stack</span>
        </h2>
        
        <div class="grid grid-cols-2 lg:grid-cols-6 gap-4">
            <div class="bento-card rounded-xl p-6 flex flex-col items-center justify-center space-y-2 group">
                <span class="font-bold text-primary text-lg group-hover:scale-110 transition-transform">React</span>
                <span class="text-[10px] uppercase font-mono tracking-widest text-on-surface-variant">Frontend</span>
            </div>
            <div class="bento-card rounded-xl p-6 flex flex-col items-center justify-center space-y-2 group">
                <span class="font-bold text-primary text-lg group-hover:scale-110 transition-transform">Tailwind</span>
                <span class="text-[10px] uppercase font-mono tracking-widest text-on-surface-variant">Styling</span>
            </div>
            <div class="bento-card rounded-xl p-6 flex flex-col items-center justify-center space-y-2 group">
                <span class="font-bold text-secondary text-lg group-hover:scale-110 transition-transform">Django</span>
                <span class="text-[10px] uppercase font-mono tracking-widest text-on-surface-variant">Backend</span>
            </div>
            <div class="bento-card rounded-xl p-6 flex flex-col items-center justify-center space-y-2 group">
                <span class="font-bold text-secondary text-lg group-hover:scale-110 transition-transform">PostgreSQL</span>
                <span class="text-[10px] uppercase font-mono tracking-widest text-on-surface-variant">Database</span>
            </div>
            <div class="bento-card rounded-xl p-6 flex flex-col items-center justify-center space-y-2 group">
                <span class="font-bold text-primary text-lg group-hover:scale-110 transition-transform">Python</span>
                <span class="text-[10px] uppercase font-mono tracking-widest text-on-surface-variant">Logic</span>
            </div>
            <div class="bento-card rounded-xl p-6 flex flex-col items-center justify-center space-y-2 group">
                <span class="font-bold text-primary text-lg group-hover:scale-110 transition-transform">TypeScript</span>
                <span class="text-[10px] uppercase font-mono tracking-widest text-on-surface-variant">Typing</span>
            </div>
        </div>
    </section>

    <!-- Featured Projects -->
    <section id="projects" class="space-y-8">
        <h2 class="font-display text-2xl font-semibold flex items-center space-x-3">
            <span class="material-symbols-outlined text-primary">rocket_launch</span>
            <span>Featured Architecture</span>
        </h2>
        
        <div class="space-y-6">
            <!-- Project 1 -->
            <div class="bento-card rounded-2xl p-8 grid md:grid-cols-2 gap-8 items-center group">
                <div class="space-y-4">
                    <h3 class="font-display text-2xl font-bold text-primary">PermAware</h3>
                    <p class="text-on-surface-variant leading-relaxed text-sm">
                        A high-security permission monitoring system designed to analyze and regulate sensitive data access in enterprise environments. Built with a focus on real-time alerting and audit trails.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-primary">Python</span>
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-primary">Django</span>
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-primary">PostgreSQL</span>
                    </div>
                    <div class="pt-4">
                        <a href="https://github.com/akajayesh" target="_blank" class="inline-flex items-center space-x-2 text-sm font-mono hover:text-primary transition-colors">
                            <span class="material-symbols-outlined text-base">link</span>
                            <span>View Repository</span>
                        </a>
                    </div>
                </div>
                <div class="bg-surface border border-outline rounded-xl aspect-video relative overflow-hidden group-hover:border-primary/50 transition-colors flex items-center justify-center">
                    <div class="absolute inset-0 bg-gradient-to-tr from-primary/10 to-transparent"></div>
                    <span class="material-symbols-outlined text-5xl text-outline group-hover:text-primary transition-colors">monitoring</span>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="bento-card rounded-2xl p-8 grid md:grid-cols-2 gap-8 items-center group">
                <div class="bg-surface border border-outline rounded-xl aspect-video relative overflow-hidden group-hover:border-secondary/50 transition-colors flex items-center justify-center order-2 md:order-1">
                    <div class="absolute inset-0 bg-gradient-to-br from-secondary/10 to-transparent"></div>
                    <span class="material-symbols-outlined text-5xl text-outline group-hover:text-secondary transition-colors">psychiatry</span>
                </div>
                <div class="space-y-4 order-1 md:order-2">
                    <h3 class="font-display text-2xl font-bold text-secondary">F.R.I.D.A.Y</h3>
                    <p class="text-on-surface-variant leading-relaxed text-sm">
                        Sophisticated AI assistant leveraging Language Models to automate developer workflows. Features natural language command processing and deep IDE integration for rapid prototyping.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-secondary">PyTorch</span>
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-secondary">FastAPI</span>
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-secondary">Redis</span>
                    </div>
                    <div class="pt-4">
                        <a href="https://github.com/akajayesh" target="_blank" class="inline-flex items-center space-x-2 text-sm font-mono hover:text-secondary transition-colors">
                            <span class="material-symbols-outlined text-base">link</span>
                            <span>View Repository</span>
                        </a>
                    </div>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="bento-card rounded-2xl p-8 grid md:grid-cols-2 gap-8 items-center group">
                <div class="space-y-4">
                    <h3 class="font-display text-2xl font-bold text-primary">FlowTime</h3>
                    <p class="text-on-surface-variant leading-relaxed text-sm">
                        A productivity engine that uses data-driven insights to optimize developer focus sessions. Integrates with various Git providers to correlate commit activity with deep work periods.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-primary">React</span>
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-primary">TypeScript</span>
                        <span class="px-2.5 py-1 rounded bg-surface border border-outline text-xs font-mono text-primary">D3.js</span>
                    </div>
                    <div class="pt-4">
                        <a href="https://github.com/akajayesh" target="_blank" class="inline-flex items-center space-x-2 text-sm font-mono hover:text-primary transition-colors">
                            <span class="material-symbols-outlined text-base">link</span>
                            <span>View Repository</span>
                        </a>
                    </div>
                </div>
                <div class="bg-surface border border-outline rounded-xl aspect-video relative overflow-hidden group-hover:border-primary/50 transition-colors flex items-center justify-center">
                    <div class="absolute inset-0 bg-gradient-to-tr from-primary/10 to-transparent"></div>
                    <span class="material-symbols-outlined text-5xl text-outline group-hover:text-primary transition-colors">hourglass_top</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats & Activity -->
    <section id="stats" class="space-y-8">
        <h2 class="font-display text-2xl font-semibold flex items-center space-x-3">
            <span class="material-symbols-outlined text-primary">query_stats</span>
            <span>Development Velocity</span>
        </h2>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
            <div class="stats-card rounded-xl p-6 space-y-2">
                <div class="text-[10px] font-mono tracking-widest text-on-surface-variant uppercase">Current Streak</div>
                <div class="text-3xl font-bold text-primary">15 Days</div>
                <div class="w-full bg-surface h-1.5 rounded-full mt-4">
                    <div class="bg-primary h-1.5 rounded-full w-[75%]"></div>
                </div>
            </div>
            <div class="stats-card rounded-xl p-6 space-y-2">
                <div class="text-[10px] font-mono tracking-widest text-on-surface-variant uppercase">Total Contributions</div>
                <div class="text-3xl font-bold text-primary">842</div>
                <div class="text-xs font-mono text-secondary">+12% from last month</div>
            </div>
            <div class="stats-card rounded-xl p-6 space-y-2">
                <div class="text-[10px] font-mono tracking-widest text-on-surface-variant uppercase">Profile Views</div>
                <div class="text-3xl font-bold text-primary">1,204</div>
                <div class="text-xs font-mono text-secondary">Top 5% of region</div>
            </div>
        </div>

        <div class="bento-card rounded-xl p-8 overflow-hidden">
            <div class="flex items-center justify-between mb-6">
                <div class="text-xs font-mono text-on-surface-variant uppercase tracking-widest">Contribution Graph</div>
                <div class="flex items-center space-x-1">
                    <div class="w-3 h-3 rounded-sm bg-[#161b22]"></div>
                    <div class="w-3 h-3 rounded-sm bg-[#322343]"></div>
                    <div class="w-3 h-3 rounded-sm bg-[#4a1073]"></div>
                    <div class="w-3 h-3 rounded-sm bg-[#6c10aa]"></div>
                    <div class="w-3 h-3 rounded-sm bg-primary"></div>
                </div>
            </div>
            
            <div id="contribution-graph" class="grid grid-flow-col gap-1 overflow-x-auto pb-2 scrollbar-hide" style="grid-template-rows: repeat(7, minmax(0, 1fr));">
                <!-- Squares injected by JS -->
            </div>
        </div>
    </section>

    <!-- Contact & Footer -->
    <section class="border-t border-outline pt-20 pb-10 text-center space-y-12">
        <div class="space-y-4">
            <h2 class="font-display text-4xl font-bold">Let's build something <span class="text-primary italic">impactful.</span></h2>
            <p class="text-on-surface-variant max-w-xl mx-auto">
                Currently open to internship opportunities, collaborative open-source projects, and technical consultancy in backend architecture.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <a href="mailto:jayeshsutar312@gmail.com" class="bento-card rounded-xl p-6 flex items-center space-x-4 group text-left">
                <span class="material-symbols-outlined text-primary group-hover:scale-110 transition-transform">alternate_email</span>
                <div>
                    <div class="text-[10px] font-mono tracking-widest text-on-surface-variant uppercase">Email</div>
                    <div class="text-sm">jayesh@sutar.dev</div>
                </div>
            </a>
            <a href="https://my-portfolio-theta-henna-16.vercel.app" target="_blank" class="bento-card rounded-xl p-6 flex items-center space-x-4 group text-left">
                <span class="material-symbols-outlined text-primary group-hover:scale-110 transition-transform">language</span>
                <div>
                    <div class="text-[10px] font-mono tracking-widest text-on-surface-variant uppercase">Portfolio</div>
                    <div class="text-sm truncate">jayeshsutar.com</div>
                </div>
            </a>
            <a href="https://github.com/akajayesh" target="_blank" class="bento-card rounded-xl p-6 flex items-center space-x-4 group text-left">
                <span class="material-symbols-outlined text-primary group-hover:scale-110 transition-transform">terminal</span>
                <div>
                    <div class="text-[10px] font-mono tracking-widest text-on-surface-variant uppercase">GitHub</div>
                    <div class="text-sm">akajayesh</div>
                </div>
            </a>
        </div>
    </section>

</main>

<footer class="border-t border-outline py-8 bg-surface-dim">
    <div class="max-w-4xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4">
        <p class="text-xs font-mono text-on-surface-variant">© 2026 Jayesh Sutar • Engineered for Quiet Excellence</p>
        <div class="flex space-x-6 text-sm font-mono text-on-surface-variant">
            <a href="https://github.com/akajayesh" target="_blank" class="hover:text-primary transition-colors">GitHub</a>
            <a href="https://www.linkedin.com/in/jayesh-sutar-89951825a" target="_blank" class="hover:text-primary transition-colors">LinkedIn</a>
            <a href="tel:+917387885582" class="hover:text-primary transition-colors">Contact</a>
        </div>
        <p class="text-xs font-mono text-secondary">v2.4.0-stable</p>
    </div>
</footer>

<script>
    // Generate mock contribution graph
    const graphContainer = document.getElementById('contribution-graph');
    const cols = 52;
    const rows = 7;
    const colors = ['bg-[#161b22]', 'bg-[#161b22]', 'bg-[#161b22]', 'bg-[#322343]', 'bg-[#4a1073]', 'bg-[#6c10aa]', 'bg-primary'];
    
    for (let c = 0; c < cols; c++) {
        for (let r = 0; r < rows; r++) {
            const div = document.createElement('div');
            // Randomly select color with higher bias for empty/dark
            const rand = Math.random();
            let colorIndex = 0;
            if (rand > 0.85) colorIndex = Math.floor(Math.random() * 4) + 3;
            else if (rand > 0.7) colorIndex = 3;
            
            div.className = `w-3 h-3 rounded-[2px] ${colors[colorIndex]} transition-colors hover:ring-1 hover:ring-white`;
            graphContainer.appendChild(div);
        }
    }
</script>

</body>
</html>
