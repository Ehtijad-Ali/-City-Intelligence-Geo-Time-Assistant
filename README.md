# 🌆 AI-Powered City Intelligence and Geo-Time Assistant

### 🌐 Smart, Interactive, and Visually Stunning City Information Platform

The **AI-Powered City Intelligence and Geo-Time Assistant** is a cutting-edge web application designed to provide rich, real-time information about any city in the world. Powered by intelligent APIs, immersive UI design, and voice interaction, it delivers a next-generation experience for exploring cities globally.

---

## 🚀 Features Overview

### 🧠 Core Intelligence Features

* **City Identification:** Detects the country, region, and key facts for any entered city.
* **Geo Coordinates:** Displays the exact latitude and longitude.
* **Local Time & Timezone:** Shows live local time and timezone data.
* **City Summary:** Provides a short yet detailed summary including:

  * Population
  * Major attractions
  * Economy overview
  * Cultural highlights
* **Nearby Cities:** Lists nearby major cities or landmarks with distance estimations.
* **Country Details:** Displays the country’s **flag** and **capital city**.
* **Weather Information:** Real-time temperature, condition, humidity, and wind data.

---

### 🗺️ Interactive Map

* Integrated **OpenStreetMap (OSM)** view with precise location markers.
* Country and city names displayed **in English**.
* Smooth zoom and drag interactions.
* Dynamic marker highlighting for selected cities.

---

### 🎤 Voice & Multilingual Capabilities

* **Voice Input:** Ask naturally — “Tell me about Paris.”
* **Voice Output:** AI responds with spoken details.
* **Multilingual Support:** Automatic or selectable language translation.
* **Language Selector:** Clean dropdown with visible text colors in dark mode.

---

### 💾 Search History

* Stores the last 5 searched cities.
* Quick recall buttons for revisiting recently viewed cities.
* Persistent storage using browser `localStorage`.

---

## 💡 Bonus Add-ons

* 🎉 **Local Events & Holidays:** Detects and displays upcoming festivals.
* 💱 **Currency & Exchange Rate:** Shows local currency and its rate vs USD.
* ⏰ **Time Difference:** Displays difference between user and city timezones.
* ✈️ **Travel Info:** Includes best time to visit and local safety index.

---

## 🎨 Modern Dark-Themed Design

### 🌈 7 Stunning Color Themes:

Choose your vibe! Instantly switch between these dynamic gradients:

1. **Purple Dream** – Elegant purple & pink glow
2. **Ocean Blue** – Deep blue & cyan tones
3. **Emerald Green** – Fresh teal & mint hues
4. **Sunset Orange** – Warm golden & coral blend
5. **Rose Pink** – Soft pink & rose gradient
6. **Amber Gold** – Luxurious amber & gold tones
7. **Cyan Teal** – Sleek modern cyan palette

All themes adapt across:

* Buttons
* Cards
* Headers
* Background gradients
* Map highlights

Your chosen theme is saved in your browser for next time!

---

## ✨ Visual & Interactive Enhancements

* Dynamic gradient backgrounds with animation
* **Glassmorphism** UI throughout
* Smooth **AOS** entrance animations
* Hover glow & scale transformations
* Pulse and fade-in microinteractions
* Floating chatbot with animated responses
* Background **video** and **audio** with toggles
* Clean typography and responsive layout

---

## 🤖 Integrated Chatbot

* Floating assistant icon in bottom-right corner
* Engaging AI-like text interaction
* Animated message bubbles with sliding effects
* Seamless open/close transitions
* Maintains chat history during session

---

## ⚙️ Tech Stack

| Category               | Technology                              |
| ---------------------- | --------------------------------------- |
| **Frontend Framework** | HTML5, CSS3, JavaScript (ES6+)          |
| **Mapping API**        | OpenStreetMap (Leaflet.js)              |
| **Weather Data**       | OpenWeatherMap API                      |
| **Voice Input/Output** | Web Speech API                          |
| **Translation**        | Google Translate API (optional)         |
| **UI Enhancements**    | AOS (Animate On Scroll), CSS Animations |
| **Theme Persistence**  | LocalStorage                            |
| **Icons**              | Font Awesome / Material Icons           |

---

## 🧩 Project Structure

```
📂 City-Intelligence-Assistant/
│
├── index.html                # Main webpage
├── style.css                 # Core and theme styles
├── script.js                 # App logic, API calls, and event handling
├── assets/
│   ├── bg-video.mp4          # Background looping video
│   ├── music.mp3             # Optional background audio
│   └── icons/                # App icons and flag assets
├── data/
│   └── cities.json           # Local database (optional)
└── README.md                 # Project documentation
```

---

## 🧭 How It Works

1. Enter or speak a city name (e.g., “Paris”).
2. The system fetches:

   * Country, coordinates, timezone
   * Weather data from OpenWeatherMap
   * Map location using Leaflet.js
   * Flag, currency, and more via APIs
3. Displays all results beautifully in animated cards.
4. You can listen to the response using voice output.
5. Change the color theme with a single click!

---

## 🗣️ Commands Examples

* “Tell me about **Paris**”
* “Show weather in **Tokyo**”
* “Where is **Dubai** located?”
* “Switch theme to **Emerald Green**”

---

## 🔊 Media Controls

* 🎧 Toggle background audio
* 🎥 Show/hide background video
* 🎨 Change theme instantly
* 💬 Open/close chatbot

---

## 🛠️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<yourusername>/City-Intelligence-Assistant.git
   cd City-Intelligence-Assistant
   ```
2. **Open the project:**
   Just open `index.html` in any modern browser (Chrome, Edge, Firefox).
3. **(Optional)** Add your API keys in `script.js`:

   ```js
   const WEATHER_API_KEY = "your_openweathermap_api_key";
   ```
4. **Enjoy!** 🎉

---

## 🔐 API Integrations

| API                           | Purpose                         |
| ----------------------------- | ------------------------------- |
| **OpenWeatherMap**            | Real-time weather info          |
| **OpenStreetMap (Leaflet)**   | Interactive maps                |
| **REST Countries API**        | Flag, capital, and country data |
| **WorldTimeAPI / TimeZoneDB** | Local time & timezone           |
| **ExchangeRate API**          | Currency and USD rate           |
| **Google Translate API**      | Multilingual response support   |

---

## 📱 Responsive Design

The website is **fully responsive**, working seamlessly on:

* Desktop 💻
* Tablet 📱
* Mobile 📲

---

## 🌟 Future Improvements

* Add AI-generated travel itineraries
* Add real-time news & local updates per city
* Offline caching for recent searches
* Integration with Gemini or OpenAI API for richer chatbot responses

---

## 🧑‍💻 Developer

**Author:** Ehtijad Ali Shah
**Role:** Junior Data Scientist & AI Developer
**GitHub:** [github.com/Ehtijad-Ali](https://github.com/Ehtijad-Ali)
**Specialties:** AI • Machine Learning • Deep Learning • Computer Vision • Data Science


Would you like me to make this README in **Markdown format** (with code blocks, emojis, and headings ready for GitHub upload)?
I can also include **badges** (for tech stack, license, and API usage) for a more professional GitHub presentation.
