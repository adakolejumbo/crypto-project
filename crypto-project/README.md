# Crypto Dashboard 📈

A modern, responsive cryptocurrency dashboard built with **React** and **Vite**.  
This application displays real-time cryptocurrency market data, interactive price charts, and detailed coin information in a clean, dark-themed UI.

🔗 **Live Demo:** (add your Vercel link here once deployed)

---

## 🚀 Features

- 📊 **Real-time crypto market data** (via CoinGecko API)
- 🔍 **Search and filter cryptocurrencies**
- 📈 **Interactive price charts** using Recharts
- 🧭 **Multi-page routing** (Home & Coin Details)
- 🌙 **Dark, dashboard-style UI**
- 📱 **Fully responsive design**
- ⚡ **Fast development & builds** with Vite

---

## 🛠️ Tech Stack

- **Frontend:** React 19
- **Build Tool:** Vite
- **Routing:** React Router
- **Charts:** Recharts
- **Styling:** Custom CSS (dark dashboard theme)
- **API:** CoinGecko (public crypto data)
- **Deployment:** Vercel

---

## 📂 Project Structure

src/
├─ api/ # API requests (CoinGecko)
├─ components/ # Reusable UI components (CryptoCard, etc.)
├─ pages/ # Page-level components (Home, CoinDetail)
├─ utils/ # Helper/formatter functions
├─ index.css # Global styles & theme
├─ App.jsx # App layout & routing
└─ main.jsx # React entry point

yaml
Copy code

---

## 🖥️ Getting Started (Local Development)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/adakolejumbo/crypto-project.git
cd crypto-project
2️⃣ Install dependencies
bash
Copy code
npm install
3️⃣ Start the development server
bash
Copy code
npm run dev
Open your browser at:

arduino
Copy code
http://localhost:5173
🏗️ Build for Production
bash
Copy code
npm run build
To preview the production build locally:

bash
Copy code
npm run preview
🌐 Deployment
This project is optimized for Vercel.

Push changes to GitHub

Import the repository into Vercel

Vercel automatically builds and deploys the app

For React Router support on refresh, the project includes a Vercel rewrite configuration.

🎨 UI & Design Notes
Dark-themed dashboard inspired by modern fintech & crypto platforms

Card-based layout with hover animations

Color-coded price changes (green/red)

Smooth transitions and responsive grid layout

📌 Future Improvements
⏳ Time-range selection for charts (7d / 30d / 1y)

⭐ Watchlist / favorites

🌗 Light/Dark theme toggle

💾 Local caching for API calls

🔐 Authentication for personalized dashboards

👤 Author
Adakole Jumbo-Ochigbo
🔗 GitHub: https://github.com/adakolejumbo

