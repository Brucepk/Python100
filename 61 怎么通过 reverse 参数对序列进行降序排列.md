# Python100
把Python知识点整理成100道习题，知识点来自两本书：Python基础教程（第3版）和流畅的Python，以后会定期加入更多的习题，大家帮忙点个赞哈，点赞越多，更新越快～


## 怎么通过 reverse 参数对序列进行降序排列
reverse 参数一般放在 sorted() 方法里面，reverse 默认值为 False，序列默认升序排列，降序排列的话需要将 reverse 值设置为 True。


```
>>> l = [1, 9, 5, 8]
>>> j = sorted(l, reverse=True)
>>> j
[9, 8, 5, 1]
```

