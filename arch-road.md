## 前进一个台阶

* 广度
* 深度
	>继续钻研技术
	>继续攀登
* 搭建平台，谁都可以。但是能知其原理，并能成功应用在显示业务的才算架构师。
* 架构师不仅仅是搭个平台了的，其实谁的可以搭个平台，但是要用起来，那就不行了。

## 应用场景+解决方案

### 1.并发问题
	>原子性
	>并发
	>重复
	>缓存
	>问题：一个数据只能操作一次，怎么解决。
### 2.使用Jemeter 怎么获知系统的最大并发性
	>参数依赖：CPU，内存？No

### 3.大并发下订单的监控
	>订单系统，客服系统，物流系统
	>监控层
	>公司需要订单状况，用户需要获知订单是否发货，货在哪？
	>>
	>解决方案：把所有的订单暂时放在一个缓冲里，之后操作这些数据，你怎样办。

### 4.前端连续提交两次问题
	>一个表单用户提交多次，怎么把后面的数据返回去。

### 6.Spark SQL 与 Hadoop 
	>使用什么数据取数据
	>赛去哪里
	>hdfs引擎

### 7.mysql 引擎 mySAM 
	>mysql myisam innodb 区别
	>mysql 行锁的问题。
### 8.oracle 与 mysql 分页的区别
	>mysql limit
	>ROWNUM <= 40和RN >= 21

### 9.最后一台手机问题
	>A与B同时进来抢购一台手机，怎么保证手机数量不为-1；
	>并发锁,锁

### 10.多个并发只能修改一个数据
	>mysql 行锁，还有什么。 update 查询返回结果
### 11.秒杀活动 10000个人同时进来强一台手机
	>tomcat 一般支持200到500个并发 
	> 使用队列作为缓存，并从队列中强
### redis 与 memcached 之间理解
	>memcached 内存型的
	>url:http://blog.csdn.net/tonysz126/article/details/8280696/