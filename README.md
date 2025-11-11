# Switch ON/OFF - Interactive Light Switch Application

A simple yet interactive web application that simulates a light switch mechanism with dynamic visual feedback. Toggle the switch to control a bulb and see a cat's reaction to the light changes!

## 🎯 Project Overview

This project demonstrates fundamental web development concepts including DOM manipulation, event handling, responsive design, and state management. It's a beginner-friendly application perfect for learning how JavaScript interacts with HTML and CSS.

## ✨ Features

- **Interactive Switch Controls**: Click ON/OFF buttons to toggle the light
- **Dynamic Visual Feedback**:
  - Bulb image changes between lit and unlit states
  - Cat image reacts to light changes (normal/eyes-only expression)
  - Status text updates in real-time
  - Button colors highlight active/inactive states
- **Dark Theme Design**: Modern dark mode interface with good contrast
- **Responsive Layout**: Uses flexbox for proper alignment across different screen sizes
- **Clean Code**: Well-structured HTML, CSS, and JavaScript

## 🏗️ Project Structure

```
Switch ON or OFF/
├── index.html          # HTML structure and layout
├── styles.css          # Styling and theme definitions
├── script.js           # JavaScript logic and event handlers
└── README.md          # This file
```

## 📋 File Descriptions

### `index.html`
- Semantic HTML structure
- Embeds bulb and cat images from CloudFront CDN
- Defines switch control buttons with event listeners
- Links to Bootstrap CDN for utility classes and jQuery dependencies

### `styles.css`
- Dark background theme (`#0b0b0b`)
- Switch board styling with gray background (`#7b8794`)
- Button state colors:
  - ON active: Green (`#22c55e`)
  - OFF active: Red (`#e12d39`)
  - Inactive: Light gray (`#cbd2d9`)
- Flexbox-based responsive layout
- Typography using Roboto font family

### `script.js`
- `switchOn()` function: Turns the light ON
  - Updates bulb image to lit state
  - Changes cat to normal expression
  - Updates status to "Switched On"
  - Changes button colors accordingly
- `switchOff()` function: Turns the light OFF
  - Updates bulb image to unlit state
  - Changes cat to eyes-only expression
  - Updates status to "Switched Off"
  - Changes button colors accordingly

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (images are hosted on CloudFront CDN)

### Installation & Usage

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **Click the buttons**:
   - Click "OFF" to turn off the light
   - Click "ON" to turn on the light
4. **Watch the animations** as the bulb and cat respond to the switch changes

No build process or dependencies to install - just open and play!

## 🎨 Color Palette

| Element | Color | Hex Code |
|---------|-------|----------|
| Background | Dark Black | `#0b0b0b` |
| Switch Board | Gray | `#7b8794` |
| ON Button (Active) | Green | `#22c55e` |
| OFF Button (Active) | Red | `#e12d39` |
| Inactive Buttons | Light Gray | `#cbd2d9` |
| Text | White | `#ffffff` |

## 📐 Component Specifications

### Bulb Image
- Dimensions: 150px width
- States: On (lit) / Off (unlit)
- CDN hosted from `d2clawv67efefq.cloudfront.net`

### Cat Image
- Dimensions: 300px width
- States: Normal / Eyes-only expression
- CDN hosted from `d2clawv67efefq.cloudfront.net`

### Switch Board
- Dimensions: 294px × 139px
- Border Radius: 12px
- Padding: 32px (top/bottom), 16px (left/right)
- Margin: 16px (all around)

## 💡 How It Works

1. **Initial State**: The application loads with the light ON
2. **User Interaction**: User clicks either ON or OFF button
3. **Event Handler**: Corresponding JavaScript function is triggered
4. **DOM Updates**: Multiple elements are updated simultaneously:
   - Bulb image source
   - Cat image source
   - Status text content
   - Button background colors
5. **Visual Feedback**: All changes are immediately visible to the user

### State Management Flow

```
User Click
    ↓
JavaScript Function Called
    ↓
DOM Elements Updated
    ├─ Bulb Image
    ├─ Cat Image
    ├─ Status Text
    └─ Button Colors
    ↓
Visual Feedback on Screen
```

## 🔧 Customization

You can easily customize this project:

- **Change Colors**: Modify the hex values in `styles.css`
- **Change Images**: Update image URLs in `index.html` and `script.js`
- **Change Text**: Modify status messages in `script.js`
- **Add Animations**: Add CSS transitions and animations
- **Add Sound**: Include audio effects for switch clicks

## 📚 Learning Outcomes

By studying this project, you'll learn:

- ✅ HTML structure and semantic elements
- ✅ CSS styling and flexbox layout
- ✅ JavaScript DOM manipulation with `getElementById()` and `textContent`
- ✅ Event handling with `onclick` attributes
- ✅ State management principles
- ✅ Image CDN usage
- ✅ Responsive web design basics

## 🐛 Troubleshooting

### Images Not Loading
- Check your internet connection
- Verify CloudFront CDN is accessible
- Try refreshing the page

### Buttons Not Responding
- Ensure JavaScript is enabled in your browser
- Check browser console for any errors (F12)
- Try a different browser

## 🎓 Future Enhancements

- Add sound effects for switch clicks
- Add animation transitions between states
- Add keyboard controls (spacebar to toggle)
- Add local storage to remember last state
- Add accessibility features (ARIA labels)
- Create a settings panel for customization
- Add multiple rooms with independent switches

## 📄 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

Created as a simple interactive web application project.

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements!

---

**Happy Switching! 🔦**

For more information or questions, feel free to reach out or open an issue on GitHub.
