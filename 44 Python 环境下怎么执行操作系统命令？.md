# Python100
把Python知识点整理成100道习题，知识点来自两本书：Python基础教程（第3版）和流畅的Python，以后会定期加入更多的习题，大家帮忙点个赞哈，点赞越多，更新越快～


## Python 环境下怎么执行操作系统命令？

用 os 模块下的 system 方法

```
>>> os.system('cd /Users/brucepk/Desktop && mkdir aaa.txt')
256
```