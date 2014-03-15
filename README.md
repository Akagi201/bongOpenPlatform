bong 开放平台
================

![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/covernew.png?raw=true)

# 介绍

bong开放平台即将开放，这里是简单的未来可提供的接口介绍，欢迎和我们一起迭代开放平台。

# 关于bong
bong是一款健康运动手环,详情请参见[bong](http://www.bong.cn/)官方主页.

# Opening

[开场白](http://oliverchen.cn/openday)

# bong首次开放日接口文档
接口需要用户授权。我们目前拟定开放的接口有：

## UserData

用户基本数据主要涵盖的是用户的一些基本情况UserId：用户的ID

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

------------

版权声明：文档由bong团队提供，版权归杭州攻壳科技有限公司所有