# demo6_advanced_aspectj_02
AOP 实现之 agent 类加载
代码参考项目 **demo6_advanced_aspectj_02**

#### 收获💡

1. 类加载时可以通过 agent 修改 class 实现增强


注意 需要先使用maven 编译（mvn compile） 再在main方法内点击运行前请添加虚拟机参数  -javaagent:(你的maven仓库路径)/org/aspectj/aspectjweaver/1.9.7/aspectjweaver-1.9.7.jar
