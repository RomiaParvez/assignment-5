# Assignment 5

## Task 1: Create a Dictionary of Student Marks

### Problem Statement:
Write a Python program that:
1. Creates a dictionary where student names are keys and their marks are values.
2. Asks the user to input a student's name.
3. Retrieves and displays the corresponding marks.
4. If the student’s name is not found, display an appropriate message.

### Solution:
The program initializes a dictionary with sample student names and their marks. It then prompts the user to enter a student's name and checks if the name exists in the dictionary. If found, it prints the marks; otherwise, it displays a "Student not found" message.

### Functionality:
- A dictionary named `student_marks` is created with predefined student names and marks.
- The user is asked to enter a student’s name.
- If the name exists in the dictionary, their marks are displayed.
- If the name is not found, an appropriate message is shown.

---

## Task 2: Demonstrate List Slicing

### Problem Statement:
Write a Python program that:
1. Creates a list of numbers from 1 to 10.
2. Extracts the first five elements from the list.
3. Reverses these extracted elements.
4. Prints both the extracted list and the reversed list.

### Solution:
The program initializes a list of numbers from 1 to 10, extracts the first five elements, reverses them, and prints both lists.

### Functionality:
- A list named `numbers` is created with values from 1 to 10.
- The first five elements are extracted using list slicing (`numbers[:5]`).
- The extracted list is then reversed using slicing (`[::-1]`).
- Both the extracted list and the reversed list are displayed as output.
