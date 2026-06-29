# preservationofspringfestival
中国春节民俗艺术传承平台 非遗传承系统 计算机毕业设计

所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。



<font style="color:rgb(17, 124, 238);">🎈</font><font style="color:rgb(17, 124, 238);">系统亮点：AI问答、协同过滤算法、可分享链接、Echarts图形化分析、接入腾讯地图、二维码扫描；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">后端使用Java编程语言的Spring boot框架</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);"></font>



<font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue3 ；UI库：Element-Plus；   
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis-plus、Spring boot框架；   
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2025版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现（部分截图）</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204716967-573f8763-8b76-4d68-b28e-e8cfc692fb2a.png)

## 2.1 普通用户
### 2.1.1 首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/45326128/1782204723162-d3c21547-294b-4248-9c15-a5d0cec3cd1b.jpeg)

### 2.1.2 首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204731287-1ab7252b-d4c3-4d21-a6dc-4e9d638995dc.png)

### 2.1.3 民俗资讯详情
 作者信息的文章总阅读数是当前作者所有资讯的浏览量总和，最上方的阅读数是当前文章的阅读量。协同过滤算法在“为你推荐”。

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204739547-0c32afe7-1c04-4e93-bfb7-340f48bbe361.png)

### 2.1.4 民俗活动
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204743161-ac409f0f-bf39-461b-ac9b-434f890254ac.png)

### 2.1.5 民俗活动详情
"相关活动"为协同过滤算法推荐。

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/45326128/1782204749218-e18952fb-57f3-4aaf-aea8-1b2d676ddcad.jpeg)

### 2.1.6 实践任务
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204764592-a63490d7-a55b-4389-b6a5-4e40d5592ce5.png)

### 2.1.7 提交实践任务
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/45326128/1782204770213-9acc102b-04d6-443c-a5ca-6bab15ea7139.jpeg)

### 2.1.8 权益兑换
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204777963-80e7b038-c9b1-48d6-9d55-535da30ef19e.png)

### 2.1.9 AI问答
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204780967-935ed563-bc15-4bd3-bf6d-06409dcb4548.png)

### 2.1.10 我的报名
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204783630-7f3325b2-4f21-4c57-8e61-de38b4fecbce.png)

### 2.1.11 我的收藏
### <!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204800148-db5b7d3f-588f-4604-9aef-ade46690dc70.png)2.1.12 我的举报
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204802991-aad5a809-8754-4ec6-bfb3-1ef90a07772e.png)

### 2.1.13任务提交
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204809391-d37f6800-2e8b-433e-8499-f0897974c483.png)

### 2.1.14 传承值明细
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204808922-4e9c388d-d0a9-4266-8ea3-7e96fc79c0f2.png)

### 2.1.15 兑换记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204813523-417d13dc-ed69-4c6f-b426-365170857194.png)

### 2.1.16 我的证书
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204815682-4eb6e9c7-dfef-4548-a706-82a03eba8339.png)

## 2.2 传承人
普通用户的基础功能 传承人都有，额外功能如下：

### 2.2.1 资讯管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204818841-f9b52b58-b2ec-4038-a4f2-cb77b15909d8.png)

## 2.3 文化机构管理员
普通用户的基础功能 ，文化机构管理员都有，额外功能如下：

### 2.3.1 活动管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204821805-2f68052d-3a7a-48cd-95fd-398064a2085a.png)

### 2.3.2 报名管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204824743-ab252c1e-8d90-497f-beeb-93b91de53607.png)

## 2.4 	平台超级管理员
### 2.4.1 用户管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204827236-bb15a512-cfee-4317-b076-92d16707e8c3.png)

### 2.4.2 用户统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204837982-25a1bc85-997c-42d4-a23c-3e39a2062890.png)

### 2.4.3 民俗资讯管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204922273-3f6a92fe-0b39-4eaf-860d-022821e9eea8.png)

