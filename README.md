# Age Checker - Mini Project #3

This mini-project is a simple HTML file that prompts the user to enter their age and checks if they are 18 years or older. It utilizes JavaScript to handle user input and display a message based on the age provided.

## Getting Started

To use this age checker, open the provided HTML file named `index.html` in your web browser. No additional setup or installation is required.

## How to Use

1. Open the `index.html` file in your web browser.

2. The web page will display the heading "Mini Project #3" followed by a prompt dialog box.

3. The JavaScript code is embedded within the `<script>` tag after the `<h1>` element.

4. The user is prompted to enter their age using `prompt()`, and the entered value is stored in the `num` variable.

5. The code logs the type of the `num` variable, which will be "string" due to the `prompt()` function returning a string.

6. The `num` variable is then converted to a number using `Number(num)`.

7. The code logs the type of the `num` variable again, which should now be "number."

8. If the `num` variable is a truthy value (not `null`, `undefined`, `NaN`, `0`, `""`, or `false`) and the value is greater than or equal to 18, it updates the content of the `<h4>` element with the ID `elem` to display the message "You are 18 or older!!!"

9. If the `num` variable is not a valid number or less than 18, no message is displayed on the web page.

## Code Details

The implementation uses HTML and JavaScript to prompt the user for their age and determine if they are 18 years or older.

### JavaScript Logic

The JavaScript code inside the `<script>` tag prompts the user to enter their age using `prompt()` and stores the input in the `num` variable.

It logs the type of the `num` variable, which will initially be "string" due to the input from `prompt()`.

The `num` variable is then converted to a number using `Number(num)` so that arithmetic operations can be performed on it.

It logs the type of the `num` variable again, which should now be "number" after the conversion.

If the `num` variable is a truthy value and its value is greater than or equal to 18, it selects the `<h4>` element with the ID `elem` using `document.getElementById("elem")` and updates its content to display the message "You are 18 or older!!!"
