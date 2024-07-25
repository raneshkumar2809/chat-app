# Syncronus

Syncronus is a real-time chat application built using React for the frontend, Node.js for the backend, and MongoDB for the database. It allows users to create accounts, join chat rooms, and send messages in real-time.

## Features

- User authentication (Sign up, Log in, Log out)
- Real-time messaging
- Join existing chat rooms or create new ones
- Responsive design for mobile and desktop

## Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.io


## Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/chatapp.git
    cd chatapp
    ```

2. **Backend Setup**

    Navigate to the `server` directory and install the dependencies:

    ```bash
    cd server
    npm install
    ```

    Start the server:

    ```bash
    nodemon index.js
    ```

3. **Frontend Setup**

    Navigate to the `client` directory and install the dependencies:

    ```bash
    cd ../client
    npm install
    ```

    Start the React development server:

    ```bash
    npm run dev
    ```

    The application should now be running on [http://localhost:5173](http://localhost:5173).

## Usage

1. Open your browser and go to [http://localhost:5173](http://localhost:5173).
2. Sign up for a new account or log in if you already have one.
3. Join an existing chat room or create a new one.
4. Start chatting in real-time!

Note: MondoDB should be installed on your device. Check this to setup MongoDB on your device [https://www.mongodb.com/docs/manual/installation/](https://www.mongodb.com/docs/manual/installation/)
