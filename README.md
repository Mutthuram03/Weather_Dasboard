# 🌦️ Weather Dashboard App  

## 📖 Introduction  
Imagine taking a trip and wanting to know your destination’s weather so you can pack accordingly, or maybe you’re going to several different places and want to check the weather for each one. That’s exactly why I built the **Weather Dashboard App**.  

In addition to weather updates, the app also allows users to look up restaurants or addresses on a map. This required integrating **React Router** to handle navigation between pages. The biggest challenges were working with multiple APIs, handling persistent data, and implementing tab navigation with React Router.  

The Weather Dashboard App is a **React.js web application** that allows users to:  
- Search for and view **current weather conditions** in any city worldwide.  
- Explore a city or address on an **interactive Google Map**.  
- View weather for saved cities on a **dashboard with tiles**.  

---

## 🚀 Features  
✅ Search for current weather conditions in any city worldwide  
✅ Display weather details on individual tiles  
✅ Search for cities/addresses on Google Maps  
✅ Responsive design for desktop and mobile  
✅ Weather icons representing live conditions  
✅ Persistent storage of searched cities (local storage)  
✅ Interactive Google Map with directions  

---

## 🛠️ Technologies Used  
- **Frontend**: React.js, JavaScript, JSX, React-Bootstrap, CSS  
- **Build Tool**: Vite  
- **Networking**: Axios  
- **Version Control**: Git & GitHub  

---

## 🌐 APIs Integrated  
- **Google Geolocation API** – Retrieve user’s location coordinates  
- **Google Maps Directions API** – Interactive maps with directions  
- **OpenWeather API** – Weather data for cities worldwide  

---

## ⚡ Challenges Faced  
- Integrating **OpenWeather API** with **Google Maps** on the same UI  
- Using Axios for async API calls and rendering data dynamically  
- Persistently storing searched city weather data  
- Setting up **React Router** for tab/page navigation  

---

## 🔑 API Keys Setup  

### Google API Key  
1. Go to [Google Cloud Console](https://console.cloud.google.com/).  
2. Create a **New Project**.  
3. Enable **Geolocation API** and **Maps Static API**.  
4. Go to **APIs & Services → Credentials → Create Credentials → API Key**.  
5. Copy your key.  

### OpenWeather API Key  
1. Go to [OpenWeather](https://home.openweathermap.org/).  
2. Sign up or log in.  
3. Navigate to **My API Keys**.  
4. Generate a new key and copy it.  

---

## 🔧 Add API Keys to the Project  

In **`Home.jsx`**, replace:  
```js
export const WEATHER = "YOUR_OPENWEATHER_API_KEY";

const geoURL = `https://www.googleapis.com/geolocation/v1/geolocate?key=${import.meta.env.VITE_MAP_API_KEY}`;
const staticURL = `https://maps.googleapis.com/maps/api/staticmap?center=${lat},${lon}&zoom=${zoom}&size=${size}&key=${import.meta.env.VITE_MAP_API_KEY}`;
## ⚙️ Installation

Clone the repository

git clone https://github.com/Mutthuram03/Weather_Dasboard.git
cd Weather_Dasboard


Install dependencies

npm install


Run the development server

npm run dev


Open in browser: http://localhost:5173

