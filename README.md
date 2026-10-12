# Umbrella Checker

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Open-Meteo](https://img.shields.io/badge/Open--Meteo-FF6B6B?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8+PHBhdGggZD0iTTEyIDZ2MTJNNiAxMmgxMiIvPjwvc3ZnPg==&logoColor=white)
![No API Key](https://img.shields.io/badge/No%20API%20Key-00C853?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-FF5722?style=for-the-badge&logo=responsive&logoColor=white)
![License](https://img.shields.io/badge/License-Free%20to%20Use-009688?style=for-the-badge)

A simple, beautiful weather app that tells you whether you should carry an umbrella today based on the chance of rain.

## Features

- **Quick Weather Check**: Enter any city name to instantly see today's rain chance and temperature
- **Smart Umbrella Recommendation**: Automatically suggests carrying an umbrella when rain chance is 40% or higher
- **Temperature Toggle**: Switch between Celsius and Fahrenheit with a single click (no extra API calls)
- **3-Day Forecast**: View the next 3 days' weather with day names, temperatures, and rain chances
- **Dynamic Background**: The page background changes to match the weather - blue-gray when rain is likely, bright sky-blue otherwise
- **Responsive Design**: Works beautifully on both desktop and mobile devices
- **No API Key Required**: Uses the free Open-Meteo API

## How to Use

1. Open `index.html` in your web browser
2. Type a city name (e.g., "London", "Tokyo", "Mumbai")
3. Press Enter or click the "Check" button
4. View the results:
   - Current temperature with °C/°F toggle
   - Rain chance percentage
   - Umbrella recommendation banner with emoji
   - 3-day forecast cards

## Technology

- **HTML5**: Single-file structure with semantic markup
- **CSS3**: Modern styling with CSS variables, flexbox, and grid layouts
- **Vanilla JavaScript**: No frameworks, pure JavaScript for logic and API calls
- **Open-Meteo API**: Free weather data with no authentication required

## API Endpoints

- Geocoding: `https://geocoding-api.open-meteo.com/v1/search`
- Weather Forecast: `https://api.open-meteo.com/v1/forecast`

## Rain Threshold

The app recommends carrying an umbrella when the daily precipitation probability is **40% or higher**. This threshold can be adjusted by modifying the `RAIN_THRESHOLD` constant in the JavaScript code.

## Browser Compatibility

Works in all modern browsers that support:
- ES6+ JavaScript
- CSS Grid and Flexbox
- CSS Custom Properties (variables)
- Fetch API

## File Structure

```
one/
└── index.html    # Complete app (HTML, CSS, and JavaScript in one file)
```

## Customization

You can easily customize the app by modifying:
- **Colors**: Edit the CSS variables in the `:root` selector
- **Rain threshold**: Change the `RAIN_THRESHOLD` constant in JavaScript
- **Styling**: Modify CSS classes for different elements
- **Forecast days**: Adjust the `forecast_days` parameter in the API call

## License

Free to use and modify.
