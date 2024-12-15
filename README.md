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
- **Space Complexity:** O(n)

### Quick Sort
- **Description:** Selects a pivot, partitions the array into smaller and larger elements, and sorts recursively.
- **Time Complexity:** O(n log n) (average), O(n²) (worst case)
- **Space Complexity:** O(log n)

### Selection Sort
- **Description:** Finds the smallest element in the unsorted array and swaps it to the correct position.
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)

---

## Challenges and Future Enhancements
### Challenges Faced:
- Handling large arrays while maintaining real-time responsiveness.
- Balancing detailed visualization with efficient computation.

### Planned Improvements:
1. Add advanced sorting methods (Heap Sort, Radix Sort, etc.).
2. Implement graphical animations for enhanced visualization.
3. Include execution time and memory usage metrics for performance comparison.
4. Transition from CLI to a GUI or web-based platform for broader accessibility.

---

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request


