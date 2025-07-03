🧠 Friends App — Social Connect Practice Project

📌 Overview
This project is a sample social app built to explore friendship logic, user interactions, and front-end dynamics using JavaScript and Rails. It was designed as a hands-on playground to understand how users connect, interact, and manage relationships in a web environment.

🛠️ Tech Stack
Backend: Ruby on Rails

Frontend: HTML, CSS, JavaScript

Database: SQLite / PostgreSQL

Tools: Rails Admin, Devise, AJAX, Bootstrap

🚀 Features
User registration and login (via Devise)

Add/remove friends functionality

Dynamic UI updates using AJAX

Role-based access and basic moderation logic

Responsive design with Bootstrap

📁 Structure Highlights
app/models/friendship.rb: Manages friend relationships

app/controllers/friends_controller.rb: Handles friend actions

app/views/friends/index.html.erb: Displays friend list and actions

app/assets/javascripts/friends.js: AJAX logic for dynamic updates

🧪 How to Run Locally
bash
git clone https://github.com/AdityaChavan2681/Friends-App.git
cd Friends-App
bundle install
rails db:create db:migrate
rails server
Then visit http://localhost:3000 to explore the app.

🧠 Reflection
This project helped me understand user-centric design, relational modeling, and interactive UI flows. It’s a reminder that even simple apps can teach powerful lessons about empathy, structure, and clarity.
