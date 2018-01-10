## Towards Automatic Wild Animal Detection in Low Quality Camera-trap Images Using Two-channeled Perceiving Residual Pyramid Networks

This paper is accepted at ICCV workshop.

[Full-text is available on CVF.](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w41/Zhu_Towards_Automatic_Wild_ICCV_2017_paper.pdf)

## Abstract

Monitoring animals in the wild without disturbing them
is possible using camera trapping framework, which is a
technique to study wildlife using automatically triggered
cameras and produces great volumes of data. However,
camera trapping collects images often result in low image
quality and includes a lot of false positives (images
without animals), which must be detection before the postprocessing
step. This paper presents a two-channeled perceiving
residual pyramid networks (TPRPN) for cameratrap
images objection. Our TPRPN model attends to generating
high-resolution and high-quality results. In order
to provide enough local information, we extract depth cue
from the original images and use two-channeled perceiving
model as input to training our networks. Finally, the
proposed three-layer residual blocks learn to merge all the
information and generate full size detection results. Besides,
we construct a new high-quality dataset with the help
of Wildlife Thailand’s Community and eMammal Organization.
Experimental results on our dataset demonstrate that
our method is superior to the existing object detection methods


## Framework
![QFramework saliency detection](https://github.com/ChunbiaoZhu/VWM/blob/master/framework.png)

## CODE

Code is available.

You can download in [here](https://github.com/ChunbiaoZhu/VWM/)


    1.Requirement:

    theano

    lasagne

    PIL 

    2.How to use
    
    Run TPRPN_demo.py, You can download in [here](https://github.com/ChunbiaoZhu/VWM/blob/master/TPRPN_demo.py)

    3.The trained model is available in [OneDrive](https://1drv.ms/u/s!Ai2piCK4u8Cygl6_aV0YKRNFuSur).

    Step1: Download the model "TPRPN.pkl.gz" .

    Step2: Put the "TPRPN.pkl.gz" in TPRPN-Master.
    
    4. Download Image folder, put your test image(*.jpg) into this folder.


## DATASET-Part1

Dataset is public.

You can download in [here](https://github.com/ChunbiaoZhu/VWM/blob/master/VWM-DATASET-Part1.zip)

## Cite this paper as:

    @InProceedings{Zhu_2017_ICCV_Workshops,
    author = {Zhu, Chunbiao and Li, Thomas H. and Li, Ge},
    title = {Towards Automatic Wild Animal Detection in Low Quality Camera-Trap Images Using Two-Channeled Perceiving Residual Pyramid Networks},
    booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
    month = {Oct},
    year = {2017}
    }


## Acknowledgements

This work was supported by the grant of National Natural Science Foundation of China (No.U1611461), Shenzhen Peacock Plan (20130408-183003656), and Science and Technology Planning Project of Guangdong Province, China (No. 2014B090910001).


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/ChunbiaoZhu/VWM/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:zhuchunbiao@pku.edu.cn>.

