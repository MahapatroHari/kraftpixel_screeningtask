# KraftPixel Assignment

This project is a responsive HTML and CSS-based web page layout for a company website. It includes a header with navigation, a main content area introducing the company, and a metrics section displaying key statistics. The layout adapts to different screen sizes using media queries, making it user-friendly on both mobile and desktop devices.

## Project Overview

The project comprises:
1. **HTML** for structure.
2. **CSS** for styling and layout, with specific styles for desktop and mobile views.

## Features

- **Header Section**: 
  - Contains a logo, navigation links, and login/signup buttons.
  - Includes dropdown menus for "Products" and "Resources" in the navigation.
  - The navigation is responsive, adjusting layout for mobile and desktop screens.
- **Main Header Section**:
  - Displays a title and description about the company.
  - Positioned in the center to draw user attention.
- **Metrics Section**:
  - Highlights company achievements using statistics, such as "Projects Completed" and "Return on Investment."
  - Displays dynamically in a grid on larger screens for better visual organization.

## File Structure

```plaintext
├── index.html        # Main HTML file containing the page structure
├── style.css         # CSS file for styling the page
└── assets/           # Folder containing images such as logos, menu icon, and chevron icons
```

## Code Explanation

### HTML Structure

The HTML is structured semantically, with descriptive tags (`<header>`, `<section>`, `<nav>`, `<div>`) that improve accessibility and readability.

- **Header**: Contains a toolbar for navigation and authentication links.
- **Main Header Section**: Displays introductory content about the company.
- **Metrics Section**: Organized into a grid that showcases company statistics.

### CSS Styling

- **Global Reset**: Resets all padding, margin, and box-sizing with `* { padding: 0; margin: 0; box-sizing: border-box; }`.
- **Flexbox**: Used for layout in the `.toolbar` and other flex-based layouts.
- **Grid Layout**: Used in `.stats` to arrange statistics in a responsive grid.
- **Responsive Design**: Media queries adjust the layout at screen widths of 768px and above for an optimal desktop view.

## Usage

1. **Open the HTML File**: Open `index.html` in a browser to view the page.
2. **Modify Styles**: If you wish to change the appearance, modify `style.css`.
3. **Add Images**: Replace placeholder images (e.g., `Logomark.png`, `menu.png`) in the `assets` folder.

## Fonts and Icons

The project uses the "Inter" font from Google Fonts and includes icons and images, which should be placed in an `assets` folder for easy reference.

## Future Enhancements

- **JavaScript Interactivity**: Adding dropdown functionality for the "Products" and "Resources" buttons.
- **Expanded Layouts**: Additional sections or pages can be integrated for a complete website experience.
- **Enhanced Responsiveness**: Further media queries can enhance responsiveness for additional screen sizes.
