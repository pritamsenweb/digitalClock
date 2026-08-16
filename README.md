# ⏰ Digital Clock

A simple digital clock built with HTML, CSS, and JavaScript. It displays the current local time and updates every second in real time.

## ✨ Features

- Real-time clock updates every second
- Clean and modern UI
- Fully responsive layout
- Built with vanilla JavaScript
- No external libraries required

## 🛠️ Built With

- HTML5 for structure
- CSS3 for styling
- JavaScript for time updates and DOM manipulation

## 📁 Project Structure

```bash
DigitalClock/
├── index.html
├── script.js
└── README.md
```

## ▶️ How to Run

1. Open the project folder.
2. Open `index.html` in your browser.
3. The clock will display the current time automatically.

## 🧠 How It Works

The JavaScript code gets the current time using the `Date` object and updates the clock display every second with `setInterval()`.

```javascript
setInterval(() => {
    let date = new Date().toLocaleTimeString();
    clock.innerHTML = `${date}`;
}, 1000);
```

## 📌 Notes

This project is a beginner-friendly JavaScript exercise focused on:

- DOM manipulation
- Date and time handling
- Real-time UI updates
- Basic frontend styling
