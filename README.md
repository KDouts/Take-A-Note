# Take-A-Note
An application that will write and save notes

When presented to the index.html a button is supposed to redirect the page to the notes.html and it does not. 

Looking into the code I was able to find that the href for the buttom was not in the correct syntax. It was changed from /notes to notes.html.

When properly linked to the notes.html I am presented with a styleless page with two input for a note title and the body text. 

The link to the style.css was linking through the wrong folder and was easily corrected to the correct path.

Both of the html file were linking the wrong path to the index.js and a simple fix was made to properly link it.