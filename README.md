House-GAN
======

Code and instructions for our paper:
[House-GAN: Relational Generative Adversarial Networks for Graph-constrained House Layout Generation](https://arxiv.org/pdf/2003.06988).

Data
------
![alt text](https://github.com/ennauata/housegan/blob/master/refs/sample.jpg "Sample")
[LIFULL HOME’s database](https://www.nii.ac.jp/dsc/idr/lifull) offers five million real floorplans, from which we retrieved 117,587. The database does not contain bubble diagrams. We used the floorplan vectorization algorithm [1] to generate the vector-graphics format, later converted into room bounding boxes and bubble diagrams. The vectorized floorplans utilized in this paper can be found [here](https://www.dropbox.com/sh/p707nojabzf0nhi/AAB4UPwW0EgHhbQuHyq60tCKa?dl=0), this dataset does not include the original RGB images from LIFULL dataset.<br/>
<br/>

[[1]](https://jiajunwu.com/papers/im2cad_iccv.pdf) Liu, C., Wu, J., Kohli, P., Furukawa, Y.:  Raster-to-vector:  Revisiting  floorplan transformation, ICCV 2017.

Running pretrained models
------
#### Coming soon

Training models
------
#### Coming soon

Acknowledgement
------
This research is partially supported by NSERC Discovery Grants, NSERC Discovery Grants Accelerator Supplements, DND/NSERC Discovery Grant Supplement, and Autodesk. We would like to thank architects and students for participating in our user study.
