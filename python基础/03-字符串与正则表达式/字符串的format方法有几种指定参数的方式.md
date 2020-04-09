# 格式化字符串，format集中指定参数的方式
## 默认方式（传入的参数与{}一一对应）、命名参数和位置参数{2}

```py
# 默认大括号
s1 = 'Today is {},the temperature is {} degrees.'
print(s1.format('Saturday',24))

# 命名参数
s2 = 'Today is {day},the temperature is {degree} degrees.'
print(s2.format(degree = 30, day='Sunday')) # 命名参数顺序无所谓

# 默认+命名参数混合模式
s3 = 'Today is {week},{}, the {} temperature is {degree}'
print(s3.format('abcd',12345,degree=24,week='Sunday'))

# 位置参数，占位符1，2，3，4 指明匹配顺序
s4 = 'Today is {week},{1}, the {0} temperature is {degree} degrees.'
print(s4.format('abcde',1234,degree = 45,week='Sunday'))

# 类中应用
class Person:
    def __init__(self):
        self.age = 20
        self.name = 'Bill'

person = Person()

s5 = "My name is {p.name}，my age is {p.age}."
print(s5.format(p = person))
```


