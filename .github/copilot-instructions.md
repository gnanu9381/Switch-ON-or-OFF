# AI Agent Instructions for Switch ON/OFF Project

## Project Overview
This is a simple interactive web application that simulates a light switch mechanism with visual feedback. The project demonstrates DOM manipulation, event handling, and responsive design patterns.

## Project Structure
- `index.html`: Main HTML structure with bulb and cat images, and switch controls
- `styles.css`: Styling definitions for layout, theme, and responsive design
- `script.js`: JavaScript logic for switch functionality and state management

## Key Components and Patterns

### Image State Management
- Images are hosted on cloudfront CDN (`d2clawv67efefq.cloudfront.net`)
- Two states for each image:
  - Bulb: on (`bulb-go-on-img.png`) and off (`bulb-go-off-img.png`)
  - Cat: normal (`cat-img.png`) and eyes only (`cat-eyes-img.png`)
- Image dimensions are controlled via CSS:
  - Bulb: 150px width
  - Cat: 300px width

### Layout System
- Uses flexbox for centering and alignment
- Utility classes for common layout patterns:
  - `.d-flex`: Display flex container
  - `.flex-row`: Horizontal layout
  - `.justify-content-center`: Center alignment
  - `.text-center`: Text alignment
  - `.pt-5`: Padding top utility

### Switch Interface
- Switch board specifications:
  - Dimensions: 294x139px
  - Border radius: 12px
  - Padding: 32px top/bottom, 16px left/right
  - Margin: 16px all around

### Theme System
Color tokens:
- Background: Dark mode (rgb(11, 11, 11))
- Switch board: Gray (rgb(123, 135, 148))
- ON button active: Green (rgb(34, 197, 94))
- OFF button active: Red (rgb(225, 45, 57))
- Inactive button: Gray (rgb(203, 210, 217))

### JavaScript State Management
- Direct DOM manipulation using `getElementById()`
- State changes are synchronized across:
  1. Image sources (bulb and cat)
  2. Status text content
  3. Button background colors

## Development Guidelines
1. Element ID Conventions:
   - `bulbImage`: Bulb image element
   - `catImage`: Cat image element
   - `switchStatus`: Status text element
   - `onSwitch`/`offSwitch`: Control buttons

2. Component State Management:
   - Always update bulb and cat images together
   - Update status text to match current state
   - Toggle button colors to reflect active state

3. Typography:
   - Font family: "Roboto"
   - Status text: 24px, weight 500
   - Button text: 24px, weight bold

4. Accessibility:
   - Use semantic HTML elements
   - Maintain color contrast ratios
   - Ensure interactive elements are keyboard accessible