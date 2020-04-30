### 项目介绍
作者想用纯golang（不用任何爬虫框架）写一个爬虫，以体现golang语言作为网络语言的优点。
共分为5个目录。每个目录是彼此分开，各不影响的。
可以一步一步看到一个代码整体的演化过程，其实很容易就可以发现并没有改动多少代码，就可以从一个单任务版本的代码演化成一个并发版本的爬虫了，接着由并
发版本的会演化成分布式版本的爬虫了。

### 目录介绍
* 01basic 如何获取网页内容
* 02crawler 单任务版本实现爬虫
* 03crawler 简单调度器实现并发版本爬虫
* 04crawler 队列调度器实现并发版本爬虫
* 05crawler 分布式爬虫实现（部分）

### 关于代码的相关文章介绍
* [02crawler单任务版本爬虫的一点说明](https://www.cnblogs.com/anmutu/p/12725642.html)
* [03crawler简单调度器实现并发版本爬虫的一点说明](https://www.cnblogs.com/anmutu/p/12734031.html)
* [04crawler队列调度器实现并发版本爬虫的一点说明](https://www.cnblogs.com/anmutu/p/12765207.html)

