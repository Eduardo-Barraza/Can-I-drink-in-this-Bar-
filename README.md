### 1. **User Input**
   - **Lesson**: How to collect input from the user using the `input()` function.
   - **Details**: The program uses `input()` to ask the user for their age and drink choice, demonstrating how to gather and use user-provided information.
   ```python
   age = int(input("What is your age? "))
   drink_choice = int(input("What would you like to drink? Enter the number (1, 2, or 3): "))
   ```

### 2. **Conditional Statements**
   - **Lesson**: How to use `if`, `elif`, and `else` statements to make decisions in the program.
   - **Details**: The program checks the user's age to determine if they can enter the bar and uses additional conditions to determine the drink choice and calculate the bill.
   ```python
   if age >= 21:
       # Allow entry
   else:
       # Deny entry
   ```

### 3. **Variable Assignment**
   - **Lesson**: How to assign values to variables and use them later in the program.
   - **Details**: Variables like `age`, `drink_choice`, and `bill` are used to store and manipulate data.
   ```python
   bill = 0
   ```

### 4. **Print Statements**
   - **Lesson**: How to use the `print()` function to display messages to the user.
   - **Details**: The program uses `print()` to display welcome messages, menu options, and the final bill.
   ```python
   print("Welcome to the bar!")
   print(f"Your final bill is ${bill}")
   ```

### 5. **Data Conversion**
   - **Lesson**: How to convert data types, such as converting user input from a string to an integer.
   - **Details**: The `input()` function returns a string, so the program converts this input to an integer using `int()`.
   ```python
   age = int(input("What is your age? "))
   ```

### 6. **Basic Arithmetic**
   - **Lesson**: How to perform arithmetic operations to calculate values.
   - **Details**: The program calculates the total bill based on the user's drink choice.
   ```python
   if drink_choice == 1:
       bill = 5
   elif drink_choice == 2:
       bill = 7
   elif drink_choice == 3:
       bill = 30
   ```

### 7. **Error Handling for Invalid Input**
   - **Lesson**: How to handle invalid input using conditional statements.
   - **Details**: The program includes a condition to check for invalid drink choices and prints an appropriate message.
   ```python
   else:
       print("Invalid choice. Please choose a valid drink next time.")
   ```

### 8. **String Interpolation**
   - **Lesson**: How to use f-strings for string interpolation to include variables in strings.
   - **Details**: The program uses f-strings to include the final bill amount in the output message.
   ```python
   print(f"Your final bill is ${bill}")
 
