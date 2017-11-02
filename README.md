# Matching Patches for Pollen Identification through Spatially-aware Dictionary Learning and Coding

[project page](http://www.ics.uci.edu/~skong2/recurrentDepthSeg)

![](https://github.com/aimerykong/PatchMatchingForPollenIdentification/blob/master/figures/example_demo.png)


![](https://github.com/aimerykong/PatchMatchingForPollenIdentification/blob/master/figures/patchMatchDemo.png)

  critchfieldii             |     glauca          |     mariana
:-------------------------:|:-------------------------:|:-------------------------:  
![](https://github.com/aimerykong/PatchMatchingForPollenIdentification/blob/master/figures/patches_critchfieldii_K300L0.1_D0.1_E200_B2_globalContrastNorm.png)  |  ![](https://github.com/aimerykong/PatchMatchingForPollenIdentification/blob/master/figures/patches_glauca_K300L0.1_D0.1_E200_B2_globalContrastNorm.png)   |  ![](https://github.com/aimerykong/PatchMatchingForPollenIdentification/blob/master/figures/patches_mariana_K300L0.1_D0.1_E200_B2_globalContrastNorm.png)




This folder contains demo codes for generating exemplar patch candidates in training dictionary, 
how to do viewpoint aligment, and the whole classification pipeline for our project with the following published paper.
 
    @inproceedings{kong2016spatially,
      title={Spatially aware dictionary learning and coding for fossil pollen identification},
      author={Kong, Shu and Punyasena, Surangi and Fowlkes, Charless},
      booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops},
      year={2016}
    }


The libsvm toolbox is required. Please compile it under ``libs'' directory before running the code.

The dataset is large; to download the dataset, 
please go [google drive](https://drive.google.com/folderview?id=0BxeylfSgpk1Mdk1HeVhaaEdxMEk&usp=sharing).
To run the demos, please put the downloaded folder under proper directory (refer to addpath in the script).
Note that the fossilized pollen grains are not released for now. Please stay tuned.


For questions, please contact
 
 Shu Kong (Aimery) aimerykong AT gmail com

