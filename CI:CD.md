## jenkins/CI/CD

http://www.infoq.com/cn/news/2017/01/alibaba-yunxiao-cicd-devops

### 持续集成（Continuous integration，简称CI）

1. 什么叫CI？

   **持续集成指的是，频繁地（一天多次）将代码集成到主干。**

   它的好处主要有两个。

   > **（1）快速发现错误。**每完成一点更新，就集成到主干，可以快速发现错误，定位错误也比较容易。
   >
   > **（2）防止分支大幅偏离主干。**如果不是经常集成，主干又在不断更新，会导致以后集成的难度变大，甚至难以集成。

   **持续集成的目的，就是让产品可以快速迭代，同时还能保持高质量。**它的核心措施是，代码集成到主干之前，必须通过自动化测试。只要有一个测试用例失败，就不能集成。

   ​



### 持续交付(Continuous Delivery)

持续交付并不是指软件每一个改动都要尽快的部署到产品环境中，而是指任何的修改都被证明可以在任何时候实施部署。



持续交付(Continuous Delivery)是一系列的开发实践方法，用来确保让代码能够快速、安全的部署到产品环境中，它通过将每一次改动都提交到一个模拟产品环境中，使用严格的`自动化测试`，确保业务应用和服务能符合预期。





### 持续部署（continuous deployment）





### 自动化测试

什么叫自动化测试？

前端自动化测试，后台自动化测试
