# watt
⚡ Watt — Energy Insights
A free, privacy-first Progressive Web App (PWA) for Irish electricity customers. Import your ESB Networks smart meter data and get personalised insights, tariff comparisons, and night rate optimisation — all running locally on your device.
🔒 Your data never leaves your device. No accounts, no servers, no tracking.
Features
Overview — total usage, rate breakdown, monthly trends, top insights
Night Rate Optimiser — hourly heatmap, shift savings calculator, see exactly what moving loads to the night window would save
Tariff Comparison — your actual 30-minute usage data modelled against major Irish suppliers (Yuno, Electric Ireland, Energia, Bord Gáis, Pinergy)
Trends — daily usage chart, hourly averages, day-of-week patterns, peak days
Advice — prioritised recommendations with estimated annual savings
How to Use
Step 1 — Download your ESB data
Go to myaccount.esbnetworks.ie
Log in and go to Meter Readings
Select Download HDF to get your CSV export
Step 2 — Install the app
Open [the app URL] in Chrome on Android
Tap the three-dot menu (⋮) → Add to Home screen
Tap Add — it installs like a native app, no Play Store needed
Step 3 — Import your data
Open Watt from your home screen
Tap Choose CSV File and select your downloaded HDF file
Your data is analysed instantly and stored locally for future sessions
Privacy
All data processing happens entirely in your browser using JavaScript. Your electricity data is stored in your device's local IndexedDB storage — the same mechanism used by apps like Google Maps for offline data. Nothing is transmitted to any server. The app creator has no access to your data.
Compatibility
✅ Android (Chrome) — full PWA install support
✅ iOS (Safari) — works as a web app, Add to Home Screen from Share menu
✅ Desktop browsers — works as a regular web app
Data Format
Designed for the ESB Networks HDF CSV export format (Irish smart meters). The file typically looks like:
MPRN,Meter Serial Number,Read Value,Read Type,Read Date and End Time
10310042721,000000000012345678,0.245,Active Import Interval (kWh),06-03-2026 00:30
Tariff Rates
Tariff rates are based on published unit rates as of early 2026. Rates change periodically — always verify on supplier websites before making switching decisions. Standing charges, PSO levy and 9% VAT are included in all estimates.
Supplier
Night
Day
Peak
Standing/day
Yuno Energy (TOU Variable)
€0.1891
€0.3091
€0.3354
€0.5926
Electric Ireland (Home Electric+ Night)
€0.1652
€0.3145
—
€0.6200
Energia (Smart EV Saver)
€0.1420
€0.2980
—
€0.6400
Bord Gáis (Smart Home)
€0.1750
€0.3210
—
€0.5800
Pinergy (Smart PAYG)
€0.1890
€0.3350
—
€0.5500
Built With
Vanilla HTML/CSS/JavaScript — no frameworks, no build tools
Chart.js for data visualisation
IndexedDB for local persistent storage
Hosted on GitHub Pages
Not affiliated with ESB Networks or any energy supplier. For informational purposes only.