<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Antik Mahmud | Pioneer of Bangladeshi 2D Storytime Animation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        display: ['Fredoka', 'sans-serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        studio: {
                            dark: '#0B1120',
                            card: '#131C31',
                            border: '#1E293B',
                            coral: '#FF5E5B',
                            gold: '#FFBE0B',
                            teal: '#00F5D4',
                            purple: '#9B5DE5'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #0B1120;
            color: #F8FAFC;
            overflow-x: hidden;
        }
        /* Subtle Animator Grid Pattern */
        .animator-grid {
            background-image: 
                linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
            background-size: 36px 36px;
        }
        /* Comic Halftone Effect */
        .comic-shadow {
            box-shadow: 6px 6px 0px #FF5E5B;
            transition: all 0.25s ease;
        }
        .comic-shadow:hover {
            transform: translate(-3px, -3px);
            box-shadow: 9px 9px 0px #FFBE0B;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(1.5deg); }
        }
        .animate-float {
            animation: float 5s ease-in-out infinite;
        }
    </style>
</head>
<body class="animator-grid antialiased selection:bg-studio-coral selection:text-white">

    <!-- Navbar -->
    <nav class="sticky top-0 z-50 backdrop-blur-md bg-studio-dark/85 border-b border-studio-border">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <a href="#" class="flex items-center gap-2.5 group">
                <div class="w-9 h-9 rounded-xl bg-studio-coral flex items-center justify-center font-display font-bold text-white text-xl shadow-md group-hover:rotate-6 transition-transform">
                    A
                </div>
                <span class="font-display font-bold text-xl tracking-wide text-white">
                    Antik<span class="text-studio-gold">Mahmud</span>
                </span>
            </a>

            <div class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
                <a href="#about" class="hover:text-studio-gold transition-colors">About</a>
                <a href="#work" class="hover:text-studio-gold transition-colors">Signature Works</a>
                <a href="#timeline" class="hover:text-studio-gold transition-colors">Journey</a>
                <a href="#books" class="hover:text-studio-gold transition-colors">Books & Comics</a>
                <a href="#impact" class="hover:text-studio-gold transition-colors">Impact</a>
            </div>

            <a href="#explore" class="px-4 py-2 rounded-full bg-studio-gold text-studio-dark font-display font-semibold text-sm hover:bg-amber-300 transition-colors">
                Explore Legacy
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative pt-14 pb-20 md:pt-24 md:pb-28 overflow-hidden">
        <!-- Ambient Glow -->
        <div class="absolute top-20 left-1/4 w-72 h-72 bg-studio-coral/15 rounded-full blur-3xl pointer-events-none"></div>
        <div class="absolute bottom-10 right-1/4 w-80 h-80 bg-studio-teal/10 rounded-full blur-3xl pointer-events-none"></div>

        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-12 gap-12 items-center">
            <div class="md:col-span-7 space-y-6">
                <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-studio-card border border-studio-border text-xs font-semibold uppercase tracking-wider text-studio-teal">
                    <span class="w-2 h-2 rounded-full bg-studio-teal animate-ping"></span>
                    Bangladeshi Animator • Cartoonist • Author
                </div>

                <h1 class="font-display text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight text-white">
                    Turning Everyday <span class="text-studio-gold">Deshi Stories</span> into Iconic Animation.
                </h1>

                <p class="text-slate-300 text-lg leading-relaxed max-w-2xl">
                    Meet <strong class="text-white">Antik Mahmud</strong>—the creative force who revolutionized Bengali YouTube by introducing relatable, humorous, and deeply nostalgic 2D storytime animation to millions across Bangladesh and beyond.
                </p>

                <div class="flex flex-wrap gap-4 pt-2">
                    <a href="#work" class="px-6 py-3.5 rounded-xl bg-studio-coral text-white font-display font-semibold text-base hover:bg-rose-500 transition-all shadow-lg shadow-studio-coral/25">
                        Discover His Work
                    </a>
                    <a href="#timeline" class="px-6 py-3.5 rounded-xl bg-studio-card border border-studio-border text-slate-200 font-display font-semibold text-base hover:border-studio-gold hover:text-studio-gold transition-all">
                        Read His Journey
                    </a>
                </div>
            </div>

            <!-- Custom Vector Animator Card Illustration -->
            <div class="md:col-span-5 flex justify-center">
                <div class="relative w-full max-w-sm animate-float">
                    <div class="bg-studio-card border-2 border-slate-700 rounded-3xl p-6 comic-shadow">
                        <!-- Top Window Dots -->
                        <div class="flex items-center justify-between pb-4 mb-4 border-b border-slate-800">
                            <div class="flex gap-1.5">
                                <span class="w-3 h-3 rounded-full bg-studio-coral"></span>
                                <span class="w-3 h-3 rounded-full bg-studio-gold"></span>
                                <span class="w-3 h-3 rounded-full bg-studio-teal"></span>
                            </div>
                            <span class="text-xs font-mono text-slate-400">24 FPS • DHAKA_STUDIO.FLA</span>
                        </div>

                        <!-- Stylized Animator Avatar SVG -->
                        <div class="bg-slate-900/90 rounded-2xl p-6 flex flex-col items-center justify-center border border-slate-800">
                            <svg viewBox="0 0 220 200" class="w-48 h-44" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <!-- Background Circle -->
                                <circle cx="110" cy="100" r="78" fill="#1E293B" stroke="#FFBE0B" stroke-width="3" stroke-dasharray="6 6"/>
                                <!-- Drawing Tablet -->
                                <rect x="42" y="138" width="136" height="32" rx="8" fill="#0F172A" stroke="#00F5D4" stroke-width="2.5"/>
                                <line x1="58" y1="154" x2="132" y2="154" stroke="#334155" stroke-width="4" stroke-linecap="round"/>
                                <!-- Stylus Pen -->
                                <path d="M148 112L168 148" stroke="#FF5E5B" stroke-width="6" stroke-linecap="round"/>
                                <circle cx="146" cy="109" r="3" fill="#FFBE0B"/>
                                <!-- Character Head -->
                                <rect x="78" y="46" width="64" height="72" rx="28" fill="#FDE68A"/>
                                <!-- Hair -->
                                <path d="M74 68C74 42 94 32 114 34C134 36 146 48 144 70C136 56 122 52 108 54C94 56 82 60 74 68Z" fill="#0F172A"/>
                                <!-- Glasses -->
                                <rect x="85" y="72" width="21" height="15" rx="4" fill="#0B1120" stroke="#FF5E5B" stroke-width="2.5"/>
                                <rect x="114" y="72" width="21" height="15" rx="4" fill="#0B1120" stroke="#FF5E5B" stroke-width="2.5"/>
                                <line x1="106" y1="79" x2="114" y2="79" stroke="#FF5E5B" stroke-width="2.5"/>
                                <!-- Eyes -->
                                <circle cx="95" cy="79" r="2.5" fill="#FFFFFF"/>
                                <circle cx="124" cy="79" r="2.5" fill="#FFFFFF"/>
                                <!-- Smile -->
                                <path d="M100 98Q110 107 120 98" stroke="#0F172A" stroke-width="3" stroke-linecap="round"/>
                            </svg>

                            <div class="mt-3 text-center">
                                <h2 class="font-display text-xl font-bold text-white">Antik Mahmud</h2>
                                <p class="text-xs text-studio-gold font-medium mt-0.5">Dhaka, Bangladesh 🇧🇩</p>
                            </div>
                        </div>

                        <!-- Bottom Mini Tags -->
                        <div class="mt-4 flex flex-wrap gap-2 justify-center">
                            <span class="px-2.5 py-1 rounded-md bg-slate-800 text-xs text-slate-300">2D Animation</span>
                            <span class="px-2.5 py-1 rounded-md bg-slate-800 text-xs text-slate-300">Storytime</span>
                            <span class="px-2.5 py-1 rounded-md bg-slate-800 text-xs text-slate-300">Unmad Cartoonist</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Stats Banner -->
    <section class="border-y border-studio-border bg-studio-card/60">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-10 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
            <div>
                <div class="font-display text-3xl sm:text-4xl font-bold text-studio-gold">1.5M+</div>
                <div class="text-sm text-slate-400 mt-1">YouTube Subscribers</div>
            </div>
            <div>
                <div class="font-display text-3xl sm:text-4xl font-bold text-studio-coral">100M+</div>
                <div class="text-sm text-slate-400 mt-1">Total Video Views</div>
            </div>
            <div>
                <div class="font-display text-3xl sm:text-4xl font-bold text-studio-teal">10+</div>
                <div class="text-sm text-slate-400 mt-1">Published Books & Comics</div>
            </div>
            <div>
                <div class="font-display text-3xl sm:text-4xl font-bold text-studio-purple">1st Gen</div>
                <div class="text-sm text-slate-400 mt-1">BD Storytime Animator</div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mb-12">
                <span class="text-studio-coral font-display font-semibold uppercase tracking-wider text-sm">Who Is He?</span>
                <h2 class="font-display text-3xl sm:text-4xl font-bold text-white mt-2">
                    A Storyteller Who Gave Bangladeshi Youth a Visual Voice
                </h2>
            </div>

            <div class="grid md:grid-cols-3 gap-6">
                <div class="bg-studio-card border border-studio-border rounded-2xl p-6 hover:border-studio-gold/50 transition-colors">
                    <div class="w-12 h-12 rounded-xl bg-studio-coral/15 text-studio-coral flex items-center justify-center font-display text-2xl font-bold mb-4">
                        01
                    </div>
                    <h3 class="font-display text-xl font-bold text-white mb-2">Roots in Cartooning</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Before conquering YouTube, Antik honed his craft as a cartoonist, contributing to Bangladesh's legendary satire magazine <strong class="text-slate-200">Unmad</strong>. That sharp wit and observational humor remain the backbone of every frame he draws.
                    </p>
                </div>

                <div class="bg-studio-card border border-studio-border rounded-2xl p-6 hover:border-studio-gold/50 transition-colors">
                    <div class="w-12 h-12 rounded-xl bg-studio-gold/15 text-studio-gold flex items-center justify-center font-display text-2xl font-bold mb-4">
                        02
                    </div>
                    <h3 class="font-display text-xl font-bold text-white mb-2">Pioneering 2D Storytime</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        At a time when Bangladeshi YouTube was dominated by live-action sketches and vlogs, Antik introduced expressive, fast-paced animated storytime videos—turning mundane school days, exams, and family quirks into viral comedy.
                    </p>
                </div>

                <div class="bg-studio-card border border-studio-border rounded-2xl p-6 hover:border-studio-gold/50 transition-colors">
                    <div class="w-12 h-12 rounded-xl bg-studio-teal/15 text-studio-teal flex items-center justify-center font-display text-2xl font-bold mb-4">
                        03
                    </div>
                    <h3 class="font-display text-xl font-bold text-white mb-2">Bestselling Comic Author</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Extending his universe beyond screens, Antik became a regular sensation at the <strong class="text-slate-200">Amar Ekushey Book Fair</strong>, inspiring young readers with illustrated adventure books, sci-fi comics, and graphic novels.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Filterable Signature Works Showcase -->
    <section id="work" class="py-20 bg-studio-card/40 border-y border-studio-border">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-10">
                <div>
                    <span class="text-studio-gold font-display font-semibold uppercase tracking-wider text-sm">Creative Universe</span>
                    <h2 class="font-display text-3xl sm:text-4xl font-bold text-white mt-2">
                        What Makes His Content Iconic?
                    </h2>
                </div>

                <!-- Category Filter Buttons -->
                <div class="flex flex-wrap gap-2" id="filter-buttons">
                    <button data-filter="all" class="filter-btn active px-4 py-2 rounded-full text-xs font-semibold bg-studio-coral text-white transition-all">
                        All Themes
                    </button>
                    <button data-filter="animation" class="filter-btn px-4 py-2 rounded-full text-xs font-semibold bg-studio-card border border-studio-border text-slate-300 hover:border-studio-gold transition-all">
                        2D Storytime
                    </button>
                    <button data-filter="nostalgia" class="filter-btn px-4 py-2 rounded-full text-xs font-semibold bg-studio-card border border-studio-border text-slate-300 hover:border-studio-gold transition-all">
                        Deshi Nostalgia
                    </button>
                    <button data-filter="books" class="filter-btn px-4 py-2 rounded-full text-xs font-semibold bg-studio-card border border-studio-border text-slate-300 hover:border-studio-gold transition-all">
                        Books & Comics
                    </button>
                </div>
            </div>

            <!-- Cards Grid -->
            <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6" id="work-grid">
                <div class="work-card bg-studio-card border border-studio-border rounded-2xl p-6 flex flex-col justify-between" data-category="animation nostalgia">
                    <div>
                        <span class="inline-block px-2.5 py-1 rounded-md bg-studio-coral/15 text-studio-coral text-xs font-semibold mb-3">School & Exam Chronicles</span>
                        <h3 class="font-display text-xl font-bold text-white mb-2">SSC, HSC & Classroom Chaos</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            From strict invigilators to last-night exam panic and hilarious teacher archetypes, Antik captured the universal Bangladeshi student struggle like nobody else.
                        </p>
                    </div>
                    <div class="mt-5 pt-4 border-t border-slate-800 text-xs text-slate-400 font-medium">
                        Signature Style: Exaggerated facial expressions & rapid comedic timing
                    </div>
                </div>

                <div class="work-card bg-studio-card border border-studio-border rounded-2xl p-6 flex flex-col justify-between" data-category="nostalgia animation">
                    <div>
                        <span class="inline-block px-2.5 py-1 rounded-md bg-studio-gold/15 text-studio-gold text-xs font-semibold mb-3">Middle-Class Family Life</span>
                        <h3 class="font-display text-xl font-bold text-white mb-2">Relatable Deshi Household</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Eid shopping crowds, noisy relatives asking about grades, load-shedding childhood memories, and neighborhood cricket—every episode feels like home.
                        </p>
                    </div>
                    <div class="mt-5 pt-4 border-t border-slate-800 text-xs text-slate-400 font-medium">
                        Signature Style: Authentic Dhaka slang & warm nostalgia
                    </div>
                </div>

                <div class="work-card bg-studio-card border border-studio-border rounded-2xl p-6 flex flex-col justify-between" data-category="animation">
                    <div>
                        <span class="inline-block px-2.5 py-1 rounded-md bg-studio-teal/15 text-studio-teal text-xs font-semibold mb-3">Social Commentary</span>
                        <h3 class="font-display text-xl font-bold text-white mb-2">Satire With a Message</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Beyond pure comedy, his videos subtly critique toxic social norms, peer pressure, career anxiety, and internet trends without ever sounding preachy.
                        </p>
                    </div>
                    <div class="mt-5 pt-4 border-t border-slate-800 text-xs text-slate-400 font-medium">
                        Signature Style: Sharp wit rooted in editorial cartooning
                    </div>
                </div>

                <div class="work-card bg-studio-card border border-studio-border rounded-2xl p-6 flex flex-col justify-between" data-category="books">
                    <div>
                        <span class="inline-block px-2.5 py-1 rounded-md bg-studio-purple/15 text-
