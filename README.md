Weather Radar Tracker
Weather Radar Tracker is a Java Swing application that provides real-time weather updates, personalized clothing recommendations, and intelligent transportation suggestions. It interfaces seamlessly with the OpenWeatherMap API to fetch live weather details based on user input.

✨ Features
✅ Real-Time Weather Data – Retrieves temperature, city name, and weather description from OpenWeatherMap.
✅ Personalized Clothing & Accessories Advice – Suggests outfits based on current weather conditions.
✅ Intelligent Transport Suggestions – Recommends suitable transportation modes based on temperature.
✅ Smooth Fade-In Animation – Enhances UI with visually appealing transitions.
✅ User-Friendly Interface – Simple input field, retrieval button, and dynamic display area.

📂 1. Project Structure
graphql
Copy
Edit
WeatherRadarTracker/
│── src/
│   ├── WeatherTracker.java   # Main Java Swing application
│   ├── WeatherService.java   # Handles API requests & data processing
│   ├── RecommendationEngine.java   # Provides clothing & transport suggestions
│   ├── UIEffects.java   # Handles fade-in animations
│── assets/
│   ├── icon.png   # Application icon (optional)
│── README.md   # Documentation
│── pom.xml (if using Maven)
│── WeatherRadarTracker.iml
└── .gitignore
🚀 2. Installation & Setup
🛠 Step 1: Install Java & IDE
Ensure you have Java 17+ installed:

sh
Copy
Edit
java -version
If not installed, download it from Oracle JDK or use OpenJDK.

🛠 Step 2: Clone the Repository
sh
Copy
Edit
git clone https://github.com/yourusername/WeatherRadarTracker.git
cd WeatherRadarTracker
🛠 Step 3: Install Dependencies (If Using Maven)
sh
Copy
Edit
mvn clean install
🛠 Step 4: Get OpenWeatherMap API Key
Go to OpenWeatherMap
Sign up & generate an API key
Copy the key and update it in WeatherService.java:
java
Copy
Edit
private static final String API_KEY = "your_api_key_here";
🎨 3. UI & Functionalities
📍 User Input & Weather Retrieval
Users enter a city name
Click "Retrieve Weather"
Weather details (temperature, description) are displayed
👕 Personalized Recommendations
Cold Weather → Suggests jackets, gloves, warm clothes
Hot Weather → Suggests light clothing, sunglasses, hydration
🚕 Transport Suggestions
Cold Weather → Recommends taxis, ride-sharing
Warm Weather → Encourages buses, metros, walking
🎬 Smooth Fade-In Animation
Weather data smoothly appears for an enhanced user experience
▶️ 4. Running the Application
🏃 Run with Java (Standalone)
sh
Copy
Edit
javac -d bin src/*.java
java -cp bin WeatherTracker
🏃 Run in IntelliJ IDEA / Eclipse
Open the project in your IDE
Run WeatherTracker.java
🛠 5. Debugging & Fixes
✅ Issue: "Invalid API Key"

Ensure the correct API key is set in WeatherService.java.
✅ Issue: "Swing UI not appearing"

Ensure you're using Java 17+. Run java -version to check.
✅ Issue: "Data not loading"

Check your internet connection and API key validity.
🎯 6. Why Use This?
✅ Beyond Basic Weather Apps – Provides outfit & transport recommendations.
✅ Intelligent UX – Smooth fade-in effects enhance user experience.
✅ Easy to Use – Simple, intuitive, and Java-based.
✅ Customizable – Modify recommendations based on preferences.

📜 7. License
This project is open-source and free to use! 🚀
