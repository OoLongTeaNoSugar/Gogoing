**目录：**
- [Go语言学习](#go语言学习)
  - [Go基础](#go基础)
    - [定义变量](#定义变量)
    - [Go数据底层的存储](#go数据底层的存储)


# Go语言学习

## Go基础
### 定义变量

使用`var`关键字是Go最基本的定义变量方式，与C语言不同的是Go把变量类型放在变量名后面

```go
//定义一个名称为“variableName”，类型为"type"的变量
var variableName type
```

关于string：
>在Go中字符串是不可变的，但可以做切片操作


### Go数据底层的存储
![avater](https://raw.githubusercontent.com/astaxie/build-web-application-with-golang/master/zh/images/2.2.basic.png)

