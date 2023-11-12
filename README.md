# llm-resource

LLM全栈优质资源汇总

> 非常欢迎大家也参与进来，收集更多优质大模型相关资源。



## 目录


- [LLM量化](#llm量化)






## LLM 算法

### Transformer

原理：
- [Transformer模型详解（图解最完整版](https://zhuanlan.zhihu.com/p/338817680)
- [OpenAI ChatGPT（一）：十分钟读懂 Transformer](https://zhuanlan.zhihu.com/p/600773858)
- [Transformer的结构是什么样的？各个子模块各有什么作用？](https://blog.csdn.net/m0_54929869/article/details/118881804)
- [以Transformer结构为基础的大模型参数量、计算量、中间激活以及KV cache剖析](https://mp.weixin.qq.com/s/3JYz6yrLeBr5ujip3LZe6w)
- [Transformer 一起动手编码学原理](https://mp.weixin.qq.com/s/NgUNuWhvp2SqG-XWYv2PGQ)


源码：

- [OpenAI ChatGPT（一）：Tensorflow实现Transformer](https://zhuanlan.zhihu.com/p/603243890)
- [OpenAI ChatGPT（一）：十分钟读懂 Transformer](https://zhuanlan.zhihu.com/p/600773858)
- [GPT （一）transformer原理和代码详解](https://zhuanlan.zhihu.com/p/632880248)
- [Transformer源码详解（Pytorch版本）](https://zhuanlan.zhihu.com/p/398039366)
- [搞懂Transformer结构，看这篇PyTorch实现就够了](https://zhuanlan.zhihu.com/p/339207092)

### GPT


- [State of GPT：大神Andrej揭秘OpenAI大模型原理和训练过程](https://mp.weixin.qq.com/s/zmEGzm1cdXupNoqZ65h7yg)
- [OpenAI联合创始人亲自上场科普GPT，让技术小白也能理解最强AI](https://mp.weixin.qq.com/s/MD4WwwJLXm8rEm-sniX8Gw)



### GLM 

原理：
- [预训练语言模型：GLM](https://zhuanlan.zhihu.com/p/641499380)


### LLaMA




## LLM 训练

- [OPT-175B是如何炼成的](https://zhuanlan.zhihu.com/p/622061951)
- [全网最全-混合精度训练原理](https://zhuanlan.zhihu.com/p/441591808)
- [飞桨分布式训练4D混合并行可训千亿级AI模型](https://ai.baidu.com/forum/topic/show/987996)
- [Transformer Math 101](https://blog.eleuther.ai/transformer-math/) - 如何计算显存消耗?


学习率(warmup, decay)：
- [模型调优，学习率设置（Warm Up、loss自适应衰减等），batch size调优技巧，基于方差放缩初始化方法](https://blog.csdn.net/sinat_39620217/article/details/130236886)
- [深度学习模型训练小技巧](https://blog.csdn.net/sgyuanshi/article/details/108394444)


### LLM 微调方法

- [Adapting P-Tuning to Solve Non-English Downstream Tasks](https://developer.nvidia.com/blog/adapting-p-tuning-to-solve-non-english-downstream-tasks/)




### RLHF


- [MOSS-RLHF](https://github.com/OpenLMLab/MOSS-RLHF)






## LLM 推理


- [使用HuggingFace的Accelerate库加载和运行超大模型](https://zhuanlan.zhihu.com/p/605640431) : device_map、no_split_module_classes、 offload_folder、 offload_state_dict
- [使用 DeepSpeed 和 Accelerate 进行超快 BLOOM 模型推理](https://huggingface.co/blog/zh/bloom-inference-pytorch-scripts)
- [LLM七种推理服务框架总结](https://zhuanlan.zhihu.com/p/653352979)
- [LLM投机采样（Speculative Sampling）为何能加速模型推理](https://zhuanlan.zhihu.com/p/653734659)
- [大模型推理妙招—投机采样（Speculative Decoding）](https://zhuanlan.zhihu.com/p/651359908)
- https://github.com/flexflow/FlexFlow/tree/inference
- []()



## LLM 压缩


- [模型转换、模型压缩、模型加速工具汇总](https://blog.csdn.net/WZZ18191171661/article/details/99700992)
- [AI 框架部署方案之模型转换](https://zhuanlan.zhihu.com/p/396781295)
- [Pytorch 模型转 TensorRT (torch2trt 教程)](https://zhuanlan.zhihu.com/p/570822430)


### LLM量化

- [LLM 量化技术小结](https://zhuanlan.zhihu.com/p/651874446)
- [NLP（十一）：大语言模型的模型量化(INT8/INT4)技术](https://zhuanlan.zhihu.com/p/627436535)
- [LLM大语言模型量化方法介绍（一）](https://www.birentech.com/Research_nstitute_details/13.html) @壁仞







### LLM 剪枝


### LLM 蒸馏

### LLM 稀疏化

- [NLP（八）：大语言模型的稀疏化技术](https://zhuanlan.zhihu.com/p/615399255)

## LLM 应用


## AI框架

### PyTorch

- [PyTorch 源码解读系列](https://zhuanlan.zhihu.com/p/328674159) @ OpenMMLab 团队
- [[源码解析] PyTorch 分布式](https://juejin.cn/post/7026144707591815175) @ 罗西的思考
- [PyTorch 分布式(18) --- 使用 RPC 的分布式流水线并行](https://juejin.cn/post/7043601075307282462) @ 罗西的思考
- [【Pytorch】model.train() 和 model.eval() 原理与用法](https://blog.csdn.net/weixin_44211968/article/details/123774649)

### DeepSpeed

- [DeepSpeed使用指南(简略版)](https://blog.csdn.net/weixin_43301333/article/details/127237122)
- [关于Deepspeed的一些总结与心得](https://zhuanlan.zhihu.com/p/650824387)


### Megatron-LM

- [Megatron-LM 近期的改动](https://zhuanlan.zhihu.com/p/651192295)
- [深入理解 Megatron-LM（1）基础知识](https://zhuanlan.zhihu.com/p/650234985) @ 简枫
- [深入理解 Megatron-LM（2）原理介绍](https://zhuanlan.zhihu.com/p/650383289)
- [[源码解析] 模型并行分布式训练Megatron (1) --- 论文 & 基础](https://juejin.cn/post/7057837676430360584) @ 罗西的思考
- [[源码解析] 模型并行分布式训练Megatron (2) --- 整体架构](https://juejin.cn/post/7061942798957674504)
- [[细读经典]Megatron论文和代码详细分析(1)](https://zhuanlan.zhihu.com/p/366906920) @迷途小书僮​
- [[细读经典]Megatron论文和代码详细分析(2)](https://zhuanlan.zhihu.com/p/388830967)








### Megatron-DeepSpeed



## LLM 测评

- [CLiB中文大模型能力评测榜单](https://github.com/jeinlee1991/chinese-llm-benchmark)
- [huggingface Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
- HELM：https://github.com/stanford-crfm/helm
- HELM：https://crfm.stanford.edu/helm/latest/
- lm-evaluation-harness：https://github.com/EleutherAI/lm-evaluation-harness/
- CLEVA：http://www.lavicleva.com/#/homepage/overview
- CLEVA：https://github.com/LaVi-Lab/CLEVA/blob/main/README_zh-CN.md



## 应用

- [langchain java](https://github.com/HamaWhiteGG/langchain-java)


## 综合

- [通向AGI之路：大型语言模型（LLM）技术精要](https://zhuanlan.zhihu.com/p/597586623)
- [大语言模型的涌现能力：现象与解释](https://zhuanlan.zhihu.com/p/621438653)
- [NLP（十八）：LLM 的推理优化技术纵览](https://zhuanlan.zhihu.com/p/642412124)
- [并行计算3：并行计算模型](https://zhuanlan.zhihu.com/p/568947162)


### safetensors

- https://huggingface.co/docs/safetensors/index
- https://github.com/huggingface/safetensors/tree/v0.3.3



## 基础

- [入门 | 一文概览深度学习中的激活函数](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650732724&idx=4&sn=5230b8bb1811cda38ab97afb417d1613&chksm=871b3ccab06cb5dcdf0bdfadcc7ae85d8ae95588bed0b884a55ba50b76d541771104675fbb3e&scene=21#wechat_redirect)
- [NLP的四个范式](https://zhuanlan.zhihu.com/p/456951972)


## AI编译器


- [TVM资料](https://github.com/BBuf/tvm_mlir_learn)
- [AI编译器原理](https://www.bilibili.com/read/cv21242696/?spm_id_from=333.999.0.0) @ZIMO酱


## CUDA

- [CUDA编程入门（一）CUDA编程模型](https://zhuanlan.zhihu.com/p/97044592)
- [GPU编程（CUDA）](https://face2ai.com/program-blog/)


## AI 芯片

- [业界AI加速芯片浅析（一）百度昆仑芯](https://zhuanlan.zhihu.com/p/593143821)




## LLMOps

- [MLOps Landscape in 2023: Top Tools and Platforms](https://neptune.ai/blog/mlops-tools-platforms-landscape)
- [What Constitutes A Large Language Model Application?  ](https://cobusgreyling.medium.com/what-constitutes-a-large-language-model-application-bacf81103475)：LLM Functionality Landscape







