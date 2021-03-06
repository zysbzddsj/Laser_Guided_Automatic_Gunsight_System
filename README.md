# Laser Guided Automatic Gunsight System

项目名称：激光引导自动炮瞄系统

完成时间：2016年5月

项目内容：本次作业我们通过灰度梯度加上圆度检测的方法来摄像机视野中的圆形激光光斑，并实现双目摄像机的三维坐标测量算法获得激光光斑的三维坐标。我们使用玩具手枪、舵机、云台搭建了具有两个自由度的炮台装置。在得到激光光斑的坐标后，我们根据子弹的运动方程求解出炮台所需的水平偏转角和仰角，再通过Arduino单片机驱动舵机旋转到指定角度。最终通过第三个舵机的旋转带动与扳机相连的细线扣动扳机进行发射。炮台操作中，我们只需要帮主炮台进行上膛动作，使用激光笔指定炮台位置和目标位置，剩下的工作全部由炮台自动完成，即激光引导自动炮瞄系统。

完成情况：三人团队合作实现，项目历时三周，我们较为出色地完成了我们开始预期的结果。在项目进行的过程中，团队合作能力，动手能力和编程能力得到了极大的提升，同时了解了更多计算机图形学和计算机视觉方面的技术。

本人负责：主控程序实现(平台为Visual Studio C++和Arduino SDK)，代码调试和视频拍摄。

主要技术：C++/MATLAB/OpenCV库/Qt/Arduino单片机/SolidWorks/3D打印

项目主页：http://staff.ustc.edu.cn/~lgliu/Courses/ComputerGraphics_2016_spring-summer/Projects/index3.html （包含视频，代码和总结报告）
