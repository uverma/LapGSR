# LapGSR: Laplacian Reconstructive Network for Guided Thermal Super-Resolution

## Abstract
In the last few years, the fusion of multi-modal data has been widely studied for various applications such as robotics, gesture recognition, and autonomous navigation. Indeed, high-quality visual sensors are expensive, and consumer-grade sensors produce low-resolution images. Researchers have developed methods to combine RGB color images with non-visual data, such as thermal, to overcome this limitation to improve resolution. Fusing multiple modalities to produce visually appealing, high-resolution images often requires dense models with millions of parameters and a heavy computational load, which is commonly attributed to the intricate architecture of the model.
We propose LapGSR, a multimodal, lightweight, generative model incorporating Laplacian image pyramids for guided thermal super-resolution. This approach uses a Laplacian Pyramid on RGB color images to extract vital edge information, which is then used to bypass heavy feature map computation in the higher layers of the model in tandem with a combined pixel and adversarial loss. LapGSR preserves the spatial and structural details of the image while also being efficient and compact. This results in a model with significantly fewer parameters than other SOTA models while demonstrating excellent results on two cross-domain datasets viz. ULB17-VT and VGTSR datasets.

## Pre-Print
Pre-Print Available at https://arxiv.org/abs/2411.07750 

## Datasets
The work utilized publicly available standard datasets, viz. ULB17-VT ( https://zenodo.org/records/2557535 )  and VGTSR ( https://drive.google.com/drive/folders/19WLeBytRQ8IkE0Cf-s6Ejzcg9WJGBltE ). 

Please note that the link provided is for reference purposes only. All ownership and rights to the dataset belong to the original authors. Any use of the dataset should comply with the terms and conditions set by the original authors.

