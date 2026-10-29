# ratibku-app
Muslim App to track zikr in Bahasa Melayu

RatibKu: Daily Zikr & Du'a Companion

A minimalist, privacy-first daily remembrance and supplication tracker designed to nurture consistency (istiqamah) through verified Quranic and Hadith traditions.

📖 Overview

RatibKu (from Arabic Wird/Ratib – a structured litany of daily remembrance, and Malay Ku – my) is a responsive single-page web application and Progressive Web App (PWA). It provides Muslims with an intuitive, distraction-free companion to set daily goals, engage with authentic adhkar, count repetitions with tactile precision, and monitor weekly progress—all while keeping spiritual data private and local.

✨ Features

Sunnah-Aligned Adhkar & Du'as: Pre-loaded with essential daily litanies (Morning Adhkar, Post-Salah Wird, Evening Adhkar, and Bedtime Du'as).

Academic & Scholarly Verification: Every card features authentic Arabic typography, phonetic transliteration, clear translation (English & Malay), and canonical source citations (Sahih al-Bukhari, Sahih Muslim, Hisnul Muslim).

Personalized Daily Goals: Customize target sets and repetition counts (e.g., 33x vs. 100x) based on your daily routine.

Interactive Tasbih Counter:

Large, ergonomic tap target designed for one-handed thumb interaction.

Visual circular progress ring with smooth completion animations.

Haptic feedback pulse on mobile devices when each milestone is reached.

Ethical Gamification (Istiqamah over Vanity):

Earn completion stars upon finishing full sets.

Unlock milestone badges (e.g., Istiqamah Pemula, Pencinta Zikir, Minggu Barakah) without intrusive leaderboards or vanity metrics.

Weekly Adherence Dashboard: A rolling 7-day calendar overview displaying daily consistency, star totals, and completed counts.

Offline-First & Local Persistence: Operates completely offline with automatic localStorage retention; no compulsory login or server data collection required.

🛠️ Tech Stack

Markup & Styling: Semantic HTML5, Tailwind CSS (via CDN)

Typography: Google Fonts (Amiri for classical Arabic typography, Inter for Latin interfaces)

Scripting: Modern Vanilla JavaScript (ES6+, zero heavy framework dependencies)

Icons & Visual Effects: Lucide Icons (SVG) and Canvas-Confetti

📂 Project Structure

ratibku/
├── index.html         # Complete single-page application (UI, styles & logic)
├── manifest.json      # Progressive Web App configuration
├── sw.js              # Offline-first Service Worker
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
└── README.md          # Project documentation


🚀 Getting Started

1. Running Locally

Since RatibKu is a client-side application, you can run it immediately without running a build step or installing Node dependencies:

Clone or download this repository:

git clone https://github.com/your-username/ratibku.git
cd ratibku


Open index.html directly in any modern web browser:

macOS: open index.html

Linux: xdg-open index.html

Windows: start index.html

2. Free Static Hosting

You can deploy RatibKu to production in seconds using any static host:

Cloudflare Pages / Netlify: Drag and drop the project folder directly into the dashboard for an instant edge-cached live URL.

GitHub Pages:

Push this folder to a GitHub repository.

Navigate to Settings > Pages.

Under Branch, select main and / (root).

Click Save to receive your live https://<username>.github.io/<repo>/ link.

📱 Installing as a PWA (Mobile)

RatibKu can be installed directly onto your device's home screen as a standalone application:

iOS (Safari): Tap the Share button (box with an arrow) → Scroll down and select Add to Home Screen.

Android (Chrome): Tap the three-dot menu icon in the upper right → Select Install App or Add to Home screen.

🔒 Privacy & Adab (Etiquette)

In keeping with Islamic ethics regarding the preservation of sincerity in worship:

Zero Tracking: No analytics, trackers, or cookies are stored on remote servers.

Local Storage Only: All zikr counts, personal goals, and streak data remain on your local device.

Quiet Mode Support: Designed with soft color palettes (deep emerald #064E3B and muted slate) to prevent visual distractions in mosques or dark rooms.

📄 License

Distributed under the MIT License. Feel free to use, modify, and distribute for personal and educational purposes.
