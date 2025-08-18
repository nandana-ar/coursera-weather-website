# European Weekly Weather Forecast Website Coursera

A simple, responsive web application that provides a 7-day weather forecast for major European cities using the [7Timer! Weather API](http://www.7timer.info/).
The app displays only the available weather data for the selected city, making it clean and easy to read.

---

## Features

- Select a European city from a dropdown menu.
- Display a 7-day weather forecast including:
  - **Temperature** (`temp2m`)
  - **Humidity** (`rh2m`)
  - **Wind speed and direction** (`wind10m`)
  - **Precipitation type and amount** (`prec_type`, `prec_amount`)
  - **Weather conditions** (`weather`) with icons
<!-- Responsive design for desktops, tablets, and mobile devices. -->
- Loading spinner while fetching data.
- Error message handling if the API call fails.

---

## Technologies Used

- **HTML5** - Structure of the website.
- **CSS3** - Styling, responsive layout, and design.
- **JavaScript (ES6)** - Fetching and displaying weather data dynamically.
- **7Timer! Weather API** - Source of weather data.

---

## Project Structure
    index.html         # Main HTML file
    master.css         # Stylesheet for the website
    script.js          # JavaScript logic
    images/
        clear.png
        cloudy.png
        .....
    README.md

