# Sorting_Visualizer# 📊 Sorting Visualizer

A web application that visualizes various sorting algorithms to help users understand how they work. This interactive tool demonstrates the step-by-step process of different sorting methods through animated visualizations.

## ✨ Features

- **Multiple Sorting Algorithms**: Visualize various sorting techniques:
  - Bubble Sort
  - Selection Sort
  - Quick Sort
  - Merge Sort

- **Interactive Controls**:
  - Adjust array size
  - Control visualization speed
  - Generate new random arrays
  - Start, pause, and reset animations

- **Educational Elements**:
  - Real-time highlighting of comparisons and swaps
  - Step-by-step visualization of algorithm execution
  - Time and space complexity information for each algorithm

## 🛠️ Technologies Used

- **HTML5**: Structure of the web application
- **CSS3**: Styling and animations
- **JavaScript**: Algorithm implementation and DOM manipulation
- **No external libraries**: Built with pure vanilla JavaScript

## 💻 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/SortingVisualizer.git
   ```

2. Navigate to the project directory:
   ```bash
   cd SortingVisualizer
   ```

3. Open `index.html` in your web browser.

## 📖 How to Use

1. **Adjust the Array Size**: Use the slider to change the number of elements.
2. **Select Speed**: Choose visualization speed from slow to fast.
3. **Generate New Array**: Create a new random array to sort.
4. **Select Algorithm**: Choose which sorting algorithm to visualize.
5. **Start Sorting**: Click the "Sort" button to begin visualization.

## 📚 Algorithm Information

### Bubble Sort
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)
- **Description**: Repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order.

### Selection Sort
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)
- **Description**: Divides the array into a sorted and an unsorted region, repeatedly selects the smallest element from the unsorted region and moves it to the sorted region.

### Quick Sort
- **Time Complexity**: O(n log n) average, O(n²) worst case
- **Space Complexity**: O(log n)
- **Description**: Uses a divide-and-conquer strategy with a pivot element to partition the array.

### Merge Sort
- **Time Complexity**: O(n log n)
- **Space Complexity**: O(n)
- **Description**: Divides the array into halves, sorts each half, then merges the sorted halves back together.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
