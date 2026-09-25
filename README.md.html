<!DOCTYPE html>
<html lang="es" class="dark scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brandon Rambauth | SRE & Observability Ops Control</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        noc: {
                            bg: '#07090e',
                            sidebar: '#0d111a',
                            card: '#121824',
                            border: '#1f293d',
                            neonGreen: '#00ff9d',
                            neonCyan: '#00e5ff',
                            neonPurple: '#a855f7',
                            amber: '#f59e0b'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['JetBrains Mono', 'Fira Code', 'monospace']
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome Icons & Google Fonts -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600&family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet">
    
    <style>
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #07090e;
        }
        ::-webkit-scrollbar-thumb {
            background: #1f293d;
            border-radius: 3px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #00e5ff;
        }
        .glow-green {
            box-shadow: 0 0 20px -3px rgba(0, 255, 157, 0.25);
        }
        .glow-cyan {
            box-shadow: 0 0 20px -3px rgba(0, 229, 255, 0.25);
        }
        .bg-tech-grid {
            background-size: 24px 24px;
            background-image: 
                linear-gradient(to right, rgba(31, 41, 61, 0.3) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(31, 41, 61, 0.3) 1px, transparent 1px);
        }
        .scanline-overlay {
            background: linear-gradient(
                to bottom,
                rgba(255,255,255,0),
                rgba(255,255,255,0) 50%,
                rgba(0, 0, 0, 0.3) 50%,
                rgba(0, 0, 0, 0.3)
            );
            background-size: 100% 4px;
        }
    </style>
