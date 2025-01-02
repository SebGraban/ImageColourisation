# ImageColourisation

In order to train the models the fit function has to be called, to do this it is necessary to ensure that enough GPU VRAM is available.

Model Autencoder requires around 4GB of VRAM.
Model U-Net requires around 16GB of VRAM. 

The U-Net model was to large to include in the dataset; therefore, we have the fit function inside the notebook, but beware it is computationally expensive to train. 

