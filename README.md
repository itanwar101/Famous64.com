# Famous64

A modern, fast web application for streaming famous movies and shows.

## Features

- 🎬 Curated content library
- ⭐ Top rated recommendations
- 🎯 Personalized experience
- 🚀 Fast and smooth performance

## Project Setup

```bash
# Install dependencies
npm install

# Development server (http://localhost:5173)
npm run dev

# Build for production
npm run build

# Preview production build
npm preview
```

## Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions.

Visit: [https://itanwar101.github.io/Famous64.com/](https://itanwar101.github.io/Famous64.com/)

## Technology Stack

- **Frontend**: Vite + Vanilla JavaScript
- **Hosting**: GitHub Pages
- **CI/CD**: GitHub Actions
- **Build Tool**: Vite

## License

MIT License - Feel free to use this project!


🇧🇩 Famous64 - Bangladesh Heritage Showcase
Famous64 is a premium, high-fidelity e-commerce and heritage showcase web application designed to highlight the authentic local specialties, traditional fabrics, organic products, and handicrafts across all 64 districts of Bangladesh.

✨ Key Features
64 District Items Browser

Filter and explore regional specialties grouped dynamically under Bangladesh's 8 divisions (Dhaka, Chattogram, Rajshahi, Khulna, Barishal, Sylhet, Rangpur, Mymensingh).
District Spotlight Cards explaining the historic origin story, unique heritage, and cultural fame of the selected region.
Full Bilingual Support (English & Bangla)

A floating header toggle switcher allows users to instantly swap the entire application language.
Seamlessly translates product catalogs, district spotlights, checkout forms, receipts, navigation links, and administrative panels.
Value Save Combo Bundles

Specially curated gift selections (like the Organic Sundarban & Natore Delights or the Sylhet High-Tea selection) with integrated free delivery.
Bilingual Editorial Blog

Hand-crafted articles documenting the lives of rural weavers (Jamdani, Nakshi Kantha), date palm harvesters, and mangrove honey collectors.
Interactive Quote & Timeline Builder

Features a live project estimation sheet comparing WooCommerce, Laravel, and Next.js stacks.
Users can select custom modules (e.g. Android App, SMS Notification Gateway) to watch the project budget (BDT) and development schedule recalculate live.
Seller & Admin Dashboard Simulator

Tracks mock earnings, counts incoming orders, and offers a status changer for recent orders.
Includes a fully localized Product Upload Form that immediately publishes items live into the database catalog!
🛠️ Technology Stack
Frontend Framework: React (v19)
Build Tool: Vite (v8)
Animations: Framer Motion
Icons: Lucide React
Styling: Pure CSS3 variables with a bespoke deshi color palette (Forest Green, National Crimson, Royal Gold, and backing Glassmorphism).
🚀 Getting Started
To run the application locally on your machine, open your terminal inside the Famous64 directory and run the following commands:

1. Install Dependencies
bash

npm install
2. Run the Development Server
bash

npm run dev
Once started, open http://localhost:5173/ in your web browser.

3. Build for Production
bash

npm run build
This will compile and bundle the files into the dist folder, fully optimized and ready for web hosting.

📂 File Architecture
/src/data.js — Core database holding 64 districts data, products, blogs, and the bilingual translation dictionary.
/src/App.jsx — Router views, application layout, sub-components, and active state management.
/src/index.css — Heritage theme styling, colors, and responsive layouts.
/index.html — Document entry and SEO metadata headers.
