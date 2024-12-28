Interactive  Form Validator:

A dynamic and user-friendly interactive form validation project designed to ensure smooth data entry with real-time feedback.

Features

Real-time password matching validation.
Dynamic dropdown updates for Degree and Department selection.
Comprehensive input validation using HTML5 features and custom JavaScript logic.
Visually appealing and interactive UI with styled error messages.

Installation

Follow these steps to install and set up the project locally:

git clone https://github.com/Gladson-dev/Interactive_valid_form.git
cd interactive-valid-form
npm install
npm start

Key Features

HTML Structure

The form contains fields such as First Name, Middle Name, Last Name, Gender (radio buttons), Address, Zip Code, Country (dropdown), Phone Number (dropdown and text input), Email, Password (with specific pattern), Degree, Department, and College information.
The fields are structured with labels and input fields. Each input is either a text box, radio button, dropdown, or password input.
Each section of the form is followed by a "Submit" and "Clear" button.

CSS Styling

The form has been styled to appear centered on the page within a light green container with rounded corners.
Input fields are styled with a width of 20-40%, padding, and border-radius for a smooth appearance.
The background of the page features an image to enhance the visual appeal, making the form more interactive.

Error messages (styled in red) are shown when the input validation fails.
Each dropdown and input field has consistent styling with rounded corners and padding to make the form look clean.

JavaScript Validation

Password Matching

There is a password confirmation feature where the script checks if the password and the re-entered password match.
If they don't match, an error message is displayed, and the form field is marked invalid.

Degree and Department Dropdown Logic

The script dynamically updates the options in the "Department" dropdown based on the selected degree.
For instance, if the user selects "PhD," the department options change to specific research fields like AI, Quantum Computing, etc. If "B.E" is selected, technical department options like Computer Science and Electronics are displayed.

Input Validations

The form uses HTML5 input validation features such as:
required attributes to ensure that the user cannot submit the form without filling out certain fields.
pattern attributes for fields like Zip Code and Phone Number to match specific formats (e.g., Zip Code must be exactly 6 digits).
type="email" for validating the email format and type="password" with a password pattern ensuring that the password contains uppercase, lowercase, a digit, and a special character.
Custom validation is used for password confirmation to ensure that the two password fields match before submission.

Interactive Feedback

The user is immediately alerted with error messages for fields like password mismatch, ensuring an interactive and user-friendly experience.
Real-time updates to the department options based on degree selection allow for a smoother, more dynamic form experience.

Enhancements

Error Messages: While there is an error span in the HTML (<span class="error" id="f_name_error"></span>), there is no clear logic to display them dynamically except for the password mismatch. 

For output reference:
(https://github.com/user-attachments/files/18265623/Interactive-form-validation-MINI-project.1.pdf)
