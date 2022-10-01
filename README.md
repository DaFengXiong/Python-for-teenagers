# Python-for-teenagers
### 简介
- Python 是一个高层次的结合了解释性、编译性、互动性和面向对象的脚本语言。
- Python 的设计具有很强的可读性，相比其他语言经常使用英文关键字，其他语言的一些标点符号，它具有比其他语言更有特色语法结构。
  - 解释型的语言
  - 交互式语言
  - 面向对象的
  - 容易入手
- 主要的应用领域
  - 云计算：云计算最热的语言，典型的应用OpenStack
  - WEB开发：许多优秀的 WEB 框架，许多大型网站是Python开发、YouTube、Dropbox、Douban……典型的Web框架包括Django
  - 科学计算和人工智能：典型的图书馆NumPy、SciPy、Matplotlib、Enided图书馆、熊猫
 系统操作和维护：操作和维护人员的基本语言
  - 金融：定量交易、金融分析，在金融工程领域，Python 不仅使用最多，而且其重要性逐年增加。
  - 图形 GUI：PyQT，WXPython，TkInter

### 基础语法
1. 标识符 是用来表示变量，用来存储数据，（内存），
  - 第一个必须是字母表中的字母或者下划线；
  - 标识符的其他部分必须由字母、数字、下划线组成
  - 标识符是大小写敏感的
  - 举例：
3. Python 保留字
4. 注释
5. print使用
6. mu编辑器的使用
7. if elif else
8. 字符串
9. 字符串索引

### 示例
```

print(" This is a plus program! ")

number_1 = 100
number_2 = 100

print(" number_1 is " + str(number_1) )
print(" number_2 is " + str(number_2) )

result_plus = number_1 + number_2

print("number_1 plus number_2 is " + str(result_plus) )

def add(input1, input2):
    return input1+input2
   

result_1 = add(1,1)
result_2 = add(2,2)
result_3 = add(3,3)

print(result_1)
print(result_2)
print(result_3)


Judge = True

if Judge:
    print("In True")
    print("In True")
else:
    print("In False")

x = 1
y = 0
    
if x>y :
    print(x*2)
else:
    print(x)
    
rain = False
hot = False
cool= True

# 可以没有else

if rain :
    print("stay home")
elif hot:
    print("swimming")
elif cool:
    print("bicycle")
    
if cool :
    print("bicycle")

x = 1
y = 1

result_plus = x + y 

result_plus_int = float(result_plus)

print(result_plus)
print(result_plus_int)

rain = True

print(rain)

if rain == 1.0:
    print("is rain")
    
xx = 0.5
yy = 2 

yy = xx
print(yy)

dog_name = "xiaohei"
print(dog_name)
print(dog_name[0]) # 索引从0 开始
print(dog_name[1:3])  # 不包括索引3


str='123456789'
print(str)                 # 输出字符串
print(str[0:-1])           # 输出第一个到倒数第二个的所有字符
print(str[0])              # 输出字符串第一个字符
print(str[2:5])            # 输出从第三个开始到第五个的字符
print(str[2:])             # 输出从第三个开始后的所有字符
print(str[1:5:2])          # 输出从第二个开始到第五个且每隔一个的字符（步长为2）
print(str * 2)             # 输出字符串两次
print(str + '你好')         # 连接字符串
```


### words
1. Interpreted language    解释型语言
2. Compiled language
3. Interactive language
4. Object Oriented Programming OOP
5. Procedure orientied Programming
6. Scripts language
7. invalid syntax
