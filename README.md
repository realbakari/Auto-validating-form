# Auto-validating-form

There are several validation functions that are defined. These functions take a single input value and check if it matches a certain pattern using regular expressions. If the input value is invalid, the function throws a ``ValidationError`` with an error message describing the problem.

The validation functions are:

- ``validateName(name)``: checks if name contains only letters (upper or lower case).
- ``validatePassword(password)``: checks if password is not empty and has a length of at least 6 characters.
- ``validateConfirmPassword(password)``: checks if password matches the password entered in the password field. This function is called when the user submits a form with a password and confirm password fields.
- ``validateEmail(email)``: checks if email has a valid email format.
- ``validateUsername(username)``: checks if username contains only letters, digits, dots and underscores.
- ``validateDay(day)``: checks if day is a number between 0 and 99.
- ``validateYear(year)``: checks if year is a four-digit number.
- ``validatePhoneNumber(phoneNumber)``: checks if phoneNumber is a valid phone number. This function supports both formatted and non-formatted phone numbers.
