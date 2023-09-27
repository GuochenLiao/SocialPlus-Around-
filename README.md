# SocialPlus: A Cloud and React-Based Social Network

Welcome to SocialPlus! This project is a short-video social network application designed to allow users to create, browse, and search for posts. It's built using React JS for the frontend and Go for the backend, and it leverages various cloud services and technologies to provide a seamless and scalable user experience.

## 🌟 Features

- **User Authentication**: Secure registration, login, and logout using JWT tokens.
- **Post Creation**: Users can create posts with short videos and text messages.
- **Media Browsing**: Browse through a feed of posts from various users.
- **Keyword Searching**: Find posts easily with keyword-based search functionality.
- **Responsive Design**: A user-friendly interface that works on both desktop and mobile browsers.

## 🛠️ Technologies Used

### Frontend

- **React JS**: For building the user interface.
- **React Router v4**: For managing frontend routing.

### Backend

- **Go**: Handles business logic including post creation, search, and user authentication.
- **Elasticsearch**: Used for storing and searching posts and user data.
- **Google Cloud Storage**: Used for storing media files like images and videos.

### Middleware

- **JWT (JSON Web Tokens)**: Used for user authentication.
- **Google App Engine**: For deploying the backend services.

## 🏗️ Architecture

SocialPlus follows a microservices architecture, with distinct services handling different functionalities. The application is structured using the MVC (Model-View-Controller) design pattern, separating the concerns of data (Model), user interface (View), and logic (Controller).

### Data Management

- **User Schema**: Contains Username, Password, Age, and Gender.
- **Post Schema**: Contains Id, User (creator), Message (content), Url (media URL), and Type (media type).

### Deployment

The application is deployed to the cloud, utilizing Google App Engine for the backend and a suitable static site hosting service for the frontend. The deployment process involves building the application, configuring the cloud resources, and monitoring the application's performance and errors.

## 🌱 Future Enhancements

- Advanced search functionalities.
- User profiles and customization.
- Real-time notifications.
- Integration of comments and likes.
- Implementation of caching mechanisms for improved performance.

## 📝 Conclusion

SocialPlus is a scalable and maintainable social network application that combines modern technologies to deliver a rich user experience. It is a demonstration of the integration of various technologies and services to build a full-fledged application.

Feel free to explore the codebase, and contributions are always welcome!

