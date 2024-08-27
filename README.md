# Password Generator
This is a simple Password Generator web application that allows users to generate random passwords based on selected criteria. The application is built using HTML, CSS, and JavaScript.


### Features
Generate random passwords of varying lengths.
Include/exclude uppercase letters, lowercase letters, numbers, and special characters.
Copy the generated password to the clipboard with a single click.
Responsive design, works on both desktop and mobile devices.
Live Demo
You can check out the live demo of the Password Generator here.

### Technologies Used
###### HTML: For the structure of the web page.
###### CSS: For styling the web page, including layout and responsiveness.
###### JavaScript: For the functionality of the password generator.
###### Setup




##### You can simply double-click the index.html file, or use a local server like Live Server in VSCode.
#### Usage
Open the Password Generator in your web browser.
Select the desired password criteria:
Length of the password.
Include/exclude uppercase letters.
Include/exclude lowercase letters.
Include/exclude numbers.
Include/exclude special characters.
Click the Generate Password button.
The generated password will be displayed in the output box.
Click the Copy to Clipboard button to copy the password.


#### Problems Encountered
###### During the development of this Password Generator, several challenges were encountered:

###### Ensuring Unique Character Selection: One of the main challenges was ensuring that the password generator would select characters from all chosen character sets (uppercase, lowercase, numbers, special characters). Initially, there was a tendency for the generator to favor certain character types over others, leading to less secure passwords.

###### Solution: Implemented logic to guarantee that at least one character from each selected set is included in the password.

###### Responsive Design Issues: Creating a responsive design that looked good on both desktop and mobile devices was challenging, especially when it came to the layout of the form and buttons.

###### Solution: Used CSS Flexbox and media queries to adjust the layout based on the screen size, ensuring a user-friendly experience across devices.

###### Copy to Clipboard Functionality: Implementing the "Copy to Clipboard" feature was tricky due to varying support across different browsers.
