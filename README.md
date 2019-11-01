# Generative Multi-View Human Action Recognition
This repository contains code for our International Conference on Computer Vision (ICCV) 2019 paper: [Generative Multi View Human Action Recognition](https://github.com/wanglichenxj/Generative-Multi-View-Human-Action-Recognition/blob/master/representation/ICCV19_MulitView_ActionRecognition.pdf) (GMVAR). 

## Introduction
<div align="center">
    <img src="presentation/concept_1.png", width="450">
</div>

Multi-view action recognition targets to integrate complementary information from different views to improve classification performance. It is a challenging task due to the distinct gap between heterogeneous feature domains. Moreover, most existing methods neglect to consider the incomplete multi-view data, which limits their potential compatibility in real-world applications.

<div align="center">
    <img src="presentation/framework_1.png", width="1000">
</div>

In this work, we propose a Generative Multi-View Action Recognition (GMVAR) framework to address the challenges above. The adversarial generative network is leveraged to generate one view conditioning on the other view, which fully explores the latent connections in both intra-view and cross-view aspects. Our approach enhances the model robustness by employing adversarial training, and naturally handles the incomplete view case by imputing the missing data. Moreover, an effective View Correlation Discovery Network (VCDN) is proposed to further fuse the multi-view information in a higher-level label space. Extensive experiments demonstrate the effectiveness of our proposed approach by comparing with state-of-the-art algorithms.

## Code & datasets
### Datasets
The datasets utilized in our experiments are provided in this repository. They are UWA dataset, MHAD dataset and DHA dataset.


## Authors
Welcome to send us Emails if you have any questions about the code and our work :-)
* **Lichen Wang** [Website](https://sites.google.com/site/lichenwang123/)
* **Zhengming Ding** [Website](http://allanding.net/)
* **Zhiqiang Tao** [Website](http://ztao.cc/)
* **Yunyu Liu** [Website](https://wenwen0319.github.io/)
* **Yun Raymond Fu** [Website](http://www1.ece.neu.edu/~yunfu/)

## Citation
Please cite our paper if you like or use our work for your research, thank you very much!
```
@inproceedings{VCDN_lichen1,
  title={Generative Multi-View Human Action Recognition},
  author={Wang, Lichen and Ding, Zhengming and Tao, Zhiqiang and Liu, Yunyu and Fu, Yun},
  booktitle={Proc. IEEE International Conference on Computer Vision},
  year={2019},
  organization={}
}
```










