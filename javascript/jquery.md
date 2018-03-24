jQuery序列化表单为json字符串

```
json = JSON.stringify($('#test-form').serialize().split('&').reduce((x,y) => {
var item = y.split('=');
var key = item[0];
var value = item[1];
x[key] = value;
return x;},{}))
```



