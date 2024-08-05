

## Note
Due to some deployment issues, this new repository was created. For accessing the previous repository, follow this URL: "https://github.com/alwaysAnsh/Trello-copy"

This project is built using Vite for the client-side and Node.js for the server-side. The project structure is as follows:

root
├── client
│ ├── node_modules
│ ├── package.json
│ ├── src
│ │ └── pages
│ │ └── Dashboard.jsx
│ │ └── other files    
└── server
├── package.json
├── index.js
├── other files

Follow these instructions to set up and run the project locally.

### Prerequisites

Make sure you have the following installed on your local machine:
- Node.js (v14 or later)
- npm (v6 or later)

### Installation

1. Clone the repository:

   git clone <repository-url>
 
# Navigate to client directory and install dependencies
cd client
npm install

# Navigate to server directory and install dependencies
cd ../server
npm install

Environment Variables
Create a .env file in the server directory with the following content:

MONGODB_URL=your_mongodb_connection_string
PORT=your_port_number
JWT_SECRET=your_jwt_secret_key

# Running the Application
1. Start the server:
   cd server
   npm start
   
3. cd ../client
    npm run dev

The client application should now be running on http://localhost:5173 and the server on the port you specified in the .env file.

# Contributing
Feel free to fork this repository and make contributions. Pull requests are always welcome.



