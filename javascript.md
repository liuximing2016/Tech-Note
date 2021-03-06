```
// 兼容标准模式和混合模式的clientHeight等获取方式
clientHeight = document.documentElement.clientHeight || document.body.clientHeight
scrollTop = document.documentElement.scrollTop || document.body.scrollTop
```

关于标准模式和混合模式的区别，参考：

* [DOCTYPE与浏览器模式详解（标准模式&混杂模式）](https://www.cnblogs.com/imxiu/p/3541932.html)
* [clientHeight , scrollHeight , offsetHeight之间的区别及兼容方案](https://www.cnblogs.com/nanshanlaoyao/p/5964730.html)
* [document.body.clientWidth/Height和document.documentElement.clientWidth/Height](https://www.douban.com/note/252530973/)

在提交前做eslint检查，通不过无法提交的配置：

```
"scripts": {
  "precommit": "npm run lint"
},
```

 chrome浏览器font-size最小为12px

Promise的好处：

* 异步执行的流程中，将执行代码和处理结果的代码清晰的分离\(.then, .catch\)；
* 采用链式写法，支持串行、并行\(Promise.all\)、竞争\(Promise.race\)，相比传统的"回调地狱"简洁清晰太多。



