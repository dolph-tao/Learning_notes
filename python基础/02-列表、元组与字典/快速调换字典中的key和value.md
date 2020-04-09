# 快速调换字典中的key和value
```py
d = {'a':1,'b':2}
print({v:k for k,v in d.items()})
```
