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



# 🎬 MERN Video Library

A full-stack video library web application built using the MERN (MongoDB, Express, React, Node.js) stack. This platform allows **Admins** to manage videos and users to **view**, **like**, **dislike**, **comment**, **search**, and **filter** videos. Admins have full CRUD capabilities, while users can interact with embedded YouTube videos.

---

## 🚀 Features

### 🔐 Authentication
- User & Admin roles with JWT-based authentication
- Authentication forms powered by **Formik**
- Cookie management for secure login sessions

### 👤 Admin
- Perform **Create, Read, Update, Delete (CRUD)** operations on videos
- Upload videos using YouTube embed links
- View all user interactions (likes, dislikes, comments)

### 👥 Users
- View a list of uploaded videos
- **Like**, **Dislike**, and **Comment** on videos
- Watch embedded YouTube videos
- **Search** videos by title
- **Filter** videos by category

### 🧰 Tech Stack

| Area                | Technology              |
|---------------------|--------------------------|
| Frontend            | React.js                 |
| Backend             | Node.js, Express.js      |
| Database            | MongoDB                  |
| Form Handling       | Formik                   |
| Routing             | React Router DOM         |
| Authentication      | JWT, Cookies             |
| State & Effects     | React Hooks              |

---

## 📂 Project Structure

🔒 Authentication & Roles
Admin Login: Full access (CRUD, user management)

User Login: Limited access (Read-only with interaction)

🔍 Search & Filter
Search bar available to quickly find videos by title.

Filter dropdown to view videos by specific categories.

📝 Commenting System
Users can:

Add comments

View others' comments

React to videos via likes/dislikes

📦 API Endpoints (Sample)
Auth
POST /api/auth/register

POST /api/auth/login

Videos
GET /api/videos - All videos

GET /api/videos/:id - Single video

POST /api/videos (Admin only)

PUT /api/videos/:id (Admin only)

DELETE /api/videos/:id (Admin only)

Interactions
POST /api/videos/:id/like

POST /api/videos/:id/dislike

POST /api/videos/:id/comment
