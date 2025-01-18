# Sorting Visualization Project

## Overview
The **Sorting Visualization** project is an interactive tool designed to visualize the process of different sorting algorithms in real time. It provides users with an intuitive, graphical representation of how various sorting algorithms work, helping to better understand the concepts of algorithmic complexity and sorting behavior. This project supports various sorting algorithms, allowing users to compare their performance and efficiency.

## Features
- Visualize popular sorting algorithms, including:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
- Interactive user interface to control sorting speed and algorithm selection.
- Dynamic visualization with animations to clearly show each step of the algorithm.
- Option to generate random datasets of varying sizes to test and compare algorithms.

## Technologies Used
- **Frontend**: 
  - HTML5, CSS3, JavaScript
  - D3.js (for rendering the visualizations)
  - Bootstrap (for responsive design)
- **Algorithms**: JavaScript implementations of various sorting algorithms.
- **Version Control**: Git (GitHub for hosting the repository)

## Installation
To run the Sorting Visualization project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sorting-visualization.git
    ```

2. Navigate into the project directory:
    ```bash
    cd sorting-visualization
    ```

3. Open the `index.html` file in a web browser to launch the project.

## How It Works
1. **User Interface**: The UI features a "Generate" button to create a random dataset and a dropdown to select the sorting algorithm.
2. **Algorithm Selection**: Users can choose from the listed sorting algorithms and control the speed of the sorting process using a slider.
3. **Visualization**: Each sorting algorithm is visualized by animating the array being sorted. As the algorithm progresses, the visual state of the array is updated to show each comparison and swap of elements.

## Sorting Algorithms Included
- **Bubble Sort**: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
- **Selection Sort**: Finds the smallest element in the unsorted part of the array and swaps it with the first unsorted element.
- **Insertion Sort**: Builds a sorted section of the array one element at a time by inserting each element into its correct position.
- **Merge Sort**: Divides the array into halves, recursively sorts each half, and then merges the sorted halves.
- **Quick Sort**: Selects a pivot element and partitions the array around the pivot, recursively sorting the partitions.
- **Heap Sort**: Builds a max heap and repeatedly extracts the maximum element, placing it in the sorted section of the array.

## Acknowledgements
- Inspired by various sorting algorithm visualizations found online.
- Libraries used:
  - [D3.js](https://d3js.org/) for rendering the visualizations.
  - [Bootstrap](https://getbootstrap.com/) for the UI layout.
  
Feel free to use and modify this project for educational purposes or further enhancements!
