<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZORO TRADER - Research &amp; Market Education</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Playfair+Display:ital,wght@0,700;0,800;1,700&amp;display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            950: '#050814',
                            900: '#0a1128',
                            800: '#101a38',
                            700: '#17244d'
                        },
                        gold: {
                            300: '#f6e095',
                            400: '#e5c365',
                            500: '#d4af37',
                            600: '#b38f24'
                        },
                        cyanAccent: {
                            400: '#38bdf8',
                            500: '#0ea5e9',
                            600: '#0284c7'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                        serif: ['Playfair Display', 'serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #0a1128;
            font-family: 'Plus Jakarta Sans', sans-serif;
            color: #ffffff;
            overflow-x: hidden;
        }

        .gold-gradient-text {
            background: linear-gradient(135deg, #FFF0CA 0%, #d4af37 50%, #b38f24 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gold-border-glow {
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.35);
        }

        .cta-pulse {
            box-shadow: 0 0 25px rgba(14, 165, 233, 0.45);
            animation: pulse-glow 2.2s infinite;
        }

        @keyframes pulse-glow {
            0% {
                box-shadow: 0 0 0 0 rgba(14, 165, 233, 0.7);
            }
            70% {
                box-shadow: 0 0 0 16px rgba(14, 165, 233, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(14, 165, 233, 0);
            }
        }

        .bg-grid-pattern {
            background-size: 30px 30px;
            background-image: 
                linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-between p-4 sm:p-6 bg-navy-900 bg-grid-pattern relative pb-28 sm:pb-8 selection:bg-gold-500 selection:text-navy-950">

    <!-- Top Utility Bar (Copy HTML Code Button) -->
    <div class="w-full max-w-md flex justify-end mb-2">
        <button id="copyCodeBtn" onclick="copyPageHTML()" class="text-xs bg-navy-800/90 hover:bg-navy-700 text-gold-400 border border-gold-500/30 px-3 py-1.5 rounded-lg flex items-center gap-1.5 transition-all duration-200 shadow-md backdrop-blur-md active:scale-95">
            <i class="fa-regular fa-copy"></i>
            <span id="copyBtnText">Copy Source Code</span>
        </button>
    </div>

    <!-- Header Top Badge -->
    <header class="w-full max-w-md text-center">
        <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-navy-800/80 border border-gold-500/30 text-xs tracking-wider text-gold-300 font-semibold uppercase shadow-lg backdrop-blur-sm">
            <span class="w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
            RESEARCH &amp; MARKET EDUCATION • TRADING COMMUNITY
        </div>
    </header>

    <!-- Main Content Card -->
    <main class="w-full max-w-md my-auto flex flex-col items-center justify-center text-center space-y-6 pt-4">
        
        <!-- Profile Photo Container -->
        <div class="relative group">
            <!-- Outer Glow Halo -->
            <div class="absolute -inset-1.5 bg-gradient-to-r from-gold-500 via-amber-300 to-gold-600 rounded-full blur-md opacity-70 group-hover:opacity-100 transition duration-300"></div>
            
            <div class="relative w-36 h-36 sm:w-44 sm:h-44 rounded-full p-1 bg-gradient-to-tr from-gold-600 via-gold-300 to-amber-200 gold-border-glow">
                <img src="https://i.ibb.co/q3xQ8HMP/IMG-20261026-180311-312.jpg" alt="ZORO TRADER Profile Picture" class="w-full h-full object-cover rounded-full border-4 border-navy-950 shadow-inner" onerror="this.onerror=null; this.src='https://placehold.co/300x300/101a38/d4af37?text=ZORO+TRADER';">
            </div>

            <!-- Verified Analyst Badge -->
            <div class="absolute -bottom-3 left-1/2 transform -translate-x-1/2 bg-gradient-to-r from-gold-400 via-gold-500 to-amber-600 text-navy-950 text-xs font-extrabold px-3.5 py-1 rounded-full border-2 border-navy-950 shadow-xl flex items-center gap-1.5 whitespace-nowrap">
                <i class="fa-solid fa-circle-check text-navy-950 text-sm"></i>
                <span>VERIFIED ANALYST</span>
            </div>
        </div>

        <!-- Main Title & Subtitle -->
        <div class="space-y-3 pt-3">
            <p class="text-xs sm:text-sm font-bold tracking-widest text-cyanAccent-400 uppercase">
                Stock Market &amp; Option Trading Specialist
            </p>
            
            <h1 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight leading-tight">
                Learn &amp; Trade with <br>
                <span class="font-serif gold-gradient-text text-4xl sm:text-5xl block mt-1 drop-shadow-md">ZORO TRADER</span>
            </h1>

            <p class="text-xs sm:text-sm text-gray-300 max-w-xs mx-auto leading-relaxed">
                Daily Market Analysis • Nifty &amp; Bank Nifty • Educational Insights
            </p>
        </div>

        <!-- Telegram Main CTA Button -->
        <div class="w-full px-2 pt-1">
            <a href="https://t.me/+gM70YcQjR7xkODI1" target="_blank" rel="noopener noreferrer" class="cta-pulse w-full py-4 px-6 rounded-2xl bg-gradient-to-r from-sky-500 via-cyanAccent-500 to-blue-600 hover:from-sky-400 hover:to-blue-500 text-white font-extrabold text-lg sm:text-xl flex items-center justify-center gap-3 transform active:scale-95 transition-all duration-200 border border-cyan-300/40 shadow-2xl">
                <i class="fa-paper-plane text-2xl text-white"></i>
                <span>Join Telegram Community — Free</span>
            </a>
            
            <p class="text-xs text-gray-400 mt-2.5 font-medium flex items-center justify-center gap-1">
                <i class="fa-solid fa-lock text-[10px] text-gold-400"></i>
                Instant Free Access • 100% Educational Content
            </p>
        </div>

        <!-- Community Social Proof -->
        <div class="flex items-center justify-center gap-3 py-1 bg-navy-800/50 px-4 rounded-full border border-slate-800">
            <div class="flex -space-x-2 overflow-hidden">
                <span class="inline-flex items-center justify-center h-7 w-7 rounded-full bg-blue-900 border-2 border-navy-950 text-[10px] font-bold text-sky-300">ZT</span>
                <span class="inline-flex items-center justify-center h-7 w-7 rounded-full bg-amber-900 border-2 border-navy-950 text-[10px] font-bold text-gold-300">RK</span>
                <span class="inline-flex items-center justify-center h-7 w-7 rounded-full bg-emerald-900 border-2 border-navy-950 text-[10px] font-bold text-emerald-300">AM</span>
                <span class="inline-flex items-center justify-center h-7 w-7 rounded-full bg-purple-900 border-2 border-navy-950 text-[10px] font-bold text-purple-300">VS</span>
                <span class="inline-flex items-center justify-center h-7 w-7 rounded-full bg-navy-700 border-2 border-navy-950 text-[10px] font-bold text-gray-300">+</span>
            </div>
            <p class="text-xs text-gray-300 font-medium">
                Join our growing <strong class="text-gold-400 font-bold">50,000+</strong> trading community
            </p>
        </div>

        <!-- Key Feature Cards -->
        <div class="w-full pt-2 space-y-2.5">
            <div class="grid grid-cols-2 gap-3">
                <div class="flex items-center justify-start gap-3 p-3 rounded-xl bg-navy-800/80 border border-slate-700/60 text-xs font-semibold text-gray-200 shadow-sm text-left">
                    <div class="w-8 h-8 rounded-lg bg-gold-500/10 border border-gold-500/30 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-chart-pie text-gold-400"></i>
                    </div>
                    <span>Daily Market Updates</span>
                </div>
                
                <div class="flex items-center justify-start gap-3 p-3 rounded-xl bg-navy-800/80 border border-slate-700/60 text-xs font-semibold text-gray-200 shadow-sm text-left">
                    <div class="w-8 h-8 rounded-lg bg-cyanAccent-500/10 border border-cyanAccent-500/30 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-bullseye text-cyanAccent-400"></i>
                    </div>
                    <span>Nifty &amp; BankNifty Setup</span>
                </div>
            </div>

            <div class="flex items-center justify-center gap-2.5 p-3 rounded-xl bg-navy-800/80 border border-slate-700/60 text-xs font-semibold text-gray-200 shadow-sm">
                <span class="text-base">🇮🇳</span>
                <span>Made for Indian Traders &amp; Investors</span>
            </div>
        </div>

    </main>

    <!-- Footer Disclaimer -->
    <footer class="w-full max-w-md mt-8 pt-4 border-t border-slate-800/60 text-center">
        <p class="text-[10px] text-gray-500 leading-normal">
            <strong>Disclaimer:</strong> Investment in securities market are subject to market risks. Read all the related documents carefully before investing. Registration granted by SEBI and certification from NISM in no way guarantee performance of the intermediary or provide any assurance of returns to investors. All content shared is strictly for educational purposes.
        </p>
        <p class="text-[10px] text-gray-600 mt-2 font-semibold tracking-wider">
            © 2026 ZORO TRADER • ALL RIGHTS RESERVED
        </p>
    </footer>

    <!-- Mobile Floating Sticky Bottom CTA Bar -->
    <div class="fixed bottom-0 left-0 right-0 p-3 bg-navy-950/90 border-t border-slate-800/80 backdrop-blur-md z-50 sm:hidden">
        <a href="https://t.me/+gM70YcQjR7xkODI1" target="_blank" rel="noopener noreferrer" class="w-full py-3 px-4 rounded-xl bg-gradient-to-r from-sky-500 to-cyanAccent-600 text-white font-bold text-base flex items-center justify-center gap-2.5 shadow-lg active:scale-95 transition-transform">
            <i class="fa-paper-plane text-lg"></i>
            <span>Join Free Telegram Channel</span>
        </a>
    </div>

    <!-- JavaScript to Handle Copying Source Code -->
    <script>
        function copyPageHTML() {
            const fullHTML = document.documentElement.outerHTML;
            
            const tempTextArea = document.createElement("textarea");
            tempTextArea.value = "<!DOCTYPE html>\n" + fullHTML;
            document.body.appendChild(tempTextArea);
            tempTextArea.select();
            
            try {
                document.execCommand("copy");
                const btnText = document.getElementById("copyBtnText");
                const originalText = btnText.innerText;
                btnText.innerText = "Copied to Clipboard!";
                
                setTimeout(() => {
                    btnText.innerText = originalText;
                }, 2000);
            } catch (err) {
                console.error("Failed to copy code: ", err);
            }
            
            document.body.removeChild(tempTextArea);
        }
    </script>

</body>
</html>
