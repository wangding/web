# 第 1 章：HTML 基础

## 阅读参考资料

- [HTML 介绍](https://developer.mozilla.org/zh-CN/docs/learn/HTML/Introduction_to_HTML)
- [IBM web 开发者中心](https://developer.ibm.com/zh/technologies/web-development/)

## 搭建开发环境

**方式一：导入虚拟机（推荐）**

- 下载并安装 vmware workstation Pro 15+（**已经安装 vmware workstation，跳过此步**）
- 下载 [mocha 虚拟机](http://pan.baidu.com/s/1o8a3E3o)压缩文件
- 解压缩 mocha 虚拟机
- 用 vmware workstation，打开解压后的 mocha 虚拟机
- 启动 mocha 虚拟机
- 登录 mocha 虚拟机，用户名：wangding，密码：ddd
- 配置 mocha 虚拟机的网卡 IP 地址，具体操作请参考：[教学视频](https://www.bilibili.com/video/bv1iy4y1y7hm)
- 确保在 mocha 虚拟机中，`ping www.baidu.com` 可以正常执行
- 下载并安装 [xshell 6](https://www.netsarang.com/zh/free-for-home-school/)
- 用 XShell 链接 mocha 虚拟机
- 配置 mocha 虚拟机的 git 参数，包括：user.name 和 user.email
- 在 GitHub 或码云创建测试仓库，确保 git 可以向远程仓库提交代码

**方式二：从头安装**

- 安装步骤请参考：[Node.js 开发环境搭建](setup-dev-env.html)
- 安装 CentOS 虚拟机，请参考：[教学视频](http://edu.51cto.com/center/course/lesson/index?id=166501)

## 熟悉开发环境的使用

- 熟悉[开发环境的使用](http://nodejs.wangding.co/env-manual.html)
- 熟悉常用的 [linux 命令用法](http://note.wangding.co/linux/centos.html)
- 熟悉 [Git 命令](http://note.wangding.co/office/git.html)的用法
- 熟悉 [vim 的用法](http://note.wangding.co/office/vim.html)

## Hello World

基本要求：
- 在[码云](https://gitee.com)上创建 html-demo 项目仓库
- 在仓库目录下，创建 01-hello-world 目录
- 在目录下添加 index.html 页面
- 页面标题为：hello world
- 页面正文为：hello HTML5!，这行文本作为 h1 元素的内容
- 将代码通过 Gitee Pages 功能发布上线
- 用浏览器测试查看发布上线的网页

示例参考：
- [hello world](https://wangding.github.io/html-demo/01-hello-world/)

## 经典回忆

- 在仓库目录下，创建 02-basic 目录
- 在目录下添加 index.html 页面
- 页面标题为：经典回忆
- 页面第一行为 h1 元素，内容是：经典回忆
- 页面正文为一句引文，这行文本作为 p 元素的内容
- 引文中有 strong 强调文字
- 引文结束后，另起一行，写出引文的出处
- 引文的出处需要加上链接，链接到该文章的百度百科词条
- 引文后面是一个跟引文内容相关的配图
- 将代码通过 Gitee Pages 功能发布上线
- 用浏览器测试查看发布上线的网页

示例参考：
- [经典回忆](https://wangding.github.io/html-demo/02-basic/)

## 古诗

- 在仓库目录下，创建 03-text-basic 目录
- 在目录下添加 01-gu-shi.html 页面
- 页面标题是古诗的名称
- 页面第一行为 h1 元素，内容是古诗的名字
- 页面正文为古诗的句子，两句放到一行，这行文本作为 p 元素的内容
- 句子之间用两个半角空格间隔（注意：应该使用空格的实体符号）
- 将代码通过 Gitee Pages 功能发布上线
- 用浏览器测试查看发布上线的网页

示例参考：
- [静夜思](https://wangding.github.io/html-demo/03-text-basic/01-jing-ye-si.html)

## 食谱

- 在 03-text-basic 目录下，添加 02-shi-pu.html 页面
- 页面标题是菜肴的名称
- 页面第一行为 h1 元素，内容是：宫保鸡丁的做法
- 页面正文为菜肴制作方法，见下面

```
宫保鸡丁，川菜系中的传统名菜，由鸡丁、干辣椒、花生米等炒制而成。由于其入口鲜辣，鸡肉的鲜嫩配合花生的香脆，广受大众欢迎。
相传宫保鸡丁是清朝光绪年间的署理四川总督丁宝桢所发明，是他招待客人时叫家厨煮的菜肴。由于丁宝桢后来被封为东宫少保（太子少保），所以被称为“丁宫保”，而这道菜亦被称为“宫保鸡丁”

原料
  去骨鸡胸肉：一斤八两
  花椒粒：两大匙
  葱：两根（切段）
  蛋白：一个
  淀粉：三大匙
  酱油：两大匙
  蒜末：半茶匙
  糖：半茶匙
  白醋：一茶匙
  色拉油：适量
  盐：两茶匙

做法
  先用蛋白一个、盐半茶匙及淀粉两大匙搅拌均匀，调成“腌料”，鸡胸肉切成约一厘米见方的碎丁并用“腌料”搅拌均匀，腌渍半小时。
  用酱油一大匙、淀粉水一大匙、糖半茶匙、盐四分之一茶匙、白醋一茶匙、蒜末半茶匙调拌均匀，调成“综合调味料”。
  鸡丁腌好以后，色拉油下锅烧热，先将鸡丁倒入锅内，用大火快炸半分钟，炸到变色之后，捞出来沥干油汁备用。
  在锅里留下约两大匙油，烧热后将切好的干辣椒下锅，用小火炒香后，再放入花椒粒和葱段一起爆香。随后鸡丁重新下锅，用大火快炒片刻后，再倒入“综合调味料”继续快炒。
  如果你采用正宗川菜做法，最后只需加入花生米，炒拌几下就可以起锅了。
  如果你在北方，可加入黄瓜丁、胡萝卜丁和花生米，翻炒后起锅。

大千鸡
张大千居加拿大期间，曾按自己喜好改变宫保鸡丁的做法，并传授当地厨师，厨师将之命名为“大千鸡”，以兹纪念。大千鸡与宫保鸡丁不同之处，是使用经细工去皮、出骨、剔膜的鸡腿肉，以干辣椒、豆瓣酱为味，而且不用花生。
```

- 原料，做法和大千鸡为二级标题元素
- 原料的内容为无序列表
- 做法的内容是操作步骤，为有序列表
- 其他未提及的内容是普通段落
- 将代码通过 Gitee Pages 功能发布上线
- 用浏览器测试查看发布上线的网页

示例参考：
- [宫保鸡丁](https://wangding.github.io/html-demo/03-text-basic/02-gong-bao-ji-ding.html)
