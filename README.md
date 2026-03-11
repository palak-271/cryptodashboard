<div align="center">
  <h1>💰 Crypto Dashboard</h1>
  <p>A modern, responsive cryptocurrency dashboard built with React and Tailwind CSS. Track real-time prices, view historical charts, and manage your watchlist with a beautiful, animated user interface.</p>
</div>

## ✨ Features

- **📊 Real-time Data**: Up-to-date cryptocurrency prices and market statistics.
- **📈 Interactive Charts**: Detailed historical price charts utilizing Recharts.
- **⭐ Watchlist Tracker**: Save and track your favorite cryptocurrencies.
- **🔍 Detailed Coin Insights**: Modal view with comprehensive data for individual coins.
- **💵 Multi-Currency Support**: Switch between different fiat currencies.
- **✨ Smooth Animations**: High-quality UI transitions powered by Framer Motion.
- **📱 Responsive Design**: Fully optimized for both desktop and mobile devices.

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Charts**: [Recharts](https://recharts.org/)
- **Icons**: [Lucide React](https://lucide.dev/)

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd crypto-dashboard
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`.
5. CLICK this LINK [crypto-dashboard-psi-three.vercel.app](https://crypto-dashboard-psi-three.vercel.app/)

## 📜 Available Scripts

In the project directory, you can run:

- `npm run dev` - Starts the development server with Hot Module Replacement (HMR).
- `npm run build` - Builds the app for production to the `dist` folder.
- `npm run preview` - Previews the production build locally.
- `npm run lint` - Runs ESLint to evaluate the code and catch potential issues.

## 📁 Project Structure

```text
src/
├── assets/         # Static assets (images, fonts, etc.)
├── components/     # Reusable React components (Header, StatsPanel, CoinTable, etc.)
├── context/        # React Context providers (CurrencyContext for currency switching)
├── hooks/          # Custom Hooks (useCryptoData for API integration)
├── App.jsx         # Main application layout, state, and routing logic
├── main.jsx        # Application entry point binding to the DOM
└── index.css       # Global styles and Tailwind directives
```

## 📄 License

This project is open-source and available under the MIT License.
