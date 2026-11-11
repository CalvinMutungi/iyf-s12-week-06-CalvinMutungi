
# Week 06: Weather Dashboard

## Author
- **Name:** Calvin Mutungi Wambui
- **GitHub:** [@CalvinMutungi](https://github.com/CalvinMutungi)
- **Date:** November 11, 2026

## Project Description
A responsive Weather Dashboard application built to master asynchronous JavaScript, Fetch API interactions, error management, and persistent local storage through the OpenWeatherMap API.

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+, Async/Await, Fetch API)
- OpenWeatherMap API
- GitHub Actions
- Browser Local Storage API

## Features
- **Real-time Weather Data:** Search global cities to fetch live temperature, weather descriptions, wind speed, pressure, and humidity.
- **Robust Error Handling:** Displays clear status notifications for invalid cities, network disruptions, and API key activation delays.
- **Recent Search History:** Automatically stores up to five unique recent city searches using `localStorage` for quick access.
- **Secure Configuration Management:** Uses a decoupled `config.js` framework integrated with GitHub Actions secrets to protect API credentials.
- **Responsive Design:** Provides an adaptable interface for different screen sizes and devices.

## How to Run
1. Clone this repository:

   ```bash
   git clone https://github.com/CalvinMutungi/iyf-s12-week-06-CalvinMutungi.git
   ```

2. Navigate into the project directory:

   ```bash
   cd iyf-s12-week-06-CalvinMutungi
   ```

3. Open the project using GitHub Codespaces or a local development environment.
4. Configure your OpenWeatherMap API key.
5. Launch `index.html` in your browser.

## Lessons Learned
- Mastered avoiding blocking operations and writing clean, sequential logic using `async/await`.
- Gained hands-on experience handling REST API responses using the native Fetch API.
- Learned to manage HTTP status codes and implement error handling using `try/catch`.
- Understood how to maintain credential security through GitHub Actions secret injection.
- Improved understanding of asynchronous JavaScript and client-side data persistence.

## Challenges Faced
- Handled newly generated, unactivated API keys returning HTTP 401 errors by implementing explicit error handlers to prevent application crashes.
- Managed local storage array constraints to limit recent searches to five unique cities without unnecessarily cluttering client-side state.
- Ensured the application remained responsive and provided useful feedback during API failures.

## Live Demo
[View Live Demo](https://calvinmutungi.github.io/iyf-s12-week-06-CalvinMutungi/)
