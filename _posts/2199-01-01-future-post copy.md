---
title: 'Future Blog Post'
date: 2199-01-01
permalink: /posts/2012/08/blog-post-4/
tags:
  - cool posts
  - category1
  - category2
---

# 《Learnable Privacy-Preserving Anonymization for Pedestrian Images》

- privacy-utility trade-off: 将Anonymization与**Person Re-identification**(行人重识别)任务相结合
- 以传统方法处理后的图像做监督，不是face swap
- 同时给出了anonymization encoder, recovery decoder & Re-ID model, 并且三者是同时训练
- supervision upgradation:为了更好的privacy protection & Re-ID performance采用不断升级监督图像的方法

```
The supervision is upgraded by replacing the original desensitized
images with the learned anonymized images, which are constrained
by both privacy protection and Re-ID performance.
```

- 在训练Re-ID model时采用raw image & anonymized image混合训练的策略
- 两个图像质量评估指标：PSNR & SSIM

# 《Denoising Diffusion Implicit Models》

- [reference](https://zhuanlan.zhihu.com/p/639540034)