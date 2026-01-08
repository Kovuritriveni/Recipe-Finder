🍽️ Recipe Finder Web Application

A modern and interactive Recipe Finder Website built using HTML, CSS, and Vanilla JavaScript.
The application fetches real-time recipe data from a public REST API and displays recipes with images, ingredients, instructions, and cooking videos.

🔥 Features

🔍 Search recipes by name

🎲 Get a random recipe

🖼️ Display recipe images dynamically

📋 View ingredients with measurements

🧾 Step-by-step cooking instructions

🎥 Cooking video links (YouTube)

🪟 Modal popup for detailed recipe view

📱 Responsive and user-friendly UI

⚠️ Proper loading and error handling

🛠️ Tech Stack

HTML5 – Structure of the website

CSS3 – Styling, layout, animations

Vanilla JavaScript – Logic, DOM manipulation, API integration

REST API – TheMealDB API

🌐 API Used

This project uses the TheMealDB Public API to fetch recipe data.

API Endpoints:

Search Recipe

https://www.themealdb.com/api/json/v1/1/search.php?s=recipeName


Random Recipe

https://www.themealdb.com/api/json/v1/1/random.php


Recipe Details

https://www.themealdb.com/api/json/v1/1/lookup.php?i=recipeId

⚙️ How It Works

User enters a recipe name or clicks Get Random Recipe

JavaScript sends a request to the API using fetch()

API returns recipe data in JSON format

JavaScript dynamically creates recipe cards using DOM manipulation

Clicking a recipe opens a modal with full details

📁 Project Structure
Recipe-Finder/
│
├── index.html      # Main HTML structure
├── style.css       # Styling and UI design
├── main.js         # JavaScript logic & API handling
└── README.md       # Project documentation

🧠 JavaScript Concepts Used

DOM Manipulation

Event Handling

Fetch API

Async / Await

Template Literals

Error Handling (try...catch)

Dynamic Content Rendering

🎯 Why This Project?

Demonstrates strong Vanilla JavaScript fundamentals

Shows real-world API integration

Implements dynamic UI updates without frameworks

Ideal for frontend developer / fresher resumes
