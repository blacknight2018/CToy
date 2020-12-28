
## 一个简单到不能再简单的解释器

### 类型
> int

### 常量
> 十进制整数

> 字符串

### 语句
> if {};

> if {} 
> 
> else if {}
> 
> else {};

> while (){};

> break ;

> return ;

### 输出
> print(); 调用的是c语言的printf

### Hello World
```
func int  main(int a)
{
    print("Hello World");
}
```

### 求阶乘
```
func int ff(int n)
{
    if(n==1)
    {
        return 1;
    }
    return ff(n-1)*n;
}
func int  main(int a)
{
    print("%d",ff(6));
}
```
