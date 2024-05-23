
1) Stitch_well_image_segments was used to stitch together overlapping images of a single
organoid culture well into one large image

2) Organoid_binary_classifer was used to make the optional binary classifer capable of
distinguishing between images of shperical/cystic organoids and irregular/budded organoids

3) MASK R-CNN spherical and MASK R-CNN irregular contain the code used to train the two 
MASK R-CNN models, one for each organoid morphology. Present in the folder are the models 
themselves as well as a text file containing the link to the COCO weights used for training. 
The code for inference using each model are at the bottom of each notebook.

4) emperical_MLR_model_organoids contains the code used to train the emperical
multiple linear regression model used to infer estimated number of nuclei 
based on organoid area.