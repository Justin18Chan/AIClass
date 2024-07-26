# Stable Diffusion

[TOC]

## 0. 背景

2022年，Stable Diffusion模型横空出世，成为AI行业从传统深度学习时代走向AIGC时代的标志性模型之一，并为工业界、投资界、学术界和竞赛界都注入了新的AI想象空间，让AI再次“性感”。

Stable Diffusion（简称SD）是AI绘画领域的一个核心模型，能够进行文生图（txt2img）和图生图（img2img）等图像生成任务。与Midjourney不同的是，Stable Diffusion是一个完全开源的项目（模型、代码、训练数据、论文、生态等全部开源），这使得其能快速构建强大繁荣的上下游生态（AI绘画社区、基于SD的自训练AI绘画模型、丰富的辅助AI绘画工具与插件等），并且吸引了越来越多的AI绘画爱好者加入其中，与AI行业从业者一起推动AIGC领域的发展与普惠。


## 1. 资源


### 1.1 论文

SD1 论文: [High-Resolution Image Synthesis with Latent Diffusion Models](./paper/2112.10752v2.pdf)
[原文地址](https://arxiv.org/abs/2112.10752)
[中文翻译](https://mp.weixin.qq.com/s?__biz=Mzk0MzIzODM5MA==&mid=2247486384&idx=1&sn=2d95accb08d2ae33ccd7c06cdda46167&chksm=c337b629f4403f3f3dde71d9a1c58f9a5badf141ac4f83702e2177e65bd0bb671819ae523423#rd)

SD3 论文: [Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](./paper/Stable+Diffusion+3+Paper.pdf)
[原文地址](https://stabilityai-public-packages.s3.us-west-2.amazonaws.com/Stable_Diffusion_3_Paper.pdf)




SD Turbo技术报告: [Adversarial Diffusion Distillation](./paper/adversarial_diffusion_distillation.pdf)
[原文地址](https://static1.squarespace.com/static/6213c340453c3f502425776e/t/65663480a92fba51d0e1023f/1701197769659/adversarial_diffusion_distillation.pdf)



### 1.2 项目

1) 官方项目

SD 1.4官方项目：[CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion)
SD 1.5官方项目：[runwayml/stable-diffusion](https://github.com/runwayml/stable-diffusion)
SD 2.x官方项目：[Stability-AI/stablediffusion](https://github.com/Stability-AI/stablediffusion)
SD 3.x官网: [stable-diffusion-3](https://stability.ai/news/stable-diffusion-3)



diffusers库中的SD代码pipelines：[diffusers/pipelines/stable_diffusion](https://github.com/huggingface/diffusers/tree/main/src/diffusers/pipelines/stable_diffusion)
SD web 项目: [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
1) 其它项目

- 训练项目
 
【重点推荐】**SD-Train**
通过网盘分享的文件：SD-Train
链接: https://pan.baidu.com/s/1qsuUxFdw6BpIGbErc0303w?pwd=d7ze 提取码: d7ze 
--来自百度网盘超级会员v5的分享


- 组件项目
  **[ComfyUI 控制面板](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file)**
  **[汉化 ComfyUI 中文语言包](https://github.com/AIGODLIKE/AIGODLIKE-ComfyUI-Translation)**
  > 语言包设置方法：
  * 将 ZIP 包解压到 ComfyUI\custom_nodes 目录中：
  * 进入设置中心切换语言为中文


### 1.3 模型

1) Hugging Face
**Stable Diffusion 3**:
[stable-diffusion-3-medium](https://huggingface.co/stabilityai/stable-diffusion-3-medium)

Stable Diffusion第三方模型资源：[civitai](https://civitai.com/) (全球最全的SD模型资源库)

**WeThinkIn_SD_真人模型**
通过网盘分享的文件：WeThinkIn_SD_真人模型.safetensors
链接: https://pan.baidu.com/s/1cdFiq7EBPL5bNiHh8jQIYA?pwd=v7y2 提取码: v7y2 
--来自百度网盘超级会员v5的分享




### 1.4 数据

**小丑女数据集**
coolharley_data
通过网盘分享的文件：coolharley_data
链接: https://pan.baidu.com/s/1Ea6MCzfPMN0lYQXPgIYJdA?pwd=9rjr 提取码: 9rjr 
--来自百度网盘超级会员v5的分享

**宝可梦数据集**
通过网盘分享的文件：pokemon_data
链接: https://pan.baidu.com/s/11IBFZ8Z3iFjDpRrM8uzGkw?pwd=44gx 提取码: 44gx 
--来自百度网盘超级会员v5的分享


### 1.5 网络结构

**SD网络结构图**
链接: https://pan.baidu.com/s/1Dp_N7Lu0jSVc-IwNJkqzfA?pwd=fd2k 提取码: fd2k 

- [SD CLIP Encoder网络结构图](./imgs/network_structure/SD_CLIP_Encoder_structure.png)
- [SD VAE网络结构图](./imgs/network_structure/SD_VAE_structure.png)
- [SD U-Net网络结构图](./imgs/network_structure/SD_U-Net_structure.png)


### 1.6 其它


Stable Diffusion热门社区 [reddit/StableDiffusion](https://www.reddit.com/r/StableDiffusion/) （全球讨论最激烈的SD资讯论坛）



## 2. 文章资料

* [深入浅出完整解析Stable Diffusion（SD）核心基础知识](https://zhuanlan.zhihu.com/p/632809634)【重点推荐】
* [Stable Diffusion 3 论文及源码概览](https://zhuanlan.zhihu.com/p/708691681)【重点推荐】
* [文生图模型之Stable Diffusion](https://zhuanlan.zhihu.com/p/617134893)【重点推荐】
* [Stable Diffusion 训练指南 (LyCORIS)](https://ericfu.me/stable-diffusion-finetune-guide/)【重点推荐】
* [stable diffusion组成以及diffusion过程](http://proanimer.com/2023/10/05/stable-diffusion%E7%BB%84%E6%88%90%E4%BB%A5%E5%8F%8Adiffusion%E8%BF%87%E7%A8%8B/)
* [Stable Diffusion（SD）核心基础知识——（文生图、图生图）](https://blog.csdn.net/weixin_47748259/article/details/135502977)
* [Stable Diffusion 原理介绍与源码分析（一）](https://zhuanlan.zhihu.com/p/613337342)【重点推荐】
* [Stable Diffusion之核心基础知识和网络结构解析](https://blog.csdn.net/weixin_43056275/article/details/137050956)【重点推荐】
* [Stable Diffusion模型LoRA的本地训练（微调）方法](https://zhuanlan.zhihu.com/p/619348969)
* [零基础读懂Stable Diffusion（I）：怎么组成](https://zhuanlan.zhihu.com/p/597247221) [【英文原文】](https://jalammar.github.io/illustrated-stable-diffusion/)
* [零基础读懂Stable Diffusion（II）：怎么训练](https://zhuanlan.zhihu.com/p/597732415)
* [零基础读懂Stable Diffusion（III）：怎么控制](https://zhuanlan.zhihu.com/p/598070109)