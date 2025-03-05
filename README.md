# Sorting Visualizer
---
## Overview
Sorting Visualizer is a web-based application that allows users to visualize various sorting algorithms in action. The project dynamically generates an array of bars, representing numerical values, and provides buttons to sort the array using different sorting algorithms.
---
## Features
- Generates a new random dataset for sorting
- Allows users to adjust the size of the dataset
- Provides speed control for visualization
- Implements the following sorting algorithms:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Quick Sort
  - Merge Sort
- Responsive and visually appealing UI with Bootstrap integration
---
## Technologies Used
- **HTML, CSS, JavaScript** for structuring, styling, and logic
- **Bootstrap 5** for UI styling
- **JavaScript** for sorting algorithms and animations
---
## Project Structure
```
Sorting Visualizer/
│-- index.html       # Main HTML file
│-- style.css        # Styling for visualization
│-- Js Algo/        # JavaScript files for sorting algorithms
│   │-- sorting.js      # Main script for array generation and control
│   │-- bubble.js       # Bubble Sort algorithm
│   │-- insertion.js    # Insertion Sort algorithm
│   │-- merge.js        # Merge Sort algorithm
│   │-- quick.js        # Quick Sort algorithm
│   │-- selection.js    # Selection Sort algorithm
```
---
## Setup and Usage
1. Clone the repository or download the project files.
2. Open `index.html` in a web browser.
3. Click **New Credit Data** to generate a new dataset.
4. Adjust the **Size of Data** slider to change the dataset size.
5. Adjust the **Speed** slider to modify sorting speed.
6. Click a sorting algorithm button to visualize the sorting process.
---
## How It Works
- The `sorting.js` file initializes the array and handles visualization updates.
- Each sorting algorithm has its own dedicated JavaScript file implementing the logic.
- CSS is used to animate the bars dynamically as they are sorted.
- User interaction is handled through event listeners attached to buttons and sliders.
---
## Contributing
Feel free to fork the project and contribute by improving functionality or adding new features!



