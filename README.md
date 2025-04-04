# E-Waste Crisis Website

A dynamic, responsive front-end website highlighting the global e-waste crisis. This project uses Bootstrap, animations, and an attractive color scheme to create an engaging and educational experience about electronic waste issues and solutions.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Color Scheme](#color-scheme)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Compatibility](#browser-compatibility)
- [Contributing](#contributing)
- [License](#license)

## Overview

This website serves as an educational platform about the growing crisis of electronic waste (e-waste). It presents key statistics, environmental and social impacts, and sustainable solutions in an engaging, visually appealing format. The site is designed to be fully responsive, with animated elements and interactive components that enhance user experience.

## Features

- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **Animated Elements**: Uses Animate.css for smooth entrance animations
- **Interactive Components**: Statistics cards, solution highlights, and timeline presentation
- **Bootstrap Integration**: Leverages Bootstrap 5 for layout and components
- **Custom Color Scheme**: Uses carefully selected complementary colors
- **Dynamic Navigation**: Smooth scrolling with active section highlighting
- **Visual Data Presentation**: Progress bars and counter displays for statistics
- **Floating Icon Animation**: Dynamic background elements in the hero section
- **Back-to-Top Button**: Easy navigation for longer page scrolling
- **Timeline Visualization**: Responsive historical timeline of e-waste development

## Technologies Used

- HTML5
- CSS3 (with custom animations)
- Bootstrap 5.3
- Font Awesome 6.0
- Animate.css 4.1.1
- JavaScript (for interactive elements)

## Project Structure

```
e-waste-website/
│
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # Custom CSS (included inline in the HTML for this version)
│   ├── js/
│   │   └── scripts.js      # JavaScript functions (included inline in the HTML for this version)
│   └── images/             # Image assets (using placeholders in this version)
├── README.md               # Project documentation
└── LICENSE                 # License information
```

## Color Scheme

The website uses a carefully selected color palette that represents environmental themes:

- **Primary Color**: `#0a6c75` (Teal blue) - Representing water bodies affected by e-waste
- **Secondary Color**: `#2eb086` (Green) - Symbolizing environmental sustainability
- **Accent Color**: `#f0a202` (Amber) - Highlighting important call-to-action elements
- **Dark Color**: `#333333` (Dark gray) - For text and dark sections
- **Light Color**: `#f8f9fa` (Off-white) - For backgrounds and contrast
- **Danger Color**: `#e74c3c` (Red) - For highlighting critical statistics

These colors are applied consistently throughout the site to create visual harmony while ensuring accessibility standards are met.

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/e-waste-website.git
   cd e-waste-website
   ```

2. **Open in a browser**
   - Simply open the `index.html` file in any modern web browser
   - Alternatively, use a local development server:
     ```bash
     # If you have Python installed
     python -m http.server
     # Or with Node.js
     npx serve
     ```

3. **External Dependencies**
   All external libraries are loaded via CDN links, so no additional installation is required:
   - Bootstrap CSS and JS
   - Font Awesome
   - Animate.css

## Usage

The website is designed to be intuitive and easy to navigate. Here's how different sections can be utilized:

- **Navigation**: Use the top navbar to jump to different sections
- **Statistics**: Showcase key e-waste figures with visual representations
- **Impact Section**: Details environmental and social consequences of e-waste
- **Solutions**: Presents approaches to address the e-waste crisis
- **Timeline**: Historical perspective on e-waste development
- **Take Action**: Call-to-action section with resources for involvement

## Customization

### Content Customization

1. **Update Statistics**: 
   - Modify the numbers in the Statistics section to reflect the latest data
   - Adjust progress bars by changing the `width` percentage values

2. **Image Replacement**:
   - Replace placeholder images with actual images related to e-waste
   - Recommended image sizes:
     - Hero image: 600×400px
     - Section images: 400×300px

3. **Text Content**:
   - Update factual information to reflect current statistics and research
   - Customize the call-to-action section with relevant local resources

### Style Customization

1. **Color Scheme**:
   - Modify the CSS variables in the `:root` selector at the top of the CSS section:
     ```css
     :root {
         --primary: #your-color;
         --secondary: #your-color;
         ...
     }
     ```

2. **Animation Timing**:
   - Adjust animation delays by modifying the `animation-delay` properties
   - Change floating icon behavior by modifying the `@keyframes float` definition

3. **Layout Adjustments**:
   - The website uses Bootstrap grid system - modify column classes to change layouts
   - Adjust padding and margin values with Bootstrap spacing utilities or custom CSS

## Browser Compatibility

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

Mobile browsers are fully supported with the responsive design.

## Contributing

Contributions are welcome to improve the website and keep information current:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgments

- Data sources: United Nations E-waste Coalition, Global E-waste Statistics Partnership
- Icons provided by Font Awesome
- Animations powered by Animate.css
- Layout framework by Bootstrap

---

*This website was created to raise awareness about the growing e-waste crisis and promote sustainable solutions.*
