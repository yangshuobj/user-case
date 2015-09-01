#开发android客户端某页面的具体流程：
#####1 根据原型图，建立该页面数据所依赖的DataModel，位置：data目录下。当然前提是还没有这个Model。
#####2建立该Model对应的net Service，参考retrofit框架。位置：data/java/data/net.
#####3 建立XXXReturn的API调用接口返回数据类型 位置： data/java/data/net/bean
#####4 建立该业务的Repo接口和实现。 位置：data/java/data/impl
