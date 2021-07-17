# One_Tap_Updater
AN OCR APP THAT AUTOMATES FORM UPDATES (Isolated OCR for Handwritten Text)

Many organizations like banks and insurance companies give customers empty forms to submit their applications. The applicants fill in the applications and submit them. But eventually, the data from these forms are needed to be fed into the machine. Our product can help these organizations in updating the contents of these forms in spreadsheets with just a single ‘tap’. In this project, we considered a particular case and shown how this system can work for updating the submitted college registration forms. 

We have used image processing techniques like dilation, adaptive thresholding, Gaussian to remove noises and used contours to detect the boxes in the form. We trained these boxes on a modified Resnet architecture to get the final model.
