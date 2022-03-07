# composite_materials_quality_inspection

## 现场应用的问题总结
### 对于拼缝边缘特征检测效果稳定性的提升
1. 根据相机硬件相对于铺接头相对位置固定的特点，所采集的点云在相机坐标系中的x,y,z三个轴方向的变化也相对固定——可以先对采集的点云做一个变化校正，使得铺接前进的方向沿着x轴或者y轴的方向，z轴垂直于铺丝铺带的整体平面，根据预设的工艺参数，沿着x轴或者y轴设定一个滑动窗口进行检测判断——降低误判率

### 对于多余物检测效果的提升
1. 

### 对于检测效率实时性的提升
1. 高效得遍历点云的方法：[blog](https://blog.csdn.net/weixin_30482181/article/details/101291202)
2. 点云并行加速计算方法：OpenMP, [GPU](https://github.com/PointCloudLibrary/pcl/blob/master/gpu/features/test/test_normals.cpp), CUDA

## 数据通讯
1. python socket通讯，[blog](https://blog.csdn.net/sinat_36645384/article/details/79128137)
2. python读取软件存储的数据库
3. modbus入门，[blog](http://www.elecfans.com/rengongzhineng/596297.html)
