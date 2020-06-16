# 如何使用GitHub（小白版）


## 什么是GitHub

Git是由Linux之父Linus Tovalds为了更好地管理linux内核开发而创立的分布式版本控制/软件配置管理软件。

简单来说，Git是一个管理你的【代码的历史记录】的工具。

------------------------------------------------

## 学习步骤

### 注册安装

去官网注册一个账号
然后，下载一个GitHub Desktop（Mac or Wins）客户端（方便使用）

假设小伙伴四人一起写一本小说，暂且叫做...《量化人生》

终于可以正式开始了！

### step1:创建新项目
我们四个人远程共同写一本书，要有一个笔记本吧？
![avatar](https://github.com/quantitative-trading-research/how_to_use_github/blob/master/github-repositories.png)

[repositories]就是笔记本们，你只需知道Repository是个放项目的地方就行。有时候会出现Repositories，是多个Repository的意思。

**fork**
如果你不想新建一个笔记本，看到小伙伴之前写过一个好到炸裂的文章，想把他的直接全部偷过来，修改修改就成你自己的文章了，这应该怎么办呢？
github还提供了一个很赞的功能叫做fork，你只需点击这个神奇的按钮，就可以把他的【笔记本】变成你自己的啦！任意修改都可以。
![avatar](https://github.com/quantitative-trading-research/how_to_use_github/blob/master/github-fork.jpg)

### step2:把【笔记本】克隆到本地
【笔记本】在云端，你要把它摘下来放到自己的电脑上写小说才方便，在这里我们叫[clone]是不是很形象！步骤如图：
![avatar](https://github.com/quantitative-trading-research/how_to_use_github/blob/master/github-clone.jpg)

或者是直接去客户端
![avatar](https://github.com/quantitative-trading-research/how_to_use_github/blob/master/github-desktop.jpg)

### step3:可以开始写作啦！
你的笔记本里已经自动有一个文档了，这个时候让我们回到网页版
你只需要在web端点开这个README.md可以开始在里面写你的小说了。
![avatar](https://github.com/quantitative-trading-research/how_to_use_github/blob/master/github-readme.jpg)
或者直接点开刚刚clone到电脑上的文件夹直接在里面写。

### step4:上传你写的小说
在本地写完之后你要上传到云端让其他小伙伴都能看见你写出什么幺蛾子了吧。
回到客户端，你发现有变化！！！
![avatar](https://github.com/quantitative-trading-research/how_to_use_github/blob/master/github-commit.jpg)
没错，在你头像旁边给你这次提交的内容起一个名字，以后如果再次寻找的时候会很方便。然后点下面的Commit to master。

### step5:回退到之前的版本
夜深人静的时候，我趁着你们都在睡觉把小说的结局偷偷地改成女主死掉了！
你醒来觉得我这结局改的太悲伤了，完全不能接受！结局必须要和之前那样王子公主幸福的生活在一起的happy ending！
问题又来了，怎么退回到我修改结局之前的happy ending？

还是刚刚那个客户端，选择history然后右键选择revert this commit!
你又回到happy ending的状态啦！

### step6:
其他小伙伴写了一章华丽无比的番外，你要更新本地的小说和他写的保持一致怎么办？
git pull

------------------------------

好了，知道这些基本操作入门应该够了。
入门初期迅速得到一些正反馈对于学习一门新技能来说实在是太重要了！尤其是编程这么炫酷的事情！
所以先不要管什么复杂的issue啊wiki啊乱七八糟的操作，按照上面的一步一步来，如果遇到什么问题，可以通过站内搜索（awesome github）、知乎等平台寻找答案，一般都会解决。