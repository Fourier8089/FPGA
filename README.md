# FPGA
1.此项目采用Verilog代码编写，目的是使用vivado编写FxLMS算法，对噪声进行降噪
2.data.v 文件用于对输入信号进行延时存储，滤波器阶数为16，次级路径由d(n)=x(n-5)确定；
3.erro.v 文件用于计算误差
4.filter_out.v 文件用于计算滤波器输出
5.w_update.v 文件用于更新滤波器系数
