# 用逗号分隔输出的字符串
```py
print("aa","bb",sep=",")
```

# 如何让print不换行
```py
print('hello',end='') # 指定为空串 默认是换行符
print('world')
```
# 格式化
```py
# 1
s = 'road'
x = len(s)
print('The length of %s is %d' % (s,x))

# 2
from io import StringIO
import sys
old_stdout = sys.stdout
result = StringIO()
sys.stdout = result
print('The length of %s is %d' % (s,x))
sys.stdout = old_stdout
result_str = result.getvalue()
print('result_str',result_str,sep=':')
```




