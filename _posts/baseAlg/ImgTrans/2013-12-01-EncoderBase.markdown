---
title: 图像编码基本概念
date: 2015-01-01 11:02:00
categories: fbImgT
---

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

### 概述

   数字通信模型中有信道编码和信源编码，其中信道编码的主要任务是解决信息传输的可靠性问题。信源编码的主要任务是解决信息表达的有效性问题。而图像编码属于信源编码的范畴，目的是研究数码压缩率，即高效编码问题。图像编码方法分类如下：

<center><img src="{{ site.baseurl }}/images/pdBase/encoder_a1.png"></center>
   
---

### 图像中的冗余信息

* 视觉冗余：人类视觉系统不敏感或不能感知的那部分图像信息；
						
* 空间冗余：图像内部相邻像素之间存在相关性；

* 时间冗余：图像序列的不同帧之间存在大量的相关性；	
							
* 信息熵冗余：编码冗余，如果图像中平均每个像素使用的比特数大于该图像的信息熵H，则图像中存在冗余；

* 结构冗余：图像全局或不同部分之间存在很强的纹理结构多自相似性；					

* 知识冗余：某些图像中还包含于某些先验知识有关的信息；

---
       
### 图像编码评价

<center><img src="{{ site.baseurl }}/images/pdBase/encoder_a2.png"></center>

---

### 数据压缩方法概括

<center><img src="{{ site.baseurl }}/images/pdBase/encoder_a3.png"></center>
