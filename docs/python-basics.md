# Python 基础语法

## 变量和数据类型

Python 中不需要提前声明变量类型，直接赋值即可：

```python
name = "Alice"      # 字符串
age = 25            # 整数
height = 1.68       # 浮点数
is_student = True   # 布尔值
```

## 条件判断

```python
score = 85

if score >= 90:
    print("优秀")
elif score >= 60:
    print("及格")
else:
    print("不及格")
```

## 循环

### for 循环

```python
for i in range(5):
    print(i)
```

### while 循环

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

## 函数

```python
def greet(name):
    return f"你好，{name}！"

message = greet("Python")
print(message)
```

## 列表和字典

```python
# 列表
fruits = ["苹果", "香蕉", "橙子"]
print(fruits[0])  # 苹果

# 字典
person = {"name": "Bob", "age": 30}
print(person["name"])  # Bob
```

!!! note "提示"
    列表用 `[]`，字典用 `{}`，注意区分。
