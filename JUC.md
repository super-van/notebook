# JUC

参考视频

## synchronized

JUC编程通用步骤：

1. 创建资源类，在其中定义域和方法。
2. 定义任务方法：判断；做任务；通知。
3. 创建多个线程，调用资源类的任务方法。