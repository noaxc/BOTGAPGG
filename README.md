BOTGAP.GG - AI Powered LoL Statistics
=====================================

BOTGAP.GG is a League of Legends statistics web app that uses the Riot Games API to fetch and display personalized player statistics, recent matches, champion masteries, and other useful data. The app leverages a dynamic and engaging UI with flickering neon effects and subtle animations to deliver a visually appealing experience.

Table of Contents
-----------------

-   [Features](#features)
-   [Demo](#demo)
-   [Prerequisites](#prerequisites)
-   [Installation](#installation)
-   [Environment Variables](#environment-variables)
-   [Usage](#usage)
-   [Folder Structure](#folder-structure)
-   [Contributing](#contributing)
-   [License](#license)

* * * * *

Features
--------

-   Fetches and displays League of Legends player statistics, including recent match history and champion masteries.
-   Unique neon-styled UI with flickering effects and subtle animations.
-   Customizable background champion splashes to create an immersive experience.
-   Responsive layout optimized for desktop and mobile.

Demo
----

*A screenshot or link to a live demo can be placed here if applicable.*

* * * * *

Prerequisites
-------------

To run this project, you will need to have the following installed:

-   [Node.js](https://nodejs.org/) (version 14 or higher)
-   [Python](https://www.python.org/) (version 3.7 or higher)
-   Riot Games API Key (obtainable from the [Riot Developer Portal](https://developer.riotgames.com/))
-   [Git](https://git-scm.com/) (optional, for cloning the repository)

* * * * *

Installation
------------

Follow these steps to set up the project on your local machine:

1.  **Clone the Repository**

    bash

    Copy code

    `git clone https://github.com/username/repository-name.git
    cd repository-name`

2.  **Install Frontend Dependencies**\
    Navigate to the frontend folder (assumed to be `league-ai-frontend`).

    bash

    Copy code

    `cd league-ai-frontend
    npm install`

3.  **Install Backend Dependencies**\
    Navigate to the backend folder and set up the Python environment.

    bash

    Copy code

    `cd ../backend
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install -r requirements.txt`

* * * * *

Environment Variables
---------------------

Make sure you have a `.env` file in the `backend` folder with your Riot Games API Key.

### Backend `.env` Example

plaintext

Copy code

`RIOT_API_KEY=YOUR_RIOT_API_KEY_HERE`

You may also need additional environment variables, depending on your specific configuration. Be sure to keep these keys private and **never share them publicly**.

* * * * *

Usage
-----

### Running the Backend Server

Ensure you're in the backend directory and activate the virtual environment if necessary. Start the Flask server:

bash

Copy code

`flask run`

### Running the Frontend

Open a new terminal and navigate to the frontend directory. Start the React development server:

bash

Copy code

`npm start`

### Accessing the App

Once both servers are running, open your browser and navigate to:

arduino

Copy code

`http://localhost:3000`

* * * * *

Folder Structure
----------------

The project is organized as follows:

bash

Copy code

`repository-name
├── league-ai-frontend  # Frontend folder
│   ├── src
│   │   ├── components  # React components for various UI elements
│   │   ├── assets      # Background images and splash arts
│   │   └── App.js      # Main application file
│   ├── public
│   └── .env            # Add frontend-specific environment variables if needed
├── backend             # Backend folder
│   ├── app.py          # Main backend server file using Flask and Cassiopeia
│   └── .env            # Contains the Riot API key
└── README.md           # Project README file`

* * * * *

Contributing
------------

Contributions are welcome! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Commit your changes (`git commit -m 'Add new feature'`).
4.  Push to the branch (`git push origin feature/your-feature-name`).
5.  Open a Pull Request.

* * * * *

License
-------

This project is licensed under the MIT License. See the LICENSE file for details.

* * * * *

Feel free to reach out if you encounter any issues or have questions about setting up the project. Enjoy using BOTGAP.GG!