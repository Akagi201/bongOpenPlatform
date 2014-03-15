bong 开放平台
================

![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/covernew.png?raw=true)

# 介绍

bong开放平台即将开放，这里是简单的未来可提供的接口介绍，欢迎和我们一起迭代开放平台。

# 关于bong
bong是一款健康运动手环,详情请参见[bong](http://www.bong.cn/)官方主页.

# Opening

[开场白](http://oliverchen.cn/openday)
309 天以来，我们所做的努力，不是在想怎么把 bong 卖出去，也不是什么商业模式可以更加赚钱。

我们一直在思考，如何能够更好的改变人们的生活，哪怕只有一点点。

直到今天，你还可以在点名时间，knewone，bongcn 公众号上看到我们一起经过的风风雨雨——起床闹钟、久坐提醒的争执，跳票，更换供应商，T1、T2 内测……

我们有坚定的信念，也保持着开放的心态，New bong 的成功离不开用户两个月里提出的几千条反馈意见。

我们深知，唯有和用户一起，共同前进，才能拥抱未来。

曾经有无数用户提出需要各种分析视图、统计报表、PK 比赛……我们并非漠视，而是一直在等待产品的基础部分稳定。

直到 New bong 问世，一件在心里等待了几个月的事情，终于，是时候开始了。

我们深知，多样化的个性需求，只有多态的开放环境才能够满足，而创建这样多态的开放环境，才是我们真正的梦想。

所以有了 「bong 开放日」——

无论你是否正在使用 bong，甚至无论你是否了解 bong，只要你内心有一股不灭的创造精神，只要你期待科技对人类生活的改变。

我们都诚挚的邀请你，和 bong 一起探索这条开放之路，共同鉴证一段历史的开启。

# 首次「bong 开放日」行程与报名方式

- 开放日互动平台：微信

- 3月15日（本周六）14:00 ~ 16:00
	- 公布开放接口
	- 全体脑暴接口应用方法

- 3月15日（本周六）16:00 ~ 3月16日（本周日）16:00
	- 24 小时原型马拉松：利用开放接口，设计产品原型

- 3月16日（本周日）16:00 ~ 18:00
	- 二次脑暴，选出优秀的产品原型
	- 讨论实现这些原型的方法

# 如何参加
- 我们已经在知乎上提出了一个问题：「未来五年内，科技会如何改变我们的生活？」，点击阅读原文可见，请回答，然后把你的答案链接回复给 bongcn 公众号，并在同一条信息里附上 「bong 开放日」这几个字。
# bong首次开放日接口文档
接口需要用户授权。我们目前拟定开放的接口有：

## UserData

用户基本数据主要涵盖的是用户的一些基本情况

- UserId：用户的ID
- UserName：在bong使用的用户昵称
- Gender：用户的性别
- BornYear：用户的出生年
- SportTarget：用户给自己设定的热量消耗目标
- SleepTarget：用户给自己设定的睡眠长度目标
- isTied：用户是否连接了bong手环

## bongBlock

bong开放平台能够提供某个用户的某一段运动，根据用户的ID和运动时间即可获得。

- userId：这一段运动所属于的用户
- ID：一段运动的ID
- StartTime：获取开始的时间
- EndTime：获取结束的时间
- subType：这一段运动的综合类型
- calories：消耗的能量
- steps：一共走了多少步
- distance：一共走了多远

## nobongBlock

bong开放平台能够提供某个用户的某一段非bong状态的情况，根据用户的ID和时间即可获得。

- userId：这一段非bong所属于的用户
- ID：一段非bong的ID
- StartTime：获取开始的时间
- EndTime：获取结束的时间
- subType：这一段运动的综合类型
- calories：消耗的能量
- steps：一共走了多少步
- distance：一共走了多远
- actTime：这一段的活跃时间
- nonActTime：这一段的非活跃时间

#Hacker Marathon

[如何制作原型101](http://oliverchen.cn/proto)

[原型提交入口](http://oliverchen.cn/vote)

[作品也可以放到proto文件夹下](https://github.com/Ginshell/bongOpenPlatform/blob/master/proto/)

**其他问题，可以联系小q(thisismyid1234）或者在『bong开放日』群中提出，我们会及时解答，也可以发到 github 上的 issue tracker 里**

**请大家随时关注微信群中的消息，我们会及时公布进展，这个群会将一直维持持续下去)或者在『bong开放日』群中提出**


------------

版权声明：文档由bong团队提供，版权归杭州攻壳科技有限公司所有