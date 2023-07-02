## Triangle Formation Checker

This program determines if a triangle can be formed with the given lengths of its three sides. The program prompts the user to enter the lengths of the three sides and checks if they satisfy the condition for triangle formation. 

### Program Execution

1. The program prompts the user to enter the length of the first side of the triangle.
2. The program prompts the user to enter the length of the second side of the triangle.
3. The program prompts the user to enter the length of the third side of the triangle.
4. The program checks if a triangle can be formed by calling the `isValidTriangle()` function.
5. If the lengths of the sides satisfy the condition for triangle formation, the message "The triangle can be formed." is displayed.
6. If the lengths of the sides do not satisfy the condition for triangle formation, the message "Those values do not form a triangle." is displayed.

### Function

The program uses the `isValidTriangle()` function to check if a triangle can be formed. The function takes in three arguments: `sideA`, `sideB`, and `sideC`, which represent the lengths of the three sides of the triangle. The function returns a boolean value:

- `true` if the lengths of the sides satisfy the condition for triangle formation.
- `false` if the lengths of the sides do not satisfy the condition for triangle formation.

### How to Run

To run the program, open the HTML file in a web browser. The program will display prompts for entering the lengths of the triangle sides, and the result will be displayed in the HTML element with the ID `myDiv1`. Test it on this link: https://triangleformationchecker.netlify.app/
