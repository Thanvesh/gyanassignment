# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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


# Internship Assignment Project

This project is a part of an internship assignment, aiming to create a web application for discovering and exploring events. The application displays both recommended events and upcoming events, providing users with an intuitive interface to find exciting activities happening near them.

## Live Demo

[Live Demo](https://gyanassignment-f0i0r3qd9-thanveshs-projects.vercel.app/)

## Features

- **Recommended Events:** Displays recommended events with horizontal scrolling for easy browsing.
- **Upcoming Events:** Fetches and displays upcoming events with lazy loading, enhancing performance and user experience.
- **Responsive Design:** Optimized for both desktop and mobile browsers, ensuring seamless accessibility across devices.
- **API Integration:** Utilizes a REST API to fetch event data, providing real-time information to users.
- **Dynamic Content:** Renders dynamic event content, including event names, locations, dates, and thumbnail images.

## Technologies Used

- **Frontend Framework:** React.js
- **HTTP Client:** Axios
- **Lazy Loading:** Intersection Observer API
- **Styling:** CSS

## Setup and Local Development

**Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git

**Navigate to the project directory:**
bash
Copy code
cd your-repository

**Install dependencies:**
bash
Copy code
npm install

**Run the project:**
bash
Copy code
npm start

**Project Structure**
css
Copy code
├── public
│   └── index.html
├── src
│   ├── components
│   │   ├── Header.js
│   │   ├── Loader.js
│   │   ├── RecommendedEvents.js
│   │   ├── UpcomingEvents.js
│   │   └── Location.js
│   ├── images
│   │   ├── Banner.svg
│   │   ├── image1.svg
│   │   ├── image2.svg
│   │   ├── image3.svg
│   │   ├── image4.svg
│   │   ├── image5.svg
│   │   ├── image6.svg
│   │   └── image7.svg
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
**Design Decisions**
**Lazy Loading:** Implemented lazy loading using the Intersection Observer API to enhance performance by loading upcoming events incrementally.
**Component-based Architecture:** Leveraged React.js for its component-based architecture, facilitating modularity and reusability of code.
**Responsive Design:**Ensured responsiveness across various devices and screen sizes for an optimal user experience.

**API Integration**
Integrated with the provided REST API to fetch event data dynamically, enabling real-time updates and information retrieval.
Utilized Axios for making HTTP requests, ensuring seamless communication with the backend server.
Future Enhancements
**Authentication:** 
Implement user authentication to personalize event recommendations based on user preferences.
Filtering and Sorting: Add filtering and sorting options to allow users to refine event searches based on criteria such as location, date, and category.
Performance Optimization: Further optimize performance through code refactoring and caching mechanisms to reduce load times and enhance scalability.

**Credits**
Event data provided by [gyangrove].
Banner image sourced from [https://drive.google.com/file/d/1hFKPSETzU0K0U9pgcpcvoVk0XCEJxQ8k/view].
**License**
This project is licensed under the MIT License.

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
