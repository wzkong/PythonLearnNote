# HUOBI_Trader_Requirement

[TOC]

## Python_Basis

* python crash course(Python编程：从入门到实践)

* effective python（暂时不看）

### Python crash course

#### 第一章 起步

​	无

#### 第二章 变量和简单数据类型

**2.2 变量**

2.2.1 变量的命名和使用

​	字母或者下划线开头；慎用小写字母l和大写字母O

**2.3 字符串**

2.3.1 修改大小写

```
name = "ada lovelace"

name.title()
>> Ada Lovelace

name.upper()
>> ADA LOVELACE

name.lower()
>> ada lovelace
```

使用\t，\n

2.3.4  删除空白

```
language = "python "
language.rstrip()
>> 'python'
```

2.3.5 

字符串双引号中可以包括单引号，"One of Python's strengths is its diverse community."  或者相反

**2.4 数字**

2.4.3 使用str()避免类型错误

数字得转化为str再合并

#### 第三章 列表简介

**3.2 修改、添加和删除元素**

3.2.2 在列表中添加元素

1.末尾

```
motorcycles = ['honda', 'yamaha', 'suzuki'] print(motorcycles) 
motorcycles.append('ducati') 
print(motorcycles)

>> ['honda', 'yamaha', 'suzuki'] 
>> ['honda', 'yamaha', 'suzuki', 'ducati']
```

2.insert

```
motorcycles = ['honda', 'yamaha', 'suzuki'] 
motorcycles.insert(0, 'ducati') 
print(motorcycles)

>> ['ducati', 'honda', 'yamaha', 'suzuki']
```

3.2.3 删除元素

1.del（直接删除）

```
motorcycles = ['honda', 'yamaha', 'suzuki'] 
print(motorcycles) 
del motorcycles[0] 
print(motorcycles)

>> ['honda', 'yamaha', 'suzuki']
>> ['yamaha', 'suzuki']
```

2.pop（取出删除）

```
motorcycles = ['honda', 'yamaha', 'suzuki'] 
first_owned = motorcycles.pop(0) 
print('The first motorcycle I owned was a ' + first_owned.title() + '.')

>> The first motorcycle I owned was a Honda.
```

3.根据值删除

```
motorcycles = ['honda', 'yamaha', 'suzuki', 'ducati'] print(motorcycles) 
too_expensive = 'ducati' 
motorcycles.remove(too_expensive) print(motorcycles) 
print("\nA " + too_expensive.title() + " is too expensive for me.")

>> ['honda', 'yamaha', 'suzuki', 'ducati']
>> ['honda', 'yamaha', 'suzuki'] 
>> A Ducati is too expensive for me.
```

**3.3 组织列表**

3.3.1 sort() 永久性

reverse

```
cars = ['bmw', 'audi', 'toyota', 'subaru'] 
cars.sort(reverse=True) 
print(cars)

>> ['toyota', 'subaru', 'bmw', 'audi']
```

3.3.2 sorted(list)

3.3.3 reverse() 反序

### 第四章 操作列表

**4.3 创建数值列表**

4.3.1 range()

4.3.3 简单计算

```
min
max
sum
```

4.3.4 列表解析

··

## Data_processing(matplolib, numpy, pandas)

通过billibilli网课学习

## SQL

MySQL必知必会

## LINUX

鸟哥LINUX教程

## Network

## Github操作