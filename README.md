# -在栈板识别的数据流转的过程中，分为以下几个流程
参数定义
模板预处理
场景点云预处理
地面分割
点云聚类分割
区域精提取
二维图像边缘检测与坐标系计算
初始化变量
遍历所有行进行边缘检测
后处理：平滑占空比信号
坐标计算（调用外部逻辑）
孔洞Z方向定位与坐标转换
确定Y方向坐标
有效性处理（剔除无效NaN值）
可视化验证
提取最终配准区域
可视化结果
NDT粗配准
ICP精配准
结果可视化
参数输出