</head>
<body class="bg-noc-bg text-slate-200 font-sans antialiased min-h-screen bg-tech-grid selection:bg-noc-neonGreen selection:text-noc-bg flex flex-col">

    <header class="sticky top-0 z-50 bg-noc-sidebar/95 backdrop-blur-md border-b border-noc-border text-xs font-mono">
        <div class="max-w-[1700px] mx-auto px-4 py-2.5 flex flex-wrap items-center justify-between gap-4">
            
            <!-- System Identity -->
            <div class="flex items-center space-x-3">
                <a href="#hero" class="flex items-center gap-2 font-bold text-slate-100 hover:text-noc-neonCyan transition-colors">
                    <span class="w-2.5 h-2.5 rounded-full bg-noc-neonGreen animate-pulse"></span>
                    <span class="text-noc-neonGreen font-mono">&gt; OPS_CTRL</span>
                    <span class="hidden sm:inline text-slate-400">| Brandon Rambauth</span>
                </a>
                <span class="hidden md:inline-block px-2 py-0.5 rounded bg-emerald-500/10 text-noc-neonGreen border border-noc-neonGreen/30 text-[10px]">
                    STATUS: ALL_SYSTEMS_NOMINAL
                </span>
            </div>

            <!-- Ticker Stats -->
            <div class="hidden lg:flex items-center space-x-6 text-slate-400">
                <div class="flex items-center gap-1.5">
                    <i class="fa-solid fa-bolt text-noc-neonCyan"></i>
                    <span>MTTR OPTIMIZATION: <strong class="text-white">-40%</strong></span>
                </div>
                <div class="flex items-center gap-1.5">
                    <i class="fa-solid fa-shield-cat text-noc-neonGreen"></i>
                    <span>PREDICTIVE DETECTION: <strong class="text-white">95%</strong></span>
                </div>
                <div class="flex items-center gap-1.5">
                    <i class="fa-solid fa-network-wired text-noc-neonPurple"></i>
                    <span>STACK: <strong class="text-white">Dynatrace / Datadog / SRE</strong></span>
                </div>
            </div>

            <!-- Quick Contacts Header CTA -->
            <div class="flex items-center space-x-3">
                <a href="https://www.linkedin.com/in/brandon-rambauth/" target="_blank" rel="noopener noreferrer" class="p-1.5 rounded bg-noc-card border border-noc-border hover:border-noc-neonCyan text-slate-300 hover:text-noc-neonCyan transition-all" title="LinkedIn">
                    <i class="fa-brands fa-linkedin text-sm"></i>
                </a>
                <a href="mailto:bc.cespedes2002@gmail.com" class="p-1.5 rounded bg-noc-card border border-noc-border hover:border-noc-neonGreen text-slate-300 hover:text-noc-neonGreen transition-all" title="Email">
                    <i class="fa-regular fa-envelope text-sm"></i>
                </a>
                <a href="tel:+573194892106" class="px-2.5 py-1 rounded bg-noc-neonCyan/10 text-noc-neonCyan border border-noc-neonCyan/30 font-bold hover:bg-noc-neonCyan hover:text-noc-bg transition-all">
                    <i class="fa-solid fa-phone mr-1"></i> +57 3194892106
                </a>
            </div>

        </div>
    </header>

    <div class="flex-1 max-w-[1700px] w-full mx-auto flex flex-col lg:flex-row">
        
        <!-- SIDEBAR NAVIGATION -->
        <aside class="w-full lg:w-64 bg-noc-sidebar/60 border-b lg:border-b-0 lg:border-r border-noc-border p-4 shrink-0 font-mono text-xs">
            <div class="sticky top-16 space-y-6">
                
                <!-- Operator Info Card -->
                <div class="bg-noc-card p-3.5 rounded-lg border border-noc-border">
                    <div class="text-slate-400 text-[10px] uppercase tracking-wider mb-1">OPERATOR_PROFILE</div>
                    <div class="font-bold text-white text-sm">Brandon Rambauth</div>
                    <div class="text-noc-neonCyan text-[11px] font-semibold">Especialista Observabilidad / SRE</div>
                    <div class="mt-2 pt-2 border-t border-noc-border/60 text-slate-400 text-[10px] space-y-1">
                        <p><i class="fa-solid fa-location-dot text-slate-500 mr-1"></i> Bogotá, Colombia</p>
                        <p><i class="fa-solid fa-graduation-cap text-slate-500 mr-1"></i> MSc (c) Data Analytics</p>
                    </div>
                </div>

                <!-- Navigation List -->
                <nav class="space-y-1">
                    <div class="text-slate-500 text-[10px] uppercase tracking-wider px-2 py-1 font-semibold">NAVIGATION_PANELS</div>
                    <a href="#hero" class="flex items-center gap-2.5 px-3 py-2 rounded-md bg-noc-card text-noc-neonCyan font-bold border border-noc-border hover:border-noc-neonCyan/50 transition-colors">
                        <i class="fa-solid fa-terminal w-4"></i> Overview / Terminal
                    </a>
                    <a href="#kpis" class="flex items-center gap-2.5 px-3 py-2 rounded-md text-slate-300 hover:bg-noc-card hover:text-noc-neonGreen transition-colors">
                        <i class="fa-solid fa-chart-simple w-4"></i> Métricas & KPI
                    </a>
                    <a href="#experience" class="flex items-center gap-2.5 px-3 py-2 rounded-md text-slate-300 hover:bg-noc-card hover:text-noc-neonGreen transition-colors">
                        <i class="fa-solid fa-server w-4"></i> Experiencia Laboral
                    </a>
                    <a href="#stack" class="flex items-center gap-2.5 px-3 py-2 rounded-md text-slate-300 hover:bg-noc-card hover:text-noc-neonGreen transition-colors">
                        <i class="fa-solid fa-cubes w-4"></i> Tech Stack & Cloud
                    </a>
                    <a href="#education" class="flex items-center gap-2.5 px-3 py-2 rounded-md text-slate-300 hover:bg-noc-card hover:text-noc-neonGreen transition-colors">
                        <i class="fa-solid fa-graduation-cap w-4"></i> Educación & Certs
                    </a>
                    <a href="#terminal-widget" class="flex items-center gap-2.5 px-3 py-2 rounded-md text-slate-300 hover:bg-noc-card hover:text-noc-neonPurple transition-colors">
                        <i class="fa-solid fa-code w-4"></i> Interactive Bash
                    </a>
                </nav>

                <!-- Status Panel Widget -->
                <div class="bg-noc-card/80 p-3 rounded-lg border border-noc-border space-y-2">
                    <div class="flex justify-between items-center text-[10px]">
                        <span class="text-slate-400">TELEMETRY_ENGINE</span>
                        <span class="text-noc-neonGreen font-bold">ONLINE</span>
                    </div>
                    <div class="w-full bg-slate-800 h-1.5 rounded-full overflow-hidden">
                        <div class="bg-noc-neonGreen h-full w-[98%]"></div>
                    </div>
                    <div class="text-[10px] text-slate-400 flex justify-between">
                        <span>Cluster: Multi-tenant</span>
                        <span>SLA: 99.9%</span>
                    </div>
                </div>

            </div>
        </aside>

        <!-- MAIN DASHBOARD CONTENT AREA -->
        <main class="flex-1 p-4 lg:p-8 space-y-12 overflow-hidden">
            
            <section id="hero" class="relative">
                <div class="bg-noc-card border border-noc-border rounded-xl p-6 lg:p-8 shadow-2xl relative overflow-hidden glow-cyan">
                    <div class="absolute top-0 right-0 p-4 font-mono text-[10px] text-slate-600 hidden sm:block">
                        HOST: SRE-NODE-01 | REGION: BOG-COL
                    </div>

                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                        
                        <!-- Left Bio Column -->
                        <div class="lg:col-span-8 space-y-5">
                            
                            <!-- Prompt Simulation -->
                            <div class="font-mono text-xs sm:text-sm text-noc-neonGreen flex items-center gap-2 bg-noc-bg/80 px-3 py-1.5 rounded border border-noc-border max-w-max">
                                <span class="text-noc-neonPurple">sys_admin@brandon-sre:~$</span>
                                <span>whoami</span>
                            </div>

                            <h1 class="text-3xl sm:text-5xl font-extrabold text-white tracking-tight">
                                Brandon David <br/>
                                <span class="text-transparent bg-clip-text bg-gradient-to-r from-noc-neonCyan via-noc-neonGreen to-noc-neonPurple">
                                    Rambauth Céspedes
                                </span>
                            </h1>

                            <div class="font-mono text-slate-300 text-sm sm:text-base font-semibold flex items-center gap-2">
                                <span class="px-2 py-0.5 rounded bg-noc-neonCyan/10 text-noc-neonCyan border border-noc-neonCyan/30">
                                    Especialista en Observabilidad & SRE
                                </span>
                                <span class="text-slate-500">|</span>
                                <span class="text-slate-400">Ingeniero de Sistemas</span>
                            </div>

                            <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                                Más de <strong class="text-white">4 años de experiencia</strong> transformando esquemas reactivos de monitoreo en <strong class="text-noc-neonGreen">modelos predictivos basados en analítica de datos, mejora de procesos y automatización</strong>. Especializado en visibilidad en tiempo real, reducción acelerada de MTTR y optimización de costos en entornos de alta exigencia transaccional.
                            </p>

                            <!-- Tool Badges -->
                            <div class="pt-2 flex flex-wrap gap-2 text-xs font-mono">
                                <span class="px-2.5 py-1 rounded bg-noc-bg text-noc-neonCyan border border-noc-border">Dynatrace (SaaS/Managed)</span>
                                <span class="px-2.5 py-1 rounded bg-noc-bg text-noc-neonGreen border border-noc-border">Datadog</span>
                                <span class="px-2.5 py-1 rounded bg-noc-bg text-noc-amber border border-noc-border">SolarWinds</span>
                                <span class="px-2.5 py-1 rounded bg-noc-bg text-noc-neonPurple border border-noc-border">Python & Scripting</span>
                                <span class="px-2.5 py-1 rounded bg-noc-bg text-slate-300 border border-noc-border">IBM Cloud / AWS / Azure</span>
                            </div>

                            <!-- CTAs -->
                            <div class="pt-4 flex flex-wrap gap-3">
                                <a href="mailto:bc.cespedes2002@gmail.com" class="px-5 py-2.5 rounded-lg bg-noc-neonCyan text-noc-bg font-bold font-mono text-xs hover:bg-cyan-300 transition-all shadow-lg shadow-noc-neonCyan/20 flex items-center gap-2">
                                    <i class="fa-regular fa-paper-plane"></i> Contactar Ahora
                                </a>
                                <a href="https://www.linkedin.com/in/brandon-rambauth/" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-lg bg-noc-bg border border-noc-border text-slate-200 font-mono text-xs hover:border-noc-neonGreen hover:text-noc-neonGreen transition-all flex items-center gap-2">
                                    <i class="fa-brands fa-linkedin"></i> Perfil LinkedIn
                                </a>
                                <button onclick="window.print()" class="px-4 py-2.5 rounded-lg bg-noc-bg border border-noc-border text-slate-400 font-mono text-xs hover:text-white transition-all flex items-center gap-2" title="Imprimir / Exportar a PDF">
                                    <i class="fa-solid fa-print"></i> PDF CV
                                </button>
                            </div>

                        </div>

                        <!-- Right Live Telemetry Graphic / Photo Card -->
                        <div class="lg:col-span-4">
                            <div class="bg-noc-bg/90 rounded-lg p-4 border border-noc-border font-mono text-xs space-y-4">
                                <div class="flex justify-between items-center pb-2 border-b border-noc-border text-slate-400">
                                    <span>SYSTEM_HEALTH_METRICS</span>
                                    <span class="text-noc-neonGreen"><i class="fa-solid fa-circle text-[8px] mr-1"></i>LIVE</span>
                                </div>

                                <div class="space-y-3">
                                    <div>
                                        <div class="flex justify-between text-slate-300 mb-1">
                                            <span>Predictive Alerting:</span>
                                            <span class="text-noc-neonGreen font-bold">95.0% Accuracy</span>
                                        </div>
                                        <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden">
                                            <div class="bg-noc-neonGreen h-full w-[95%]"></div>
                                        </div>
                                    </div>

                                    <div>
                                        <div class="flex justify-between text-slate-300 mb-1">
                                            <span>Dynatrace Cost Reduction:</span>
                                            <span class="text-noc-neonCyan font-bold">33% Saved</span>
                                        </div>
                                        <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden">
                                            <div class="bg-noc-neonCyan h-full w-[80%]"></div>
                                        </div>
                                    </div>

                                    <div>
                                        <div class="flex justify-between text-slate-300 mb-1">
                                            <span>Splunk to Dynatrace Migration:</span>
                                            <span class="text-noc-neonPurple font-bold">100% Complete</span>
                                        </div>
                                        <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden">
                                            <div class="bg-noc-neonPurple h-full w-[100%]"></div>
                                        </div>
                                    </div>
                                </div>

                                <div class="p-3 bg-noc-card rounded border border-noc-border/80 text-slate-400 text-[11px] space-y-1">
                                    <div class="text-slate-300 font-bold mb-1">// Referencias profesionales:</div>
                                    <p>• Diego Bermúdez (Líder NOC/SOC PearSolutions)</p>
                                    <p>• Harol Rambauth (Consultor en Bosonit)</p>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </section>

            <section id="kpis" class="space-y-4">
                <div class="flex items-center gap-2 text-xs font-mono text-noc-neonCyan">
                    <i class="fa-solid fa-chart-line"></i>
                    <span class="uppercase tracking-wider">// KPI_METRICS & OPERATIONAL_IMPACT</span>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                    
                    <!-- KPI 1 -->
                    <div class="bg-noc-card p-5 rounded-xl border border-noc-border hover:border-noc-neonGreen/50 transition-all group">
                        <div class="flex justify-between items-start">
                            <span class="text-xs font-mono text-slate-500">METRIC_01</span>
                            <i class="fa-solid fa-shield-halved text-noc-neonGreen text-lg group-hover:scale-110 transition-transform"></i>
                        </div>
                        <div class="text-3xl font-extrabold font-mono text-white mt-2 mb-1">95%</div>
                        <div class="text-xs font-bold text-noc-neonGreen mb-1">Detección Predictiva</div>
                        <p class="text-xs text-slate-400">Incidentes detectados antes de afectar al usuario final en Puntos Colombia.</p>
                    </div>

                    <!-- KPI 2 -->
                    <div class="bg-noc-card p-5 rounded-xl border border-noc-border hover:border-noc-neonCyan/50 transition-all group">
                        <div class="flex justify-between items-start">
                            <span class="text-xs font-mono text-slate-500">METRIC_02</span>
                            <i class="fa-solid fa-coins text-noc-neonCyan text-lg group-hover:scale-110 transition-transform"></i>
                        </div>
                        <div class="text-3xl font-extrabold font-mono text-white mt-2 mb-1">-33%</div>
                        <div class="text-xs font-bold text-noc-neonCyan mb-1">Optimización de Costos</div>
                        <p class="text-xs text-slate-400">Reducción de costos operativos mediante tuning de Dynatrace.</p>
                    </div>

                    <!-- KPI 3 -->
                    <div class="bg-noc-card p-5 rounded-xl border border-noc-border hover:border-noc-neonPurple/50 transition-all group">
                        <div class="flex justify-between items-start">
                            <span class="text-xs font-mono text-slate-500">METRIC_03</span>
                            <i class="fa-solid fa-rocket text-noc-neonPurple text-lg group-hover:scale-110 transition-transform"></i>
                        </div>
                        <div class="text-3xl font-extrabold font-mono text-white mt-2 mb-1">3 Meses</div>
                        <div class="text-xs font-bold text-noc-neonPurple mb-1">Migración de Plataforma</div>
                        <p class="text-xs text-slate-400">Migración total de Splunk hacia Dynatrace ejecutada con éxito.</p>
                    </div>

                    <!-- KPI 4 -->
                    <div class="bg-noc-card p-5 rounded-xl border border-noc-border hover:border-noc-amber/50 transition-all group">
                        <div class="flex justify-between items-start">
                            <span class="text-xs font-mono text-slate-500">METRIC_04</span>
                            <i class="fa-solid fa-clock text-noc-amber text-lg group-hover:scale-110 transition-transform"></i>
                        </div>
                        <div class="text-3xl font-extrabold font-mono text-white mt-2 mb-1">+4 Años</div>
                        <div class="text-xs font-bold text-noc-amber mb-1">Experiencia Especializada</div>
                        <p class="text-xs text-slate-400">Gestión de observabilidad, SRE, multi-cloud y ecosistemas enterprise.</p>
                    </div>

                </div>
            </section>

            <section id="experience" class="space-y-4">
                <div class="flex items-center justify-between">
                    <div class="flex items-center gap-2 text-xs font-mono text-noc-neonGreen">
                        <i class="fa-solid fa-server"></i>
                        <span class="uppercase tracking-wider">// WORK_EXPERIENCE_LOGS</span>
                    </div>
                    <span class="text-xs font-mono text-slate-500">SORT: CHRONOLOGICAL_DESC</span>
                </div>

                <div class="space-y-4 font-mono">
                    
                    <!-- Log Item 1 -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 hover:border-noc-neonCyan/60 transition-all">
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-noc-border/80 pb-3 mb-3">
                            <div>
                                <span class="text-xs text-noc-neonCyan font-bold">[CURRENT_ROLE]</span>
                                <h3 class="text-lg font-bold text-white tracking-tight">Administrador de Plataformas de Observabilidad</h3>
                                <p class="text-xs text-slate-300">Periferia IT / BNP Paribas Cardif Colombia</p>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-noc-neonCyan/10 text-noc-neonCyan text-xs border border-noc-neonCyan/30">
                                Abril 2026 - Actualidad
                            </span>
                        </div>

                        <ul class="text-xs text-slate-300 space-y-2 font-sans leading-relaxed list-disc list-inside">
                            <li>Administro y optimizo el ecosistema global de observabilidad en entornos multi-tenant e internacionales sobre <strong class="text-white">Dynatrace (Managed y SaaS), Datadog y ELK Stack</strong>.</li>
                            <li>Lidero la integración de soluciones de observabilidad con la nube financiera <strong class="text-white">IBM Financial Services Cloud</strong> y herramientas de terceros.</li>
                            <li>Diseño e implemento flujos de automatización y scripting para la remediación de eventos, al tiempo que ejecuto ingeniería inversa para eliminar deuda técnica.</li>
                            <li>Transformo la telemetría en insights estratégicos y KPIs orientados al negocio, asegurando el rendimiento transaccional.</li>
                        </ul>
                    </div>

                    <!-- Log Item 2 -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 hover:border-noc-neonGreen/60 transition-all">
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-noc-border/80 pb-3 mb-3">
                            <div>
                                <span class="text-xs text-noc-neonGreen font-bold">[PREVIOUS_ROLE]</span>
                                <h3 class="text-lg font-bold text-white tracking-tight">Analista de Observabilidad</h3>
                                <p class="text-xs text-slate-300">Puntos Colombia</p>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-400 text-xs border border-noc-border">
                                Abril 2025 - Marzo 2026
                            </span>
                        </div>

                        <ul class="text-xs text-slate-300 space-y-2 font-sans leading-relaxed list-disc list-inside">
                            <li>Lideré el cambio de paradigma operativo hacia un modelo predictivo mediante tuning avanzado de Dynatrace, <strong class="text-noc-neonGreen">detectando el 95% de incidentes proactivamente</strong>.</li>
                            <li>Diseñé e implementé automatizaciones que <strong class="text-noc-neonGreen">redujeron los costos operativos en un 33%</strong>.</li>
                            <li>Ejecuté la migración total de <strong class="text-white">Splunk a Dynatrace en solo 3 meses</strong>.</li>
                        </ul>
                    </div>

                    <!-- Log Item 3 -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 hover:border-noc-neonPurple/60 transition-all">
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-noc-border/80 pb-3 mb-3">
                            <div>
                                <span class="text-xs text-noc-neonPurple font-bold">[PREVIOUS_ROLE]</span>
                                <h3 class="text-lg font-bold text-white tracking-tight">Monitoring Leader</h3>
                                <p class="text-xs text-slate-300">Servinform</p>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-400 text-xs border border-noc-border">
                                Octubre 2024 - Abril 2025
                            </span>
                        </div>

                        <ul class="text-xs text-slate-300 space-y-2 font-sans leading-relaxed list-disc list-inside">
                            <li>Dirigí equipos técnicos en proyectos de observabilidad, estandarizando indicadores críticos para alinear infraestructura con objetivos del negocio.</li>
                            <li>Coordiné el escalamiento y remediación de incidentes con automatizaciones sobre <strong class="text-white">EasyVista y SolarWinds</strong>.</li>
                            <li>Consultoría directa a desarrollo facilitando la adopción de prácticas SRE.</li>
                        </ul>
                    </div>

                    <!-- Log Item 4 -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 hover:border-noc-amber/60 transition-all">
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-noc-border/80 pb-3 mb-3">
                            <div>
                                <span class="text-xs text-noc-amber font-bold">[PREVIOUS_ROLE]</span>
                                <h3 class="text-lg font-bold text-white tracking-tight">Project Engineer II</h3>
                                <p class="text-xs text-slate-300">E-dea Networks</p>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-400 text-xs border border-noc-border">
                                Junio 2022 - Agosto 2024
                            </span>
                        </div>

                        <ul class="text-xs text-slate-300 space-y-2 font-sans leading-relaxed list-disc list-inside">
                            <li>Lideré proyectos de arquitectura e infraestructura crítica enfocados en observabilidad para clientes enterprise de gran escala.</li>
                            <li>Tuning avanzado sobre bases de datos SQL y redes para maximizar el rendimiento de la suite <strong class="text-white">SolarWinds</strong>.</li>
                            <li>Orquestación de integración multi-cloud (<strong class="text-white">AWS, Azure y GCP</strong>).</li>
                        </ul>
                    </div>

                </div>
            </section>

            <section id="stack" class="space-y-4">
                <div class="flex items-center gap-2 text-xs font-mono text-noc-neonPurple">
                    <i class="fa-solid fa-cubes"></i>
                    <span class="uppercase tracking-wider">// TECH_STACK & OBSERVABILITY_SUITE</span>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 font-mono text-xs">
                    
                    <!-- Observability Suite -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 space-y-3">
                        <div class="flex items-center gap-2 text-noc-neonCyan font-bold border-b border-noc-border pb-2">
                            <i class="fa-solid fa-eye"></i> Observabilidad
                        </div>
                        <ul class="space-y-2 text-slate-300">
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Dynatrace (SaaS/Managed)</span>
                                <span class="text-noc-neonCyan">Expert</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Datadog</span>
                                <span class="text-noc-neonCyan">Advanced</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>SolarWinds Suite</span>
                                <span class="text-noc-neonCyan">Expert</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Splunk & ELK Stack</span>
                                <span class="text-noc-neonCyan">Advanced</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Observe</span>
                                <span class="text-noc-neonCyan">Proficient</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Cloud & Infra -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 space-y-3">
                        <div class="flex items-center gap-2 text-noc-neonGreen font-bold border-b border-noc-border pb-2">
                            <i class="fa-solid fa-cloud"></i> Cloud & Infraestructura
                        </div>
                        <ul class="space-y-2 text-slate-300">
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Microsoft Azure</span>
                                <span class="text-noc-neonGreen">Proficient</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Amazon Web Services (AWS)</span>
                                <span class="text-noc-neonGreen">Proficient</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>IBM Financial Services Cloud</span>
                                <span class="text-noc-neonGreen">Proficient</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>EasyVista & ITSM</span>
                                <span class="text-noc-neonGreen">Advanced</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Code & Data -->
                    <div class="bg-noc-card border border-noc-border rounded-xl p-5 space-y-3">
                        <div class="flex items-center gap-2 text-noc-neonPurple font-bold border-b border-noc-border pb-2">
                            <i class="fa-solid fa-code"></i> Código & Analítica
                        </div>
                        <ul class="space-y-2 text-slate-300">
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Python & Bash Scripting</span>
                                <span class="text-noc-neonPurple">Advanced</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>SQL & NoSQL (MongoDB)</span>
                                <span class="text-noc-neonPurple">Advanced</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>Analítica de Datos Avanzada</span>
                                <span class="text-noc-neonPurple">MSc Candidate</span>
                            </li>
                            <li class="flex items-center justify-between p-2 rounded bg-noc-bg border border-noc-border/60">
                                <span>SRE / Lean / Scrum</span>
                                <span class="text-noc-neonPurple">Expert</span>
                            </li>
                        </ul>
                    </div>

                </div>
            </section>

            <section id="education" class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                
                <!-- Education -->
                <div class="lg:col-span-5 space-y-4">
                    <div class="flex items-center gap-2 text-xs font-mono text-noc-neonCyan">
                        <i class="fa-solid fa-graduation-cap"></i>
                        <span class="uppercase tracking-wider">// ACADEMIC_BACKGROUND</span>
                    </div>

                    <div class="space-y-3 font-mono text-xs">
                        <div class="bg-noc-card border border-noc-border p-4 rounded-xl">
                            <span class="text-noc-neonGreen font-bold">2025 - En curso</span>
                            <h3 class="text-sm font-bold text-white mt-1">Maestría en Ingeniería y Analítica de Datos</h3>
                            <p class="text-slate-400">Universidad Jorge Tadeo Lozano</p>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-4 rounded-xl">
                            <span class="text-slate-500 font-bold">2019 - 2023</span>
                            <h3 class="text-sm font-bold text-white mt-1">Ingeniero de Sistemas</h3>
                            <p class="text-slate-400">Universidad Jorge Tadeo Lozano</p>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-4 rounded-xl">
                            <span class="text-slate-500 font-bold">2024</span>
                            <h3 class="text-sm font-bold text-white mt-1">Diplomado en Gestión de Proyectos</h3>
                            <p class="text-slate-400">Politécnico de Colombia</p>
                        </div>
                    </div>
                </div>

                <!-- Certifications -->
                <div class="lg:col-span-7 space-y-4">
                    <div class="flex items-center justify-between">
                        <div class="flex items-center gap-2 text-xs font-mono text-noc-neonGreen">
                            <i class="fa-solid fa-certificate"></i>
                            <span class="uppercase tracking-wider">// CERTIFICATIONS (+20)</span>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 font-mono text-xs">
                        <div class="bg-noc-card border border-noc-border p-3.5 rounded-lg flex items-center gap-3">
                            <i class="fa-solid fa-award text-noc-neonCyan text-xl"></i>
                            <div>
                                <div class="font-bold text-white">Dynatrace Essentials</div>
                                <div class="text-[10px] text-slate-400">Dynatrace</div>
                            </div>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-3.5 rounded-lg flex items-center gap-3">
                            <i class="fa-solid fa-award text-noc-amber text-xl"></i>
                            <div>
                                <div class="font-bold text-white">Network Performance Monitor</div>
                                <div class="text-[10px] text-slate-400">SolarWinds</div>
                            </div>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-3.5 rounded-lg flex items-center gap-3">
                            <i class="fa-solid fa-award text-noc-neonPurple text-xl"></i>
                            <div>
                                <div class="font-bold text-white">DPN Sales Specialist</div>
                                <div class="text-[10px] text-slate-400">Datadog</div>
                            </div>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-3.5 rounded-lg flex items-center gap-3">
                            <i class="fa-solid fa-award text-noc-amber text-xl"></i>
                            <div>
                                <div class="font-bold text-white">SolarWinds Self-Hosted Platform</div>
                                <div class="text-[10px] text-slate-400">SolarWinds</div>
                            </div>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-3.5 rounded-lg flex items-center gap-3">
                            <i class="fa-solid fa-award text-noc-neonGreen text-xl"></i>
                            <div>
                                <div class="font-bold text-white">Data Analytics</div>
                                <div class="text-[10px] text-slate-400">MinTIC Colombia</div>
                            </div>
                        </div>

                        <div class="bg-noc-card border border-noc-border p-3.5 rounded-lg flex items-center gap-3">
                            <i class="fa-solid fa-award text-noc-neonGreen text-xl"></i>
                            <div>
                                <div class="font-bold text-white">MongoDB SI Associate</div>
                                <div class="text-[10px] text-slate-400">MongoDB</div>
                            </div>
                        </div>
                    </div>
                </div>

            </section>

            <section id="terminal-widget" class="space-y-4">
                <div class="flex items-center gap-2 text-xs font-mono text-noc-neonPurple">
                    <i class="fa-solid fa-terminal"></i>
                    <span class="uppercase tracking-wider">// INTERACTIVE_TELEMETRY_SHELL</span>
                </div>

                <div class="bg-noc-bg border border-noc-border rounded-xl p-4 font-mono text-xs shadow-2xl space-y-3">
                    <div class="flex items-center justify-between border-b border-noc-border pb-2 text-slate-500 text-[11px]">
                        <span>BASH_EMULATOR_V2.4</span>
                        <span>Type 'help' to view commands</span>
                    </div>

                    <!-- Output Screen -->
                    <div id="terminal-output" class="h-44 overflow-y-auto space-y-2 text-slate-300 pr-2 leading-relaxed">
                        <p class="text-noc-neonGreen">Welcome to Brandon Rambauth's SRE Terminal.</p>
                        <p class="text-slate-400">Type <span class="text-noc-neonCyan font-bold">'help'</span> for list of available telemetry commands.</p>
                    </div>

                    <!-- Input Line -->
                    <form id="terminal-form" class="flex items-center gap-2 pt-2 border-t border-noc-border/80">
                        <span class="text-noc-neonPurple font-bold">sre@brandon-ops:~$</span>
                        <input id="terminal-input" type="text" autocomplete="off" class="flex-1 bg-transparent text-noc-neonGreen focus:outline-none font-mono text-xs" placeholder="help, skills, exp, contact, clear...">
                        <button type="submit" class="px-3 py-1 rounded bg-noc-card border border-noc-border text-slate-300 hover:text-white">RUN</button>
                    </form>
                </div>
            </section>

            <footer class="pt-8 pb-4 text-center text-xs font-mono text-slate-500 border-t border-noc-border">
                <p>© <span id="current-year"></span> Brandon David Rambauth Céspedes — SRE & Observability Control Center</p>
            </footer>

        </main>
    </div>

    <script>
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Interactive Terminal Logic
        const terminalOutput = document.getElementById('terminal-output');
        const terminalForm = document.getElementById('terminal-form');
        const terminalInput = document.getElementById('terminal-input');

        const commands = {
            'help': 'Comandos disponibles: <span class="text-noc-neonCyan">skills</span>, <span class="text-noc-neonCyan">exp</span>, <span class="text-noc-neonCyan">certifications</span>, <span class="text-noc-neonCyan">contact</span>, <span class="text-noc-neonCyan">clear</span>',
            'skills': 'Especialidades: Dynatrace (SaaS/Managed), Datadog, SolarWinds, Python, Scripting Bash, SQL/NoSQL, AWS, Azure, SRE Enablement.',
            'exp': 'Experiencia actual: Administrador de Plataformas de Observabilidad en Periferia IT / BNP Paribas Cardif. Roles previos en Puntos Colombia, Servinform y E-dea Networks.',
            'certifications': 'Certificaciones principales: Dynatrace Essentials, Datadog DPN, SolarWinds NPM & Self-Hosted, MongoDB SI Associate, MinTIC Data Analytics.',
            'contact': 'Contacto directo: Email: bc.cespedes2002@gmail.com | Phone: +57 3194892106 | LinkedIn: in/brandon-rambauth'
        };

        terminalForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const rawVal = terminalInput.value.trim().toLowerCase();
            terminalInput.value = '';

            if (!rawVal) return;

            // Render Prompt Line
            const promptLine = document.createElement('p');
            promptLine.innerHTML = `<span class="text-noc-neonPurple">sre@brandon-ops:~$</span> <span class="text-white">${rawVal}</span>`;
            terminalOutput.appendChild(promptLine);

            if (rawVal === 'clear') {
                terminalOutput.innerHTML = '';
                return;
            }

            const responseLine = document.createElement('p');
            if (commands[rawVal]) {
                responseLine.innerHTML = commands[rawVal];
                responseLine.className = 'text-slate-300 pl-2 border-l border-noc-neonGreen/40';
            } else {
                responseLine.innerHTML = `Comando no reconocido: '${rawVal}'. Escribe <span class="text-noc-neonCyan">'help'</span>.`;
                responseLine.className = 'text-red-400 pl-2';
            }

            terminalOutput.appendChild(responseLine);
            terminalOutput.scrollTop = terminalOutput.scrollHeight;
        });
    </script>
</body>
</html>
