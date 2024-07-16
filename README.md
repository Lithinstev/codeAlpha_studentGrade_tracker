# codeAlpha_studentGrade_tracker
# Student Grades Management Program

This Java program is designed to assist teachers in managing student grades. It allows a teacher to enter multiple student grades, store them, and then calculate and display the average, highest, and lowest grades. The program utilizes basic input and output operations, arrays (specifically `ArrayList`), and simple calculations to provide a comprehensive overview of the entered grades.

## Key Features

1. **User Input for Grades**:
    - The program prompts the teacher to enter grades for students.
    - Input continues until the teacher enters `-1`, signaling the end of input.

2. **Data Storage**:
    - Grades are stored in an `ArrayList<Double>`, which allows dynamic resizing as more grades are added.

3. **Calculations**:
    - **Average Grade**: The program calculates the average of all entered grades.
    - **Highest Grade**: It finds and displays the highest grade from the list.
    - **Lowest Grade**: It finds and displays the lowest grade from the list.

4. **Output**:
    - After processing the input, the program outputs the average, highest, and lowest grades.
    - If no grades are entered, it informs the user accordingly.

## Code Breakdown

1. **Imports**:
    - `ArrayList` for dynamic grade storage.
    - `Collections` for easy computation of maximum and minimum values.
    - `Scanner` for reading user input.

2. **Main Method**:
    - Initializes the `ArrayList` for storing grades.
    - Uses a `Scanner` to read input in a loop until `-1` is entered.
    - Calls helper methods to compute and print the average, highest, and lowest grades.
    - Closes the `Scanner` to avoid resource leaks.

3. **Helper Method**:
    - `calculateAverage` method sums up all grades and divides by the number of grades to get the average.

This program demonstrates fundamental programming concepts such as loops, conditionals, data structures, and basic input/output operations in Java, making it a useful tool for teachers and a great learning exercise for novice Java developers.
