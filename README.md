# 1-2-1
1-2-1: Renaissance of Single-Network Paradigm for Virtual Try-On

[Shuliang Ning*](https://ningshuliang.github.io/),
[Xiaodong Gu*](https://scholar.google.com.hk/citations?user=aJPO514AAAAJ&hl=zh-CN&oi=ao),
[Qi Zuo*](https://scholar.google.com/citations?view_op=list_works&hl=en&user=UDnHe2IAAAAJ),
[Yipeng Qin](https://profiles.cardiff.ac.uk/staff/qiny16),
[Lingteng Qiu](https://lingtengqiu.github.io/),
[Zilong Dong#](https://scholar.google.com/citations?user=GHOQKCwAAAAJ&hl=zh-CN&oi=ao),
[Xiaoguang Han#](https://gaplab.cuhk.edu.cn/)

<a href='https://ningshuliang.github.io/2023/Arxiv/index.html'><img src='https://img.shields.io/badge/Project-Page-Green'></a> <a href='https://arxiv.org/abs/2312.04534'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a> [![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://www.youtube.com/watch?v=d1nb4OfT5BM)

<img src=".\figs\teaser.png">

<!-- ## TODO :triangular_flag_on_post:

- [ ] Provide the generation trial on [ModelScope's 3D Object Generation](https://modelscope.cn/studios/Damo_XR_Lab/3D_AIGC/summary)
- [ ] Text to ND Diffusion Model
- [ ] Multiview-ND and Multiview-Albedo Diffusion Models
- [ ] Release code (The code will be public around the end of Dec.2023.) -->





<!-- ## Install

```
- System requirement: Ubuntu20.04
- Tested GPUs: A100 40G.
- Cuda 11.7
```

Install requirements using following scripts.

~~~
git clone https://github.com/ningshuliang/PICTURE.git
conda create -n picture
conda activate picture
pip install -r requirements.txt
~~~

Download the pretrained weights [baiduyun](https://pan.baidu.com/s/1J-KC9n8HGX7yXnI-jk8zZA?pwd=qpky) or [Hugging Face ](https://huggingface.co/Shuliang/PICTURE/tree/main/pretrain_models) and place it in the pretrain_models directory.

## Stage 1

~~~
cd Stage1_Text_to_Parsing
bash test.sh
~~~

## Stage 2

~~~
cd Stage2_Parsing_to_Image
bash test.sh
~~~ -->



## Architecture

![architecture](figs/pipeline.png)

## Experiments

![text-to-nd](figs/VITONHD.png)

##More video results are shown in project page. 



<!-- ## Citation	

```
@article{qiu2023richdreamer,
    title={RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D}, 
    author={Lingteng Qiu and Guanying Chen and Xiaodong Gu and Qi zuo and Mutian Xu and Yushuang Wu and Weihao Yuan and Zilong Dong and Liefeng Bo and Xiaoguang Han},
    year={2023},
    journal = {arXiv preprint arXiv:2311.16918}
}
``` -->

