# Python100
把Python知识点整理成100道习题，知识点来自两本书：Python基础教程（第3版）和流畅的Python，以后会定期加入更多的习题，大家帮忙点个赞哈，点赞越多，更新越快～

## 怎么用for循环实现把字符串变成Unicode码位的列表


```
>>> st = '!@#$%^&*'
>>> codes = []
>>> for s in st:
    codes.append(ord(s))

>>> codes
[33, 64, 35, 36, 37, 94, 38, 42]
```