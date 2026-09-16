<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>N. Abdul Fasith | Founder & IT Specialist</title>
  
  <!-- Meta SEO -->
  <meta name="description" content="Portfolio of N. Abdul Fasith - Founder of GCSST, IT Undergraduate, and Cybersecurity Enthusiast based in Trincomalee, Sri Lanka." />
  <meta name="author" content="N. Abdul Fasith" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              cyan: '#06b6d4',
              blue: '#3b82f6',
              dark: '#0a0f1d',
              card: '#111827',
              border: '#1f2937'
            }
          }
        }
      }
    }
  </script>

  <!-- Google Fonts: Inter & JetBrains Mono -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">

  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
    .mono {
      font-family: 'JetBrains Mono', monospace;
    }
    .gradient-text {
      background: linear-gradient(135deg, #38bdf8 0%, #818cf8 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .card-glow:hover {
      box-shadow: 0 0 25px -5px rgba(56, 189, 248, 0.15);
    }
  </style>
</head>
<body class="bg-[#0a0f1d] text-slate-300 antialiased selection:bg-cyan-500/20 selection:text-cyan-300">

  <!-- NAVBAR -->
  <header class="fixed top-0 left-0 w-full z-50 bg-[#0a0f1d]/85 backdrop-blur-md border-b border-slate-800/80">
    <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
      <a href="#" class="text-xl font-bold tracking-tight text-white flex items-center gap-2">
        <span class="text-cyan-400 mono">&lt;AF /&gt;</span>
        <span>Abdul Fasith</span>
      </a>

      <!-- Desktop Nav -->
      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
        <a href="#about" class="hover:text-cyan-400 transition-colors">About</a>
        <a href="#skills" class="hover:text-cyan-400 transition-colors">Skills</a>
        <a href="#projects" class="hover:text-cyan-400 transition-colors">Projects</a>
        <a href="#education" class="hover:text-cyan-400 transition-colors">Education & Leadership</a>
        <a href="#contact" class="hover:text-cyan-400 transition-colors">Contact</a>
        <a href="https://wa.me/94702448089" target="_blank" class="px-4 py-2 text-xs font-semibold rounded-lg bg-cyan-500/10 text-cyan-400 border border-cyan-500/30 hover:bg-cyan-500/20 transition-all flex items-center gap-2">
          <i data-lucide="message-square" class="w-4 h-4"></i> Chat on WhatsApp
        </a>
      </nav>

      <!-- Mobile Menu Button -->
      <button id="menu-btn" class="md:hidden text-slate-300 hover:text-white" aria-label="Toggle Menu">
        <i data-lucide="menu" class="w-6 h-6"></i>
      </button>
    </div>

    <!-- Mobile Nav Drawer -->
    <div id="mobile-menu" class="hidden md:hidden border-b border-slate-800 bg-[#0d1424] px-6 py-6 space-y-4">
      <a href="#about" class="block text-slate-300 hover:text-cyan-400 font-medium">About</a>
      <a href="#skills" class="block text-slate-300 hover:text-cyan-400 font-medium">Skills</a>
      <a href="#projects" class="block text-slate-300 hover:text-cyan-400 font-medium">Projects</a>
      <a href="#education" class="block text-slate-300 hover:text-cyan-400 font-medium">Education & Leadership</a>
      <a href="#contact" class="block text-slate-300 hover:text-cyan-400 font-medium">Contact</a>
      <a href="https://wa.me/94702448089" target="_blank" class="w-full py-2.5 text-center text-sm font-semibold rounded-lg bg-cyan-500/10 text-cyan-400 border border-cyan-500/30 block">
        Chat on WhatsApp
      </a>
    </div>
  </header>

  <main class="pt-20">
    <!-- HERO SECTION -->
    <section class="min-h-[calc(100vh-5rem)] flex items-center relative overflow-hidden py-16">
      <!-- Glow Gradients -->
      <div class="absolute -top-32 -left-32 w-96 h-96 bg-cyan-500/10 rounded-full blur-3xl pointer-events-none"></div>
      <div class="absolute top-1/2 -right-32 w-96 h-96 bg-indigo-500/10 rounded-full blur-3xl pointer-events-none"></div>

      <div class="max-w-7xl mx-auto px-6 w-full grid md:grid-cols-12 gap-12 items-center">
        <div class="md:col-span-7 space-y-6">
          <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-cyan-500/10 border border-cyan-500/30 text-cyan-400 text-xs font-mono">
            <span class="relative flex h-2 w-2">
              <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-cyan-400 opacity-75"></span>
              <span class="relative inline-flex rounded-full h-2 w-2 bg-cyan-500"></span>
            </span>
            Available for Projects & Tech Collaborations
          </div>

          <h1 class="text-4xl sm:text-6xl font-extrabold text-white tracking-tight leading-tight">
            Hi, I'm <span class="gradient-text">N. Abdul Fasith</span>
          </h1>

          <p class="text-lg sm:text-xl font-medium text-slate-300">
            Founder <span class="text-cyan-400">@ GCSST</span> | IT Undergraduate | Cybersecurity Enthusiast
          </p>

          <p class="text-slate-400 leading-relaxed text-base max-w-xl">
            Passionate technologist from Trincomalee, Sri Lanka, driven by secure software engineering, automation, and technological leadership. Building robust web solutions, security utilities, and driving enterprise growth through tech and digital marketing.
          </p>

          <div class="flex flex-wrap gap-4 pt-4">
            <a href="#projects" class="px-6 py-3 rounded-lg bg-cyan-500 hover:bg-cyan-400 text-slate-950 font-semibold transition-all shadow-lg shadow-cyan-500/25 flex items-center gap-2">
              <i data-lucide="code" class="w-4 h-4"></i> View Projects
            </a>
            <a href="#contact" class="px-6 py-3 rounded-lg border border-slate-700 bg-slate-900/60 hover:bg-slate-800 text-white font-medium transition-all flex items-center gap-2">
              <i data-lucide="mail" class="w-4 h-4"></i> Contact Me
            </a>
            <a href="https://wa.me/94702448089" target="_blank" class="px-6 py-3 rounded-lg border border-emerald-500/40 bg-emerald-950/20 hover:bg-emerald-900/30 text-emerald-400 font-medium transition-all flex items-center gap-2">
              <i data-lucide="phone" class="w-4 h-4"></i> WhatsApp
            </a>
          </div>

          <!-- Social Links -->
          <div class="pt-6 flex items-center gap-5 text-slate-400">
            <a href="https://github.com/abdulfasith37" target="_blank" class="hover:text-white transition-colors" title="GitHub">
              <i data-lucide="github" class="w-6 h-6"></i>
            </a>
            <a href="https://www.linkedin.com/in/abdulfasith" target="_blank" class="hover:text-white transition-colors" title="LinkedIn">
              <i data-lucide="linkedin" class="w-6 h-6"></i>
            </a>
            <a href="mailto:abdulfasith373@gmail.com" class="hover:text-white transition-colors" title="Email">
              <i data-lucide="mail" class="w-6 h-6"></i>
            </a>
            <span class="text-xs mono text-slate-500 flex items-center gap-1.5 ml-2">
              <i data-lucide="map-pin" class="w-4 h-4 text-cyan-400"></i> Trincomalee, Sri Lanka
            </span>
          </div>
        </div>

        <!-- Terminal / Interactive Showcase Card -->
        <div class="md:col-span-5">
          <div class="rounded-xl border border-slate-800 bg-[#0d1424] shadow-2xl overflow-hidden card-glow transition-all">
            <div class="bg-slate-900/80 px-4 py-3 border-b border-slate-800 flex items-center justify-between">
              <div class="flex items-center gap-2">
                <div class="w-3 h-3 rounded-full bg-rose-500/80"></div>
                <div class="w-3 h-3 rounded-full bg-amber-500/80"></div>
                <div class="w-3 h-3 rounded-full bg-emerald-500/80"></div>
              </div>
              <span class="text-xs mono text-slate-400">fasith@dev-box: ~</span>
              <i data-lucide="terminal" class="w-4 h-4 text-slate-500"></i>
            </div>
            <div class="p-6 mono text-xs leading-relaxed space-y-3">
              <p class="text-slate-400"><span class="text-cyan-400">$</span> whoami</p>
              <p class="text-emerald-400">Abdul Fasith [Founder, Engineer, Security Researcher]</p>
              
              <p class="text-slate-400"><span class="text-cyan-400">$</span> cat organization.json</p>
              <p class="text-indigo-300">
                {<br>
                &nbsp;&nbsp;"name": "Global Cybersecurity and Software Technologies (GCSST)",<br>
                &nbsp;&nbsp;"role": "Founder",<br>
                &nbsp;&nbsp;"mission": "Empowering next-gen tech innovators & secure engineering"<br>
                }
              </p>

              <p class="text-slate-400"><span class="text-cyan-400">$</span> current_status</p>
              <p class="text-amber-300">"Undergrad @ Univ of Vavuniya | Building Scalable Tech"</p>

              <p class="text-slate-400 flex items-center gap-1">
                <span class="text-cyan-400">$</span> <span class="animate-pulse">_</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="py-20 border-t border-slate-800/80 bg-slate-950/40">
      <div class="max-w-7xl mx-auto px-6">
        <div class="max-w-3xl">
          <h2 class="text-xs uppercase tracking-widest text-cyan-400 mono font-semibold">About Me</h2>
          <h3 class="text-3xl sm:text-4xl font-bold text-white mt-2">Bridging Software Engineering, Security & Enterprise Growth</h3>
        </div>

        <div class="grid md:grid-cols-3 gap-8 mt-12">
          <div class="p-6 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all card-glow">
            <div class="w-12 h-12 rounded-lg bg-cyan-500/10 border border-cyan-500/20 text-cyan-400 flex items-center justify-center mb-5">
              <i data-lucide="shield-check" class="w-6 h-6"></i>
            </div>
            <h4 class="text-lg font-semibold text-white">Cybersecurity & Tools</h4>
            <p class="text-slate-400 text-sm mt-2 leading-relaxed">
              Passionate about network defense, pentesting workflows, automation tools in mobile/Linux environments, and understanding modern threat landscapes.
            </p>
          </div>

          <div class="p-6 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all card-glow">
            <div class="w-12 h-12 rounded-lg bg-blue-500/10 border border-blue-500/20 text-blue-400 flex items-center justify-center mb-5">
              <i data-lucide="layers" class="w-6 h-6"></i>
            </div>
            <h4 class="text-lg font-semibold text-white">Software Development</h4>
            <p class="text-slate-400 text-sm mt-2 leading-relaxed">
              Solid grounding in Object-Oriented Programming (OOP) in Java, Python, and C/C++, coupled with full-stack web applications using PHP, JavaScript, and modern frameworks.
            </p>
          </div>

          <div class="p-6 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all card-glow">
            <div class="w-12 h-12 rounded-lg bg-indigo-500/10 border border-indigo-500/20 text-indigo-400 flex items-center justify-center mb-5">
              <i data-lucide="trending-up" class="w-6 h-6"></i>
            </div>
            <h4 class="text-lg font-semibold text-white">Founder & Digital Growth</h4>
            <p class="text-slate-400 text-sm mt-2 leading-relaxed">
              Founder of GCSST. Experienced in tech management, team leadership, AI-assisted workflows, and data-driven client acquisition using Meta Ads.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- SKILLS SECTION -->
    <section id="skills" class="py-20 border-t border-slate-800/80">
      <div class="max-w-7xl mx-auto px-6">
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-12">
          <div>
            <h2 class="text-xs uppercase tracking-widest text-cyan-400 mono font-semibold">Technical Arsenal</h2>
            <h3 class="text-3xl font-bold text-white mt-2">Skills & Technologies</h3>
          </div>
          <p class="text-sm text-slate-400 mt-2 md:mt-0">Combining programming fundamentals with modern operational skill sets.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
          <!-- Programming Languages -->
          <div class="p-6 rounded-xl bg-slate-900/40 border border-slate-800">
            <h4 class="text-white font-semibold flex items-center gap-2 mb-4 text-sm">
              <i data-lucide="code-2" class="w-4 h-4 text-cyan-400"></i> Core Languages
            </h4>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Java</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Python</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">C</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">C++</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">PHP</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">JavaScript</span>
            </div>
          </div>

          <!-- Web Development -->
          <div class="p-6 rounded-xl bg-slate-900/40 border border-slate-800">
            <h4 class="text-white font-semibold flex items-center gap-2 mb-4 text-sm">
              <i data-lucide="globe" class="w-4 h-4 text-blue-400"></i> Web Engineering
            </h4>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">HTML5</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">CSS3</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Responsive UI</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Tailwind CSS</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">E-Commerce Arch</span>
            </div>
          </div>

          <!-- Security & Systems -->
          <div class="p-6 rounded-xl bg-slate-900/40 border border-slate-800">
            <h4 class="text-white font-semibold flex items-center gap-2 mb-4 text-sm">
              <i data-lucide="shield" class="w-4 h-4 text-emerald-400"></i> Security & Systems
            </h4>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Cybersecurity Fundamentals</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Termux Automation</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Metasploit Workflows</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Linux Environment</span>
            </div>
          </div>

          <!-- Leadership & Marketing -->
          <div class="p-6 rounded-xl bg-slate-900/40 border border-slate-800">
            <h4 class="text-white font-semibold flex items-center gap-2 mb-4 text-sm">
              <i data-lucide="briefcase" class="w-4 h-4 text-indigo-400"></i> Leadership & Growth
            </h4>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Meta Ads Manager</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Digital Marketing</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">AI Tool Integration</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Team Management</span>
              <span class="px-2.5 py-1 text-xs rounded-md bg-slate-800 text-slate-300">Public Speaking</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- PROJECTS SECTION -->
    <section id="projects" class="py-20 border-t border-slate-800/80 bg-slate-950/40">
      <div class="max-w-7xl mx-auto px-6">
        <div class="max-w-3xl mb-12">
          <h2 class="text-xs uppercase tracking-widest text-cyan-400 mono font-semibold">Featured Work</h2>
          <h3 class="text-3xl sm:text-4xl font-bold text-white mt-2">Projects & Technical Builds</h3>
          <p class="text-slate-400 mt-2">A showcase of utility tools, enterprise solutions, and applications.</p>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">

          <!-- Project 1: PROVENOM -->
          <div class="flex flex-col justify-between p-6 rounded-xl bg-slate-900/70 border border-slate-800 hover:border-cyan-500/50 transition-all card-glow">
            <div>
              <div class="flex items-center justify-between mb-4">
                <span class="text-xs mono px-2 py-1 rounded bg-rose-500/10 text-rose-400 border border-rose-500/20">Security Automation</span>
                <a href="https://github.com/Prohackers535/PROVENOM" target="_blank" class="text-slate-400 hover:text-white transition-colors" title="View Source">
                  <i data-lucide="github" class="w-5 h-5"></i>
                </a>
              </div>
              <h4 class="text-lg font-bold text-white">PROVENOM Automation Tool</h4>
              <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                An automated command-line tool designed for Termux environments that streamlines configuration, dependencies, and deployment processes for security research frameworks.
              </p>
            </div>
            <div class="pt-6 border-t border-slate-800/80 mt-6 flex flex-wrap gap-2 items-center justify-between">
              <div class="flex gap-2">
                <span class="text-xs mono text-cyan-300">#Python</span>
                <span class="text-xs mono text-slate-400">#Termux</span>
                <span class="text-xs mono text-slate-400">#Security</span>
              </div>
              <a href="https://github.com/Prohackers535/PROVENOM" target="_blank" class="text-xs font-semibold text-cyan-400 hover:text-cyan-300 flex items-center gap-1">
                Repo <i data-lucide="arrow-up-right" class="w-3.5 h-3.5"></i>
              </a>
            </div>
          </div>

          <!-- Project 2: Student Grade Management System -->
          <div class="flex flex-col justify-between p-6 rounded-xl bg-slate-900/70 border border-slate-800 hover:border-cyan-500/50 transition-all card-glow">
            <div>
              <div class="flex items-center justify-between mb-4">
                <span class="text-xs mono px-2 py-1 rounded bg-blue-500/10 text-blue-400 border border-blue-500/20">Enterprise Software</span>
                <a href="https://github.com/abdulfasith37/IT1214-Student-Grade-System" target="_blank" class="text-slate-400 hover:text-white transition-colors" title="View Source">
                  <i data-lucide="github" class="w-5 h-5"></i>
                </a>
              </div>
              <h4 class="text-lg font-bold text-white">Student Grade Management System</h4>
              <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                A lightweight Java application built to digitize spreadsheet tracking. Encapsulates structural student models using OOP principles, fast unique key record retrieval, and institutional performance monitoring.
              </p>
            </div>
            <div class="pt-6 border-t border-slate-800/80 mt-6 flex flex-wrap gap-2 items-center justify-between">
              <div class="flex gap-2">
                <span class="text-xs mono text-cyan-300">#Java</span>
                <span class="text-xs mono text-slate-400">#OOP</span>
                <span class="text-xs mono text-slate-400">#DataStructures</span>
              </div>
              <a href="https://github.com/abdulfasith37/IT1214-Student-Grade-System" target="_blank" class="text-xs font-semibold text-cyan-400 hover:text-cyan-300 flex items-center gap-1">
                Repo <i data-lucide="arrow-up-right" class="w-3.5 h-3.5"></i>
              </a>
            </div>
          </div>

          <!-- Project 3: Warehouse Inventory System -->
          <div class="flex flex-col justify-between p-6 rounded-xl bg-slate-900/70 border border-slate-800 hover:border-cyan-500/50 transition-all card-glow">
            <div>
              <div class="flex items-center justify-between mb-4">
                <span class="text-xs mono px-2 py-1 rounded bg-indigo-500/10 text-indigo-400 border border-indigo-500/20">Logistics / Inventory</span>
                <a href="https://github.com/abdulfasith37/IT1214-Warehouse-Inventory-System" target="_blank" class="text-slate-400 hover:text-white transition-colors" title="View Source">
                  <i data-lucide="github" class="w-5 h-5"></i>
                </a>
              </div>
              <h4 class="text-lg font-bold text-white">Warehouse Inventory System</h4>
              <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                Console-based inventory management platform leveraging the Java Collections Framework and OOP. Features an intuitive menu to track, add, update, delete, search, and audit item stocks seamlessly.
              </p>
            </div>
            <div class="pt-6 border-t border-slate-800/80 mt-6 flex flex-wrap gap-2 items-center justify-between">
              <div class="flex gap-2">
                <span class="text-xs mono text-cyan-300">#Java</span>
                <span class="text-xs mono text-slate-400">#Collections</span>
                <span class="text-xs mono text-slate-400">#Architecture</span>
              </div>
              <a href="https://github.com/abdulfasith37/IT1214-Warehouse-Inventory-System" target="_blank" class="text-xs font-semibold text-cyan-400 hover:text-cyan-300 flex items-center gap-1">
                Repo <i data-lucide="arrow-up-right" class="w-3.5 h-3.5"></i>
              </a>
            </div>
          </div>

          <!-- Project 4: Urban Innovate Website -->
          <div class="flex flex-col justify-between p-6 rounded-xl bg-slate-900/70 border border-slate-800 hover:border-cyan-500/50 transition-all card-glow">
            <div>
              <div class="flex items-center justify-between mb-4">
                <span class="text-xs mono px-2 py-1 rounded bg-emerald-500/10 text-emerald-400 border border-emerald-500/20">Web Development</span>
                <i data-lucide="layout" class="w-5 h-5 text-slate-500"></i>
              </div>
              <h4 class="text-lg font-bold text-white">Urban Innovate Platform</h4>
              <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                A modern interactive web portal focused on urban community innovation, built with responsive layouts, accessible UI components, and modern client-side scripting.
              </p>
            </div>
            <div class="pt-6 border-t border-slate-800/80 mt-6 flex flex-wrap gap-2 items-center justify-between">
              <div class="flex gap-2">
                <span class="text-xs mono text-cyan-300">#HTML5</span>
                <span class="text-xs mono text-slate-400">#CSS3</span>
                <span class="text-xs mono text-slate-400">#JavaScript</span>
              </div>
              <span class="text-xs text-slate-500">Production Build</span>
            </div>
          </div>

          <!-- Project 5: E-Commerce Platform -->
          <div class="flex flex-col justify-between p-6 rounded-xl bg-slate-900/70 border border-slate-800 hover:border-cyan-500/50 transition-all card-glow">
            <div>
              <div class="flex items-center justify-between mb-4">
                <span class="text-xs mono px-2 py-1 rounded bg-amber-500/10 text-amber-400 border border-amber-500/20">Web & Commerce</span>
                <i data-lucide="shopping-cart" class="w-5 h-5 text-slate-500"></i>
              </div>
              <h4 class="text-lg font-bold text-white">E-Commerce Web Solution</h4>
              <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                Custom commercial web application featuring product catalog structuring, checkout flow logic, cart state persistence, and responsive storefront components.
              </p>
            </div>
            <div class="pt-6 border-t border-slate-800/80 mt-6 flex flex-wrap gap-2 items-center justify-between">
              <div class="flex gap-2">
                <span class="text-xs mono text-cyan-300">#PHP</span>
                <span class="text-xs mono text-slate-400">#FullStack</span>
                <span class="text-xs mono text-slate-400">#UI/UX</span>
              </div>
              <span class="text-xs text-slate-500">Web App</span>
            </div>
          </div>

          <!-- Project 6: Digital Marketing & Meta Ads -->
          <div class="flex flex-col justify-between p-6 rounded-xl bg-slate-900/70 border border-slate-800 hover:border-cyan-500/50 transition-all card-glow">
            <div>
              <div class="flex items-center justify-between mb-4">
                <span class="text-xs mono px-2 py-1 rounded bg-purple-500/10 text-purple-400 border border-purple-500/20">Growth & Strategy</span>
                <i data-lucide="target" class="w-5 h-5 text-slate-500"></i>
              </div>
              <h4 class="text-lg font-bold text-white">Meta Ads Performance Campaigns</h4>
              <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                Data-driven campaign management utilizing Meta Ads Manager. Structured audience targeting, funnel experiments, and creative iterations for lead generation and brand authority.
              </p>
            </div>
            <div class="pt-6 border-t border-slate-800/80 mt-6 flex flex-wrap gap-2 items-center justify-between">
              <div class="flex gap-2">
                <span class="text-xs mono text-cyan-300">#MetaAds</span>
                <span class="text-xs mono text-slate-400">#Analytics</span>
                <span class="text-xs mono text-slate-400">#Growth</span>
              </div>
              <span class="text-xs text-slate-500">Client Execution</span>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- EDUCATION & LEADERSHIP SECTION -->
    <section id="education" class="py-20 border-t border-slate-800/80">
      <div class="max-w-7xl mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-12">
          
          <!-- Education Column -->
          <div>
            <div class="flex items-center gap-3 mb-8">
              <div class="w-10 h-10 rounded-lg bg-cyan-500/10 border border-cyan-500/20 flex items-center justify-center text-cyan-400">
                <i data-lucide="graduation-cap" class="w-5 h-5"></i>
              </div>
              <h3 class="text-2xl font-bold text-white">Education</h3>
            </div>

            <div class="space-y-6 border-l-2 border-slate-800 pl-6 relative">
              <div class="relative">
                <span class="absolute -left-[31px] top-1.5 w-3 h-3 rounded-full bg-cyan-400 border-4 border-[#0a0f1d]"></span>
                <h4 class="text-lg font-semibold text-white">BSc in Information Technology</h4>
                <p class="text-cyan-400 text-sm font-medium">University of Vavuniya</p>
                <p class="text-slate-400 text-sm mt-2 leading-relaxed">
                  Focusing on core software systems, data engineering, algorithms, networking, and applied information technology principles.
                </p>
              </div>
            </div>
          </div>

          <!-- Leadership Column -->
          <div>
            <div class="flex items-center gap-3 mb-8">
              <div class="w-10 h-10 rounded-lg bg-indigo-500/10 border border-indigo-500/20 flex items-center justify-center text-indigo-400">
                <i data-lucide="award" class="w-5 h-5"></i>
              </div>
              <h3 class="text-2xl font-bold text-white">Leadership & Venture</h3>
            </div>

            <div class="space-y-6 border-l-2 border-slate-800 pl-6 relative">
              <div class="relative">
                <span class="absolute -left-[31px] top-1.5 w-3 h-3 rounded-full bg-indigo-400 border-4 border-[#0a0f1d]"></span>
                <h4 class="text-lg font-semibold text-white">Founder & Director</h4>
                <p class="text-indigo-400 text-sm font-medium">Global Cybersecurity and Software Technologies (GCSST)</p>
                <p class="text-slate-400 text-sm mt-2 leading-relaxed">
                  Leading institutional initiatives, mentoring emerging talent, curating modern tech training programs, and overseeing operations in software engineering and digital transformation.
                </p>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="py-20 border-t border-slate-800/80 bg-slate-950/40">
      <div class="max-w-7xl mx-auto px-6">
        <div class="max-w-3xl mb-12">
          <h2 class="text-xs uppercase tracking-widest text-cyan-400 mono font-semibold">Get In Touch</h2>
          <h3 class="text-3xl sm:text-4xl font-bold text-white mt-2">Let's Connect & Collaborate</h3>
          <p class="text-slate-400 mt-2">Feel free to reach out directly through WhatsApp, email, or social profiles.</p>
        </div>

        <div class="grid md:grid-cols-12 gap-10">
          
          <!-- Direct Details -->
          <div class="md:col-span-5 space-y-5">
            <a href="mailto:abdulfasith373@gmail.com" class="flex items-start gap-4 p-4 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all">
              <div class="w-10 h-10 rounded-lg bg-cyan-500/10 text-cyan-400 flex items-center justify-center shrink-0">
                <i data-lucide="mail" class="w-5 h-5"></i>
              </div>
              <div>
                <p class="text-xs text-slate-400 mono">Email Me</p>
                <p class="text-sm font-medium text-white break-all">abdulfasith373@gmail.com</p>
              </div>
            </a>

            <a href="https://wa.me/94702448089" target="_blank" class="flex items-start gap-4 p-4 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-emerald-500/40 transition-all group">
              <div class="w-10 h-10 rounded-lg bg-emerald-500/10 text-emerald-400 flex items-center justify-center shrink-0">
                <i data-lucide="phone" class="w-5 h-5"></i>
              </div>
              <div>
                <p class="text-xs text-slate-400 mono">WhatsApp & Phone</p>
                <p class="text-sm font-medium text-white group-hover:text-emerald-400 transition-colors">+94 70 244 8089</p>
              </div>
            </a>

            <a href="https://www.linkedin.com/in/abdulfasith" target="_blank" class="flex items-start gap-4 p-4 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-slate-700 transition-all">
              <div class="w-10 h-10 rounded-lg bg-blue-500/10 text-blue-400 flex items-center justify-center shrink-0">
                <i data-lucide="linkedin" class="w-5 h-5"></i>
              </div>
              <div>
                <p class="text-xs text-slate-400 mono">LinkedIn</p>
                <p class="text-sm font-medium text-white">in/abdulfasith</p>
              </div>
            </a>

            <div class="flex items-start gap-4 p-4 rounded-xl bg-slate-900/60 border border-slate-800">
              <div class="w-10 h-10 rounded-lg bg-purple-500/10 text-purple-400 flex items-center justify-center shrink-0">
                <i data-lucide="map-pin" class="w-5 h-5"></i>
              </div>
              <div>
                <p class="text-xs text-slate-400 mono">Location</p>
                <p class="text-sm font-medium text-white">Trincomalee, Sri Lanka</p>
              </div>
            </div>
          </div>

          <!-- Quick Interactive Form (Triggers Direct WhatsApp / Email) -->
          <div class="md:col-span-7">
            <div class="p-8 rounded-xl bg-slate-900/60 border border-slate-800">
              <h4 class="text-lg font-bold text-white mb-2">Send a Direct Message</h4>
              <p class="text-xs text-slate-400 mb-6">Type your message below to send directly to my WhatsApp.</p>

              <form id="contact-form" class="space-y-4" onsubmit="handleSendWhatsApp(event)">
                <div class="grid sm:grid-cols-2 gap-4">
                  <div>
                    <label class="text-xs mono text-slate-400 block mb-1.5">Your Name</label>
                    <input type="text" id="sender-name" required placeholder="John Doe" class="w-full px-4 py-2.5 rounded-lg bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-cyan-400 transition-colors" />
                  </div>
                  <div>
                    <label class="text-xs mono text-slate-400 block mb-1.5">Subject</label>
                    <input type="text" id="sender-subject" required placeholder="Project Inquiry / Opportunity" class="w-full px-4 py-2.5 rounded-lg bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-cyan-400 transition-colors" />
                  </div>
                </div>
                <div>
                  <label class="text-xs mono text-slate-400 block mb-1.5">Message</label>
                  <textarea id="sender-message" rows="4" required placeholder="Write your message here..." class="w-full px-4 py-2.5 rounded-lg bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-cyan-400 transition-colors"></textarea>
                </div>
                <button type="submit" class="w-full py-3 rounded-lg bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-semibold transition-all flex items-center justify-center gap-2">
                  <i data-lucide="send" class="w-4 h-4"></i> Dispatch to WhatsApp (+94 70 244 8089)
                </button>
              </form>
            </div>
          </div>

        </div>
      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="border-t border-slate-800/80 py-8 bg-[#0a0f1d] text-center text-xs text-slate-500">
    <div class="max-w-7xl mx-auto px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
      <p>&copy; <span id="current-year"></span> N. Abdul Fasith. All rights reserved.</p>
      <div class="flex items-center gap-6">
        <a href="https://github.com/abdulfasith37" target="_blank" class="hover:text-cyan-400 transition-colors">GitHub</a>
        <a href="https://www.linkedin.com/in/abdulfasith" target="_blank" class="hover:text-cyan-400 transition-colors">LinkedIn</a>
        <a href="https://wa.me/94702448089" target="_blank" class="hover:text-cyan-400 transition-colors">WhatsApp</a>
      </div>
    </div>
  </footer>

  <!-- Scripts -->
  <script>
    // Initialize Lucide Icons
    lucide.createIcons();

    // Auto set current year in footer
    document.getElementById('current-year').textContent = new Date().getFullYear();

    // Mobile menu toggle
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // Close mobile menu when a navigation link is clicked
    document.querySelectorAll('#mobile-menu a').forEach(link => {
      link.addEventListener('click', () => {
        mobileMenu.classList.add('hidden');
      });
    });

    // Handle interactive contact sending straight to your WhatsApp
    function handleSendWhatsApp(event) {
      event.preventDefault();
      const name = document.getElementById('sender-name').value;
      const subject = document.getElementById('sender-subject').value;
      const message = document.getElementById('sender-message').value;

      const formattedText = `Hi Abdul Fasith,%0A%0A*Name:* ${encodeURIComponent(name)}%0A*Subject:* ${encodeURIComponent(subject)}%0A*Message:* ${encodeURIComponent(message)}`;
      window.open(`https://wa.me/94702448089?text=${formattedText}`, '_blank');
    }
  </script>
</body>
</html>
