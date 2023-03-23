# SWJTU-OPT-SAR
###*Introduction*

**SWJTU-OPT-SAR** is a sufficiently annotated high-resolution remote sensing dataset for land use classification, which combines high-resolution RGB optical images with SAR images at a resolution of **0.5** meters.

###*Details*
SWJTU-OPT-SAR uses high-resolution optical and SAR images from Google Earth L18 products imaged during 2010/10/21-2016/8/25 with a spatial resolution of 0.5 m.

It contains 2231 pairs of images of the same area with a size of 256×256. The dataset contains two study areas, one covers an area in the longitude range of 122.836°E-122.869°E and the latitude range of 45.105°N-45.133°N, and the other with a longitude range of 110.135°E-110.160°E and latitude range of 34.593°N-34.626°N,which covering a wide range of different terrain and vegetation.The location of the study area is shown on the map below.
![exmple.png](./dataset.png)

The images in the dataset are fully labeled with pixel-level categories, including background, bare ground, vegetation, trees, houses, water, roads, and others, where the label values and category percentages are shown in the table below.

| Label | Name | Percent(%) |
| :-----:| :----: | :----: |
|0 |background |2.26|
|1 |bare ground |55.84|
|2 |low vegetation |26.55|
|3 |trees |5.29|
|4 |houses |4.39|
|5 |water |1.69|
|6 |roads |3.88|
|7 |other |0.11|

##*Dataset Organization*
The dataset are organized as:
```
├─SWJTU-OPT-SAR dataset
│  ├─label
│  │  ├─1
│  │  │    1.png
│  │  │    ……
│  │  ├─10
│  │  ├─11
│  │  ├─……
│  │  ├─HY_C
│  │  └─HY_D
│  ├─optical
│  │  ├─1
│  │  ├─10
│  │  ├─11
│  │  ├─……
│  │  ├─HY_C
│  │  └─HY_D
│  └─sar
│      ├─1
│      ├─10
│      ├─11
│      ├─……
│      ├─HY_C
│      └─HY_D
```
###*Examples of Annotated Images*
The optical images and SAR images of some typical features in the SWJTU-OPT-SAR dataset with the corresponding annotation results are shown below.
![exmple.png](./example.png)

###*Contact*
If you encounter any problem in using SWJTU-OPT-SAR dataset or have any feedback, please contact:

+ Ye Yuanxin : yeyuanxin@home.swjtu.edu.cn
+ Wei Kan : 1196581377@qq.com

###*Source Dataset*
Dataset is avaliable: 

Onedrive: https://1drv.ms/u/s!Aoqb185R1UPpgw7xhN4eO607rCPI?e=JFo4c8

BaiduYun: https://pan.baidu.com/s/1PnRq8Rpp37RTj9p14nZMiQ password:w4x3
