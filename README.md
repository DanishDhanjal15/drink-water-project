# Drink Water Tracker

A beautiful and interactive water intake tracker built with vanilla HTML, CSS, and JavaScript. Features a visual cup system that helps you track your daily water consumption with real-time feedback and smooth animations.

## Features

- *Visual Water Tracking*: Large cup display that fills up as you drink water
- *Interactive Small Cups*: Click on 250ml cups to mark them as consumed
- *Real-time Progress*: 
  - Dynamic percentage display
  - Remaining water calculation
  - Visual fill animation
- *Smart Cup Logic*: 
  - Toggle cups on/off by clicking
  - Automatic big cup updates
  - Smooth transitions
- *Responsive Design*: Works seamlessly on desktop and mobile devices
- *Clean UI*: Modern design with smooth animations and transitions
- *Goal Tracking*: 2-liter daily water intake goal

## How to run

### Quick Start
- Open index.html in any modern browser
- No setup or installation required

### Local Development Server (Recommended)
For better development experience, use a local server:

*Python 3:*
bash
python3 -m http.server

Then visit http://localhost:8000/index.html

*Node.js (if you have it):*
bash
npx serve .

Then visit the provided URL

## Files Structure


drink-water/
├── index.html      # Main application interface
├── style.css       # Custom styling and animations
├── script.js       # Water tracking logic and interactions
└── README.md       # This file


## Usage

1. *View Goal*: See your daily water intake goal (2 liters)
2. *Track Progress*: Watch the large cup fill up as you drink water
3. *Mark Consumption*: Click on the small 250ml cups to mark them as consumed
   - Blue cups = consumed
   - White cups = not yet consumed
4. *Monitor Progress*: 
   - Percentage display shows completion
   - Remaining water is calculated and displayed
   - Visual feedback updates in real-time

## Technical Details

- *Pure JavaScript*: No frameworks or dependencies
- *CSS Custom Properties*: Variables for consistent theming
- *Flexbox Layout*: Modern CSS layout system
- *Smooth Animations*: CSS transitions for fluid interactions
- *Event-Driven*: Click handlers for interactive cups
- *Dynamic Updates*: Real-time calculation and display updates
- *Responsive Design*: Mobile-friendly interface

## How It Works

The application uses an intuitive visual system:

- *8 Small Cups*: Each represents 250ml of water (total 2 liters)
- *1 Large Cup*: Visual representation of overall progress
- *Smart Logic*: 
  - Clicking a cup toggles its state
  - Big cup fills proportionally to consumed small cups
  - Percentage and remaining water update automatically
  - Smooth animations provide visual feedback

## Key Features Explained

### Cup Interaction
- Click any small cup to mark it as consumed (fills with blue)
- Click again to unmark it (returns to white)
- Smart logic prevents gaps in the sequence

### Visual Feedback
- Large cup fills from bottom to top
- Percentage display shows completion percentage
- Remaining water shows how much is left to drink
- Smooth transitions make interactions feel natural

### Progress Tracking
- Goal: 2 liters (8 cups of 250ml each)
- Real-time calculation of consumed vs remaining water
- Visual progress indicator with percentage

## Browser Support

Works in all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Customization

- *Goal Amount*: Modify the goal in script.js (currently 2 liters)
- *Cup Size*: Change the small cup volume in the HTML and calculations
- *Colors*: Update CSS custom properties for different themes
- *Animations*: Adjust transition timing in CSS
- *Layout*: Modify cup sizes and spacing in CSS

## Styling Features

- *Modern Design*: Clean, minimalist interface
- *Smooth Transitions*: 0.3s ease transitions for all interactions
- *Color Scheme*: Blue theme with white accents
- *Typography*: Montserrat font for clean readability
- *Responsive*: Adapts to different screen sizes

## Future Enhancements

Potential improvements you could add:
- Local storage to persist daily progress
- Multiple day tracking
- Customizable goals
- Reminder notifications
- Progress statistics
- Different cup sizes
- Achievement system

## License

This is a demo project. Feel free to use and modify for your own projects.

---

*Made with ❤ by Danish Dhanjal*
