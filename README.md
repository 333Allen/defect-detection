# 缺陷检测
用于无纺布缺陷检测的halcon视觉识别。

do.hdev为一段自研的halcon视觉缺陷检测代码。通过频域、空间域的转换和傅里叶变换等处理之后，得到剔除背景的图片。然后经过一定的预处理和blob处理，在多次尝试后找到一个能够较准确地识别缺陷、鲁棒性较高的视觉处理方法。
同时，这里列举了五张无纺布缺陷检测的测试图。

# 缺陷分类
检测出缺陷后，将带有缺陷的区域截取出来，于是后续就可以利用我们开发的分类算法来将不同缺陷识别并区分开来。
