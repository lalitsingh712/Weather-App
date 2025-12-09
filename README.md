🌦️ Weather Repo

A simple and efficient Weather Forecasting Application built using Java and Spring Boot.
This project fetches real-time weather information using an external API and exposes clean REST endpoints.

🚀 Features

🌤️ Fetch current weather for any city

⚡ Fast and lightweight Spring Boot backend

🔧 Clean REST API architecture

📦 Beginner-friendly project structure

🌐 Easily extendable for weekly forecast or UI integration

🛠 Tech Stack

Java 17+

Spring Boot

REST API

Maven

JSON Parsing (Jackson)

📁 Project Structure
src/
 ├─ main/java/com/example/weather
 │   ├─ controller
 │   ├─ service
 │   └─ model
 └─ main/resources
     └─ application.properties

▶️ How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/Weather-Repo.git
cd Weather-Repo

2. Configure Weather API Key

Add the API key in application.properties:

weather.api.key=YOUR_API_KEY

3. Run the App

Using Maven:

mvn spring-boot:run


Or run the WeatherApplication.java file directly from IntelliJ.

📡 Example API Endpoint

Get weather info:

GET /api/weather/{city}


Response example:

{
  "city": "Delhi",
  "temperature": "24°C",
  "description": "Clear Sky",
  "humidity": "42%"
}

