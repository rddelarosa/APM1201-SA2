# Sorting Algorithm Simulator
---
## Presented to:

Prof. Frederick Gella

## Submitted by:

  - Awit, Julia
  - Dela Rosa, Roland
  - Sigue, Patrick

## Overview
The Sorting Algorithm Simulator is an interactive Python-based tool designed to help users understand and visualize the workings of various sorting algorithms. By providing step-by-step insights, the simulator bridges the gap between theoretical understanding and practical application, making it an ideal learning tool for students, educators, and coding enthusiasts.

---

## Features
- **Simulation of Five Key Sorting Algorithms:**
  1. Bubble Sort
  2. Insertion Sort
  3. Merge Sort
  4. Quick Sort
  5. Selection Sort

- **Real-Time Visualization:**
  - Displays intermediate steps for better comprehension.
  - Shows how arrays evolve as the sorting progresses.

- **User Interaction:**
  - Option to input custom arrays or generate randomized arrays.
  - Select sorting algorithm with detailed explanations.

- **Performance Metrics:**
  - Observe time elapsed for different input sizes (e.g., 100, 1,000, 10,000 elements).

---

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/sorting-simulator.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd sorting-simulator
   ```
3. **Install Required Libraries:**
   Ensure you have Python 3 installed. Then run:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Use
1. **Run the Simulator:**
   ```bash
   python simulator.py
   ```
2. **Choose Array Input:**
   - Enter your own array.
   - Generate a random array by specifying size and range.
3. **Select a Sorting Algorithm:**
   - Options: Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, Selection Sort.
4. **Observe the Simulation:**
   - Watch how the array is sorted step-by-step.
   - Review the final sorted output and time elapsed.

---

## Algorithms Included
### Bubble Sort
- **Description:** Repeatedly swaps adjacent elements if they are in the wrong order.
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)

### Insertion Sort
- **Description:** Builds a sorted array incrementally by inserting elements into their correct positions.
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)

### Merge Sort
- **Description:** Divides the array into halves, sorts them, and merges them back together.
- **Time Complexity:** O(n log n)
- **S# Sorting Algorithm Simulator

## Project Description
The Sorting Algorithm Simulator is an educational tool designed to help users understand and visualize how popular sorting algorithms work. This project bridges the gap between theory and practice by providing a hands-on, interactive experience that showcases the step-by-step process of sorting arrays using different algorithms.

### Features
- **Interactive Simulation**: Supports Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, and Selection Sort.
- **Customizable Input**: Users can input custom arrays or generate random arrays.
- **Visualization**: Displays the intermediate steps of each sorting algorithm.
- **User-Friendly Interface**: A simple command-line interface to guide users through the process.

### Benefits
- Enhances understanding of sorting algorithms through interactive learning.
- Promotes analytical thinking by allowing users to compare the efficiency of different algorithms.
- Makes complex algorithmic concepts accessible and engaging.

---

## Setup Instructions

### Prerequisites
- Python 3.8 or later

### Installation Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/username/sorting-algorithm-simulator.git
   cd sorting-algorithm-simulator
   ```

2. **Set Up Virtual Environment (Optional)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Required Libraries**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Simulator**
   ```bash
   python sorting_simulator.py
   ```

---

## Usage Examples

### Example 1: Manual Array Input
1. Run the simulator:
   ```bash
   python sorting_simulator.py
   ```
2. Select the option to manually input an array.
3. Enter your array, e.g., `[5, 3, 8, 1, 2]`.
4. Choose a sorting algorithm (e.g., Bubble Sort).
5. Observe the step-by-step sorting process in the console.

### Example 2: Random Array Generation
1. Run the simulator:
   ```bash
   python sorting_simulator.py
   ```
2. Select the option to generate a random array.
3. Specify the size and range of the array.
4. Choose a sorting algorithm (e.g., Merge Sort).
5. Observe the detailed sorting process and final sorted array.

---

## Test Cases
To ensure the simulator works correctly, test cases have been provided in `tests.py`. The test cases cover:

1. **Basic Functionality**: Sorting simple arrays (e.g., `[3, 1, 2]` => `[1, 2, 3]`).
2. **Edge Cases**:
   - Empty arrays (e.g., `[]`).
   - Single-element arrays (e.g., `[1]`).
   - Arrays with duplicate elements (e.g., `[4, 2, 4, 1]`).
3. **Large Arrays**: Sorting arrays with thousands of elements to test performance.

### Running Tests
1. Ensure you are in the project directory.
2. Run the test suite:
   ```bash
   python -m unittest tests.py
   ```
3. Review the test results in the console.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---


