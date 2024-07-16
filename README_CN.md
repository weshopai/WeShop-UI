<p align="left">
    中文</a>&nbsp ｜ &nbsp<a href="README.md">English</a>&nbsp
</p>

# Weshop_UI_1.0.0 简介

欢迎体验 Weshop_UI_1.0.0！这是一款由[weshop.com](https://www.weshop.com)推出的开源软件，专注于利用人工智能技术生成图像。WeShop_UI_1.0.0 从在线版本中提炼出商业和专业功能，去除了一些不兼容的元素，并且正在逐步向公众开放源代码。我们致力于在保持核心业务产品的同时，推动AI图像创造领域的创新与合作。WeShop UI拥有多任务管理功能，并且界面简洁友好，非常适合初学者使用。

# 概述

WeShop_UI_1.0.0 是[weshop.com](https://www.weshop.com)的开源版本，它能够在本地环境中运行[weshop.com](https://www.weshop.com)的核心功能。这款软件采用Stable Diffusion Webui作为其主要的推理引擎，使得用户能够在本地生成高质量的AI图像，而无需依赖网络或云服务。

# 更新日志

* 2024.07 正式发布 WeShop UI 1.0.0

# 开源计划

目前，我们已经将 Web 前端、Electron 前端以及对 Automatic1111 的 Stable Diffusion WebUI 的改动开源。以下是我们的开源计划和未来规划概览：

- [x] 保持使用 https://github.com/AUTOMATIC1111/stable-diffusion-webui 上的最新版本的 Webui 
      
- [x] 开源该项目的前端部分 

- [ ] 重构并开源该项目的后端代码，目前该项目使用后端代码编译后的可执行文件

- [ ] 同时支持 ComfyUI

- [ ] 支持多 GPU 推理调度
  
- [ ] 逐步适配来自[weshop.com](https://www.weshop.com)的workflow和功能 

- [ ] 更多功能即将推出，请留下反馈和建议，帮助我们改进产品

# 功能

1. 集成 SD WebUI 功能，支持 SDXL 模型和 SDXL 的 Controlnet
   
2. 共享显卡利用率以提高性能
   
3. 拥有高效的任务管理功能
   
4. 批量任务执行，批量任务执行，组合不同参数大规模执行单个任务

# 如何在本地使用 Weshop UI
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_1.png?raw=true)

单击右下角的“启动”按钮启动工具。根据计算机的规格，启动需要一些时间。![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_2.png?raw=true)
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_3.png?raw=true)

软件启动后，会自动通过浏览器打开工作台网页。选择要执行的任务类型。目前，功能包括文本转图像 (txt2img) 和图像转图像 (img2img)。
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_4.png?raw=true)

选择图像生成的所需参数。
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_5.png?raw=true)
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_6.png?raw=true)

通过选择所需的 ControlNet 和 AfterDetailer 参数进一步细化生成。单击右下角的“生成”按钮开始生成过程。
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_7.png?raw=true)

生成过程完成后，生成的图像将很快显示。单击右上方的“再次编辑”按钮以调整参数或再次生成。
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/cn_8.png?raw=true)

对于遇到的任何错误，请单击“提交BUG”按钮，然后将发送错误信息。或者可以从我们的 Github 页面 https://github.com/weshopai/WeShop-UI 发送反馈

# 系统要求

- Windows 7 或更高系统 
  
- 8GB 显存的 Nvidia GPU
  
- 16GB 内存

# 下载

可以用以下方式下载 Weshop UI 1.0.0：

百度网盘：https://pan.baidu.com/s/11ENVMjLQFZINrYd-yJuMiw?pwd=wsui 

Steam: 即将推出

# 安装与使用

解压缩 weshop-1.0.0.zip 和 weshop-model-pack.zip

1. 将 weshop/models 替换为 weshop-model-pack/models
   
2. 将 weshop/extensions/sd-webui-controlnet/models 替换为 weshop-model-pack/extensions/sd-webui-controlnet/models
  
3. 将 weshop/extensions/sd-webui-controlnet/annotator/downloads 替换为 weshop-model-pack/extensions/sd-webui-controlnet/annotator/downloads
  
4. 单击 weshop.exe 启动 

对于 Steam 用户，请在商店中找到 WeShop_AI，然后直接通过 Steam 启动软件。

# 图库

![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/9.png?raw=true)
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/10.png?raw=true)
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/11.png?raw=true)
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/12.png?raw=true)
![alt text](https://github.com/weshopai/WeShop-UI/blob/main/screenshots/13.png?raw=true)



# 致谢 

该项目使用了以下开源项目：

<https://github.com/sgreben/http-file-server>: 用于存储程序运行过程中产生的文件

<https://github.com/pierrre/imageserver>: 用于存储程序运行过程中产生的图像文件

<https://github.com/facebookresearch/segment-anything>: 对上传的图像进行分割以创建蒙版 

<https://github.com/sczhou/CodeFormer>: 放大图像
