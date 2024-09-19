
# YAPP Instant Messaging App

Welcome to our Instant Messaging App! This README will guide you through the setup process to get the application running on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (version 14.x or later recommended)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

## Setup Instructions

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/instant-messaging-app.git
cd instant-messaging-app
```

### 2. Server Setup

Navigate to the server folder and install the dependencies:

```bash
cd server
npm install
```

### 3. Client Setup

The client-side of this application uses Vite for a faster and leaner development experience. Navigate to the client folder and install the dependencies:

```bash
cd ../client
npm install
```

### 4. Environment Variables

Both the server and client may require environment variables. Create `.env` files in both the `server` and `client` directories based on the provided `.env.example` files.

### 5. Running the Application

To run the application, you'll need to start both the server and the client.

Start the server:

```bash
cd ../server
npm run dev
```

In a new terminal, start the client:

```bash
cd ../client
npm run dev
```

The client should now be running on `http://localhost:5173` (or another port if 5173 is in use).

## Additional Information

- The server runs on `http://localhost:3000` by default. You can change this in the server's configuration if needed.
- Make sure both the server and client are running simultaneously for the full functionality of the app.
- Check the console output for any error messages or additional instructions.

## Troubleshooting

If you encounter any issues during setup:
1. Ensure all dependencies are correctly installed.
2. Check that you're using a compatible version of Node.js.
3. Verify that all required environment variables are set correctly.
4. If problems persist, please open an issue in this repository with details of the error and your setup.

Happy messaging!

Made by: Ryan, Franklin, Darlene, Andrew 



