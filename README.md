# Form-Validation-Site

This project focuses on implementing various form validations, dynamic field changes, and displaying the submitted form data in an HTML table.

## Form Validations

1. Validations include not null, min and max length, alphanumeric checks, and regex validations for phone number, email, and zip code.
2. The submit button remains disabled until all field validations pass.
3. Validation errors display in red text next to each field and disappear upon correction.
4. Validations are implemented on key events, not just on form submission.

## Dynamic Field Changes

1. Implemented a single select list with 5 elements.
2. An `onChange` event dynamically adds a checkbox that changes based on the selection.
3. Enabling the checkbox adds a mandatory text field, and disabling it hides the text field.

## Displaying Submitted Data

1. Upon submission, the data is displayed in an HTML table.
2. All form fields are cleared after submission.

## Additional Instructions

1. Email validation restricts the domain to '@northeastern.edu'.
2. Street Address 2 is optional, and if blank, the corresponding table value will be blank as well.

## Submission Details

- Please submit this assignment on your PRIVATE GitHub repository, using your Northeastern email account.
- Additionally, upload a zip file of the assignment on Canvas.
- Include the GitHub URL of the assignment in the Canvas remarks.

## Repository Structure

- `index.html`: Contains the HTML structure for the form and table display.
- `script.js`: JavaScript file containing form validations, dynamic field changes, and table generation logic.
- `styles.css`: CSS file for styling the form and table.
