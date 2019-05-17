# landmark_extraction

Python code to automatically extract landarmarks in nifti segmentations.

The code finds the z-axis orientation from the segmentation header, and places three landmarks for each specified label. The landmarks are placed in the bottom, medium and top voxel labelled with the label of interest along the z-direction.
