```
// 兼容标准模式和混合模式的clientHeight等获取方式
clientHeight = document.documentElement.clientHeight || document.body.clientHeight
scrollTop = document.documentElement.scrollTop || document.body.scrollTop
```

关于标准模式和混合模式的区别，参考：

* [DOCTYPE与浏览器模式详解（标准模式&混杂模式）](https://www.cnblogs.com/imxiu/p/3541932.html)
* [clientHeight , scrollHeight , offsetHeight之间的区别及兼容方案](https://www.cnblogs.com/nanshanlaoyao/p/5964730.html)
* [document.body.clientWidth/Height和document.documentElement.clientWidth/Height](https://www.douban.com/note/252530973/)



