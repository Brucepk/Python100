# Python100
把Python知识点整理成100道习题，知识点来自两本书：Python基础教程（第3版）和流畅的Python，以后会定期加入更多的习题，大家帮忙点个赞哈，点赞越多，更新越快～


## 怎么查出通过 from xx import xx导入的可以直接调用的方法？

用 __all__ 方法，这个方法查出的是模块下不带_的所有方法，可以直接调用。

```
>>> import random
>>> random.__all__
['Random', 'seed', 'random', 'uniform', 'randint', 'choice', 'sample', 'randrange', 'shuffle', 'normalvariate', 'lognormvariate', 'expovariate', 'vonmisesvariate', 'gammavariate', 'triangular', 'gauss', 'betavariate', 'paretovariate', 'weibullvariate', 'getstate', 'setstate', 'getrandbits', 'choices', 'SystemRandom']

```