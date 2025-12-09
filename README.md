🌦️ Weather Repo — Spring Boot Weather Application

A clean and efficient Weather Forecasting Application built using Java + Spring Boot.
This project fetches real-time weather data from an external API and exposes clean REST endpoints for use in any backend or frontend app.

🚀 Features

✨ Get current weather for any city
⚡ Fast & lightweight Spring Boot backend
🔧 Clean REST API architecture
📦 Beginner-friendly layered structure
🛡 Error handling & clean JSON responses

🛠 Tech Stack

Java 17+

Spring Boot

REST API

Maven

Jackson JSON Parser

External Weather API

📁 Project Structure
src/
 ├─ main/java/com/example/weather
 │     ├─ controller      → REST endpoints
 │     ├─ service         → Weather fetching logic
 │     └─ model           → Response models
 └─ main/resources
        └─ application.properties

▶️ How to Run the Project
1. Clone the Repository
git clone https://github.com/lalitsingh712/Weather-App.git
cd Weather-Repo

2. Add Your API Key

application.properties me add karein:

weather.api.key=YOUR_API_KEY

3. Run the Application

Using Maven:

mvn spring-boot:run


OR
Directly run the WeatherApplication.java from your IDE.

📡 API Endpoint
Get current weather for a city
GET /api/weather/{city}

Example Response
{
  "city": "Delhi",
  "temperature": "24°C",
  "description": "Clear Sky",
  "humidity": "42%"
}
