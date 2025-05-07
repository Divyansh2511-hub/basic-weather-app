# Weather App

A modern, responsive React + Vite application that provides real-time weather data with a beautiful UI. Built with modern design principles and smooth animations.

## Features

- **Real-time Weather Data**
  - Current temperature and weather conditions
  - 5-day weather forecast
  - Air Quality Index (AQI)
  - UV Index
  - Humidity, wind speed, and "feels like" temperature

- **Smart Search**
  - City search with live autocomplete suggestions
  - Support for international cities
  - Error handling for invalid cities

- **Modern UI/UX**
  - Beautiful gradient text effects
  - Smooth animations and transitions
  - Interactive hover effects
  - Responsive design for all screen sizes
  - Modern typography with Outfit and Plus Jakarta Sans fonts
  - Enhanced shadows and depth effects

- **Theme Support**
  - Light and Dark theme toggle
  - Automatic theme persistence
  - Custom color schemes for each theme
  - Smooth theme transitions

## Demo

![Weather App Demo](./public/demo.gif)

## Getting Started

### Prerequisites

- Node.js v14 or higher
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Configuration

1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and obtain an API key.

2. Create a `.env` file in the project root:
   ```env
   VITE_OPENWEATHER_API_KEY=your_api_key_here
   ```

3. Update `src/App.jsx` to use the environment variable:
   ```js
   const API_KEY = import.meta.env.VITE_OPENWEATHER_API_KEY
   ```

### Running the App

Start the development server:
```bash
npm run dev
```

Open your browser at http://localhost:5173 to view the app.

### Building for Production

```bash
npm run build
```

The production-ready files will be in the `dist/` folder.

## Project Structure

```
├── public/         # Static assets & demo GIF
├── src/           
│   ├── App.jsx     # Main application logic
│   ├── App.css     # Styles and theming
│   ├── main.jsx    # Application entry point
│   └── index.css   # Global styles
├── .env           # Environment variables
├── index.html     # HTML template
├── package.json   # Dependencies & scripts
└── vite.config.js # Vite configuration
```

## Technologies Used

- React 19
- Vite 6
- Axios for API calls
- OpenWeatherMap API
- Modern CSS features (CSS Variables, Flexbox, Grid)
- Google Fonts (Outfit, Plus Jakarta Sans)

## Features in Detail

### Weather Information
- Real-time temperature display
- Weather condition icons
- Detailed weather statistics
- 5-day forecast with min/max temperatures
- Air quality and UV index information

### Search Functionality
- Intelligent city search
- Autocomplete suggestions
- Error handling for invalid inputs
- Support for international cities

### UI Components
- Responsive container layout
- Animated weather icons
- Interactive temperature display
- Weather statistics cards
- Forecast day cards
- Theme toggle button

### Styling
- CSS variables for theming
- Gradient text effects
- Enhanced shadows and depth
- Smooth transitions and animations
- Responsive design breakpoints
- Modern typography

## License

This project is released under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
