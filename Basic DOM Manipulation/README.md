# Task 3: Counter Application - DOM Manipulation

## 📋 Overview
An interactive counter application built with vanilla JavaScript that demonstrates comprehensive DOM manipulation techniques. Features include increment/decrement controls, customizable step sizes, real-time statistics tracking, and smooth animations.

## ✨ Features
- **Increment/Decrement Controls**: Easily increase or decrease the counter value
- **Zero Limit Protection**: Counter cannot go below zero
- **Variable Step Sizes**: Choose from 1, 5, 10, 50, or 100 step increments
- **Real-Time Statistics**: Track total clicks, maximum value, and minimum value
- **Smooth Animations**: Bouncing animations for value changes
- **Keyboard Shortcuts**: Control counter with arrow keys and keyboard
- **Reset Functionality**: One-click reset to clear all values
- **Responsive Design**: Works perfectly on all screen sizes
- **Visual Feedback**: Disabled states and dynamic status messages

## 🛠️ Technologies Used
- HTML5
- CSS3 (Animations, Grid, Flexbox)
- Vanilla JavaScript (ES6+)

## 📂 Project Structure
```
task3-counter-app/
│
├── index.html          # Main HTML file with embedded CSS and JS
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No dependencies or installations needed

### Installation & Usage
1. Download the `index.html` file
2. Open it in your web browser
3. Start counting! Click buttons or use keyboard shortcuts.

## 💡 How to Use

### Button Controls
- **➕ Increase**: Increment counter by current step size
- **➖ Decrease**: Decrement counter by current step size (disabled at 0)
- **🔄 Reset**: Reset counter and all statistics to zero

### Step Size Controls
Click any step button (1, 5, 10, 50, 100) to change increment/decrement value

### Keyboard Shortcuts
- **Arrow Up** or **+**: Increment counter
- **Arrow Down** or **-**: Decrement counter
- **R**: Reset counter

## 🎨 Key Features Explained

### DOM Manipulation Techniques
- **Dynamic Content Updates**: Real-time updating of counter value and statistics
- **Event Listeners**: Button clicks and keyboard event handling
- **Class Manipulation**: Adding/removing animation classes dynamically
- **Style Manipulation**: Direct style updates for visual feedback
- **Conditional Rendering**: Button disable states based on counter value

### Statistics Tracking
The app tracks and displays:
- **Total Clicks**: Count of all increment/decrement actions
- **Max Value**: Highest value reached during session
- **Min Value**: Lowest value reached (with zero limit)

### Animation System
- Bounce-up animation for increment
- Bounce-down animation for decrement
- Pulse effect on counter display background
- Smooth button hover and press effects

## 🎯 Learning Outcomes
This project demonstrates proficiency in:
- JavaScript DOM manipulation
- Event handling (click and keyboard events)
- State management with vanilla JavaScript
- CSS animations and transitions
- Conditional logic and input validation
- User interface design principles
- Accessibility considerations (ARIA labels, keyboard navigation)
- Responsive web design

## 🔒 Features Implementation

### Zero Limit Protection
```javascript
if (count <= 0) {
    decrementBtn.disabled = true;
    count = 0; // Ensure count doesn't go below 0
}
```

### Dynamic Statistics
- Automatically updates max/min values as counter changes
- Animates stat cards when new records are set
- Tracks total user interactions

### Smooth User Experience
- Visual feedback on all interactions
- Disabled button states prevent invalid actions
- Status messages provide context
- Animations make changes feel natural

## 📱 Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎮 Interactive Elements
- 3 primary action buttons (increment, decrement, reset)
- 5 step size selector buttons
- Real-time counter display with animations
- 3 live statistics cards
- Keyboard shortcut support

## 🔗 Live Demo
Will be out soon.

## 👨‍💻 Author
Theodore Gyaqueh Abbey

## 📄 License
This project is part of the Codveda Technology internship program.

## 🙏 Acknowledgments
- Codveda Technology for the internship opportunity
- Modern web app design patterns and best practices

## 🚀 Future Enhancements
Possible improvements for this project:
- Custom step size input
- Counter history/undo functionality
- Save counter state to localStorage
- Multiple independent counters
- Export statistics data

---

**#CodvedaJourney #CodvedaExperience #FutureWithCodveda**