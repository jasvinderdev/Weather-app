# 🌤️ Weather App

A simple and responsive **Weather App** built using **HTML, CSS, and JavaScript**.
It uses the **OpenWeatherMap API** to fetch and display real-time weather information for any city.

## 🚀 Features

* 🔍 Search weather by city name
* 🌡️ Displays current temperature
* 💧 Shows humidity
* 💨 Shows wind speed
* 🌤️ Dynamic weather icons based on weather conditions
* ⌨️ Search using the **Enter** key
* 📱 Responsive design for mobile devices
* 🎨 Clean and modern weather-card UI

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* OpenWeatherMap API

## 📂 Project Structure

```text
Weather-App/
│
├── index.html
├── style.css
├── script.js
├── config.js
├── weather/
│   ├── sun.png
│   ├── clouds.png
│   ├── rainy-day.png
│   ├── snow.png
│   ├── storm.png
│   ├── mist.png
│   └── dizzy.png
│
└── README.md
```

## 🔑 API Setup

This project uses the **OpenWeatherMap API**.

1. Create an account on OpenWeatherMap.
2. Generate API key.
3. Add the API key to `config.js` file:

```javascript
const API_key = "YOUR_API_KEY";
```

> **Important:** Never upload your real API key to a public GitHub repository. Use a `.gitignore` file to keep `config.js` private.

## ▶️ How to Run

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the project folder in VS Code.

3. Add your OpenWeatherMap API key in `config.js`.

4. Open `index.html` using **Live Server** or any local server.

5. Enter a city name and search for its current weather.

## 📸 Screenshot

### homepage
<img width="1888" height="883" alt="Screenshot 2026-08-09 234606" src="https://github.com/user-attachments/assets/ff9ae10d-2a4c-4f79-8217-be41a6d11db5" />

### Responive design
<img width="367" height="652" alt="Screenshot 2026-08-09 234624" src="https://github.com/user-attachments/assets/449a6acb-ac56-4c31-9030-a4fa129fbbab" />


## 📚 What I Learned

While building this project, I practiced:

* Working with APIs using `fetch()`
* Using `async/await`
* Handling JSON responses
* DOM manipulation
* Event listeners
* Conditional rendering
* Responsive CSS
* Working with external API data

## 👨‍💻 About

This project was built as a practice project while learning **JavaScript and API integration**.

If you find any mistakes or have suggestions for improvement, feel free to share them!

## Author

Jasvinder Singh
