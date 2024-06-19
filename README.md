
<img src="https://github.com/SNEIDER31LM/SwitchandFuctions/assets/169932054/9f1b9456-818c-4289-acd1-b3b4e573d86d">

# PROGRAM-HTTML
# Subject:

Programming

# Members:

* Carlos J. Chiluisa and Cristian Espinosa

# Program display

* Used language and libraries/packages: JavaScript"

# PROGRAM FUNCIONALITY
The user enters a number in the text field.
When you click the "Submit" button, the onClickSubmitButton() function is called.
The function obtains the entered value, converts it to a number, and displays an alert depending on whether the number is greater than, less than, or equal to zero. If the value entered is not a valid number, it displays an alert indicating that a valid number must be entered.

# CODE EXPLANATION
let inputValue = document.getElementById('InputText').value;:

Corrects uppercase "D" in document to lowercase "d."
Gets the value of the text field with the ID InputText.
let numberValue = Number(inputValue);:

Converts the value of inputValue to a number. This is important because the value obtained from the text field is a text string by default.
if (numberValue > 0) {...}:

Checks if the numeric value is greater than zero and displays an alert if so.
else if (numberValue < 0) {...}:

Checks if the numeric value is less than zero and displays an alert if so.
else if (numberValue === 0) {...}:

Checks if the numeric value is equal to zero and displays an alert if so.
the rest { ... }:

Add an additional check to ensure that the value entered is a valid number. If it is not, it displays an alert indicating that a valid number must be entered.


# CAPTURE OF THE EXECUTION AND FUNCTIONALITY OF THE PROGRAM
<img src="https://github.com/CarlosJoels/PROGRAM-HTTML/assets/169932054/9246ff39-822b-45f6-b727-a7af623ec98b">


