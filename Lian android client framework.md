#开发android客户端某页面的具体流程：
#####根据原型图 ，建立该页面用到的bean（POJO)，位置：data/..../net/bean/
#####根据原型图，建立该页面数据所依赖的DataModel，位置：data目录下。当然前提是还没有这个Model。
#####建立该Model对应的net Service，参考retrofit框架。位置：data/java/data/net.
#####建立XXXReturn的API调用接口返回数据类型 位置： data/java/data/net/bean
#####建立该业务的Repo接口和实现。 位置：data/java/data/impl
#####在类ViewModelComponent中增加对应的依赖注入的方法。
#####在类InteractorModule中增加依赖注入的Provider方面的接口（这部分感觉很绕，先写上吧）
