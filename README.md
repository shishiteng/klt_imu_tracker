# klt_imu_tracker

 这个一个imu辅助的光流跟踪实现，项目来自与CMU，下面是项目主页：
    http://www.cs.cmu.edu/~myung/IMU_KLT/index.html#source

# 依赖：
 OpenCV(这里用了2.4)
 CUDA
 Intel IPP (Integrated Performance Primitives)
 CMAKE

# 编译
 原来的版本是在ubuntu10下运行的，现在在ubuntu14下可以运行(IPP的部分API有变动)

# 运行
 cd ./bin
 ./klt_tracker f ./data_desk_scene.cfg

# 其他
 代码中有cpu和gpu的实现，默认使用的gpu
 用我自己的数据集可以跑起来，但是效果不好，需要debug
