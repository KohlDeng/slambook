Ubuntu与v2aky.com
=========================Linux basic knowledge==============================================
2021.7.31
sudo dpkg -i aa.deb
https://zhuanlan.zhihu.com/p/339632982
wget用法
wget http://cn.wordpress.org/wordpress-4.9.4-zh_CN.tar.gz

wireshark download
https://blog.csdn.net/magiclyj/article/details/77231707

visual network bridge
https://segmentfault.com/a/1190000009491002

apt-get update和apt-get upgrade的区别
https://blog.csdn.net/qq_19004627/article/details/79560818

echo $(nproc)

tar 解压缩与压缩命令
https://www.cnblogs.com/jyaray/archive/2011/04/30/2033362.html
tar –xvf file.tar
tar -xf

find/locate 寻找文件位置
mv ttt.txt test3 移动文件
python3
top/htop 查看动态
watch -n 10 nvidia-smi

卸载nvidia
sudo apt remove --purge nvidia*
sudo apt autoremove

sudo apt update
sudo aptgrade

ubuntu-drivers devices
sudo ubuntu-drivers autoinstall


卸载解压文件
zipinfo -1 文件名.zip | xargs rm -rf
tar -tf 文件名.tar | xargs rm -rf

chmod +x的意思就是给执行权限

2021.8.8
Ubuntu windows time symchronzie
https://gsy00517.github.io/ubuntu20200117085337/

vim usage
https://zhuanlan.zhihu.com/p/61515833

find/locate/history
https://www.cnblogs.com/azhqiang/p/7728756.html

2021.8.5
远程连接
ssh -p 22 deepin2@192.168.56.132
https://www.jianshu.com/p/b10c2b163100

git usage
git branch 可以提交 push 呈现出分支
git switch master
git merge dev1
https://blog.csdn.net/afei__/article/details/51567155
github ssh
https://docs.github.com/cn/github/authenticating-to-github/connecting-to-github-with-ssh
git pull

terminator 窗口分屏
https://www.cnblogs.com/phpper/p/9203932.html
=============================Project=========================================================================
2021.8.1
image sequence from video
ffmpeg
ros zed stereo camera
https://www.ncnynl.com/archives/201703/1445.html
https://blog.csdn.net/hhhhpanda/article/details/85037463#t6


cuda cudnn pytorch
https://www.cnblogs.com/booturbo/p/13960935.html
https://blog.csdn.net/wf19930209/article/details/81879514
https://blog.csdn.net/public669/article/details/98470857

yolo train
see zhihu links
https://blog.csdn.net/weixin_42731241/article/details/81352013
https://zhuanlan.zhihu.com/p/102628373
注意2种用法
./darknet detect cfg/yolov4.cfg yolov4.weights data/dog.jpg
./darknet detector test cfg/coco.data cfg/yolov3.cfg yolov3.weights data/dog.jpg

conda tenseorflow
https://blog.csdn.net/qq_42109740/article/details/105662320?spm=1001.2014.3001.5501
https://blog.csdn.net/qq_38901147/article/details/90049666
https://blog.csdn.net/u011435933/article/details/107045530/

nvidia-smi
https://www.huaweicloud.com/articles/eb2e49445b0949ec0552a83840a19752.html

YOLO踩坑：编译darknet_ros报错no matching function for call to ‘_IplImage::_IplImage(cv::Mat&)’的解决方案
https://blog.csdn.net/weixin_41855010/article/details/111402710

2020.08.06
camera lidar calibration
https://github.com/Livox-SDK/livox_camera_lidar_calibration


2021.8.9
ROS install
https://zhuanlan.zhihu.com/p/289327910

ROS camera timestamp
https://blog.csdn.net/hcx25909/article/details/9165195
ROS trajectory show
https://lightsail.blog.csdn.net/article/details/70256437

rqt_image_view
rqt_bag
rqt_console
rqt_loggerlevel
rqt_topic
rqt_service
rqt_rviz

2021.7
修改launch文件和yaml文件不需要重新编译，重新打开进程就可以

Ubuntu18.04：
视觉14讲代码
百度applo的代码
ROS的代码
Yolo代码

======================================bag/debag=============================================================================
package install

ubuntu1804解决libjasper-dev无法安装
https://blog.csdn.net/sophia_xw/article/details/95446515?ops_request_misc=&request_id=&biz_id=102&utm_term=Ubuntu18.04%E8%A7%A3%E5%86%B3libjasper-dev&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-5-95446515.first_rank_v2_pc_rank_v29

#coding=utf-8
#!/usr/bin/env python
https://blog.csdn.net/weixin_45839124/article/details/106794474
====================================Tasks arrangement=============================================================================
next week
fssim
camera lidar calibration
lidar SDK
camera SDK
4 cones
3 cones
train

