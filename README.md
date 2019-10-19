# ESRGAN_sobel
在ESRGAN的基础上去掉判别网络，加入边缘检测来提高精度
![image](https://github.com/sldz5/ESRGAN_sobel/blob/master/result.png)  


GT为原图，LR为4倍双三次缩小的图，ESRGAN网络模型生成的图，最后一列是本实验的生成图。  

在result文件夹中，运行python3 test.py 即可生成预测图。当然也可以修改相应的low_res来生成对应不同的测试集。
  
