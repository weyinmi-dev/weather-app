

# Weather App

A sleek, responsive weather application built with React and Vite that provides real-time weather information for any city around the world.

## Features

- **Current Weather Data**: Displays temperature, weather conditions, humidity, and wind speed
- **Dynamic Backgrounds**: Background gradient changes based on weather conditions
- **Weather Icons**: Visual representation of current weather (sunny, rainy, cloudy, snowy)
- **Search Functionality**: Look up weather information for any city
- **Responsive Design**: Works on various screen sizes

## Technologies Used

- [React](https://reactjs.org/) - Frontend framework
- [Vite](https://vitejs.dev/) - Build tool
- [OpenWeatherMap API](https://openweathermap.org/api) - Weather data provider
- CSS3 with custom styling
- Font Awesome icons

## Getting Started

### Prerequisites

- Node.js (v14.0 or later)
- npm or yarn package manager

### Installation

1. Clone the repository
2. Install dependencies:

```sh
npm install
```

3. Create a .env file in the project root with your API key:

```
VITE_API_KEY="your_openweathermap_api_key"
```

4. Run the development server:

```sh
npm run dev
```

### Building for Production

```sh
npm run build
```

## Project Structure

- WeatherApp.jsx - Main weather component
- WeatherApp.css - Styling for the weather component
- App.jsx - Root application component
- `src/assets/images/` - Weather condition images

## How It Works

The app fetches weather data from the OpenWeatherMap API and displays it in a user-friendly interface. The background and weather icon change dynamically based on current weather conditions. Users can search for different cities to view their weather information.

## License

MIT
