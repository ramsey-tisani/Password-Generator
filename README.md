# Password-Generator

This application is a random password generator. Initially when the page loads the user will see a header(Password Generator) and a content area with a subheader (Generate Password), a blank textarea with placeholder text and two buttons (Generate Password) and (Copy to Clipboard). Also Copy to Clipboard button will be disabled when the page initially loads, as there is nothing to copy yet. Below is the area where the user will select the parameters of their password. The user will need to choose a length between 8 - 128 characters and use checkboxes to determine which character types they want to use. If the user clicks the Generate Password button and the length input is less than 8 or greater than 128 an error message will appear for 1.5 seconds. Similarly if no character types are checked this will also give the user an error message for 1.5 seconds. Once the parameters are met javascript will run the necessary functions to create and display the new password into the textarea of the HTML page and enable the button Copy to Clipboard. Clicking the Copy to Clipboard button will copy the generated password to the users clipboard allowing them to paste the new password wheregit ver they like.