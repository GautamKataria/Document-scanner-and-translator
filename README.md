# Document-scanner-and-translator:
### Motive:
##### As we all know India banned many chinese apps during recent times due to security reasons. One of those apps was Camscanner which is a document scanning app.I frequently used the app and when it got banned i started to look for alternatives. Though i found some of them i thought to myself as a student learning computer vision, why dont i try to make it myself, and maybe add some features that i thought would improve the applications functionality.

### Prerequisites:
##### Opencv, Pytesseract, numpy , googletrans 

###

### SETUP:
#####    
##### Download the following files to any folder of choice.
##### make another folder named Scanned to store the scanned images.
##### Change the tesseract.exe path from your own local machine.
###    

### Working:
#####     
##### Run the pyscanner.py file
##### give it the input of the document you waant scanned
##### Provided is an example image to apply
##### Use trackbars to alter img thresholds for the picture to detect and localize the document.
##### The document can be anything, coloured or b/w.
##### When you're happy with the detections press 's' key on your keyboard to save the image.
##### When you're done with the program, press q to exit.
###

### Outcome
##### The document would be read and printed in the command prompt, it can easily be stored in a word file or something if you really want to.
##### Same with the translated text.
##### The scanned b/w picture document would be saved in the "Scanned" folder with the name "Name of doc_scanned.jpg"

#### Notes:
##### The application can also work on live camera feed in a similar way which is a functionality here but is currently turned off for simplicity.
