cv2安装方式：conda install opencv

imshow关闭方式：
cv2.waitKey(0)  # 按任意键关闭显示图片
cv2.destroyAllWindows()
cv2.waitKey(1)
cv2.waitKey(1)
cv2.waitKey(1)
cv2.waitKey(1)

顺次运行01-image argumentation.ipynb的每个代码块，可以分别实现以下功能，每个功能实现后会显示结果图像，按任意键盘键关闭。
导入模块
导入原图
查看尺寸和通道数
查看每个通道
改变三个通道数值
改变明暗
查看图谱(颜色强度的分布)
旋转
相似变换
仿射变换
投影变换

