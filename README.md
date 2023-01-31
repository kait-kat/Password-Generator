# Password-Generator

## User Story

```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security
```

## Acceptance Criteria

```
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```
## Acceptance Criteria Simplified

This project is about creating a password generator. The majority of the HTML has been done for you, all you have to do is fill in the actual generator.

* When the generate button is clicked, show the user the a series of prompts asking them for critieria. You will want to ask the following questions (it's recommended you use a `confirm` dialog unless otherwise specified):
    * What length do they want? (It's recommended you use a `prompt` for this)
    * Do they want uppercase letters? 
    * Do they want lowercase letters?
    * Do they want numeric characters?
    * Do they want special characters?
* If the user inputs invalid data (must select at least one character type, length must be between 8 and 128), then repeat the popups until they select correct data.
* Once the criteria are selected, then use a random number generator to generate the new password and place it in the given space in the HTML. There are a number of ways to do this, the instructional staff can help with hints on this if you need.