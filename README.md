# ⚡ Weather Pulse — Live Atmospheric Dashboard

> **Weather Pulse** is a sleek, real-time weather dashboard built with a liquid-glassmorphism UI, interactive SVG wave charts, 24-hour horizontal hourly forecasts, multi-source METAR & Open-Meteo API synchronization, global city search, severe alert banners, and smooth scrollbar-free touch controls.

<img width="1917" height="912" alt="image" src="https://github.com/user-attachments/assets/4c66afb7-4042-476f-94d9-e1ff4da8982d" />


## ✨ Key Features

- 🌡️ **Multi-Source Live Weather Sync**: Integrates real-time METAR weather station observations with Open-Meteo high-resolution atmospheric models.
- 🕒 **24-Hour Horizontal Hourly Strip**: Real-time hourly forecast displaying local time, condition icons, rain probabilities (`%`), and sustained wind speeds (`km/h`).
- 📈 **7-Day Interactive Wave Chart**: Smooth SVG temperature wave graph with drag-to-scroll, mouse-wheel horizontal panning, and zero scrollbar clutter.
- ⚡ **Severe Weather Alert Bar**: Dynamic emergency alert banner notifying active thunderstorm, high wind, and flood advisories.
- 🌍 **Global Search & Quick Cards**: Search any global city or click preset cards to switch views instantly with automated reverse-geocoding.
- ⚙️ **Unit & Precision Controls**: Seamless toggle between Celsius (°C) and Fahrenheit (°F) with standard or 1-decimal precision modes.
- 🎨 **Adaptive Weather Visuals**: Automatic background image transitions matching real-time WMO weather condition codes (Storm, Clear, Rain, Fog, Snow).

## 🚀 Getting Started

### Local Setup
No build tools or server dependencies required! Simply clone and open `index.html` in any web browser or serve via HTTP.

```bash
# Clone the repository
git clone https://github.com/VScsaiml-pixel/weather-pulse.git

# Navigate to project folder
cd weather-pulse

# Serve using Python (optional)
python -m http.server 8080
```

Open your browser at: https://nimble-longma-7bc32f.netlify.app/

## 🛠️ Built With

- **HTML5 & CSS3**: Liquid glassmorphism UI system with dynamic scaling via CSS custom properties (`--u`).
- **JavaScript (ES6+)**: Timezone-aware local time calculation, Open-Meteo API integration, METAR observation parsing.
- **SVG Vector Graphics**: Custom Catmull-Rom spline wave chart rendering with smooth stroke animations.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
