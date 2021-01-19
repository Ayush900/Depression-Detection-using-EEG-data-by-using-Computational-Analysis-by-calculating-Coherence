All the Functional Connectivity Matrices for all the 5 band are saved in the folder named 
Coherence matrices.

The file named generate all the images is used to create the images from the matrices for each band
in the above mentioned folder .

The images created are saved in the same directory as the file so 
the images are moved to a seperate folder named Coherence Visual representation of Matrices of 
all the bands .

These Images are fed into a cnn model and used to calculate the validation accuracy for each band 
seperately .

The file used is named Coherence all band accuracies .
The accuracies computed out to be :
alpha = 59.26
beta = 66.67
delta = 62.96
gamma = 70.37
theta = 70.37

The top 3 accuracies came out to be from the bands beta , gamma and theta bands .

The functional connectivity matrices from these three bands were the merged and then converted and 
saved as images using the file named 
'combining the three functional connectivity matrices and converting into image data for coherence'

The images created are saved in the same directory as the file so 
the images are moved to a seperate folder named 'Coherence Final Input'.

These images were used as input to a final cnn model which is used to make the final prediction .
The Final Validation accuracy came out to be 77.78

