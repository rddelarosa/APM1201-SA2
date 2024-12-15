# Sorting Algorithm Simulator
---
## Presented to:

Prof. Frederick Gella

## Submitted by:

  - Awit, Julia
  - Dela Rosa, Roland
  - Sigue, Patrick

## Project Description
The Sorting Algorithm Simulator is an interactive Python application that allows users to visualize and understand various sorting algorithms. The program supports the following algorithms:

- Bubble Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Selection Sort

Users can input their own array or generate a random array for sorting. The program provides step-by-step output to explain how each algorithm processes the data, making it an excellent learning tool.

## Setup Instructions

### Prerequisites
- Python 3.x installed on your system.
- Basic knowledge of using a Python environment or Google Colab.

### Running Locally
1. Clone or download the repository.
2. Install any required Python packages if needed (e.g., `random`, which is included by default).
3. Run the `SA2_Awit_DelaRosa_Sigue.ipynb`

### Running in Google Colab
1. Upload the script to your Google Drive or directly copy the code into a new Colab notebook cell.
2. Run the cell to execute the program.

## Usage Examples

### Starting the Application
When you start the application, you will be prompted to either:
1. Input your own array.
2. Generate a random array.
3. Exit the program.

### Example Run
#### Input
- Input Array: `[4, 2, 7, 1, 5]`
- Selected Sorting Algorithm: Bubble Sort

#### Output
- Step-by-step explanation of the sorting process.
- Final sorted array: `[1, 2, 4, 5, 7]`

### Test Cases
#### Test Case 1
Input: `[5, 2, 9, 1, 5, 6]`
Algorithm: Merge Sort
Expected Output: `[1, 2, 5, 5, 6, 9]`

#### Test Case 2
Input: `[10, 3, 15, 7]`
Algorithm: Quick Sort
Expected Output: `[3, 7, 10, 15]`

## Code Documentation
### Key Functions
- **`bubble_sort(array)`**: Implements Bubble Sort algorithm.
- **`insertion_sort(array)`**: Implements Insertion Sort algorithm.
- **`merge_sort(array)`**: Implements Merge Sort algorithm with recursive splitting and merging.
- **`quick_sort(array)`**: Implements Quick Sort algorithm with pivot selection.
- **`selection_sort(array)`**: Implements Selection Sort algorithm.
- **`get_user_input()`**: Handles user input for array selection or generation.
- **`choose_sorting_algorithm()`**: Allows users to choose the sorting algorithm.

### Comments
- Each function contains in-line comments to explain the logic and steps.
- Print statements provide a detailed view of the sorting process for visualization.

## Additional Notes
- The random array generation is limited to 10 elements to ensure clarity in the sorting process.
- The simulator is designed to be user-friendly for educational purposes.

