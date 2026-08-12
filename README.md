# 🌦️ Weather Forecast App

> **Know the sky before you step outside. ☁️**

A simple and interactive weather application that allows users to search for a city and view its current weather information in a clean and responsive interface.

---

## 🌍 About The Project

Weather conditions can change quickly, and having quick access to weather information is useful for planning daily activities.

The **Weather Forecast App** provides a simple way to check weather information by entering a city name. The application retrieves weather data through a weather API and presents important information such as temperature, humidity, wind speed, and weather conditions.

The project was developed to practice **frontend development, JavaScript API integration, asynchronous programming, DOM manipulation, and responsive UI design**.

---

## ✨ Features

### 🔎 City Search

Search for weather information by entering the name of a city.

### 🌡️ Temperature

Displays the current temperature of the searched location.

### 💧 Humidity

Shows the humidity level of the selected city.

### 💨 Wind Speed

Provides information about the current wind speed.

### ☁️ Weather Condition

Displays the current weather condition along with a weather icon.

### ⚡ Real-Time API Data

Weather information is retrieved dynamically from the weather API rather than using fixed data.

### 📱 Responsive Design

The interface adapts to different screen sizes including desktops, tablets, and mobile devices.

### 🚨 Error Handling

Invalid or unavailable city searches can be handled with an appropriate message.

---

## 🖥️ Application Flow

```text
        ┌─────────────────────┐
        │   Open Weather App  │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │   Enter City Name   │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │   Click Search      │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │   Weather API Call  │
        └──────────┬──────────┘
                   ↓
          ┌────────┴────────┐
          ↓                 ↓
     City Found        City Not Found
          ↓                 ↓
   Display Weather      Show Error
          ↓
   Temperature
   Humidity
   Wind Speed
   Weather Icon
```

---

## 🛠️ Technologies Used

| Technology      | Usage                                  |
| --------------- | -------------------------------------- |
| 🌐 HTML5        | Structure of the web application       |
| 🎨 CSS3         | Styling, layout, and responsiveness    |
| ⚡ JavaScript    | Application logic and DOM manipulation |
| 🌤️ Weather API | Retrieving weather information         |
| 🧰 VS Code      | Development environment                |
| 🔧 Git          | Version control                        |
| ☁️ GitHub       | Repository and project hosting         |

---

## 📂 Project Structure

```text
weather-forecast-app/
│
├── 📄 index.html
├── 🎨 style.css
├── ⚡ script.js
├── 📖 README.md
│
└── 📁 assets/
```

### File Details

**`index.html`**

Contains the structure of the application, including the search area and weather information section.

**`style.css`**

Controls the visual appearance, layout, buttons, cards, colors, and responsive behavior.

**`script.js`**

Handles API requests, weather data processing, user interaction, and updating the webpage dynamically.

**`README.md`**

Contains project documentation, features, technologies, and instructions.

---

## 🌡️ Weather Information

The application is designed to present information such as:

```text
📍 Location
🌡️ Temperature
☁️ Weather Condition
💧 Humidity
💨 Wind Speed
🌤️ Weather Icon
```

---

## 🔄 How It Works

1. User opens the Weather Forecast App.
2. User enters a city name.
3. The application sends the city information to the weather API.
4. The API returns the weather data.
5. JavaScript processes the response.
6. The weather information is displayed on the webpage.
7. If the city cannot be found, an error message is displayed.

---

## 🧠 Key Learning Outcomes

Through this project, I learned how to:

* Build a webpage using HTML5.
* Design interfaces using CSS3.
* Manipulate webpage elements using JavaScript.
* Work with APIs.
* Use `fetch()` for asynchronous API requests.
* Handle JSON responses.
* Handle errors from API requests.
* Create responsive web layouts.
* Organize a frontend project.
* Use Git and GitHub for version control.

---

## 🧩 Challenges Faced

During development, some challenges included:

* Understanding how API requests work.
* Handling asynchronous JavaScript operations.
* Displaying API data dynamically.
* Handling invalid city names.
* Managing API response errors.
* Designing a responsive interface.
* Connecting JavaScript with HTML elements correctly.

Solving these problems helped me understand how frontend applications communicate with external services.

---

## 📸 Screenshots

Add screenshots of your actual application here.

### 🏠 Main Interface

```text
Add your screenshot here
```

### 🌤️ Weather Result

```text
Add your screenshot here
```

You can later add images using:

```markdown
![Weather App](assets/weather-app.png)
```

---

## 🚀 How To Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/weather-forecast-app.git
```

### 2. Open the project

```bash
cd weather-forecast-app
```

### 3. Run the application

Open:

```text
index.html
```

in your browser.

---

## 🔐 API Configuration

If the project uses an API key, keep your personal API key private.

Do **not** upload a real secret API key directly to a public GitHub repository.

For a production version, the API key should be stored securely using environment variables or a backend service.

---

## 🔮 Future Enhancements

The application can be improved with:

* 📅 5-day / 7-day weather forecast
* 📍 Current location detection
* 🌙 Dark and light mode
* 🌧️ Rain probability
* 🌅 Sunrise and sunset information
* 🌡️ Celsius/Fahrenheit conversion
* 🔎 Recent search history
* ⭐ Favorite cities
* 📊 Weather charts
* 📱 Progressive Web App support
* 🎨 Dynamic backgrounds based on weather conditions

---

## 📈 Future Vision

The goal is to gradually transform this simple weather application into a more complete weather dashboard that provides users with **current conditions, forecasts, location-based weather, and visual weather analytics** in one place.

---

## 📌 Project Status

🟢 **Completed – Basic Version**

The current version focuses on city search and displaying essential weather information.

Future versions can expand the application with forecast data, location services, advanced visualizations, and additional weather metrics.

---

## 👩‍💻 Author

**Manasa**

Computer Science / Engineering Student

### Interests

`Web Development` • `JavaScript` • `AI/ML` • `Software Development`

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.

---

### 📄 License

This project was developed for **educational and learning purposes**.
