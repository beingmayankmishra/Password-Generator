

## Random Password Generator

Random Password Generator
This is a random password generator built using HTML, CSS, and JavaScript. It lets you create secure passwords of any length with options to include uppercase letters, lowercase letters, numbers, and symbols.

Features
Adjustable Length: You can set how long the password should be.
Custom Character Options: Choose which types of characters to include (uppercase, lowercase, numbers, symbols).
Password Strength Indicator: Shows whether the password is weak, medium, or strong.
Copy to Clipboard: Easily copy the generated password with a click.
Dynamic Updates: The password updates automatically as you change settings.
How It Works
Set Password Length: Use the slider to adjust the password length.

Choose Characters: Select the types of characters you want in your password (uppercase, lowercase, numbers, symbols).

Generate Password: Click the "Generate Password" button to create a new password.

Copy Password: Click the "Copy" button to copy the password to your clipboard.

Strength Indicator: A colored circle shows the strength of the password based on your selections.

Key Parts of the Code
Character Generation: Functions to create random characters for the password:

generateLowerCase(): Creates a random lowercase letter.
generateUpperCase(): Creates a random uppercase letter.
generateSymbol(): Picks a random symbol from the list.
Password Strength Check: Checks the strength of the password based on selected options and length. Updates the indicator color accordingly.

Copy to Clipboard: A function to copy the generated password to your clipboard with a message to confirm if it was successful or not.


## Live Demo

Check out the live version of the app [here](https://random-password-generatorapp.netlify.app/).
