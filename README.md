# Bachelor-Thesis-MM

Create data set for training:
First the raster data has to be loaded in data TIFs.
Then in the folder TIFs the notebook 10240Tif_to_256Array.ipynb need to run
This notebook makes all the tif data to numpys of shape(n,256,256,3) for the images and (n,256,256) and stores them in the folder np
this folder has to be moved in the data folder then
the numpy array then is gonna be shuffled and splitted into a training array and a validation array with the notebook: 10240Tif_to_256Array.ipynb
Afterward, pngs are generated out of the numpy arrays with the notebook numpy to png.ipynb
Finally, the notebook Oversampling.ipynb oversmaples the training set

after crating the data set the U-Net model cann be created and trained in the notebook: U-Net

the evaluation takes place in the notebook evaluation
