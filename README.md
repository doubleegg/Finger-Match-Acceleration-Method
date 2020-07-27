# 海量指纹库匹配任务加速机制设计
- 项目灵感来源

项目设计主要解决的问题是从有可能产生污损的指纹图像中，通过特征提取算法提取方向场信息，加速在海量指纹库中与污损指纹匹配的速度。

- 项目主要内容

我们拟使用HLS对方向场的特征提取算法进行加速设计，封装成IP核以后，设计在zynq芯片上的数据通路，并通过pynq便捷的overlay来进行应用软件部分编写。提取的方向场将与测试集的方向场进行相似度比较，以评估加速器加持下的模型精确度。

- 项目的预期成果

我们将通过网络开源的指纹数据库进行方向场提取，与传统的软件效果做比较，争取达到模型吞吐率的提升，以及精度的维持甚至提高。

---
## Ref
- 用于存放参考资料，便于查阅。
---

*该项目为2020年新工科联盟-Xilinx暑期学校（Summer School）项目。*
