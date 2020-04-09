## 同时输出单引号和双引号
```py
print('hello "world"') # 用单引号输出双引号

print("hello 'world'") # 用双引号输出单引号

print('"hello" \'world\'') # 同时输出单、双引号，用转义字符\
```
## 让转义符失效（3种方法： r、repr和\）
```PY
# 原样输出
print(r'Let \'s go!')

print(repr('hello\nworld'))

print('hello\\nworld')
```

## 保持原始格式输出字符串
```py
# 用三对双引号或者三对单引号包含内容，即原样输出字符串
print("""
   hello 
           world
                  I love you.
""")
```