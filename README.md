
# PowerLineSeg Dataset
## Overview
PowerLineSeg is an airborne LiDAR dataset, in which each point has X, Y, Z, Intensity, timestamp and label. It contains two parts. Part-A is mainly collected from mountains. Part-B is mainly collected from plains. This dataset is suitable for point cloud segmentation task. Especially, the domain adaptation task of point cloud segmentation. 

## Visualization
![Figure 1](https://user-images.githubusercontent.com/85683381/121547848-180a2300-ca3f-11eb-9380-965629cc6579.jpg)
As shown in this figure, this dataset includes four categories: Powerline, Tower, Insulator, and Ground. Ground points account for more than 96.7%. Actually, the content of ground points is quite rich, including vehicles, vegetation, buildings, highways, communication towers, etc. We are further enriching the annotations of this dataset.

## Statistics
The table below shows the data distribution of the dataset. First, we divide the data into two parts according to the terrain, and then each part is further divided into the training set, validation set and test set according to the proportion.


|  | Tower | PowerLine | Insulator | Ground |
| :------: | :------: | :------: | :------: | :------: |
| Part-A train | 676k | 742k | 18k | 85710k |
| Part-A val | 355k | 490k | 8k | 39081k |
| Part-A test | 406k | 359k | 13k | 34174k |
| Part-B train | 1389k | 1378k | 52k | 52177k |
| Part-B val | 665k | 838k | 19k | 22366k |
| Part-B test | 557k | 687k | 15k | 26309k |


## Download
The link will first take you to a license agreement, and then to the data. [[ Download ]](https://forms.gle/mZwMXvAqgZPR3YUR9) 

## Citation
To be continue.

## Acknowledgements
The file organization of this dataset is the same as that of [SemanticKITTI](http://www.semantic-kitti.org/) 

## Related Link
[PointCAD](https://github.com/PowerLineSeg/PointCAD): Unsupervised domain adaptation method for Point Cloud semantic segmentation.
[torch-points3d](https://github.com/nicolas-chaulet/torch-points3d): Framework for running common deep learning models for point cloud analysis tasks.


