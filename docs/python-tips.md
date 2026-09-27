# Python 实用技巧

## 列表推导式

用一行代码生成列表：

```python
squares = [x**2 for x in range(10)]
print(squares)
# [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

## 交换变量

不需要临时变量：

```python
a, b = 1, 2
a, b = b, a
print(a, b)  # 2 1
```

## 字符串格式化

推荐用 f-string：

```python
name = "Python"
version = 3.12
print(f"{name} 的版本是 {version}")
```

## 读取文件

使用 `with` 语句可以自动关闭文件：

```python
with open("example.txt", "r", encoding="utf-8") as f:
    content = f.read()
    print(content)
```

## 常用内置函数

| 函数 | 作用 |
|------|------|
| `len()` | 获取长度 |
| `type()` | 查看数据类型 |
| `range()` | 生成整数序列 |
| `enumerate()` | 同时获取索引和值 |
| `zip()` | 合并多个序列 |

!!! warning "注意"
    使用 `open()` 时建议加上 `encoding="utf-8"`，避免中文乱码。
