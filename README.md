# R3LIVE Dataset  
## Introduction
This project page introduce the datasets for evaluating [R3LIVE](https://github.com/hku-mars/r3live) algorithm, which include 9 rosbag files sampled with our handheld device (CAD files are also available on [github](git@github.com:ziv-lin/rxlive_handheld.git)) in HKU and HKUST campus.

## How to get?
Our datasets can be download from [Google drive](https://drive.google.com/drive/folders/15i-TRa0EA8BCbNdARVqPMDsU9JOlagVF?usp=sharing):
```
https://drive.google.com/drive/folders/15i-TRa0EA8BCbNdARVqPMDsU9JOlagVF?usp=sharing
```
or [Baidu-NetDisk [百度网盘]](https://pan.baidu.com/s/1zmVxkcwOSul8oTBwaHfuFg):
```
Link(链接)  ： https://pan.baidu.com/s/1zmVxkcwOSul8oTBwaHfuFg
Code(提取码)： wwxw
```

## Brief overview
A brief overview of these 9 sequences are shown as follows:
| No | Name | Size | Duration | Traveling length <sup>[1] | Return to origin <sup>[2] | Sensor degrade
| :-----: | ----: | :----: |  :----: |  :----: | :----: |:----: |
| 1 | degenerate_seq_00.bag   | 864.8 MB | 101 s   | 74.9 m | Yes | LiDAR, Camera |
| 2 | degenerate_seq_01.bag   | 2.1 GB   | 86 s    | 53.3 m | Yes | LiDAR
| 3 | degenerate_seq_02.bag   | 2.1 GB   | 85 s    | 75.2 m | Yes | LiDAR
| 4 | hku_campus_seq_00.bag   | 1.4 GB   | 202 s   | 190.6 m | Yes | - -
| 5 | hku_campus_seq_01.bag   | 2.2 GB   | 304 s   | 374.6 m | No  | - -
| 6 | hku_park_00.bag         | 1.8 GB   | 228 s   | 247.3 m | Yes | - -
| 7 | hku_park_01.bag         | 2.7 GB   | 351 s   | 401.8 m | Yes | - -
| 8 | hkust_campus_seq_00.bag | 7.5 GB   | 1073 s  | 1317 m | Yes | - -
| 9 | hkust_campus_seq_01.bag | 8.2 GB   | 1162 s  | 1524 m | Yes | - -

[1]: The length of traveling is calculated with the result of [R3LIVE](https://github.com/hku-mars/r3live) algorithm.<br>
[2]: We sampled the data by traveling a loop, with finally returning back to the origin (i.e., the distance between the starting and ending position is less than 10 cm).

