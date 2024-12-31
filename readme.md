# Flixx App

[Flixx App - Live Demo](https://flixx-gynp33857-mohamednaeemms-projects.vercel.app/)

Flixx App is a movie and TV show discovery web application that allows users to explore popular movies and TV shows using The Movie Database (TMDb) API. The app uses HTML, CSS, and JavaScript for the front-end, and it also integrates the Swiper library for a smooth, interactive user experience.

## Features:
- Search for movies and TV shows
- Display popular movies and TV shows with details like title, poster, and description
- Use the Swiper library to create interactive, scrollable carousels for displaying movies and shows
- Responsive design for all screen sizes

## Technologies Used:
- **HTML**: Structure of the web pages
- **CSS**: Styling and layout
- **JavaScript**: Fetching data from the TMDb API and handling app logic
- **Swiper**: A modern touch slider library for creating smooth carousels
- **TMDb API**: Used to fetch movie and show data

## Setup and Installation:

### Clone the repository:
```bash
git clone https://github.com/your-username/flixx-app.git
```

### Navigate to the project directory:
```bash
cd flixx-app
```

### Open the project in a browser:
You can open the `index.html` file directly in a browser, but it's recommended to host the project for the best experience.

## Using the TMDb API:

1. Sign up at [TMDb](https://www.themoviedb.org/) and obtain your API key.
2. Store your API key securely in the server-side code (if using a server) or use environment variables for safety.
3. Replace the hardcoded API key in your code with your personal API key.

Example (API configuration in JavaScript):
```js
const global = {
  api: {
    apiKey: 'your-api-key-here', // Replace with your own TMDb API key
    apiUrl: 'https://api.themoviedb.org/3/',
  },
};
```

### Deploy on Vercel:
1. Push your code to GitHub.
2. Go to [Vercel](https://vercel.com) and create a new project, linking it to your GitHub repository.
3. Vercel will automatically deploy your app, and you will receive a live link to your application.

## How to Use:
1. Open the **Flixx App** in your browser or via the live demo link provided at the top.
2. Use the search bar to find your favorite movies or TV shows.
3. Browse the carousels to explore popular movies and shows.

Feel free to modify the project, add new features, and explore the TMDb API to enhance the app's functionality.

## Acknowledgements:
- [TMDb API](https://www.themoviedb.org/)
- [Swiper Library](https://swiperjs.com/)