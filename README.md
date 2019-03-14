
一：图像处理-3D卷积
1.磁共振成像中用于皮质下分割的三维全卷积网络：一项大规模研究
3D fully convolutional networks for subcortical segmentation in MRI:A large-scale study
https://github.com/josedolz/3D-F-CNN-BrainStruct
2.基于长距离二维背景的三维卷积神经网络肿瘤分割
3D convolutional neural networks for tumor segmentation using long-range 2D context
https://github.com/PawelMlynarski（目前是空的）
3.





   在讨论卷积核的维度的时候，是不把channel维加进去的（或者说，卷积核的维度指的的进行滑窗操作的维度，而滑窗操作是不在channel维度上进行的，因为每个channel共享同一个滑窗位置, 但每个channel上的卷积核权重是独立的）。
   所以2D conv的卷积核其实是(c, k_h, k_w)，3D conv的卷积核就是(c, k_d, k_h, k_w)，
   其中k_d就是多出来的第三维，根据具体应用，在视频中就是时间维，在CT图像中就是层数维。

   3d卷积中，3∗3∗3大小的卷积核效果最好，深度为3的卷积核效果最好
   
   
   
   
   
   
