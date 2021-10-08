# Spinal cord and gray matter multiclass segmentation at 7T - T2Star 

<p align="center">
<img src="https://user-images.githubusercontent.com/77469192/135249501-83a5079c-057d-402d-9ddf-2d34c29ca453.gif" />
</p>

As spinal cord images acquired at 7T usually present with higher spatial resolution, new details, different contrasts and artifacts, the model was trained to refine white matter /gray matter segmentation.


The model was trained in the Center for Magnetic Resonance in Biology and Medicine (CRMBM-CEMEREM, UMR 7339, CNRS, Aix-Marseille University - France, using [ivadomed](http://ivadomed.org/). It relies on high-resolution(0.175 x 0.175 mm2) 7T T2*-weighted images from [CRMBM-CEMEREM](https://crmbm.univ-amu.fr/topic/spinal-cord-imaging/) acquired on healthy and pathological subjects (multiple sclerosis, amyotrophic lateral sclerosis). 

The convolutional neural network segments the spinal cord (SC) and the gray matter (GM) using 2D U-Net and this model is available in [SCT](https://spinalcordtoolbox.com/en/stable/) as *seg_gm_sc_7t_t2star* tool.


## Installation:
```bash
sct_deepseg -install-task seg_gm_sc_7t_t2star
```

## Launch segmentation:
```bash
sct_deepseg -i NIFTI_IMAGE -task seg_gm_sc_7t_t2star
```





## Citation:

Please cite the following refence when using this model :

---***
