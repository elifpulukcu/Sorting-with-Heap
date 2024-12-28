
# Sorting-with-Heap

## Overview

The "Sorting-with-Heap" project is a Java application developed to implement and benchmark the performance of three sorting algorithms:

- **Heap Sort**
- **Java's built-in `Arrays.sort()`**
- **Selection Sort**

This application provides a comparative analysis of these algorithms to evaluate their efficiency in sorting operations.

## Features

- **Heap Implementation**: The project includes a custom `Heap` class that supports generic types and provides methods to add and remove elements, facilitating the heap sort implementation.

- **Selection Sort Implementation**: A method that performs selection sort on an array of integers.

- **Performance Benchmarking**: The application measures and compares the execution time of each sorting algorithm by sorting arrays of random integers and calculating the average elapsed time over multiple iterations.

## Prerequisites

- **Java Development Kit (JDK)**: Ensure that JDK 8 or higher is installed on your system.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/elifpulukcu/Sorting-with-Heap.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Sorting-with-Heap
   ```

3. **Compile the Java Files**:

   ```bash
   javac *.java
   ```

4. **Run the Application**:

   ```bash
   java Elif_Pulukcu
   ```

## Usage

Upon running the application, it prompts the user to enter the desired array size. The program then performs the following steps for each sorting algorithm:

1. Generates an array of random integers within the range [0, 10,000,000].
2. Sorts the array using one of the three algorithms.
3. Measures and records the time taken to sort the array.
4. Repeats the process ten times to calculate the average sorting time.

This process allows users to observe and compare the performance of the algorithms under identical conditions.

## Contributing

Contributions to enhance the functionality or performance of this project are welcome. To contribute:

1. **Fork the Repository**
2. **Create a New Branch**:

   ```bash
   git checkout -b feature-branch
   ```

3. **Commit Your Changes**:

   ```bash
   git commit -m "Description of changes"
   ```

4. **Push to the Branch**:

   ```bash
   git push origin feature-branch
   ```

5. **Create a Pull Request**

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Developed by [Elif Pulukçu](https://github.com/elifpulukcu).
