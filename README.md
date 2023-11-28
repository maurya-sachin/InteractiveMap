# Interactive Map with Video Background

This project features an interactive map with a video background and tooltips that display additional information when hovering over shapes. The map includes paths and circles, each representing different regions.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Styling](#styling)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Modern web browser
- Stable internet connection for fetching data from the API

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/maurya-sachin/InteractiveMap.git
   ```

2. Open the `index.html` file in your web browser.

## Usage

Hover over shapes on the map to see tooltips displaying relevant information. The tooltips include details such as the name, area, and population.

## File Structure

- `index.html`: HTML file containing the map and tooltip logic.
- `styles.css`: CSS file for styling the map, tooltip, and video background.
- `script.js`: JavaScript file with the interactive tooltip logic.
- `README.md`: Documentation for the project.

## Styling

### Map and Video Background

The map and video background are styled using CSS media queries to create a responsive layout.

### Shapes

- `path`: Filled with a light gray color and has a black stroke. On hover, the stroke width increases.
- `circle`: Filled with red color and has a black stroke with a radius of 5.

### Region-Specific Styling

Each region on the map has a unique hover effect, changing the fill color on hover.

### Tooltip

The tooltip is styled with a light background color, padding, border-radius, and box-shadow for a clean appearance. The font size and weight are adjusted for readability.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
