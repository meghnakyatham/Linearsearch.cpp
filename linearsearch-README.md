# Linearsearch.cpp
Linear Search Program in C++**

This repository contains a simple C++ program that demonstrates the implementation of a linear search algorithm to find a key element within an array. The program prompts the user to input an array of integers and a key element. It then searches for the key element within the array using a linear search approach. If the key element is found, the program displays its index in the array; otherwise, it indicates that the element was not found.

### Usage

1. **Compilation**: To compile the program, ensure you have a C++ compiler installed (e.g., g++). Open a terminal/command prompt and navigate to the directory containing the source code file (`linear_search. pp). Use the following command to compile the program:

   ```bash
   g++ linear_search.cpp -o linear_search
   ```

   This will generate an executable file named `linear_search`.

2. **Execution**: Run the compiled executable in the terminal/command prompt:

   ```bash
   ./linear_search
   ```

3. **Input**: Follow the prompts to input an array of 10 integers and a key element that you want to search for.

4. **Output**: The program will display either the index of the found key element or a message indicating that the element was not found.

### Example

```
Enter numbers: 5 12 7 23 9 15 30 8 14 3
Enter key: 15
Found at 5
```

### Note

This program uses a simple linear search algorithm to find the key element within the array. It sequentially compares the key element with each element of the array until a match is found or until all elements have been checked. While the linear search is straightforward, it's not the most efficient search algorithm for larger datasets. More efficient algorithms like binary search or hash tables could be considered for improved performance with larger inputs.