### 2.4.4民俗资讯统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204924844-879d5309-fbbf-4c91-ba7b-fa4f0325b6d7.png)

### 2.4.5 民俗活动管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204928150-ee419a64-a44f-4a22-ba22-8d873f77bcc4.png)

### 2.4.6 民俗活动统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204931225-8f2d0b29-b673-4a4e-bf22-4259db8e4da6.png)

### 2.4.7 民俗活动报名管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204935255-fb1bb46b-f05b-4c65-8d5b-ef7009378359.png)

### 2.4.8 报名统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204937925-7da8ed31-0205-4df1-a5d3-4433f2369555.png)

### 2.4.9 民俗活动评价
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204940438-76077dd1-3911-408c-b9a9-8dbf9b56d6c9.png)

### 2.4.10 签到记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204942960-cc4ce36d-b724-484b-a715-7991da94d605.png)

### 2.4.11 民俗资讯评论
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204945835-c269fa38-d07c-461d-a600-f9de256dbaf7.png)

### 2.4.12 民俗资讯点赞记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204971466-87bb08fe-a037-4ded-a438-e7c5e1c0ffcc.png)

### 2.4.13 民俗资讯收藏记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204977911-622ba152-36aa-4efa-bc90-d76b668b5559.png)

### 2.4.14 传承人管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204980942-b2adb4b3-aba9-4ef7-af17-000b7bd9068f.png)

### 2.4.15 传承值明细
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204984010-f068ceed-2d0d-4e67-b356-6fc8382262d7.png)

### 2.4.16 传承值统计
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204986851-fe470d73-c5ac-4d38-ac0b-2521214c0dfd.png)

### 2.4.17 电子证书
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204990136-efeab295-4416-4d07-9114-452105a3b69c.png)

### 2.4.18 实践任务管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204994109-c4bb3196-2888-44a4-ab3e-326ce3e896c6.png)

### 2.4.19 任务提交
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204997017-e9dc18b5-a83d-43fa-82b9-235b6fdc3d1d.png)

### 2.4.20 权益商品
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782204999770-3b40ee59-9f92-4c4a-80d2-467bc2f3a37f.png)

### 2.4.21 兑换记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205002389-5f93602e-b870-49e1-8125-710b4f2a394d.png)

### 2.4.22 快速审核
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205005712-30622f54-203e-4dec-911c-aa1105f3be39.png)

### 2.4.23 审核记录
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205008199-cac30f2c-9b26-47c1-968c-94562c6dd45f.png)

### 2.4.24 用户举报
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205010760-a48f3ded-6683-4a99-b96b-12944396ed04.png)

### 2.4.25 关键词过滤
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205013443-08166b87-0a3d-44bc-98a0-114a3af40439.png)

### 2.4.26 文化机构管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205020218-a4167ccc-cfe7-44ba-9b11-070aabf169c3.png)

### 2.4.27 地域类型
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205023619-e6998b83-cb71-46db-99aa-02803f91fbf9.png)

### 2.4.28 AI知识库管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205026259-6070b19a-f7e5-422d-b15c-3aac12e7beb0.png)

# <font style="color:rgb(72, 179, 120);">三.系统代码结构截图</font>
## <font style="color:rgb(38, 38, 38);">3.1 前端</font>
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205029519-04dfe6d4-c2ec-4209-8a8b-f57098596222.png)

## 3.2 后端
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205032507-ed744232-ba8a-4e5a-b8bf-2432b3341f6c.png)

## 3.3 数据库
29张表结构

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1782205034680-64132b96-387a-469b-ae9c-25d254e9fbfd.png)

# <font style="color:rgb(72, 179, 120);">四.</font><font style="color:rgb(26, 173, 25);">源码获取</font>
<font style="color:rgb(0, 0, 0);">1.原创系统非商用，非开源，非无偿。</font>

<font style="color:rgb(0, 0, 0);">2.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>



