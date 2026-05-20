# 🌤️ Weather Dashboard

A beautiful, responsive weather dashboard that fetches real-time weather data from the **OpenWeatherMap API**.

## Features

✨ **Current Weather Information**
- Temperature, humidity, wind speed, pressure
- Visibility, sunrise/sunset times, UV index
- Wind direction indicator
- Beautiful weather icons

📅 **5-Day Weather Forecast**
- Daily forecast cards with temperature and conditions
- Visual weather icons for each day

📍 **GPS Location Support**
- Get weather for your current location
- Automatic geolocation detection

🔍 **City Search**
- Search for weather in any city worldwide
- Instant results with proper error handling

💾 **Saved Locations**
- Save your favorite locations
- Quick access to frequently checked cities
- Local storage persistence

🎨 **Beautiful UI**
- Modern dark theme with gradient backgrounds
- Smooth animations and transitions
- Fully responsive design (mobile, tablet, desktop)
- Intuitive navigation

## Getting Started

### 1. Get OpenWeatherMap API Key

1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Generate an API key from your account dashboard
4. Copy your API key

### 2. Set Up the Dashboard

1. Open `weather-script.js`
2. Find this line:
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';
   ```
3. Replace `'YOUR_API_KEY_HERE'` with your actual API key:
   ```javascript
   const API_KEY = 'abc123xyz789...';
   ```

### 3. Open the App

Simply open `weather-dashboard.html` in your web browser!

## File Structure

```
weather-dashboard/
├── weather-dashboard.html    # Main HTML file
├── weather-style.css         # Styling and responsive design
├── weather-script.js         # JavaScript with API integration
└── README.md                 # This file
```

## How to Use

### Search for Weather
1. Enter a city name in the search box
2. Click "Search" or press Enter
3. View current weather and 5-day forecast

### Use Your Location
1. Click "📍 Use My Location" button
2. Allow browser to access your location
3. Weather for your area will load automatically

### Save Locations
1. Click "+ Add Location"
2. Enter location name
3. Click "Save Location"
4. Access saved locations anytime by clicking on them

### View Details
- Hover over detail cards to see more information
- Check sunrise/sunset times
- Monitor wind direction and speed
- Track humidity and pressure changes

## API Information

### OpenWeatherMap Free Tier Includes
- Current weather data
- 5-day forecast
- Geolocation support
- Up to 1,000 calls/day

### Data Points Available
- Temperature (current, feels like, min/max)
- Weather conditions and descriptions
- Wind speed and direction
- Humidity percentage
- Atmospheric pressure
- Visibility distance
- Sunrise and sunset times
- Weather icons

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **Vanilla JavaScript** - No dependencies
- **OpenWeatherMap API** - Weather data source
- **Geolocation API** - Location detection
- **LocalStorage** - Persistent data

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Troubleshooting

### "City not found" Error
- Check the spelling of the city name
- Try using the full city name with country code (e.g., "London, UK")

### "Unable to get your location" Error
- Enable location services in your browser settings
- Check if your OS has location permission enabled
- Try using Safari or Chrome (best geolocation support)

### "Please set your OpenWeatherMap API key" Error
- You haven't set your API key yet
- Follow the "Getting Started" section above
- API key must be valid and active

### No forecast data showing
- Wait a few seconds for the data to load
- Check your internet connection
- Verify your API key is valid

## Notes

- The app uses metric units (°C, m/s, km)
- Data updates on each search/location load
- Saved locations are stored in your browser's local storage
- Free API tier has a rate limit of 1,000 calls/day

## Future Enhancements

Potential features to add:
- [ ] Hourly forecast
- [ ] Weather alerts
- [ ] Temperature unit conversion (°C/°F)
- [ ] Air quality index
- [ ] Weather history charts
- [ ] Multiple language support
- [ ] Dark/Light theme toggle

## License

Free to use and modify. Enjoy! 🌦️

---

**Questions or Issues?** Feel free to open an issue on GitHub or check the OpenWeatherMap documentation.
