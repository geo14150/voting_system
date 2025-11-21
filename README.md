Poll Voting System (Client-Server Architecture)

This repository contains a simple Poll Voting System built with a separate front-end client and a Node.js/Express back-end server. 
The system allows users to vote on predefined options, displays real-time percentage results, and persists the vote counts using a local JSON file.

🚀 Getting Started
To run this application, you need Node.js installed on your machine.

1. Installation
Navigate to the project's root directory and install the server dependencies: npm install

2. Initial Data Setup (Important!)
Since the data.json file is ignored by Git (as it changes frequently with votes), you must create it manually inside the server/ directory before starting the application.

Create a new file named data.json with the initial zero votes:
{
  "JavaScript": 0,
  "TypeScript": 0,
  "React": 0,
  "Both": 0
}

3. Running the Server
Start the Express server from the root directory: npm start

You should see the message Server is running... in your console.

4. Accessing the Client
Open your web browser and navigate to: http://localhost:3000/index.html



