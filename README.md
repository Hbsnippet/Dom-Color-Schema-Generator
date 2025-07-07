🎨 Color Scheme Switcher
A simple and interactive web project that allows users to change the background color of a webpage by clicking on color buttons.

📸 Preview
Users click colored circles to change the page background instantly.

🚀 Features
Minimal and clean UI

Smooth background color transition

Easy to customize (add more colors)

Built with HTML, CSS, and JavaScript (no frameworks)

🛠️ Technologies Used
HTML5 – Structure of the page

CSS3 – Styling the color buttons and layout

Vanilla JavaScript – Handling user interactions and background changes

📂 Project Structure
css
Copy
Edit
color-scheme-switcher/
├── index.html        # Main HTML file
├── style.css         # Styling for layout and buttons
└── color.js          # JavaScript to handle color switching
📋 How to Use
Clone or download this repository.

Open index.html in your browser.

Click on any color button (Grey, White, Blue, or Yellow) to change the page background.

📌 How It Works
Each color button has an id that matches a color name. When clicked, JavaScript grabs the button's ID and sets it as the background color of the body:

js
Copy
Edit
body.style.backgroundColor = event.target.id;
🎯 Future Improvements (optional ideas)
Add more color options

Add a “reset to default” button

Save last selected color using localStorage

Add dark/light theme toggle

👨‍💻 Author
Built with ❤️ by Hamdan Bashar
