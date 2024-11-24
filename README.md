# Movie Client

A React-based client application for interacting with a Movie API. This application allows users to view a list of movies, watch trailers, and manage reviews for movies.

## Features

- **Home Page**: Displays a carousel of movies with posters, titles, and buttons to watch trailers or view reviews.
- **Trailers**: Allows users to watch movie trailers using YouTube links.
- **Reviews**: Users can read and submit reviews for movies.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **React**: Frontend framework.
- **React Router**: For navigation.
- **Axios**: For API calls.
- **Bootstrap**: Styling and layout components.
- **Material-UI**: Carousel component.
- **FontAwesome**: For icons.
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## Components Overview
Header
File: components/header/Header.js
Description: Provides the navigation bar, branding, and login/register buttons.

Hero
File: components/hero/Hero.js
Description: Displays a carousel of movies with options to watch trailers or view reviews.

Trailer
File: components/trailer/Trailer.js
Description: Embeds YouTube trailers using ReactPlayer.

Reviews
File: components/reviews/Reviews.js
Description: Allows users to view and add reviews for movies.

Review Form
File: components/reviewForm/ReviewForm.js
Description: A form for submitting new reviews.

NotFound
File: components/notFound/NotFound.js
Description: Displays a fallback for undefined routes.

Layout
File: components/Layout.js
Description: Wraps the routes and ensures consistent layout.

API Integration
The application interacts with a backend Movie API.

Endpoints:
GET /api/v1/movies: Fetches all movies.
GET /api/v1/movies/{movieId}: Fetches details of a single movie.
POST /api/v1/reviews: Submits a new review.

Future Enhancements
Add user authentication for managing reviews.
Enable a "Watchlist" feature.
Improve error handling for API calls.
Add pagination for large movie collections.

Jorge Allan Paz Garza
