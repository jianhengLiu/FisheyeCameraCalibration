# FisheyeCameraCalibration

**Step1**
`img_catcher.cpp`   保存30张含有棋盘的照片,按`q`保存.

所保存的棋盘照片应尽量凸显镜头畸变,覆盖镜头各个位置,角度等,如下

![Screenshot from 2020-11-05 15-51-17](/home/chrisliu/NewDisk/GitResposity/FisheyeCameraCalibration/README.assets/Screenshot from 2020-11-05 15-51-17.png)

**Step2**

`fisheye_calibration.cpp`   读取保存的棋盘照片获取相机内参