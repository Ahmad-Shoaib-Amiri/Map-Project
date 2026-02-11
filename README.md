🗺️ Mapty – Workout Tracker (JavaScript OOP Project)
A modern JavaScript workout tracking application built using Object-Oriented Programming (OOP) principles.
This project was developed as part of my JavaScript learning journey to strengthen my understanding of ES6+, classes, inheritance, private fields, and browser APIs.

📸 Preview

(You can add screenshots here later)

![App Screenshot](./screenshots/mapty-preview.png)

🚀 Live Features

📍 Get user location via Geolocation API

🗺️ Interactive map powered by Leaflet.js

🏃 Add Running workouts

🚴 Add Cycling workouts

⚡ Automatic pace calculation (running)

🚴‍♂️ Automatic speed calculation (cycling)

📌 Display workouts as map markers

📋 Render workouts in a sidebar list

🎯 Click workout to focus map on its location

💾 Persistent data using Local Storage

🔄 Data remains after page reload

🏗️ Built With

HTML5

CSS3

JavaScript (ES6+)

Leaflet.js

OpenStreetMap

Geolocation API

Local Storage API

🧠 Key JavaScript Concepts Practiced

ES6 Classes

Inheritance

Encapsulation

Private Class Fields (#)

Event Delegation

DOM Manipulation

Working with External Libraries

Application Architecture

State Management

Data Persistence

📂 Project Architecture
Classes

Workout → Parent class

Running → Extends Workout

Cycling → Extends Workout

App → Main controller class

The app follows a clean OOP architecture where:

Business logic is separated into classes

App state is stored inside private fields

Rendering and logic are properly organized

⚙️ How It Works

Application requests user's location.

Map loads centered on user coordinates.

User clicks anywhere on the map.

A form appears to enter workout details.

Workout is:

Saved in memory

Rendered on the map

Rendered in the workout list

Stored in Local Storage

🛠️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/mapty-workout-tracker.git


Navigate to the project folder:

cd mapty-workout-tracker


Open index.html in your browser.

⚠️ Note: Geolocation works best when running through a local server.

You can use:

npx live-server


or VS Code Live Server extension.

🔮 Future Improvements

Planned features for upcoming versions:

✏️ Edit existing workouts

🗑️ Delete individual workouts

🧹 Delete all workouts

❗ More realistic and detailed error messages

📊 Add workout statistics (totals, averages)

🌙 Dark mode

📱 Responsive improvements

🗂️ Filter workouts by type

📚 Learning Purpose

This project was built as a hands-on practice project while learning modern JavaScript.

It significantly improved my understanding of:

Clean OOP design

Handling asynchronous APIs

Managing application state

Structuring scalable front-end applications

👨‍💻 Author

Ahmad Shoaib Amiri
Computer Engineering & Informatics Graduate
JavaScript & AI Enthusiast

📧 ahmadshoaibamiri5@gmail.com

📄 License

This project is for educational purposes.
