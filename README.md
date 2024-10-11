# NASA Image Viewer - APOD Web Application

Welcome to the **NASA Image Viewer**, a web application that fetches and displays data from NASA's [Astronomy Picture of the Day (APOD) API](https://api.nasa.gov/). This app provides users with an image or video from NASA's APOD API along with detailed descriptions and information.

## Features

- **Fetch Daily Image**: Automatically fetches the Astronomy Picture of the Day from NASA's API.
- **Detailed Information**: Displays the title, date, explanation, and media (image or video) related to the APOD.
- **Simple and Clean UI**: A minimalistic and responsive design to enhance the user experience.

## Technologies Used

This project is built with the following technologies:

- **React.js** - Frontend JavaScript library for building user interfaces.
- **Axios** - To make HTTP requests to NASA's APOD API.
- **CSS/SCSS** - For styling the application.
- **NASA APOD API** - The data source providing the daily image and details.

## How to Run Locally

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: [Install Node.js](https://nodejs.org/)
- **NPM**: Installed automatically with Node.js
- **NASA API Key**: [Get your API key here](https://api.nasa.gov/)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/heydawood/Nasa-app.git

   cd Nasa-app

   npm install
   ```
   
2. Create a .env file in the root of the project and add your NASA API key:
   ```
   REACT_APP_NASA_API_KEY=your_api_key_here
   ```
   
3. Start the development server:
   ```
   npm start
   ```
The application will run on http://localhost:3000.

## ✨ Contributions

Feel free to submit issues or pull requests if you find bugs or want to enhance this project. Contributions are welcome!

---

### 👨‍💻 Developed by [Dawood Faisal]

https://dawoods-apod-app.netlify.app/

