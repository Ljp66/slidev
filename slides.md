---
theme: penguin
colorSchema: 'auto'
layout: intro
highlighter: shiki
aspectRatio: '16/9'
themeConfig:
  logoHeader: '/logo.svg'
css: unocss
download: true
---

# 自我介绍

😊

大家好！我是**李嘉鹏**，**嘉**是嘉峪关的嘉，**鹏**是大鹏鸟的鹏。

很荣幸能加入这个大家庭，成为公司的一员。

--- 
layout: two-cols
--- 

# 家乡

我家在**河南省长垣市**，靠近黄河的一个村子里。

* 长垣历史最悠久的特色产业是烹饪，它是第一个获得“**中国烹饪之乡**”的县。
* 最早的工业是防腐，国家最重要的工程基本都靠长垣人搞防腐，一柄刷子刷出了“**中国防腐蚀之都**”。
* 长垣是医疗器材的主要供应地，**中国卫生材料生产基地**，主要供应的就是**口罩**。疫情这几年，包括中国乃至全世界，可能用的多半都是长垣生产的口罩。

::right::

在上大学之前我几乎没有出过长垣市，报志愿的时候我想到相对远一点的地方看看，然后选了好多外省的学校，最后上了吉林的**东北电力大学**。

上一年找工作的时候，我投了许多公司，这是**第一家**愿意要我的公司。听辅导员说**福建省能源石化集团**待遇不错，这里到我家的距离和吉林差不多，所以我就来到了这里。

<img src="/changyuan.png" width="270" height="300" alt="长垣市" />

---

# 工作与生活

* 我日常工作学习还是比较认真勤劳，会优先完成工作。
* 在业余时间，我热衷于探索计算机、网上冲浪，了解计算机科技和世界各地的新鲜事物，拓宽视野。
* 当然，我也喜欢看`bilibili`，玩王者荣耀，打羽毛球和乒乓球等。

---
layout: text-image
media: '/curve_error_band.png'
caption: '代码运行结果'
---

# Python

```python
import numpy as np
import matplotlib.pyplot as plt

N = 400
t = np.linspace(0, 2*np.pi, N)
r = 0.5 + np.cos(t)
x, y = r * np.cos(t), r * np.sin(t)

fig, ax = plt.subplots()
ax.plot(x, y, "k")
ax.set(aspect=1)
fig.savefig("curve_error_band.png")
plt.show()
```

---

# math

将上述代码归纳为数学表达：
$$
t\in(0 \thicksim 2\pi)
$$
$$
r = 0.5 + \cos(t)
$$
$$
x = r * \cos(t)
$$
$$
y = r * \sin(t)
$$
即：
$$
x^2 + y^2 = (0.5 + \cos(t))^2
$$

---

# ChatGPT

[OpenAI创始人亲临！解惑ChatGPT！！【TED演讲】](https://www.bilibili.com/video/BV1jg4y1A7AU/)

GPT4现在可以使用浏览器、插件、代码解释器、上传文件……

* 浏览器让GPT4可以结合网络信息回答问题；
* 插件将GPT4的能力进行拓展延伸；
* 代码解释器可以运行GPT4回答产生的代码；
* 上传文件可以让GPT4与文件内容交互。

---
layout: end
---