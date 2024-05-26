# WeatherApp

WeatherApp is a simple, user-friendly application built using React that allows users to get real-time weather information for any location. This app utilizes a weather API to fetch current weather data and displays it in an easy-to-understand format.

## Features

- **Search Functionality**: Users can search for the current weather by entering a city name.
- **Current Weather Display**: The app shows the current temperature, weather condition, humidity, and wind speed.
- **Responsive Design**: The app is designed to be fully responsive, ensuring a seamless experience on both desktop and mobile devices.
- **Error Handling**: The app gracefully handles errors, such as invalid city names or network issues, and provides user-friendly error messages.

## Screenshots
<img width="637" alt="WeatherApp" src="https://github.com/Paarth-Chandan/WeatherApp/assets/135144621/7e1fa80d-e4d0-4245-9ae1-9cc22e17e940">

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Make sure you have the following installed on your local machine:
- Node.js
- npm (Node Package Manager)

### Installation
1. Clone the repository:
```
git clone https://github.com/your-username/weatherapp.git
cd weatherapp
```
2. Install dependencies:
```
npm install
```
3. Get your own API key:
4. Start the development server:
```
npm start
```
The app will be available at http://localhost:3000.
## Usage
- Open the app in your web browser.
- Enter the name of the city you want to get the weather for in the search bar.
- Press Enter or click the search button to fetch and display the weather information.

## API
The frontend fetches real-time weather reports from https://openweathermap.org/current
**API Format:** https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}
