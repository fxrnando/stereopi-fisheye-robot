StereoPi fisheye robot tutorial scripts
===========

Set of StereoPi Fisheye Robot tutorial scripts for StereoPi board with CM3/3+ inside.

Was tested in the following environment:
* Raspbian Buster (kernel 4.19.57-v7+)
* Python 3.7.3 
* OpenCV 3.4.3 (pre-compiled, 'pip' from Python Wheels)
* Picamera 1.13


Related article: https://medium.com/stereopi/a-robot-on-stereopi-part-1-fisheye-cameras-92aa56e73a94

### Ready-to-use Buster Raspbian OpenCV image (1.87Gb, needs 8Gb micro SD or eMMC):

[Google Drive](https://drive.google.com/file/d/1eIt-qJDd_aeyK72cqOgRzUGfm5TZmfMD/view?usp=sharing)

[Yandex Disk](https://yadi.sk/d/gCYA_Yy06fpJxA)

### Brief scripts description:

**1_test.py** - starts camera preview, save captured image if 'Q' button is pressed. 
align.

**2_chess_cycle.py** - takes a series of photos for stereopair calibration, shows count
down timer. You need a printed chessboard with 9x6 parameters (file "pattern.png" included).

**3_pairs_cut.py** - just cuts all captured photos to left and right images.

**4_calibration_fisheye.py** - calibrate StereoPi cameas setup using pairs from script 4.

**5_dm_tune.py** - script for fine tune of disparity map settings.

**6_dm_video.py** - builds disparity map in real time.


**7_2d_map.py** - builds 2D map from the depth map.


