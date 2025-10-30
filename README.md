🧭 MarketWise — Landing Page Design

💡 Overview
MarketWise is a responsive and visually engaging landing page built using React + TypeScript.
The project showcases a modern fintech dashboard design that focuses on data visualization, user engagement, and clean UI components.

It’s designed to serve as a marketing or analytics landing page for a company offering stock market insights, portfolio tracking, or financial analytics.

The page highlights:
A hero section introducing the product/service.
Interactive charts showing financial trends.
Feature cards, testimonials, and call-to-action elements.
A footer with essential navigation and contact links.

🧰 Tech Stack
Category	Technologies Used
Frontend Framework	React
 with TypeScript

Styling	Tailwind CSS
 + Custom CSS
Charts / Data Visualization	Recharts
 (built on top of D3.js)
Icons	Lucide React

UI Components	Shadcn/UI (for modern and accessible UI)
Package Manager	npm / yarn / pnpm
Build Tool	Vite / React Scripts (based on your setup)

✨ Features
✅ Modern & Responsive Design – Works seamlessly across desktop and mobile.
📊 Interactive Charts – Displays financial data trends dynamically.
⚙️ Reusable Components – Modular and maintainable React components.
🎨 Tailwind-Powered Styling – Utility-first CSS for fast and scalable design.
⚡ Optimized Performance – Built with lightweight components and efficient rendering.
🧩 Clean Folder Structure – Easy to navigate and extend for future enhancements.

📂 Folder Structure
Market Wise Landing Page Design/
│
├── public/
│   └── assets/          # Images and static resources
│
├── src/
│   ├── components/      # Reusable UI components (Hero, Chart, Features, Footer, etc.)
│   ├── styles/          # Global and section-wise CSS files
│   ├── App.tsx          # Root component
│   ├── main.tsx         # Entry point
│   └── index.css        # Tailwind and global styling
│
├── package.json
└── README.md

⚙️ Installation & Setup
Follow these steps to run the project locally:

1. Clone the Repository
git clone https://github.com/<your-username>/MarketWise-Landing-Page.git
cd MarketWise-Landing-Page

2. Install Dependencies
npm install

3. Run the Development Server
npm run dev

4. Open in Browser

Visit: http://localhost:5173/
 (or as mentioned in terminal)

📊 Libraries Used
🧮 Recharts
Used for rendering visually appealing charts.
Built on top of D3.js, providing simple APIs for line, bar, and pie charts.
Allows customization using props for colors, tooltips, labels, and legends.

💅 Tailwind CSS
Enables rapid UI development using utility-first classes.
Ensures the design remains consistent, responsive, and maintainable.

🪶 Lucide React
Provides lightweight vector icons.
Used across buttons, features, and navigation elements.

🧠 Key React Concepts Used
Functional Components — Modular and reusable UI parts.
Hooks (useState, useEffect) — Manage local state and lifecycle events.
Props — Pass data between components.
Component Composition — Reusable layouts and design sections.
Responsive Design — Implemented using Tailwind breakpoints.

🏁 Quick Summary
MarketWise is a front-end focused project demonstrating a clean, responsive, and modern landing page with integrated chart visualizations — ideal for fintech or analytics-based web applications.
