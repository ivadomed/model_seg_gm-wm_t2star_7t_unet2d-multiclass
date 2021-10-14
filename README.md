# Spinal cord and gray matter multiclass segmentation at 7T - T2Star 

<p align="center">
<img src="https://user-images.githubusercontent.com/77469192/137283335-e527909c-9ec2-4790-9e66-246d492fbed9.gif" />
</p>


As spinal cord images acquired at 7T usually present with higher spatial resolution, new details, different contrasts and artifacts, the model was trained to refine white matter /gray matter segmentation.


The model was trained in the Center for Magnetic Resonance in Biology and Medicine (CRMBM-CEMEREM, UMR 7339, CNRS, Aix-Marseille University - France, using [ivadomed](http://ivadomed.org/). It relies on high-resolution(0.175 x 0.175 mm2) 7T T2*-weighted images from [CRMBM-CEMEREM](https://crmbm.univ-amu.fr/topic/spinal-cord-imaging/) acquired on healthy and pathological subjects (multiple sclerosis, amyotrophic lateral sclerosis). 

The convolutional neural network segments the spinal cord (SC) and the gray matter (GM) using 2D U-Net and this model will soon be implemented in [SCT](https://spinalcordtoolbox.com/en/stable/) as *seg_gm_sc_7t_t2star* tool. (work in progress)


## Installation (work in progress): 
```bash
sct_deepseg -install-task seg_gm_sc_7t_t2star
```

## Launch segmentation (work in progress):
```bash
sct_deepseg -i NIFTI_IMAGE -task seg_gm_sc_7t_t2star
```





## Citation:

If you find this useful, please cite our work as follows:

N. J. L. Medina, C. Gros, J. Cohen-Adad, V. Callot, and A. L. Troter, “2D Multi-Class Model for Gray and White Matter Segmentation of the Cervical Spinal Cord at 7T,” ArXiv211006516 Cs Eess, Oct. 2021, Accessed: Oct. 14, 2021. [Online]. Available: http://arxiv.org/abs/2110.06516
