# 参考
- [Spring Cloud源码分析（二）Ribbon - DD](https://zhuanlan.zhihu.com/p/31750966)
- [Spring Cloud- Ribbon设计原理](https://blog.csdn.net/luanlouis/article/details/83060310)
- [【Ribbon】源码解析（下）](https://juejin.cn/post/6974743338670882823#heading-7)

# Q
- 负载均衡：有集中式、客户端式两种方式，ribbon是后者
- 原生ribbon的关键组件: IClientConfig、IRule、IPing、ServerList、ServerListFilter、ILoadBalancer、ServerListUpdater
  - ILoadBalancer：负载均衡的client入口
  - IRule：实例选择规则
  - IPing：实例探活
  - Server（实例信息）
- 原生ribbon的关键流程
  - ILoadBalancer的构建
  - ILoadBalancer选择实例的流程
  - IPing探活 
- spc-ribbon都动了什么
  - rest+ ribbon
  - feign + ribbon
- ribbon整合eureka