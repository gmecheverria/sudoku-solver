# Sudoku-Solver
This project is a Sudoku solver application built using JavaScript and NodeJS, utilizing an external API to solve Sudoku puzzles programmatically.

<b>Overview</b>
The application retrieves solutions for Sudoku puzzles using the Solve Sudoku API by Sean Osier. This project is based on a tutorial by Ania Kubow, with personalized styling and enhancements.

Features
Solve Sudoku puzzles of varying difficulty levels.
Fetch Sudoku solutions using a reliable external API.
Custom styling and UI improvements.
Getting Started
Prerequisites
Before you begin, ensure you have the following installed:

Node.js
npm (usually comes with Node.js)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/sudoku-solver.git
Navigate to the project directory:
bash
Copy code
cd sudoku-solver
Install the dependencies:
bash
Copy code
npm install
Usage
Run the application:
bash
Copy code
npm start
Enter a Sudoku puzzle in the UI or fetch a random one.
Click "Solve" to retrieve the solution using the Solve Sudoku API.
API Reference
Solve Sudoku by Sean Osier: This API is used to fetch solutions for given Sudoku puzzles. Learn more about it here.
Project Structure
java
Copy code
sudoku-solver/
├── public/
│   ├── index.html
│   └── style.css
├── src/
│   ├── app.js
│   ├── api.js
│   └── solver.js
├── .gitignore
├── package.json
└── README.md
Credits
Project inspiration and tutorial by Ania Kubow.
API provided by Sean Osier.
