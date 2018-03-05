查找大于100M的文件：

```
find . -type f -size +100M
```

批量查杀进程：

```
ps -ef | grep '微信web开发者工具' | grep -v 'grep' | awk '{print $2}' | xargs kill -9
```



