# RGB-image-similarity-comparison-algorithm-


将彩色图分为三通道（RGB），并计算各自的直方图，对两幅图的RGB三通道分别进行直方图匹配，最终对三个匹配结果求平均值。
	
应用的算法：
∆k=i=1nmin(H1(i),H2(i))min(i=1nH1(i),i=1nH2(i))（见文档）
