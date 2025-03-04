# Movie Streaming Web App

The Movie streaming web app is a clone of the Netflix app. The app fetches movie data from the TMDb API and displays it in various sections such as trending, popular, top-rated, and upcoming movies. It also provides detailed information about individual movies, including trailers and similar movies. The web app includes a "Favorite" feature that allows users to mark movies as their favorites. The movies can be marked as favorite in the Movie Deatils page.

The web app is a movie streaming platform built with the following technologies and tools:

1. React: The app is built using React, a popular JavaScript library for building user interfaces. The main entry point is main.tsx, which renders the App component.

2. React Router: The app uses React Router for client-side routing. The routes are defined in the App component, with paths for the home page and movie details page.

3. TypeScript: The app is written in TypeScript, providing static type checking and improved developer experience.

4. Vite: The app uses Vite as the build tool and development server. The configuration is defined in vite.config.ts.

5. Tailwind CSS: The app uses Tailwind CSS for styling. The configuration is defined in tailwind.config.js, and the styles are imported in index.css.

6. Axios: The app uses Axios for making HTTP requests to The Movie Database (TMDb) API. The API functions are defined in api.ts.

7. Lucide Icons: The app uses Lucide Icons for various UI icons, such as search, heart, menu, and play icons.

8. React Player: The app uses React Player to embed and play YouTube videos for movie trailers.
