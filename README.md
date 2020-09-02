# autoencoder
The model is trained using auto encoder and a animal dataset is used for training.

Load the dataset in train.ipynb file and run all the cells as per the instructions in the file.

Once the training is done the model is saved as autoencoder.h5

Run the test.ipynb file as per the instructions written. The model saved in train.ipynb is loaded and used here.

The overall output of the test.ipynb code is that it takes the path of the image or image label and displays top "N" images which are closest to the input image.

If you further need your dataset to be clustered into K clusters then run the cells in kMeans_clustering.ipynb as per the instructions given. The training dataset will be clustured into K clusters and further it accepts the image label or path of the image as input and prints top "N" images of the cluster to which the input image belongs to.
