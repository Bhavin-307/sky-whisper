# Sky Whisper

## 🌤️ Overview

Sky Whisper is a modern and intuitive weather application built with React and Vite. It provides real-time weather updates, forecasts, and other essential meteorological data in a sleek and user-friendly interface.

## 🚀 Features

🌎 Get real-time weather updates for any location

⏳ Hourly and daily weather forecasts

📍 Search locations with auto-suggestions

🌡️ Temperature, humidity, wind speed, and other key metrics

🎨 Responsive and visually appealing UI

## 🛠️ Tech Stack

Frontend: React 19, TypeScript, Vite

UI Components: Tailwind CSS, Radix UI

State Management & Data Fetching: TanStack React Query

Routing: React Router 7

Charts & Visualization: Recharts

Other Utilities: clsx, date-fns, sonner (notifications), cmdk (command menu)

## 📂 Project Structure
```
└── 📁sky-whisper
    ├── 📁public
    │   ├── favicon.ico
    │   ├── logo.png
    │   ├── vite.svg
    ├── 📁src
    │   ├── 📁api
    │   │   ├── config.ts
    │   │   ├── types.ts
    │   │   ├── weather.ts
    │   ├── App.css
    │   ├── App.tsx
    │   ├── 📁components
    │   │   ├── city-search.tsx
    │   │   ├── current-weather.tsx
    │   │   ├── favorite-button.tsx
    │   │   ├── favorite-cities.tsx
    │   │   ├── Header.tsx
    │   │   ├── hourly-temperature.tsx
    │   │   ├── Layout.tsx
    │   │   ├── loading-skeleton.tsx
    │   │   ├── theme-provider.tsx
    │   │   ├── 📁ui
    │   │   │   ├── alert.tsx
    │   │   │   ├── button.tsx
    │   │   │   ├── card.tsx
    │   │   │   ├── command.tsx
    │   │   │   ├── dialog.tsx
    │   │   │   ├── scroll-area.tsx
    │   │   │   ├── skeleton.tsx
    │   │   │   ├── sonner.tsx
    │   │   │   ├── tooltip.tsx
    │   │   ├── weather-details.tsx
    │   │   ├── weather-forecast.tsx
    │   ├── 📁hooks
    │   │   ├── use_weather.ts
    │   │   ├── use-favorite.ts
    │   │   ├── use-geolocation.ts
    │   │   ├── use-local-storage.ts
    │   │   ├── use-search-history.ts
    │   ├── index.css
    │   ├── 📁lib
    │   │   ├── utils.ts
    │   ├── main.tsx
    │   ├── 📁pages
    │   │   ├── city-page.tsx
    │   │   ├── weather-dashboard.tsx
    │   ├── vite-env.d.ts
    ├── .env
    ├── .gitattributes
    ├── .gitignore
    ├── components.json
    ├── eslint.config.js
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── README.md
    ├── tsconfig.app.json
    ├── tsconfig.json
    ├── tsconfig.node.json
    ├── vite.config.ts
```
## 📦 Installation

Clone the repository:
```
git clone https://github.com/Bhavin-307/sky-whisper.git
cd sky-whisper

Install dependencies:

npm install

Create a .env file in the root directory and add your API key:

VITE_WEATHER_API_KEY=your_api_key_here

Start the development server:

npm run dev
```
## 🔧 Usage

Open the app in your browser: http://localhost:5173

Search for any city or allow location access for automatic weather updates.

View detailed weather conditions and forecasts.

## 🎨 Screenshots

(Include some screenshots here to showcase the UI.)

📌 Future Enhancements

🌙 Dark mode support

📍 Save favorite locations

📊 Advanced weather analytics

## 📝 Contributing

Feel free to fork this repository and contribute by submitting pull requests. Any contributions are welcome!

## 📜 License

This project is licensed under the MIT License.

## 📬 Contact

If you have any questions or feedback, reach out via [GitHub Issues](https://github.com/Bhavin-307/sky-whisper/issues).