## Abstract

This paper addresses the challenge of dense pixel correspondence estimation between two images. This problem is closely related to optical flow estimation task where ConvNets (CNNs) have recently achieved significant progress. While optical flow methods produce very accurate results for the small pixel translation and limited appearance variation scenarios, they hardly deal with the strong geometric transformations that we consider in this work. In this paper, we propose a coarse-to-fine CNN-based framework that can leverage the advantages of optical flow approaches and extend them to the case of large transformations providing dense and subpixel accurate estimates. It is trained on synthetic transformations and demonstrates very good performance to unseen, realistic, data. Further, we apply our method to the problem of relative camera pose estimation and demonstrate that the model outperforms existing dense approaches.

## Paper

[arXiv pre-print](https://arxiv.org/abs/1810.08393)

## Video

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/xnQMEr4FbHE/0.jpg)](https://www.youtube.com/watch?v=xnQMEr4FbHE)

## Source
available soooon

## Referencing

{% raw  %}
```
@inproceedings{Melekhov+Tiulpin+Sattler+Pollefeys+Rahtu+Kannala:2018,
      title = {{DGC-Net}: Dense geometric correspondence network},
     author = {Melekhov, Iaroslav and Tiulpin, Aleksei and 
               Sattler, Torsten, and 
               Pollefeys, Marc and 
               Rahtu, Esa and Kannala, Juho},
       year = {2019},
  booktitle = {Proceedings of the IEEE Winter Conference on 
               Applications of Computer Vision (WACV)}
}
```
{% endraw  %}
