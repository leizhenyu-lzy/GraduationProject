
[双目视觉（五）立体匹配算法之动态规划全局匹配](https://blog.csdn.net/He3he3he/article/details/103599445)

[双目视觉（六）U-V视差](https://blog.csdn.net/He3he3he/article/details/105293258)

[立体匹配中的全局匹配（一）动态规划笔记](https://blog.csdn.net/chuhang_zhqr/article/details/52586793)

[视差图Disparity与深度图Depth Map的一点知识](https://blog.csdn.net/qq_15295565/article/details/105964662)

[Vanishing Point Detection检测代码学习](https://blog.csdn.net/ydy1107/article/details/121355836)

[Structure SLAM 相关论文阅读（一）：消影点/消失点/灭点检测提取](https://blog.csdn.net/ydy1107/article/details/121207450)

[使用Ransac进行消失点（Vanishing point ）检测](https://sikasjc.github.io/2018/04/27/vanishing_point/)

[车道线检测传统方法&深度学习方法概览](https://blog.csdn.net/weixin_48936263/article/details/123902963)


![](Pics/disc.png)

课题名称：基于立体视觉和深度学习的实时多车道线检测系统设计及开发

研究方向：大量的交通事故是由于司机的失误导致的，为此当前众多自动驾驶公司引入ADAS系统来辅助司机进行驾驶。在ADAS系统中有很多功能，如：车道偏离预警、车道保持辅助等，都与车道线检测密不可分。为了获得更好的检测效果，本课题将传统立体视觉技术以及深度学习相结合，提出能进一步提升多车道线实时检测的准确性和鲁棒性的算法，同时开发应对更复杂的路面及外部环境的系统。

课题简介：首先通过双目相机立体视觉方法，利用3D信息获取道路的V视差图，并通过动态规划进行消失点的估计。之后，结合RANSAC方法迭代消除异常值来拟合车道线，将其作为当前场景的先验信息。同时利用深度学习的语义分割方法，进行后处理，解决当前车道线检测工作中的局限性：分类、实例化等，实现可以获取明确车道线类别的检测系统，为后续ADAS系统功能的实现提供便利。


