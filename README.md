# Cloud and Shadow Masking

Follows the method proposed in "Cloud/shadow detection based on spectral indices for multi/hyperspectral optical remote sensing imagery" (Zhai et al. 2018) (https://www.sciencedirect.com/science/article/abs/pii/S0924271618301989?via%3Dihub) 

NOTE: I have not yet included a spatial matching code block. That's because I want the dark areas and water to be masked out, which is what the spatial matching aims to prevent. Feel free to add this. I might add it later as an option.

Input is as explained in the second code block in the notebook.

The mask is shown before the image is actually masked. This allows you to adjust the parameters to optimize the mask.
