# Mini Weather Dashboard App

This is a Kotlin-based Jetpack Compose weather app developed as part of the Altametrics Android Developer Take-Home Assignment. The app allows users to search for any city and view current weather information powered by the OpenWeatherMap API.

---

## Features

-  Search weather by city name
-  Display temperature and weather condition
-  Show relevant weather icon
-  Save recent searches (up to 3 cities)
-  Show loading indicator while fetching
-  Handle invalid city and network errors
-  Unit-tested ViewModel with mocked dependencies

---

##  Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Architecture:** MVVM
- **Async:** Coroutines, Flow
- **Testing:** JUnit, Mockito, Turbine
- **Local Storage:** SharedPreferences via helper

---

##  Getting Started

### Prerequisites
- Android Studio Hedgehog or newer
- OpenWeatherMap API key (replace in `WeatherViewModel.kt`)

### Run the App
1. Clone the repository
2. Open in Android Studio
3. Build and Run on emulator or device
4. Enter a city name and tap "Search"

---

## Test Coverage

Run:
```bash
./gradlew test
```
Covers:
- `WeatherViewModel.getWeather()` success/failure logic
- Saving and displaying recent cities
- UI state changes for loading, success, and error

---

##  Design Decisions

- Used `StateFlow` for reactive UI updates
- Separated UI state (`WeatherUiState`) from business logic
- Simulated shared preferences with a mocked in-memory implementation during tests
- Added ByteBuddy agent to prevent future mocking issues

---

##  The answer of 7/6 to 20 decimal

> ZZZZ4Z4Z4Z4Z4Z4Z4Z4Z4Z

---

##  Submission

This assignment was completed by **Mohammed Zaid**  
📩 Email: zaidzedoo007@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mohammed-zaid-6860a1237/)

---
