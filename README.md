# Timer Webpage
## Overview
PitchTimer is a simple countdown timer webpage designed to help users manage their time efficiently. The webpage includes a JavaScript timer (Pitch3.js), a backend server (app.js), and associated HTML and CSS files.

## Features
- Countdown Timer: The main functionality is a countdown timer with flexible start and end times. Users can start, pause, and reset the timer.
- Alerts: An audible alert is triggered when the timer reaches zero.
- Responsive Design: The webpage is responsive, adapting to different screen sizes for a better user experience.
- Log: Requests to the server are logged in access.log.

## How to Use
1. Installation: Clone the repository to your local machine.
```bash
git clone [repository_url]
cd [repository_directory]
```
2. Run the Server: Start the server using Node.js.
```bash
npm install
node app.js
```
3. Access the Webpage: Open your web browser and go to http://localhost:3035.
4. Set Timer Values: Click on the timer text to initialize the timer with default values.
5. Start the Timer: Click on the timer text again to start the countdown.

## Files
- Pitch3.js: JavaScript file containing the timer logic and functions for time calculations.
- app.js: Node.js server file with logging functionality.
- index.html: HTML file defining the structure of the webpage.
- timer.css: CSS file for styling the webpage.

## Dependencies
- Node.js
- Express
- jQuery (included via CDN)

## Author
Ismael Rekik
