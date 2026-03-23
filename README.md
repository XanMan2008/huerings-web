<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hue Rings - Master the Spectrum</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #0f172a; color: white; }
        .glow-cyan { box-shadow: 0 0 20px rgba(0, 242, 255, 0.5); }
        .glow-pink { box-shadow: 0 0 20px rgba(255, 0, 127, 0.5); }
        .glow-lime { box-shadow: 0 0 20px rgba(57, 255, 20, 0.5); }
        .gradient-text { background: linear-gradient(to right, #00f2ff, #ff007f); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    </style>
</head>
<body class="selection:bg-[#00f2ff] selection:text-slate-900">

    <!-- Navigation -->
    <nav class="p-6 flex justify-between items-center max-w-6xl mx-auto">
        <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-[#00f2ff] to-[#ff007f] flex items-center justify-center font-black text-xl">H</div>
            <span class="font-black tracking-tighter text-2xl uppercase">Hue Rings</span>
        </div>
        <div class="hidden md:flex gap-8 text-sm font-bold uppercase tracking-widest text-slate-400">
            <a href="#features" class="hover:text-white transition-colors">Features</a>
            <a href="#support" class="hover:text-white transition-colors">Support</a>
            <a href="#privacy" class="hover:text-white transition-colors">Privacy</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="px-6 py-20 flex flex-col items-center text-center max-w-4xl mx-auto">
        <div class="relative w-40 h-40 mb-12 flex items-center justify-center">
            <div class="absolute inset-0 border-8 border-[#00f2ff] rounded-full animate-pulse opacity-50"></div>
            <div class="absolute inset-4 border-8 border-[#ff007f] rounded-full animate-pulse delay-75 opacity-50"></div>
            <div class="absolute inset-8 border-8 border-[#39FF14] rounded-full animate-pulse delay-150 opacity-50"></div>
            <span class="text-6xl">⭕</span>
        </div>
        <h1 class="text-6xl md:text-8xl font-black mb-6 tracking-tighter uppercase leading-none">
            Master the <span class="gradient-text">Spectrum</span>
        </h1>
        <p class="text-xl text-slate-400 mb-10 max-w-2xl leading-relaxed">
            A vibrant, addictive color-matching puzzle. Stack, match, and clear your way to the top of the global leaderboards.
        </p>
        <div class="flex gap-4">
            <div class="bg-white text-black px-8 py-4 rounded-full font-black text-lg shadow-xl hover:scale-105 transition-transform cursor-pointer">
                COMING SOON TO APP STORE
            </div>
        </div>
    </section>

    <!-- Features -->
    <section id="features" class="px-6 py-20 bg-slate-900/50">
        <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-12">
            <div class="p-8 rounded-3xl bg-slate-800/50 border border-white/5">
                <div class="w-12 h-12 bg-[#00f2ff]/20 rounded-xl flex items-center justify-center mb-6 text-[#00f2ff]">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="m21 16-4 4-4-4"/><path d="M17 20V4"/><path d="m3 8 4-4 4 4"/><path d="M7 4v16"/></svg>
                </div>
                <h3 class="text-2xl font-black mb-4 uppercase tracking-tight">Strategic Stacking</h3>
                <p class="text-slate-400 leading-relaxed">Stack small, medium, and large rings in a single cell to maximize your board space.</p>
            </div>
            <div class="p-8 rounded-3xl bg-slate-800/50 border border-white/5">
                <div class="w-12 h-12 bg-[#ff007f]/20 rounded-xl flex items-center justify-center mb-6 text-[#ff007f]">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20"/><path d="m17 7-5-5-5 5"/><path d="m17 17-5 5-5-5"/></svg>
                </div>
                <h3 class="text-2xl font-black mb-4 uppercase tracking-tight">Combo Chains</h3>
                <p class="text-slate-400 leading-relaxed">Trigger consecutive clears to grow your multiplier and reach legendary high scores.</p>
            </div>
            <div class="p-8 rounded-3xl bg-slate-800/50 border border-white/5">
                <div class="w-12 h-12 bg-[#39FF14]/20 rounded-xl flex items-center justify-center mb-6 text-[#39FF14]">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4"/><path d="M12 8h.01"/></svg>
                </div>
                <h3 class="text-2xl font-black mb-4 uppercase tracking-tight">Global Ranks</h3>
                <p class="text-slate-400 leading-relaxed">Compete with players worldwide and prove you are the ultimate Hue Master.</p>
            </div>
        </div>
    </section>

    <!-- Support Section -->
    <section id="support" class="px-6 py-20 max-w-4xl mx-auto text-center border-t border-white/5">
        <h2 class="text-4xl font-black mb-6 uppercase tracking-tight">Support</h2>
        <p class="text-slate-400 mb-8 text-lg">
            Having trouble with Hue Rings? We're here to help. Reach out to our support team and we'll get back to you as soon as possible.
        </p>
        <a href="mailto:leftyxan@gmail.com" class="inline-block bg-[#00f2ff] text-slate-900 px-10 py-4 rounded-full font-black text-lg hover:glow-cyan transition-all">
            EMAIL SUPPORT
        </a>
    </section>

    <!-- Privacy Policy Section -->
    <section id="privacy" class="px-6 py-20 bg-slate-900/80">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-4xl font-black mb-10 uppercase tracking-tight text-center">Privacy Policy</h2>
            <div class="prose prose-invert max-w-none text-slate-400 space-y-6 text-sm">
                <p><strong>Last Updated: March 23, 2026</strong></p>
                <p>Hue Rings ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and disclose information when you use our mobile application.</p>
                
                <h3 class="text-white font-bold text-lg uppercase">1. Information Collection</h3>
                <p>We collect information to provide a better experience for all our users. This includes:</p>
                <ul class="list-disc pl-6 space-y-2">
                    <li><strong>User Identifiers:</strong> We use Firebase Authentication to sync your high scores and achievements across devices. This may include your name and email address if you sign in with Google or Apple.</li>
                    <li><strong>Device Identifiers:</strong> We use Google AdMob to serve advertisements. AdMob may collect your device's advertising ID to provide personalized ads.</li>
                    <li><strong>Usage Data:</strong> We collect anonymous gameplay data (like high scores) to maintain our global leaderboards.</li>
                </ul>

                <h3 class="text-white font-bold text-lg uppercase">2. How We Use Information</h3>
                <p>We use the collected data to:</p>
                <ul class="list-disc pl-6 space-y-2">
                    <li>Maintain and update the global leaderboards.</li>
                    <li>Provide personalized advertisements through Google AdMob.</li>
                    <li>Analyze app performance and fix bugs through Firebase Crashlytics.</li>
                    <li>Comply with Apple's Guideline 5.1.1 regarding account deletion.</li>
                </ul>

                <h3 class="text-white font-bold text-lg uppercase">3. Third-Party Services</h3>
                <p>Our app uses third-party services that may collect information used to identify you:</p>
                <ul class="list-disc pl-6 space-y-2">
                    <li><a href="https://policies.google.com/privacy" class="text-[#00f2ff] underline">Google Play Services</a></li>
                    <li><a href="https://support.google.com/admob/answer/6128543" class="text-[#00f2ff] underline">AdMob</a></li>
                    <li><a href="https://firebase.google.com/support/privacy" class="text-[#00f2ff] underline">Firebase Analytics</a></li>
                </ul>

                <h3 class="text-white font-bold text-lg uppercase">4. Your Rights</h3>
                <p>You can request the deletion of your account and all associated data directly within the app settings. Once deleted, this action is permanent and cannot be undone.</p>

                <h3 class="text-white font-bold text-lg uppercase">5. Contact Us</h3>
                <p>If you have any questions about this Privacy Policy, please contact us at <strong>leftyxan@gmail.com</strong>.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="p-10 text-center text-slate-500 text-xs border-t border-white/5">
        <p>&copy; 2026 Hue Rings. All rights reserved.</p>
    </footer>

</body>
</html>
