---
title: 脉冲编码调制PCM
published: 2026-03-24
pinned: false
description: 网络
tags: [网络]
category: 网络
author: 蓝月奈久留
draft: false
image: "./cover.webp"
---
***
### 脉冲编码
- PCM数字化过程3个步骤：（采样，量化和编码)。⭐⭐⭐
来奎斯特采样定理：如果模拟信号的最高频率为fmax，若大于等于2fmax的采样评率对其采样，就能完整回复出原始信号。   
`F=1/T≥2f_max`

### PCM计算
- 语音最高频率是4kHz，取样频率是8kHz。对语音样本用128个等级量化，因而每个样本用7bit表示。在数字信道上传输这种数字化后的语音信号的速率是7*8000=56kbps。   
“因而每个样本用7bit”怎么来的：每个样本用？bit=log_2 N N=128 

<details>
<summary>答案</summary>
</details>   