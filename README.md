# Lora-Fog-mountain

## Description

🌴Fog-mountain is a lora model trained with screenshots of the ["Five Elements in Fog Mountain"](https://movie.douban.com/subject/30395914/) anime. It can be used to generate some scenes that conform to the style of this anime. However, because there are too few training samples, good samples can only be generated in limited scenarios.(e.g. `cloud sky, scenery, waterfall, forest, traditional Asian architecture, grass`)



⛰Below are some results displayed

<img src="https://gitee.com/develop-more/pic-bed/raw/master/img/00009-3123067695.png" alt="00009-3123067695" style="zoom:75%;" />



<img src="https://gitee.com/develop-more/pic-bed/raw/master/img/00022-2342345.png" alt="00022-2342345" style="zoom:75%;" />



<img src="https://gitee.com/develop-more/pic-bed/raw/master/img/00011-3234343.png" alt="00011-3234343" style="zoom:75%;" />



<img src="https://gitee.com/develop-more/pic-bed/raw/master/img/00015-3234343.png" alt="00011-3234344" style="zoom:75%"/>

## How to use

:book: **Note:** The fellow steps assume that you already know how to start and use `stable diffusion webui`, and manage your models

1. download this lora model and put it to your Lora file. e.g.:

   ```
   path-to-stable-diffusion-webui/models/Lora
   ```

   you can download [here](https://civitai.com/models/127130/fogmountain-or-or)

2. download **Dark Sushi Mix 大颗寿司Mix** base model and put it to your Stable Diffusion file.e.g.

   ```
   path-to-stable-diffusion-webui/models/Stable-diffusion
   ```

   you can download [here](https://civitai.com/models/24779?modelVersionId=93208)

3. start stable-diffusion-webui and try yourself prompt ,e.g.

   ```
   <lora:rog_mountain:1>rog_mountain, scenery. water, cloud sky,forest, traditional Asian architecture
   Negative prompt: human
   Steps: 50, Size: 512x512, Seed: 4325454, Model: darkSushiMixMix_225D, Version: v1.3.0, Sampler: DPM++ 2M Karras, CFG scale: 7, Model hash: cca17b08da, Hires resize: 1280x768, rog_mountain: 3864f1cc667d, Hires upscaler: Latent, Denoising strength: 0.7
   ```





### Train lora

My train datasets can be download [here](https://pan.baidu.com/s/1ID-aZiyuYLlodWR_NXTPGw?pwd=khlg 
提取码：khlg)

 you can reference fellowing website to train you own model

1. 👍https://github.com/Akegarasu/lora-scripts
2. https://zhuanlan.zhihu.com/p/618200031
3. 👍https://www.bilibili.com/video/BV1GP411U7fK/?spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=910825911a3713aa3a06c753f17b4a95

