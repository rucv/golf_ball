# Efficient Golf Ball Detection and Tracking Based on Convolutional Neural Networks and Kalman Filter 

We borrow the codes and implementations from [jwyang-faster-rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0), the Pytorch version is 1.0, pleaes refer to [jwyang-faster-rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0) for more details of setups and implementations.

## Approach
Below is the framework of proposed method:

<div style="color:#0000FF" align="center">
<img src="images/Process.png" width="430"/>
</div>

## Dataset
The dataset link is [golf_ball](https://drive.google.com/file/d/10pzr6mDQPlrylIHg8CdXzHkF4WBMZxfn/view?usp=sharing).

## Results
Some tracking results are shown below:
<div style="color:#0000FF" align="center">
<img src="images/Golf_10.png" width="430"/><img src="images/Golf_16.png" width="430"/>
</div>

## Citation
    @article{jjfaster2rcnn,
        Author = {Jianwei Yang and Jiasen Lu and Dhruv Batra and Devi Parikh},
        Title = {A Faster Pytorch Implementation of Faster R-CNN},
        Journal = {https://github.com/jwyang/faster-rcnn.pytorch},
        Year = {2017}
    }

    @inproceedings{renNIPS15fasterrcnn,
        Author = {Shaoqing Ren and Kaiming He and Ross Girshick and Jian Sun},
        Title = {Faster {R-CNN}: Towards Real-Time Object Detection
                 with Region Proposal Networks},
        Booktitle = {Advances in Neural Information Processing Systems ({NIPS})},
        Year = {2015}
    }

    @article{zhang2020efficient,
      title={Efficient Golf Ball Detection and Tracking Based on Convolutional Neural Networks and Kalman Filter},
      author={Zhang, Tianxiao and Zhang, Xiaohan and Yang, Yiju and Wang, Zongbo and Wang, Guanghui},
      journal={arXiv preprint arXiv:2012.09393},
      year={2020}
}
