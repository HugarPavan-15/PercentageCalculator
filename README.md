The Percentage Calculator is a Java-based application with a graphical user interface (GUI) designed to perform various percentage-related calculations. The application allows users to calculate percentages, percentage increases/decreases, and find the whole given a part and percentage. This project emphasizes user-friendliness, accuracy, performance, and maintainability.

Features
Calculate Percentage: Determine what percentage one number is of another.
Calculate Percentage Increase: Compute the percentage increase from one number to another.
Calculate Percentage Decrease: Compute the percentage decrease from one number to another.
Find Whole: Given a part and the percentage, find the whole value.

Error Handling: Validates user inputs and provides clear error messages for invalid inputs.

User-Friendly Interface: Simple and intuitive GUI for easy usage.

Modular Code: Clean and well-documented code structure for easy maintenance and updates.

Installation and Usage
Prerequisites
Java Development Kit (JDK) 8 or higher


Copy code
git clone https://github.com/yourusername/percentage-calculator.git
Navigate to the project directory:
sh
Copy code
cd percentage-calculator

Code Structure
Main.java: Entry point of the application. Initializes and displays the GUI.
guifolder/PercentageCalculatorGUI.java: Defines the GUI layout and handles user interactions.
calculator/Calculator.java: Contains methods for performing percentage calculations.
validation/InputValidator.java: Validates user inputs to ensure they are numeric.

Detailed Documentation
User Instructions
Open the Application: Run the application 
Input Values: Enter the required numeric values in the "Input 1" and "Input 2" fields.
Select Operation: Choose the desired calculation type from the dropdown menu.
Calculate: Click the "Calculate" button to perform the calculation.
View Result: The result will be displayed next to the "Result" label.

Future Updates
The code is modular and well-documented, making it easy to add new features or modify existing ones. Future updates could include:
Additional percentage-related calculations.
Improved error handling and user feedback.
Enhanced GUI design and usability features.

Testing
The application has been thoroughly tested to ensure all calculations are correct and reliable. Unit tests for individual calculation methods and integration tests for the GUI were performed to validate the application's functionality.

Contributing
Contributions are welcome! If you have any suggestions or improvements, please submit a pull request or open an issue.
