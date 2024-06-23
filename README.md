# Mythic-Sphere

Mythic-Sphere is a social networking platform designed for the university community, built using the MERN stack (MongoDB, Express.js, React, Node.js). It aims to provide a platform where students and faculty members can connect, share information, and engage in discussions.

## Features

### Authentication
- **User Authentication**: Secure user registration and login using JWT tokens.
- **Social Login**: Integration with social login providers (e.g., Google, Facebook) for easy access.

### Profiles
- **User Profiles**: Personalized profiles for each user with profile pictures, bio, and contact information.
- **Customization**: Ability for users to customize their profiles.

### Posts and Feeds
- **Post Creation**: Users can create posts to share updates, announcements, or thoughts.
- **Feed**: Personalized feed displaying posts from users and groups they follow.
- **Likes and Comments**: Interactive features allowing users to like and comment on posts.

### Networking
- **Follow System**: Follow other users to stay updated with their activities.
- **Groups**: Creation and management of groups for specific interests or courses.
- **Notifications**: Real-time notifications for new followers, likes, and comments.

### Messaging
- **Direct Messaging**: Private messaging between users for one-on-one conversations.
- **Group Messaging**: Communication within groups for collaborative discussions.

### Search and Discovery
- **Search Functionality**: Search for users, posts, or groups based on keywords.
- **Trending Posts**: Highlight trending posts and topics within the community.

### Admin Features
- **Admin Dashboard**: Dashboard for administrators to manage users, posts, and groups.
- **Content Moderation**: Tools for content moderation, including flagging and reporting features.

### Additional Features
- **Responsive Design**: Mobile-friendly interface for seamless access across devices.
- **Analytics**: Basic analytics to track user engagement and popular content.
- **Security**: Implementation of security best practices to protect user data and prevent unauthorized access.

## Installation

To run Mythic-Sphere locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/ahmedembeddedx/mythic-sphere.git
   ```

2. Navigate into the project directory:
   ```
   cd mythic-sphere
   ```

3. Install dependencies for both the server and client:
   ```
   cd server && npm install
   cd ../client && npm install
   ```

4. Configure environment variables:
   - Create a `.env` file in the `server` directory based on `.env.example` and provide necessary environment variables (e.g., MongoDB URI, JWT secret).

5. Start the development server:
   ```
   cd ../server && npm run dev
   cd ../client && npm start
   ```

6. Access the application in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! To contribute to Mythic-Sphere, fork the repository and create a pull request with your proposed changes. Make sure to follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by the need for a dedicated social networking platform within the university community.
