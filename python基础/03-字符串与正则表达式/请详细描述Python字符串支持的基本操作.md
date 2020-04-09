# 字符串基本操作
## 通过索引获取字符串中的某个字符串
```py
s1 = 'hello world'
print(s1[0])
print(s1[2])
```

## 分片
```py
print(s1[6:9])
print(s1[6:])
print(s1[::2])
print(s1[::-1]) #转置
```
## 重复输出用*
```py
s2 = "xyz"
print(10 * s2)
print(s2 * 20)
```
## 判断字符在字符串中
```py
print('b' in s2)
print('y' in s2)
print('b' not in s2)

print(len(s1))
print(min(s2))
print(max(s2))

a = [1,2,3,0,6]
print(2 not in a)

print(max(a))
print(min(a))
print(len(a))

print(10 * a)

a[0] = 20
```