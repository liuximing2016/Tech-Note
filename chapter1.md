添加gitignore后使之生效：

```
git rm -r --cached . //删除本地缓存
git add . //添加要提交的文件
git commit -m 'update .gitignore' //更新本地的缓存
git push origin
```



