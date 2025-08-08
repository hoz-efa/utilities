# Utilities Website

<div align="center">
  <img src="favicon.svg" alt="Utilities Logo" width="80" height="80">
  <h3>A collection of clean, minimalist web utilities for displaying time, date, and calendar information</h3>
  <p>Perfect for digital signage, dashboards, or any display purpose.</p>
</div>

## Features

- **Clean Design**: Minimalist black background with white text
- **Responsive**: Automatically adjusts to different screen sizes
- **Fullscreen Support**: Built-in fullscreen functionality with cursor hiding
- **Cross-Browser Compatible**: Works on all modern browsers
- **No Dependencies**: Pure HTML, CSS, and JavaScript

## Utilities Included

### 🕐 Clock Displays

#### Digital Clocks
- **12-Hour Clock** (`clock-12hr.html`) - Shows time in 12-hour format (e.g., "3:45 pm")
- **12-Hour Clock with Seconds** (`clock-12hr-seconds.html`) - Shows time with seconds (e.g., "3:45:23 pm")
- **24-Hour Clock** (`clock-24hr.html`) - Shows time in 24-hour format (e.g., "15:45")
- **24-Hour Clock with Seconds** (`clock-24hr-seconds.html`) - Shows time with seconds (e.g., "15:45:23")

#### Analog Clocks
- **Analog Clock** (`clock-analog.svg`) - Traditional analog clock face
- **Analog Clock with Seconds** (`clock-analog-seconds.svg`) - Analog clock with moving second hand

### 📅 Date Displays

- **Date** (`date.html`) - Shows full date (e.g., "Monday, January 15, 2024")
- **Date & Calendar** (`date-calendar.html`) - Shows date with current month calendar view

## Fullscreen Features

### How to Use Fullscreen Mode

1. **Enter Fullscreen**: Click the fullscreen button (⛶) in the top-right corner of any utility page
2. **Exit Fullscreen**: 
   - Click the fullscreen button again
   - Press the `Esc` key
   - Use browser's fullscreen exit controls

### Cursor Behavior in Fullscreen

- **Auto-Hide**: Cursor automatically disappears after 5 seconds of inactivity
- **Show on Interaction**: Cursor reappears when you:
  - Move the mouse
  - Click anywhere
  - Press any key
- **Fullscreen Button**: Also hides with the cursor for a clean display

### Perfect For

- **Digital Signage**: Clean, distraction-free displays
- **Dashboard Monitors**: Professional time/date displays
- **Presentation Screens**: Background displays during presentations
- **Kiosks**: Public information displays
- **Home Displays**: Wall-mounted screens showing time and date

## Browser Compatibility

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## File Structure

```
utilities/
├── index.html                 # Main navigation page
├── favicon.svg               # Website logo and favicon
├── clock-12hr.html           # 12-hour clock
├── clock-12hr-seconds.html   # 12-hour clock with seconds
├── clock-24hr.html           # 24-hour clock
├── clock-24hr-seconds.html   # 24-hour clock with seconds
├── clock-analog.svg          # Analog clock
├── clock-analog-seconds.svg  # Analog clock with seconds
├── date.html                 # Date display
├── date-calendar.html        # Date with calendar
└── README.md                 # This file
```

## Usage

1. **Local Use**: Simply open any HTML file in your web browser
2. **Web Server**: Upload files to any web server for online access
3. **Digital Signage**: Load directly on display devices or kiosks

## Customization

### Colors
All utilities use a dark theme by default:
- Background: `#000000` (black)
- Text: `#FFFFFF` (white)
- Accents: Semi-transparent white for buttons

### Font Sizing
- Text automatically scales to fit the screen
- Responsive design ensures readability on all devices

### Fullscreen Behavior
- Cursor hiding delay: 5 seconds (configurable in JavaScript)
- Fullscreen button position: Top-right corner
- Smooth transitions for all interactions

## Technical Details

- **No External Dependencies**: Pure HTML, CSS, and JavaScript
- **Responsive Design**: Uses CSS Grid and Flexbox
- **Fullscreen API**: Uses standard browser Fullscreen API
- **Performance Optimized**: Minimal JavaScript, efficient updates
- **Accessibility**: Keyboard navigation support

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve these utilities.

---

**Note**: The main index page (`index.html`) does not include fullscreen functionality as it serves as a navigation hub for the other utilities.
