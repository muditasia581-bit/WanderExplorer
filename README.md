# 🌍 WanderExplorer - Discover Your Dream Destination

> **Explore the world from your screen. Discover destinations, check live weather, and plan your next adventure with WanderExplorer. ✈️**

![WanderExplorer Banner](https://github.com/user-attachments/assets/4e110ff2-30a6-4ba2-a6bd-d42908714811)

---

## 📌 About The Project

**WanderExplorer** is a dynamic and visually stunning travel discovery web application designed to help users explore their dream destinations around the world.

By combining **real-time weather data, high-quality destination images, and informative summaries**, WanderExplorer creates an immersive experience for discovering cities worldwide.

Built using **HTML, CSS, and Vanilla JavaScript**, the application features a responsive design, smooth animations, and an intuitive interface that makes travel exploration simple and engaging.

---

## ✨ Features

### 🔎 Search Destinations

* Search any city worldwide (e.g., Paris, Tokyo, New York).
* Fetch real-time weather information.
* Display beautiful destination imagery.
* Get a short destination overview.

### 🏙️ Interactive Destination Cards

* Beautifully designed destination cards.
* Display:

  * City images
  * Temperature
  * Weather conditions
  * Destination summary
* Hover animations for an engaging experience.
* Remove unwanted destinations easily.

### 🖼️ Modal Gallery

* Click any destination card to open detailed information.
* View:

  * Curated image gallery
  * Famous landmarks
  * Architecture and culture highlights
  * Wikipedia-powered destination summaries

### 💾 Local Storage Support

* Save favorite destinations locally.
* Revisit destinations anytime.
* Remove individual locations.
* Clear all saved destinations.

### 📱 Responsive Design

* Fully responsive interface.
* Optimized for:

  * Desktop
  * Tablets
  * Mobile devices

### 🌌 Animated Background

* Gradient-shifting background.
* Twinkling star animations.
* Immersive travel-inspired atmosphere.

### ⚡ Error Handling

* Friendly error messages.
* Automatic error dismissal.
* Handles invalid destinations and API failures.

---

# 🛠️ Technologies Used

## Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

## APIs

### 🌦️ OpenWeatherMap API

Provides:

* Live weather data
* Temperature information
* Weather descriptions

### 🖼️ Unsplash API

Provides:

* High-quality city images
* Destination galleries

### 📖 Wikipedia REST API

Provides:

* Destination summaries
* Additional city information

## Other Technologies

* Google Fonts (Poppins)
* Local Storage API
* CSS Animations
* Glassmorphism UI
* Responsive Media Queries

---

# 🚀 Getting Started

## Prerequisites

Before running the project, make sure you have:

* A modern web browser:

  * Chrome
  * Firefox
  * Edge
* Internet connection for API requests

---

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/muditasia581-bit/WanderExplorer.git

cd WanderExplorer
```

---

### 2. API Configuration

The project uses:

* OpenWeatherMap API
* Unsplash API

You can replace the demo keys inside `index.html` with your own keys.

Example:

```javascript
const OPENWEATHER_API_KEY = "your-api-key";

const UNSPLASH_ACCESS_KEY = "your-access-key";
```

> Using your own API keys is recommended because demo keys have request limitations.

---

### 3. Run The Application

Since WanderExplorer is a static website, run it using a local server.

### Option 1: Live Server

Install:

```bash
npm install -g live-server
```

Run:

```bash
live-server
```

---

### Option 2: Python Server

```bash
python3 -m http.server 8000
```

Open:

```
http://localhost:8000
```

---

# 📂 Project Structure

```
WanderExplorer/
│
├── index.html        # Main application file
├── README.md         # Documentation
│
└── assets/           # Images and resources (if available)
```

---

# 🎮 Usage

## Search Destination

1. Enter a city name.
2. Click **Explore Now** or press Enter.
3. The application fetches:

   * Weather information
   * Destination image
   * City summary

---

## Interact With Cards

* Hover over cards for animations.
* Click cards to open detailed views.
* Remove destinations using the delete option.

---

## Manage Favorites

* Saved destinations are stored in browser Local Storage.
* Use **Clear All** to remove saved destinations.

---

# 📸 Screenshots

## Hero Section

![Hero Section](https://github.com/user-attachments/assets/4e110ff2-30a6-4ba2-a6bd-d42908714811)

---

## Empty State

![Empty State](https://github.com/user-attachments/assets/5c70b636-825c-4058-b2f5-fa803f8aaa81)

---

## Modal Gallery

![Modal Gallery](https://github.com/user-attachments/assets/d6abcff6-0356-4362-8cfd-83db191862aa)

---

## Destination Card

![Destination Card](https://github.com/user-attachments/assets/41919df9-bb39-4562-bb47-a5a53815d8c7)

---

# ⚠️ Limitations

* API rate limits may affect image and weather requests.
* API keys are currently handled on the client side.
* Unsplash may return fallback images if results are unavailable.
* Accessibility improvements can be added in future versions.

---

# 🔮 Future Improvements

## Backend Integration

Move API keys to a secure backend service using:

* Node.js / Express
* Flask

## Performance Improvements

* API response caching.
* Request optimization.
* Search debouncing.

## Additional Features

* Destination sorting and filtering.
* Offline support using Service Workers.
* Better accessibility support.
* User accounts and cloud-based favorites.

---

# 🤝 Contributing

Contributions are welcome!

### Steps:

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature/new-feature
```

3. Commit changes:

```bash
git commit -m "Add new feature"
```

4. Push changes:

```bash
git push origin feature/new-feature
```

5. Create a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project.

---

# 🙌 Acknowledgements

Special thanks to:

* 🌦️ OpenWeatherMap for weather data.
* 🖼️ Unsplash for destination images.
* 📖 Wikipedia for destination information.
* 🔤 Google Fonts for typography resources.

---

# 📬 Contact

For suggestions, feedback, or collaboration:

Open an issue in the repository or connect through GitHub.

---

## ✈️ Happy Exploring With WanderExplorer! 🌍
