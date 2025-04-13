# REST-API-CLIENT

"COMPANY" : CODTECH IT SOLUTIONS PVT.LTD

"NAME": SHUBHAM NAWANI

"INTERN ID": CT08DA523

"DOMAIN": JAVA PROGRAMMING

"DURATION": 8 WEEKS

"MENTOR": NEELA SANTOSH

#DESCRIPTION

 REST API Client - Weather Data Viewer (Java)

Task Overview
As part of my internship, I developed a Java-based REST API client application to demonstrate the ability to consume data from a public API over the internet. This project, titled "REST API Client", involved writing a Java program that connects to the OpenWeatherMap REST API to fetch and display real-time weather data for a specific city.

The goal was to understand how HTTP communication works in Java, how to handle RESTful requests, and how to parse and present structured JSON responses. The deliverable was a fully functional Java console application that makes HTTP GET requests, handles responses efficiently, and extracts meaningful data from the JSON payload.

This task was critical for learning how to bridge frontend or backend applications with real-world APIs — an essential skill for building modern, data-driven applications.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Tools and Technologies Used
1. Programming Language
Java


2. Libraries & APIs
HttpURLConnection

Built-in Java class used to send HTTP GET requests and receive responses from the API.

org.json (JSON-Java) Library

External library (json-20210307.jar) used for parsing JSON data returned by the OpenWeatherMap API.

This library allows easy conversion of strings to JSON objects, from which data like temperature and humidity can be extracted.

3. API Used
OpenWeatherMap API

A widely-used public API that returns weather data in JSON format.

Endpoint used:
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
The program uses the city name "London" and displays key weather metrics such as temperature and humidity.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Editor / Development Platform
Visual Studio Code (VS Code) was used to write, compile, and run the Java application.

Required external libraries were added manually to the project folder (json-20210307.jar) and included in the classpath during compilation.

To compile and run the program on cmd:

javac -cp .;json-20210307.jar WeatherClient.java
java -cp .;json-20210307.jar WeatherClient

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Functionality
The program consists of the following functional steps:

Construct API URL

The base API URL is appended with query parameters such as city name, API key, and units (metric).

Make HTTP GET Request

A HttpURLConnection object is used to initiate the request.

The server responds with a JSON object if the request is successful (HTTP 200).

Read and Parse JSON

The JSON response is read into a StringBuilder, and then parsed using the org.json.JSONObject class.

Extracted values:

name – City Name

main.temp – Temperature

main.humidity – Humidity

Display Results

Weather data is neatly formatted and printed to the console.

Real-World Applications
This REST API client project is a simplified yet real-world example of how Java applications interact with external services. Potential use cases and applications include:

Weather Dashboards – A core feature in weather apps, smart home devices, or travel platforms.

IoT Devices – Embedded Java programs on smart devices that fetch weather data to adjust environmental controls.

Mobile App Backends – Java is commonly used in backend services for Android apps or server-side apps consuming APIs.

API Monitoring Tools – Applications that monitor and display API metrics, or respond to external data in real time.

Learning to work with REST APIs is essential for building software that communicates across platforms and ecosystems.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Conclusion
This internship project, "REST API Client – Java Weather Application", successfully demonstrated my ability to consume external REST APIs, handle HTTP requests/responses, and parse JSON data in Java. The final deliverable was a well-structured, modular, and functional program that fetches weather data and presents it clearly via the console.

This exercise greatly enhanced my understanding of:

API consumption in Java

JSON parsing using external libraries

Error handling and response code verification

Building real-time, data-driven applications


#OUTPUT

![Image](https://github.com/user-attachments/assets/e22c5a27-db66-45e7-8cb2-b6a5ca96f86b)
