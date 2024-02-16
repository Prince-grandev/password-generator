# password-generator
This repository creates a unique password generation system.<br> 
This repository is created for Assignment 6: password generator. It contains and index.html, script.js, style.css accordingly.

### REPOSITORY DESCRIPTION

The given task involves creating a javascript code that automatically generates a password for the user.<br>
The password is created through pieces of info provided by the user such as password length & character type.


### SCREENSHOT
![proof of work](./assets/image.png)


### RELATED LINKS
[Github repository:](https://github.com/Prince-grandev/password-generator)

[Github application:](https://prince-grandev.github.io/password-generator/)

### BRIEF INTRODUCTION
This was a rather interesting project and defintely tested my knowledge of syntax, functions, arrays as well as problem solving.


### ALGORITHM

##### Step 1: Create Arrays
-Create several arrays that hold different character types.<br>
-Type of arrays: numbers, lowercased alphabets, uppercased alphabets, special characters.

##### Step 2: Create Function to vet options from User
Create a function to request various prompts from the user.<br>
-Prompt 1: Determine the number of characters the user needs for the password. (Must be between 8 and 128)<br>
-Prompt 2: Request if the user wants to include Uppercase characters<br>
    -Request if the user wants to include numbers<br>
    -Request if the user wants to include Uppercase characters<br>
    -Request if the user wants to include Lowercase characters<br>
    -Request if the user wants to include Uppercase characters<br>
    -Request if the user wants to include Special characters<br>

##### Step 3: Pick random characters from the created set of arrays
Create a function to get a random character from the given set of arrays
-Utilize random() function to get a random character from the set of arrays provided above.

##### Step 4: Generate a password for the User
Create a function to generate the created password.
 -This function must incorporate the prompts prescribed above and also run until it fills the desired number<br>
 of characters as decided by the user.

##### Step 5: Display the generated password in text area
Create a function to display the given password in text area.
-Write the generated password in the text area by referencing the given id "password".

##### Step 6: Listen for a button click event
Assign an listener function to start the whole algorithm once the generate password button is clicked.


### CONCLUSION
This exercise pushed the limits of understanding javascript. More importantly was the need to understand how to combine individual functions in order to generate the final system. I learnt alot more about function, operators and javascript syntax.