# Digital Clock

![Digital Clock Preview](https://via.placeholder.com/800x400?text=Digital+Clock+Preview)

A sleek, responsive digital clock web application with customizable themes and additional time features.

## Features

- 🕒 **Real-time Display**: Shows current time with seconds
- 🌗 **Auto Dark Mode**: Detects system preference
- 🎨 **Multiple Themes**: Choose from different color schemes
- 🌍 **Timezone Support**: Display different timezones
- 📅 **Date Display**: Shows current date (optional)
- 🚀 **Simple & Lightweight**: Pure HTML/CSS/JS with no dependencies

## Technologies Used

- HTML5
- CSS3 (Flexbox, custom properties)
- JavaScript (ES6+)
- [Optional: Moment.js for timezone support]

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ArunaMaddu/digital-clock.git
Open index.html in your browser:

bash
open index.html  # Or just double-click the file
How to Use
The clock updates automatically in real-time

Click the theme button to cycle through color schemes

[Optional] Use the dropdown to select different timezones

[Optional] Toggle date display with the calendar button

Customization
Add New Themes
Modify in css/style.css:

css
.clock.theme-midnight {
  --bg-color: #0f0f1a;
  --text-color: #e0e0ff;
  --accent-color: #6a5acd;
}
Change Time Format
Edit in js/script.js:

javascript
// 12-hour format
timeElement.textContent = new Date().toLocaleTimeString('en-US');
// 24-hour format
timeElement.textContent = new Date().toLocaleTimeString('en-US', { hour12: false });
Add Timezone Support
Add to js/script.js:

javascript
function updateTimeForTimezone(timezone) {
  const options = {
    timeZone: timezone,
    hour: '2-digit',
    minute: '2-digit',
    second: '2-digit'
  };
  return new Date().toLocaleTimeString('en-US', options);
}
Project Structure
digital-clock/
├── index.html          # Main application page
├── css/
│   ├── style.css       # Main stylesheet
│   └── themes.css      # Additional themes
├── js/
│   └── script.js       # Clock functionality
├── assets/
│   ├── icons/          # SVG icons
│   └── preview.png     # Screenshot
└── README.md
Live Demo
View Live Demo

Future Enhancements
Add world clock mode

Include stopwatch/timer functionality

Add alarm feature

Implement custom theme creator

Contributing
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feature/NewFeature)

Commit your changes (git commit -m 'Add NewFeature')

Push to the branch (git push origin feature/NewFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - @ArunaMaddu - madduaruna134gamil.com

Project Link: https://arunamaddu.github.io/Digital-Clock/
## 🌟 Show Your Support

If you like this project, feel free to ⭐ star it and share it with others!


 
👨‍💻 Created by ArunaMaddu
