---
title: 海明码
published: 2026-03-28
pinned: false
description: 网络
tags: [网络]
category: 网络
author: 蓝月奈久留
draft: false
image: "./cover.webp"
---
***
### 海明码
- 海明码是检测盒纠正差错的编码方式
- 海明距离：一个码子要变成另一个码字时必须改变的最小位数。两个码字之间不痛的比特数。
![alt text](image.png)

### 海明不等式⭐（CRC）
- 海明不等式：满足 __2^k-1≥m+k（m为信息位，m+k为编码后的数总长度__）
### 海明编码方法（1
![alt text](image-1.png)

![alt text](image-2.png)
即可补充出来结果为
![alt text](image-3.png)
只能纠正一位错误
![alt text](image-4.png)

## 练习
![alt text](image-5.png)
<details>
<summary>答案</summary>
D
B
![alt text](image-6.png)
</details>  

***
***
![alt text](image-7.png)
<details>
<summary>答案</summary>
用海明不等式
</details>  

***
***
![alt text](image-8.png)
<details>
<summary>答案</summary>
S总=110，转为10进制为6，表示第六位出错
</details>

***
***
![alt text](image-9.png)
<details>
<summary>答案</summary>
C0=1+0+1+0+1=1（这里是用偶数，所以得变多1个1凑偶数）
C1=0+1++0+1=0
C2=0
C123=101，结果十进制为5，第5位出错
c
</details>
