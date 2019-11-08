This project scans the receipts and classifies as publix or walmart receipts(other classifications to be done).

Notebook1: Preprocessing- This file adds gaussian blur and finds the edges and crops the image from its background.Also it adds bounding boxes around he text which makes easy for cnn to identify text. Needs pyimagesearch folder for dependencies. Other dependencies have to be installed using pi(few are specified in notebook)

Notebook2: This file has the cnn model building steps with Keras. We can change the hyperparameters and also data to increase accuracy. Currecnt accuracy after all epoches have run is 62%


Yet to do:
Data preprocessing gives the cropped image with bounding boxes. But its not fed to cnn model. We have to find ways to feed images from preprocessing step to model step
