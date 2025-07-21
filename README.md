# ☀️ WeatherApp GUI (Java Swing)

This is a **Java Swing-based Weather App GUI** that fetches live weather data using an external API and displays it in a user-friendly interface.

---

## 📌 Features

- 🌍 Search weather by **city name** (supports global locations)
- 🕒 Shows current **temperature**, **humidity**, **weather condition**, and **time**
- 📸 Dynamically updates icons based on weather (e.g., sunny, cloudy, rain)
- 🌐 Displays **local time of the searched city** using its time zone
- 🎯 Supports **Indian and other international cities**
- 💡 Fully embedded resources (images/icons) in `.jar` — no external dependencies!

---

## 🏗️ Technologies Used

- **Java 17**
- **Swing GUI Framework**
- **OpenWeatherMap API**
- **WorldTimeAPI for time zone info**
- `json-simple` for JSON parsing

---

## 🗂️ Project Structure

```
WeatherApp/
├── src/
│   ├── AppLauncher.java
│   ├── WeatherAppGui.java
│   ├── WeatherApp.java
│   └── assets/
│       ├── sunny.png
│       ├── cloudy.png
│       └── ... other icons
├── lib/
│   └── json-simple-1.1.1.jar
├── WeatherApp.jar
└── README.md
```

---

## 🚀 How to Run

### 🛠️ From IDE (IntelliJ, Eclipse)
1. Import project
2. Add `json-simple-1.1.1.jar` to classpath
3. Run `AppLauncher.java`

### 📦 From .jar (After Build)
1. Double-click `WeatherApp.jar` or run via command line:

```bash
java -jar WeatherApp.jar
```

### 💻 Create an .exe (Optional)
Use [Launch4j](http://launch4j.sourceforge.net/) to wrap the `.jar` into a Windows `.exe`

---

## 📍 Notes

- Internet connection is required to fetch live data.
- Ensure API keys are correct (if using a paid service).
- All images are embedded, so app runs standalone from JAR.

---

## 🧑‍💻 Author

Varsha S P  | Java learner

📅 Generated on: July 21, 2025

---

## 📃 License

Free to use for educational purposes. Attribution appreciated!
