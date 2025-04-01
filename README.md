Weather App

A simple weather application built using React that fetches real-time weather data from a Weather API.

Features
- Fetches real-time weather data.
- Displays temperature, humidity, wind speed, and weather conditions.
- Search functionality for different locations.
- Responsive design.

Technologies Used
- React.js
- Axios (for API calls)
- OpenWeatherMap API (or any other weather API of your choice)
- Tailwind CSS / Bootstrap (for styling)

Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Get your API key from OpenWeatherMap (https://openweathermap.org/) and create a `.env` file in the root directory:
   ```
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```bash
   npm start
   ```

## Usage
- Enter the city name in the search bar and press enter.
- View the current weather details for the searched city.

## Deployment
To deploy the application:
```bash
npm run dev
```

