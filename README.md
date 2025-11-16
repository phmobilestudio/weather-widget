# 🌦️ Auto-Location Weather Widget  
A lightweight, mobile-friendly widget that automatically detects a visitor’s location and shows real-time weather using free public APIs. Perfect for embedding inside **Google Sites**, **Wix**, **WordPress**, **Notion**, and any website that supports iframes.

---

## ✨ Features
- 🔍 **Auto detects visitor’s city via IP lookup**
- 🌡️ **Real-time temperature & wind conditions**
- 🌍 **No API key required (100% free)**
- ⚡ **Fast & minimal — pure HTML/CSS/JavaScript**
- 📱 **Mobile-responsive design**
- 🔗 **One-line embed code for Google Sites**

---

## 🚀 Demo  
Live demo:  
`https://yourusername.github.io/weather-widget/`

---

## 📦 Embed on Google Sites

1. Go to **Insert → Embed → Embed code**  
2. Paste this:

```html
<iframe src="https://yourusername.github.io/weather-widget/"
        width="100%" height="350" style="border:0;"></iframe>
```

3. Click **Insert**  
4. Done — the widget will auto-detect visitor location.

---

## 🛠️ How It Works

### 1. Gets User Location  
Uses **ipinfo.io** (no API key needed for basic IP geolocation):

```javascript
fetch("https://ipinfo.io/json")
```

Returns approximate coordinates.

### 2. Fetches Weather Data  
Uses **Open-Meteo API**:

```javascript
https://api.open-meteo.com/v1/forecast?latitude=xx&longitude=yy&current_weather=true
```

### 3. Displays a clean weather card  
Rendered with simple CSS for clarity and responsiveness.

---

## 📁 Folder Structure
```
weather-widget/
│── index.html
│── script.js
│── style.css
│── /assets
│     └── icon.svg
```

---

## 🧩 Browser Compatibility
✔ Google Chrome  
✔ Firefox  
✔ Safari  
✔ Edge  
✔ Mobile browsers (Android + iOS)

---

## 📝 License
MIT License — free to use, modify, and embed anywhere.

---

## 🤝 Contributions
Pull requests are welcome!  
If you want to improve design, animations, or add multi-day forecasts — feel free!

---

## ⭐ Support
If this project helped you, please ⭐ star the repository!
