# PDF-reader-using-pyttsx3
A PDF reader application made in python using pyttsx3

I use "pyttsx3" library for offline text-to-speech conversion, in addition with PyQt5 for the GUI.
For handling PDFs, I use the "PyPDF2" library

In order to use this, place a pdf file in the same directory as this file, then compile this file.
Enter the pdf name (with ".pdf") and set the voice rate and volume. Check the radio button for male voice, 
uncheck for female voice. You can also start from a particular page by typing that page in "from page" field. 
Then click SPEAK to start.

If "from page" filed is empty, it defaults to the first page(page num 0). The PDF name filed and rate filed is 
compulsory. If not entered, an error dialog box is shown. If the PDF is non-existent or is not at all a PDF, 
error is shown again.

Yeah, I know that the window is not dynamic. If I figure it out, I shall update it.
One more thing that sucks is that pyttsx3 doesn't allow us to stop the speech in between. So it has to finish 
the entire PDF before you can stop it. Or else, just close the application. PDFs with images, will not work 
obviously with images. I don't know whether its a bug or the design itself, but let me know if that is possible
to fix. Feel free to make changes to the code.

In the program, you can also modify it to speak only individual pages. Encrypted PDFs will not work 
with this program.
