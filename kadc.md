





---

大模型压缩与智能


无损压缩



语言模型是强大的压缩器。

llama语言模型甚至能直接压缩图片和语音数据，且压缩比大幅超过传统压缩软件。






用更少的比特数无损描述数据需要对数据内部的规律有本质的理解。



衡量智能？

图灵测试
平均的benchmark分数（知识、代码、数据推理）

存在刷榜现象？  如何检测数据污染


衡量压缩？

什么文本上衡量压缩

没见过的、外部的文本
不同文本代表模型的不同能力



只关注基座模型--对齐之后的模型已经不是一个通用的压缩器

统一上下文长度

更长的上下文长度会在压缩效率上有优势，但是更长的上下文能力对很多beachmark没有优势。


压缩线性代表智能


压缩指标BPC



github: llm-compression-intelligence

https://github.com/hkust-nlp/llm-compression-intelligence

----

月之暗面



大模型训练的指导方阵


压缩率是衡量模型能力强弱的唯一指标 (comp model/team/work only by loss)

scaling law 有效(more valid FLOPs ,better loss)

数据质量决定模型上限 （make loss represent intelligent）



系统优化价值观

keep 投资数据
Opti  loss/人民币
trade training cost for higher inference token/s




如何优化 loss/人民币


寻找 △（loss）/人民币 代理指标





----
提升HFU 


1. Flashattention ,tp、pp/dp/sp/ep/cp

2. 正确估算 model FLOPs

3. Always-ON Profiling System



---

提升MFU 



recompute is harmful to MFU



try to reduce max activation size in the min batch

eg. DP/PP ×  SP/CP/TeraPipe 勾

where to sway vram? ddr or others devices?



--- 

提升goodput    checkpoint & fast recovery




提升goodput :  real falure cost


save cost


fialure cost



----------


大模型训练收敛问题总结分析


----


大模型训练收敛性问题分析

盘古大模型





















































































