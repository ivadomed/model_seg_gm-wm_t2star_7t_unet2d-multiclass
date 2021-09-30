# Spinal cord and gray matter multiclass segmentation at 7T - T2Star 

![image](https://user-images.githubusercontent.com/77469192/135249501-83a5079c-057d-402d-9ddf-2d34c29ca453.gif)


As spinal cord images acquired at 7T usually present with higher spatial resolution, new details, different contrasts and artifacts, the model was trained to refine white matter /gray matter segmentation.


The model was trained in the Center for Magnetic Resonance in Biology and Medicine (CRMBM-CEMEREM, UMR 7339, CNRS, Aix-Marseille University, using ivadomed. It relies on high-resolution 7T T2*-weighted images from CRMBM-CEMEREM (https://crmbm.univ-amu.fr/topic/spinal-cord-imaging/) acquired on healthy and pathological subjects (multiple sclerosis, amyotrophic lateral sclerosis).

The convolutional neural network segments the spinal cord and the gray matter using 2D U-net.





Resolution : 0.175 x 0.175 mm2





Please cite the following refence when using the model :

---***
