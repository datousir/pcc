# PCC性能挑战赛作品简介及源代码 from 黄东旭

## 比赛方法说明

实现类似 facebook 中的 like 功能，需要：  

* 可以对一个对象（一条feed、文章、或者url）进行 like 操作，禁止 like 两次，第二次 like 返回错误码  
* 有 isLike 接口，返回参数指定的对象有没有被当前用户 like 过  
* 需要看到一个对象的 like 计数  
* 可以看到一个对象的 like 用户列表（类似 QQ 空间）  
* 上述列表加分项：Like优先显示我的好友列表(social list)  

* 数据量：每天新增的 like 对象数为 1 千万，每秒 like 计数器查询量为 30 万次 / 秒  


相关链接：
https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653548705&idx=1&sn=e066f09d766fc5e900b512e644d7c11b&chksm=813a6139b64de82f74f7b3d684cb8dd2558a930f17574b5335028c42bb59fd105a1861afd2d3&scene=21#wechat_redirect
