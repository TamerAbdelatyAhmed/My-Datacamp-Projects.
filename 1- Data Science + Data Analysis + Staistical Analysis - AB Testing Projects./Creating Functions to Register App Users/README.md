**Project Description**

Define functions to catch errors when new users register for an app!

You are a junior developer working on a registration system for a mobile app at a small startup. The product managers have asked you to improve the current sign-up flow by integrating reusable Python functions that validate user input entered into the form.

Your task is to integrate these validation functions to approve or reject sign-up attempts before account creation. Together, these existing validation functions and the new registration functions you will build will significantly improve the robustness and quality of the sign-up process, enhancing onboarding for thousands of app users.

Create a validate_user() function, using some helper validation functions to verify user input.

The function should take in the parameters: name, email, and password.
The function should call each of the helper validation functions (validate_name(), validate_email(), and validate_password()).
If any check fails, raise a ValueError with a descriptive error message about the failing validation.
If all checks pass, return True.
Now that you've validated that all the user details are correct, you want to allow users to register to the app. Create a register_user() function to handle the registration logic.

The function should take in the parameters: name, email, and password.
Inside, it should call validate_user() to ensure that the user input is valid.
If validate_user() raises a ValueError, register_user() should catch the exception and return False.
Otherwise, it should create and return a dictionary with the keys: name, email, and password.