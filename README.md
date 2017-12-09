# PR_work2
生成两个均包含 N =1000个两维随机矢量的数据集合 X和 X'，数据集合中的随机矢量来自于三个模型，它们分别满足均值矢量为m1=[1,1]^T, m_2=[4,4]^T,
m_3=[8,1]^T和协方差矩阵为S_1=S_2=S_3=2I的正态分布，
其中I是 2*2的单位矩阵。在生成数据集合 X时，假设类别的先验概率相同；
而在生成数据集合 X 时，假设类别的先验概率由矢量P = 〖[0.6,0.3,0.1]〗^T 给出。
分别画出两个数据集合的随机矢量散布图；
使用数据集合X，分别估计属于三个模型随机矢量的均值和协方差矩阵；
解释模型与参数估计值间存在差异的原因。

使用作业一所生成的两个数据集合， 完成下述工作：
1. 在两个数据集合上分别应用“似然率测试规则”、“贝叶斯风险规则”（其中C_12 = 2，
C_13 = 3， C_23=2.5， C_11=C_22=C_33=0 ， C_21=C_31=C_32=1、“最大后验概率规
则” 和“最短欧氏距离规则” 进行模式分类实验， 给出实验过程设计和实验结果。
2. 对每个数据集合给出每种分类器的分类错误率，并给出你的结论。