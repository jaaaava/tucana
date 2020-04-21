# tucana文档

## FAQ
### 本项目的意图
- 本项目并非是要打破现有的id生成方式, 也并非是为了用于生产环境
- 主要调研了业内常见的uid的实现方式
- 分析了每种uid的使用场景以及优缺点
- 为了学习, 重新实现了市面上几乎所有的uid生成器
- 后续会对所有功能做一个抽象

## 项目简介
### uuid模块
<p> 本模块实现了rfc4122

### tucana-leaf
<p> 本模块重新实现了美团的leaf

### tucana-baidu
<p> 本模块重新实现了百度的uid-generator

## 参考资料
### 美团leaf
- [Leaf——美团点评分布式ID生成系统](https://tech.meituan.com/2017/04/21/mt-leaf.html)
- [Leaf：美团分布式ID生成服务开源](https://tech.meituan.com/2019/03/07/open-source-project-leaf.html)
- [leaf github地址](https://github.com/Meituan-Dianping/Leaf)

### 百度 uid-generator
- [官方wiki](https://github.com/baidu/uid-generator/blob/master/README.zh_cn.md)
- [对uid-generator改造的一个项目](https://github.com/baidu/uid-generator/blob/master/README.zh_cn.md)

### 滴滴tinyid
- [Tinyid原理介绍](https://github.com/didi/tinyid/wiki/tinyid%E5%8E%9F%E7%90%86%E4%BB%8B%E7%BB%8D)
- [Tinyid wiki](https://github.com/didi/tinyid/wiki)

### 小米chronos
- [小米id生成器](https://github.com/XiaoMi/chronos)

### Flickr的ticket
- [分布式唯一主键生成方式（1）：flickr的Ticket服务](https://www.jianshu.com/p/a696f6909d03)

- [flickr 对于分布式系统生成全局唯一ID的解决方案](https://blog.csdn.net/lionzl/article/details/8912542)

### light-id
- [一个简单却是实用的分布式ID解决方案light-id](https://blog.csdn.net/u011499747/article/details/98114073)
- [light-id github](https://github.com/dubby1994/light-id)

### 微信的序列号生成
- [万亿级调用系统：微信序列号生成器架构设计及演变](https://www.jianshu.com/p/b06e75af0268)

### 汇总分析
- [一口气说出 9种 分布式ID生成方式，面试官有点懵了](https://www.cnblogs.com/xichji/p/12332423.html)
- [分布式ID生成方案汇总](https://www.cnblogs.com/clawhub/p/11973325.html)
- [分布式环境下的id生成方法](https://www.cnblogs.com/firstdream/p/5222511.html)
- [分布式ID方案有哪些以及各自的优劣势，我们当如何选择](https://blog.csdn.net/hl_java/article/details/78462283)
- [【分布式全局ID】细聊分布式ID生成方法](https://blog.csdn.net/wxyjuly/article/details/79353007)
- [分布式ID生成器解决方案](https://blog.csdn.net/m0_37041378/article/details/78125747)
- [分布式全局序列ID方案之Redis优化方案](https://nicky-chen.github.io/2018/10/15/id-redis/)
