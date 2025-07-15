# llm-resource（LLM 百宝箱）

LLM全栈优质资源汇总

> 非常欢迎大家也参与进来，收集更多优质大模型相关资源。

## 目录

- 🐼 [LLM算法](#llm算法)
- 🐘 [LLM训练](#llm训练)
	- 🐘 [LLM微调](#llm微调)
	- 🐼 [LLM对齐](#llm对齐)
- 🔥 [LLM推理](#llm推理)
- :palm_tree: [LLM数据工程（Data Engineering）](#llm数据工程)
- 📡 [LLM压缩](#llm压缩)
- 🐰 [LLM测评](#llm测评)
- 🐘 [AI基础知识](#ai基础知识)
- 📡 [AI基础设施](#ai基础设施)
	- :palm_tree: [AI芯片](#ai芯片)
	- 🐰 [CUDA](#cuda)
- 🐘 [AI编译器](#ai编译器)
- 🐰 [AI框架](#ai框架)
- 📡 [LLM应用开发](#llm应用开发)
- 🐘 [LLMOps](#llmops)
- 📡 [LLM实践](llm实践)
- 📡[微信公众号文章集锦](#微信公众号文章集锦)



## LLM算法


### Transformer

原理：
- [Transformer模型详解（图解最完整版](https://zhuanlan.zhihu.com/p/338817680)
- [OpenAI ChatGPT（一）：十分钟读懂 Transformer](https://zhuanlan.zhihu.com/p/600773858)
- [Transformer的结构是什么样的？各个子模块各有什么作用？](https://blog.csdn.net/m0_54929869/article/details/118881804)
- [以Transformer结构为基础的大模型参数量、计算量、中间激活以及KV cache剖析](https://mp.weixin.qq.com/s/3JYz6yrLeBr5ujip3LZe6w)
- [Transformer 一起动手编码学原理](https://mp.weixin.qq.com/s/NgUNuWhvp2SqG-XWYv2PGQ)
- [为什么transformer(Bert)的多头注意力要对每一个head进行降维？](http://www.sniper97.cn/index.php/note/deep-learning/note-deep-learning/4002/)
- [Decoder-Only Transformers: The Workhorse of Generative LLMs](https://cameronrwolfe.substack.com/p/decoder-only-transformers-the-workhorse)


源码：

- [OpenAI ChatGPT（一）：Tensorflow实现Transformer](https://zhuanlan.zhihu.com/p/603243890)
- [OpenAI ChatGPT（一）：十分钟读懂 Transformer](https://zhuanlan.zhihu.com/p/600773858)
- [GPT （一）transformer原理和代码详解](https://zhuanlan.zhihu.com/p/632880248)
- [Transformer源码详解（Pytorch版本）](https://zhuanlan.zhihu.com/p/398039366)
- [搞懂Transformer结构，看这篇PyTorch实现就够了](https://zhuanlan.zhihu.com/p/339207092)



### GPT1


### GPT2


- GPT2 源码：https://github.com/huggingface/transformers/blob/main/src/transformers/models/gpt2/modeling_gpt2.py
- GPT2 源码解析：https://zhuanlan.zhihu.com/p/630970209
- nanoGPT：https://github.com/karpathy/nanoGPT/blob/master/model.py


- 7.3 GPT2模型深度解析：http://121.199.45.168:13013/7_3.html
- GPT（三）GPT2原理和代码详解: https://zhuanlan.zhihu.com/p/637782385
- GPT2参数量剖析: https://zhuanlan.zhihu.com/p/640501114


### ChatGPT

- [State of GPT：大神Andrej揭秘OpenAI大模型原理和训练过程](https://mp.weixin.qq.com/s/zmEGzm1cdXupNoqZ65h7yg)
- [OpenAI联合创始人亲自上场科普GPT，让技术小白也能理解最强AI](https://mp.weixin.qq.com/s/MD4WwwJLXm8rEm-sniX8Gw)





### GLM

- [预训练语言模型：GLM](https://zhuanlan.zhihu.com/p/641499380)


### LLaMA



### MOE 大模型

- [Mixtral-8x7B MoE大模型微调实践，超越Llama2-65B](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486657&idx=1&sn=c5a5e55b01243f477d063c9194d24f42&chksm=fd3be592ca4c6c84bf5eefff23dcc38eeb83624e9f53bbd9a72afba71e235dddf814549322ba&token=499509118&lang=zh_CN#rd)
- [大模型分布式训练并行技术（八）-MOE并行](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486145&idx=1&sn=299c28153b286465be26e18153c6db5d&chksm=fd3be392ca4c6a84be283dad80f584443302ea29fc95744f83727e7d9d68952d3a0f8b1b66d5&token=499509118&lang=zh_CN#rd)
- [MoE架构模型爆发或将带飞国产AI芯片](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247488422&idx=1&sn=eeb18ec0f5b9e972df31d65e7db13f8f&chksm=fd3bfaf5ca4c73e38a696fe7b6f33a30af962fdddfabd92d74b1d06190442759aabe7b560f22&token=499509118&lang=zh_CN#rd)
- [大模型的模型融合方法概述](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247487652&idx=1&sn=1bbf692b6e1dc6bae719c8e0a10293a0&chksm=fd3bf9f7ca4c70e16473a98d5408f6daea5e8c116a88cb3f41dfb00ffb7f6016874ee092224c&token=499509118&lang=zh_CN#rd)
- [混合专家模型 (MoE) 详解](https://zhuanlan.zhihu.com/p/674698482)
- [群魔乱舞：MoE大模型详解](https://zhuanlan.zhihu.com/p/677638939)
- [大模型LLM之混合专家模型MoE（上-基础篇）](https://zhuanlan.zhihu.com/p/672712751)
- [大模型LLM之混合专家模型MoE（下-实现篇）](https://zhuanlan.zhihu.com/p/673048264)


### 下一代大模型

- https://github.com/NExT-GPT/NExT-GPT
- https://next-gpt.github.io/
- [Introduction to NExT-GPT: Any-to-Any Multimodal Large Language Model](https://www.kdnuggets.com/introduction-to-nextgpt-anytoany-multimodal-large-language-model)



### 多模态大模型

A Survey on Multimodal Large Language Models：https://arxiv.org/pdf/2306.13549
Efficient-Multimodal-LLMs-Survey：https://github.com/lijiannuist/Efficient-Multimodal-LLMs-Survey


### 其他

- [大模型时代的归一化技术：解密Transformer架构中Pre-Norm与RMSNorm的黄金组合](https://blog.csdn.net/qq_54445177/article/details/147096307)





## LLM训练


- [分布式训练 Playbook](https://huggingface.co/spaces/nanotron/ultrascale-playbook)
- [OPT-175B是如何炼成的](https://zhuanlan.zhihu.com/p/622061951)
- [全网最全-混合精度训练原理](https://zhuanlan.zhihu.com/p/441591808)
- [飞桨分布式训练4D混合并行可训千亿级AI模型](https://ai.baidu.com/forum/topic/show/987996)
- [Transformer Math 101](https://blog.eleuther.ai/transformer-math/) - 如何计算显存消耗?
- [Megatron-LM 第三篇Paper总结——Sequence Parallelism & Selective Checkpointing](https://zhuanlan.zhihu.com/p/522198082)
- [大模型训练踩坑](https://zhuanlan.zhihu.com/p/660759033)


- 学习率(warmup, decay)：
	- [模型调优，学习率设置（Warm Up、loss自适应衰减等），batch size调优技巧，基于方差放缩初始化方法](https://blog.csdn.net/sinat_39620217/article/details/130236886)
	- [深度学习模型训练小技巧](https://blog.csdn.net/sgyuanshi/article/details/108394444)


### LLM微调

- [Adapting P-Tuning to Solve Non-English Downstream Tasks](https://developer.nvidia.com/blog/adapting-p-tuning-to-solve-non-english-downstream-tasks/)


### LLM对齐

- [MOSS-RLHF](https://github.com/OpenLMLab/MOSS-RLHF)
- [模型调优（RLHF/DPO/ORPO）- 终极指南](https://zhuanlan.zhihu.com/p/692594519)
- [DPO: Direct Preference Optimization 论文解读及代码实践](https://zhuanlan.zhihu.com/p/642569664)
- [强化学习入门：基本思想和经典算法](https://imzhanghao.com/2022/02/10/reinforcement-learning/)
- [人人都能看懂的PPO原理与源码解读](https://zhuanlan.zhihu.com/p/677607581)
- [关于Instruct GPT复现的一些细节与想法](https://zhuanlan.zhihu.com/p/609078527)
- [【RLHF】RL 究竟是如何与 LLM 做结合的？](https://zhuanlan.zhihu.com/p/675329917)
- [【RLHF】想训练ChatGPT？得先弄明白Reward Model怎么训（附源码）](https://zhuanlan.zhihu.com/p/595579042)
- [Reinforcement Learning from Human Feedback 全家桶（RL 侧）](https://zhuanlan.zhihu.com/p/700149886)

paper:

- [LLM对齐综述](https://arxiv.org/pdf/2407.16216)
- [RLHF-PPO](https://arxiv.org/pdf/2203.02155)
- [DPO](https://arxiv.org/pdf/2305.18290)
- [ORPO](https://arxiv.org/pdf/2403.07691)


## LLM推理


- [使用HuggingFace的Accelerate库加载和运行超大模型](https://zhuanlan.zhihu.com/p/605640431) : device_map、no_split_module_classes、 offload_folder、 offload_state_dict
- [借助 PyTorch，Accelerate 如何运行超大模型](https://huggingface.co/blog/accelerate-large-models)
- [使用 DeepSpeed 和 Accelerate 进行超快 BLOOM 模型推理](https://huggingface.co/blog/zh/bloom-inference-pytorch-scripts)
- [LLM七种推理服务框架总结](https://zhuanlan.zhihu.com/p/653352979)
- [LLM投机采样（Speculative Sampling）为何能加速模型推理](https://zhuanlan.zhihu.com/p/653734659)
- [大模型推理妙招—投机采样（Speculative Decoding）](https://zhuanlan.zhihu.com/p/651359908)
- https://github.com/flexflow/FlexFlow/tree/inference
- [TensorRT-LLM(3)--架构](https://zhuanlan.zhihu.com/p/665595557)
- NLP（十八）：LLM 的推理优化技术纵览：https://zhuanlan.zhihu.com/p/642412124
- ​揭秘NVIDIA大模型推理框架：TensorRT-LLM：https://zhuanlan.zhihu.com/p/680808866
- [如何生成文本: 通过 Transformers 用不同的解码方法生成文本](https://huggingface.co/blog/zh/how-to-generate) | [How to generate text: using different decoding methods for language generation with Transformers](https://huggingface.co/blog/how-to-generate)
- [DeepSeek-V3 / R1 推理系统概览](https://zhuanlan.zhihu.com/p/27181462601)



### 大模型推理优化技术


KV Cache：
- [图解大模型推理优化：KV Cache](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486956&idx=1&sn=cd5e36857bbd8ebd750d2c172550d2bd&chksm=fd3be4bfca4c6da9f2276310995c7d60a42c0d01a960a42a38226cf954bab0d2d2a5772905df&token=1409805983&lang=zh_CN#rd)
- [大模型推理百倍加速之KV cache篇](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247487886&idx=1&sn=38d3cd36c6c5acb2fe5c80ceffcba2cf&chksm=fd3bf8ddca4c71cb243566b593dfa095926b003a4a06442cc96e8ce3f2c64171b34f0bca8428&token=1409805983&lang=zh_CN#rd)
- [大模型推理加速：看图学KV Cache](https://zhuanlan.zhihu.com/p/662498827)
- [大模型推理性能优化之KV Cache解读](https://zhuanlan.zhihu.com/p/630832593)


解码优化：
- [大模型推理妙招—投机采样（Speculative Decoding）](https://zhuanlan.zhihu.com/p/651359908)




### vLLM

- [vLLM（六）源码解读下 @HelloWorld](https://zhuanlan.zhihu.com/p/694442998)
- [猛猿：图解大模型计算加速系列：vLLM源码解析1，整体架构](https://zhuanlan.zhihu.com/p/691045737)
- [LLM推理2：vLLM源码学习 @ akaihaoshuai ](https://zhuanlan.zhihu.com/p/643336063)
- [大模型推理框架 vLLM 源码解析（一）：框架概览](https://zhuanlan.zhihu.com/p/681402162)


## LLM数据工程

- [An Initial Exploration of Theoretical Support for Language Model Data Engineering. Part 1: Pretraining @
符尧](https://yaofu.notion.site/An-Initial-Exploration-of-Theoretical-Support-for-Language-Model-Data-Engineering-Part-1-Pretraini-dc480d9bf7ff4659afd8c9fb738086eb)



## LLM压缩



- [Awesome Model Quantization](https://github.com/htqin/awesome-model-quantization)
- [Efficient-LLMs-Survey](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey)
- [Awesome LLM Compression](https://github.com/HuangOwen/Awesome-LLM-Compression)
- [模型转换、模型压缩、模型加速工具汇总](https://blog.csdn.net/WZZ18191171661/article/details/99700992)
- [AI 框架部署方案之模型转换](https://zhuanlan.zhihu.com/p/396781295)
- [Pytorch 模型转 TensorRT (torch2trt 教程)](https://zhuanlan.zhihu.com/p/570822430)



## LLM测评

- [CLiB中文大模型能力评测榜单](https://github.com/jeinlee1991/chinese-llm-benchmark)
- [huggingface Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
- HELM：https://github.com/stanford-crfm/helm
- HELM：https://crfm.stanford.edu/helm/latest/
- lm-evaluation-harness：https://github.com/EleutherAI/lm-evaluation-harness/
- CLEVA：http://www.lavicleva.com/#/homepage/overview
- CLEVA：https://github.com/LaVi-Lab/CLEVA/blob/main/README_zh-CN.md



## 提示工程


- [做数据关键步骤：怎么写好prompt？](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486771&idx=1&sn=359c029b010d7ad96fff33952ad634a8&chksm=fd3be460ca4c6d76b4996f971ff21080ca0a83f3042893bb6827752ad8af812b4afeb1151af1&token=1288418017&lang=zh_CN#rd)
- [从1000+模板中总结出的10大提示工程方法助你成为提示词大师！](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486174&idx=1&sn=97ddcd5fb44eb4e3143fa746b7d617c8&chksm=fd3be38dca4c6a9b94fb88bd3f7a5009dee53812412e6f62f9f0a5955d165dd0d5f6ce698208&scene=21#wechat_redirect)
- [一文搞懂提示工程的原理及前世今生](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247485231&idx=1&sn=acfa77264da611983a49297ab8376e8f&chksm=fd3bee7cca4c676a3ccbc459e70a9e9920b08369a4d618c4ed550c96e9acd09b594cc04b21a6&scene=21#wechat_redirect)
- [Effective Prompt: 编写高质量Prompt的14个有效方法](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486087&idx=1&sn=118b82abd4b22975e9aeb9f23ed0c9c5&chksm=fd3be3d4ca4c6ac2b41f1c3e908b845d4497a84dc9741034d1e1a830cba93515439b60a835e5&scene=21#wechat_redirect)
- [提示工程和提示构造技巧](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247487107&idx=1&sn=337325ee6a9a4d4c56821b1e759f1555&chksm=fd3be7d0ca4c6ec60b6394bf76282ee3eef6beccfe2c31885cbb111a5bdc32022ba346509681&token=1288418017&lang=zh_CN#rd)
- [一文带你了解提示攻击！](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247485936&idx=1&sn=0bcc72e5bfeb50c437253626d763f67d&chksm=fd3be0a3ca4c69b52bba0e0f22730b497c56fad99444b23d437cf49262cd5e52489fb141d338&token=1288418017&lang=zh_CN#rd)



## 综合

- [通向AGI之路：大型语言模型（LLM）技术精要](https://zhuanlan.zhihu.com/p/597586623)
- [大语言模型的涌现能力：现象与解释](https://zhuanlan.zhihu.com/p/621438653)
- [NLP（十八）：LLM 的推理优化技术纵览](https://zhuanlan.zhihu.com/p/642412124)
- [并行计算3：并行计算模型](https://zhuanlan.zhihu.com/p/568947162)
- [大模型“幻觉”，看这一篇就够了 | 哈工大华为出品](https://www.thepaper.cn/newsDetail_forward_25344873)
- [深入理解语言模型的困惑度(perplexity)](https://zhuanlan.zhihu.com/p/686808564)



**safetensors**：

- [bin和safetensors区别是什么？](https://www.zhihu.com/question/629624037/answer/3307818120)
- [Safetensors：保存模型权重的新格式](https://zhuanlan.zhihu.com/p/691446249)
- [github: safetensors](https://github.com/huggingface/safetensors)
- [huggingface: safetensors](https://huggingface.co/docs/safetensors/index)
- [Safetensors: a simple, safe and faster way to store and distribute tensors.](https://medium.com/@mandalsouvik/safetensors-a-simple-and-safe-way-to-store-and-distribute-tensors-d9ba1931ba04)
- https://huggingface.co/docs/safetensors/index
- https://github.com/huggingface/safetensors/tree/v0.3.3
- [手把手教你：LLama2原始权重转HF模型](https://zhuanlan.zhihu.com/p/669158180)


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


### Huggingface Transformers




## [AI基础知识](./ai-base.md)


## AI基础设施

### AI芯片

- [业界AI加速芯片浅析（一）百度昆仑芯](https://zhuanlan.zhihu.com/p/593143821)
- NVIDIA CUDA-X AI：https://www.nvidia.cn/technologies/cuda-x/
- [Intel，Nvidia，AMD三大巨头火拼GPU与CPU](https://zhuanlan.zhihu.com/p/629024100)
- 处理器与AI芯片-Google-TPU：https://zhuanlan.zhihu.com/p/646793355
- [一文看懂国产AI芯片玩家](https://www.xckfsq.com/news/show.html?id=29187)
- [深度 | 国产AI芯片，玩家几何](https://mp.weixin.qq.com/s?__biz=MzIwMzgzNTQ1Nw==&mid=2247599349&idx=1&sn=12459cbc418d3831d0c28e87ddb71b2f&scene=21#wechat_redirect)


### CUDA

- [CUDA编程入门（一）CUDA编程模型](https://zhuanlan.zhihu.com/p/97044592)
- [CUDA编程入门（二）GPU硬件基础](https://zhuanlan.zhihu.com/p/97131966)
- [GPU编程（CUDA）](https://face2ai.com/program-blog/)
- [CUDA编程入门极简教程](https://zhuanlan.zhihu.com/p/34587739)




## AI编译器

- [TVM资料](https://github.com/BBuf/tvm_mlir_learn)
- [AI编译器原理](https://www.bilibili.com/read/cv21242696/?spm_id_from=333.999.0.0) @ZIMO酱


## LLM应用开发

- [动手学大模型应用开发](https://github.com/datawhalechina/llm-universe)
- [langchain java](https://github.com/HamaWhiteGG/langchain-java)
- [大模型主流应用RAG的介绍——从架构到技术细节](https://luxiangdong.com/2023/09/25/ragone/#/%E5%86%99%E5%9C%A8%E5%89%8D%E9%9D%A2)
- [基于检索的大语言模型和应用（陈丹琦）](https://acl2023-retrieval-lm.github.io/)
- [大模型bad case修复方案思考](https://mp.weixin.qq.com/s/xqFkfzHVnePf1ub_sCk9iw)
- [《综述：全新大语言模型驱动的Agent》——4.5万字详细解读复旦NLP和米哈游最新Agent Survey](https://zhuanlan.zhihu.com/p/656676717)




## LLMOps

- [MLOps Landscape in 2023: Top Tools and Platforms](https://neptune.ai/blog/mlops-tools-platforms-landscape)
- [What Constitutes A Large Language Model Application?  ](https://cobusgreyling.medium.com/what-constitutes-a-large-language-model-application-bacf81103475)：LLM Functionality Landscape
- [AI System @吃果冻不吐果冻皮](https://github.com/liguodongiot/ai-system)




## RAG

- https://github.com/hymie122/RAG-Survey

## 书籍

- 大语言模型原理与工程 @杨青
- [大语言模型从理论到实践](https://intro-llm.github.io/chapter/LLM-TAP.pdf) @张奇 ：https://intro-llm.github.io/
- [动手学大模型](https://github.com/Lordog/dive-into-llms?tab=readme-ov-file)

## LLM实践

- [minGPT @karpathy](https://github.com/karpathy/minGPT)
- [llm.c @karpathy](https://github.com/karpathy/llm.c): LLM training in simple, raw C/CUDA
- [LLM101n](https://github.com/karpathy/LLM101n)
- [llama2.c](https://github.com/karpathy/llama2.c): Inference Llama 2 in one file of pure C
- [nanoGPT](https://github.com/karpathy/nanoGPT)
- [Baby-Llama2-Chinese](https://github.com/DLLXW/baby-llama2-chinese)
- [从0到1构建一个MiniLLM](https://github.com/Tongjilibo/build_MiniLLM_from_scratch)
- [gpt-fast](https://github.com/pytorch-labs/gpt-fast) 、[blog](https://pytorch.org/blog/accelerating-generative-ai-2/)
- [CSE 234: Data Systems for Machine Learning](https://hao-ai-lab.github.io/cse234-w25/)
- [DSC 291: Machine Learning Systems](https://hao-ai-lab.github.io/dsc291-s24/)


## 大模型汇总资料

- [Awesome-Chinese-LLM](https://github.com/HqWu-HITCS/Awesome-Chinese-LLM)
- [Awesome-LLM-Survey](https://github.com/HqWu-HITCS/Awesome-LLM-Survey)
- [Large Language Model Course](https://github.com/mlabonne/llm-course)
- [Awesome-Quantization-Papers](https://github.com/Zhen-Dong/Awesome-Quantization-Papers)
- [Awesome Model Quantization (GitHub)](https://github.com/htqin/awesome-model-quantization)
- [Awesome Transformer Attention (GitHub)](https://github.com/cmhungsteve/Awesome-Transformer-Attention)
- [语言模型数据选择综述](https://github.com/alon-albalak/data-selection-survey)
- [Awesome Knowledge Distillation of LLM Papers](https://github.com/Tebmer/Awesome-Knowledge-Distillation-of-LLMs)
- [Awasome-Pruning @ghimiredhikura](https://github.com/ghimiredhikura/Awasome-Pruning)
- [Awesome-Pruning @he-y](https://github.com/he-y/Awesome-Pruning)
- [awesome-pruning @hrcheng1066](https://github.com/hrcheng1066/awesome-pruning)
- [Awesome-LLM-Inference](https://github.com/DefTruth/Awesome-LLM-Inference)


## 微信公众号文章集锦

- [2024年2月大模型文章集锦](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247487320&idx=2&sn=522fdf838d4ec03f24dbc7a11a3a5a65&chksm=fd3be60bca4c6f1d0c9b0643db0d7334940fb592dac3b5fbf286c7232f6bb08b968fbd237a20&scene=21#wechat_redirect)
- [2024年1月大模型文章集锦](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247487067&idx=2&sn=33594e6a82cf79a7580272c064635d75&chksm=fd3be708ca4c6e1ece0e1f6cc22bfd286bf3e9073350b91369b1d0e7fb52b50fac8113288e43&scene=21#wechat_redirect)
- [2023年12月大模型文章集锦](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486824&idx=2&sn=4faaac42f983af46cce44b35dd416c5f&chksm=fd3be43bca4c6d2d6f5fd1cf3004c37782d0b829111ad5ecd155d6cd3adedd40655653271ba1&scene=21#wechat_redirect)
- [2023年6-11月大模型文章集锦](https://mp.weixin.qq.com/s?__biz=MzU3Mzg5ODgxMg==&mid=2247486480&idx=2&sn=b6b504f9d67a3cdad5ba0eb68eee647b&chksm=fd3be543ca4c6c55e0c2fd335de92103a1aee4e5631be34f06d7557463bc7e339fb63680ad54&scene=21&poc_token=HCwA9WWjTC-CNeedW8iQ1lZwSAwg4fwWFAVcUnai)


## 其他

- [Hugging Face 博客](https://github.com/huggingface/blog/tree/main)



