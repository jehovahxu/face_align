# face_align

[主要参考知乎专栏](https://zhuanlan.zhihu.com/p/55479744)

主要使用基于[dlib](https://github.com/davisking/dlib)的[face_recognition](https://github.com/ageitgey/face_recognition)人脸检测，做人脸缩放和转正。

首先通过人脸检测来得到关键点，然后通过关键点做人脸转正，通过人眼间距来做人脸缩放，通过左眼距边界来确定剪裁图片。


