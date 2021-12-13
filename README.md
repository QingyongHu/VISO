# Detecting and Tracking Small and Dense Moving Objects in Satellite Videos: A Benchmark

This is the official website of the **VISO** (VIdeo Satellite Objects) dataset. [[Google Drive](https://drive.google.com/file/d/1wIa52JpVn2R2OoaJHmFrYZcxmKSYJ_8k/view?usp=sharing)][[BaiduYun](https://pan.baidu.com/s/1PRz4aRfiUGulLrTRWcSVuQ)](Sharing code: viso)

### (1) Data

This dataset is a large-scale dataset for moving object detection and tracking in satellite videos, which consists of 40 
satellite videos captured by [Jilin-1 satellite platforms](http://mall.charmingglobe.com/videoIndex.html). Each image has
a resolution of 12000x5000 and contains a great number of objects with different scales. 
Four common types of vechicles, including plane, car, ship, and train, are manually-labeled. 
A total of 853,911 instances are labeled by axis-aligned bounding boxes.

<p align="center"> <img src="figs/Fig1.png" width="100%"> </p>
<p align="center"> <img src="figs/Fig2.png" width="100%"> </p>

### (2) Benchmark
We also build a new satellite video benchmark to fairly and extensively evaluate the performance of existing methods in 
several sub-tasks, including moving object detection, single-object tracking, and multi-object tracking.

- Moving Object Detection:
<p align="center"> <img src="figs/Fig3.png" width="100%"> </p>

- Single Object Tracking:
<p align="center"> <img src="figs/Fig4.png" width="50%"> </p>

- Multiple Object Tracking:
<p align="center"> <img src="figs/Fig5.png" width="100%"> </p>

### (3) Demo

<p align="center"> <a href="https://youtu.be/NctUdpQBbAU"><img src="./figs/Demo_cover_fig1.png" width="50%"></a> </p>

<p align="center"> <a href="https://youtu.be/KaabG_zrkEM"><img src="./figs/Demo_cover_fig2.png" width="50%"></a> </p>

### License
The provided dataset has been authorized by [Changguang Satellite Technology Co., Ltd.](http://www.charmingglobe.com/EWeb/index.aspx). Licensed under the CC BY-NC-SA 4.0 license, see [LICENSE](./LICENSE).


### Citation
If you find our work useful in your research, please consider citing:

  @article{yin2021detecting,
    title={Detecting and Tracking Small and Dense Moving Objects in Satellite Videos: A Benchmark},
    author={Yin, Qian and Hu, Qingyong and Liu, Hao and Zhang, Feng and Wang, Yingqian and Lin, Zaiping and An, Wei and Guo, Yulan},
    journal={IEEE Transactions on Geoscience and Remote Sensing},
    year={2021},
    publisher={IEEE}
  }

## More Repos
1. [SoTA-Point-Cloud: Deep Learning for 3D Point Clouds: A Survey](https://github.com/QingyongHu/SoTA-Point-Cloud) ![GitHub stars](https://img.shields.io/github/stars/QingyongHu/SoTA-Point-Cloud.svg?style=flat&label=Star)
2. [SensatUrban: Learning Semantics from Urban-Scale Photogrammetric Point Clouds](https://github.com/QingyongHu/SpinNet) ![GitHub stars](https://img.shields.io/github/stars/QingyongHu/SensatUrban.svg?style=flat&label=Star)
3. [3D-BoNet: Learning Object Bounding Boxes for 3D Instance Segmentation on Point Clouds](https://github.com/Yang7879/3D-BoNet) ![GitHub stars](https://img.shields.io/github/stars/Yang7879/3D-BoNet.svg?style=flat&label=Star)
4. [SpinNet: Learning a General Surface Descriptor for 3D Point Cloud Registration](https://github.com/QingyongHu/SpinNet) ![GitHub stars](https://img.shields.io/github/stars/QingyongHu/SpinNet.svg?style=flat&label=Star)
5. [SQN: Weakly-Supervised Semantic Segmentation of Large-Scale 3D Point Clouds with 1000x Fewer Labels](https://github.com/QingyongHu/SQN) ![GitHub stars](https://img.shields.io/github/stars/QingyongHu/SQN.svg?style=flat&label=Star)




