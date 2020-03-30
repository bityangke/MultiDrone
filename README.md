#Multi-Drone based Single Object Tracking with Agent Sharing Network

![VisDrone](https://github.com/VisDrone/MultiDrone/blob/master/camera.jpg)

Drone equipped with cameras can dynamically track the target in the air from a broader view compared with static cameras or moving sensors over the ground. However, it is still challenging to accurately track the target using a single drone due to several factors such as appearance variations and severe occlusions. In this paper, we collect a new Multi-Drone single Object Tracking (MDOT) dataset that consists of 92 groups of video clips with 113,918 high resolution frames taken by two drones and 63 groups of video clips with 145,875 high resolution frames taken by three drones. Besides, two evaluation metrics are specially designed for multi-drone single object tracking, i.e., automatic fusion score (AFS) and ideal fusion score (IFS). Moreover, an agent sharing network (ASNet) is proposed by self-supervised template sharing and view-aware fusion of the target from multiple drones, which can improve the tracking accuracy significantly compared with single drone tracking. Extensive experiments on MDOT show that our ASNet significantly outperforms recent state-of-the-art trackers.

![VisDrone](https://github.com/VisDrone/MultiDrone/blob/master/dataset.jpg)

# Download

The data and code will be released soon. 

# ASNet

![VisDrone](https://github.com/VisDrone/MultiDrone/blob/master/reason.png)



# Citation
Please cite this paper if you want to use it in your work.
```
@article{zhu2020multi,
  title={Multi-Drone based Single Object Tracking with Agent Sharing Network},
  author={Zhu, Pengfei and Zheng, Jiayu and Du, Dawei and Wen, Longyin and Sun, Yiming and Hu, Qinghua},
  journal={arXiv preprint arXiv:2003.06994},
  year={2020}
}
```
