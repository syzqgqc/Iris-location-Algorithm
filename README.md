# 基于单位扇环灰度的虹膜定位算法
提出了基于单位扇环灰度的虹膜定位算法。这种方法首先利用投影法分割出一个包含瞳孔的矩形区域，根据最大类间方差法确定矩形区域的阈值，分割瞳孔。为了确定某一方向上虹膜外边界点，需要根据瞳孔中心分割出该方向上的一个扇形区域。然后以扇宽为5，计算每个扇形半环的平均灰度值，计算灰度值变化最大的位置的横坐标作为该方向上的半径。再在其他方向上确定边界点，对这些点进行筛选并进行圆的拟合，最终实现虹膜的定位。实验结果表明：采用该方法所分割的虹膜影像可以获得良好的效果，具有良好的应用和参考价值。
