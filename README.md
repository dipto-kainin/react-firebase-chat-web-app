# React Firebase Chat Web App

This is a simple chat web application built using React and Firebase.

## Features

-   Real-time messaging
-   User authentication with Firebase
-   Responsive design

## Technologies Used

-   React
-   Firebase (Firestore, Authentication)
-   CSS

## Getting Started

### Prerequisites

-   Node.js
-   npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/dipto-kainin/react-firebase-chat-web-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd react-firebase-chat-web-app
    ```
3. Install dependencies:
    ```sh
    npm install
    ```
    or
    ```sh
    yarn install
    ```

### Configuration

1. Create a Firebase project and set up Firestore and Authentication.
2. Create a `.env` file in the root directory and add your Firebase configuration:
    ```env
    REACT_APP_FIREBASE_API_KEY=your-api-key
    REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
    REACT_APP_FIREBASE_PROJECT_ID=your-project-id
    REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
    REACT_APP_FIREBASE_APP_ID=your-app-id
    ```

### Running the App

```sh
npm start
```

or

```sh
yarn start
```

The app will be available at `http://localhost:3000`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

-   [React](https://reactjs.org/)
-   [Firebase](https://firebase.google.com/)
