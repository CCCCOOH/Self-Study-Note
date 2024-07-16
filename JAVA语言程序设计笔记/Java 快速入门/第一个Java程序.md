# 第一个 Java 程序

## 前言

这里先讨论不使用 **IDE编译器** 而是 **文本编辑器** 来进行编译。

新建文本编辑器，输入以下代码：

```java
public static Hello {
	public static void main(String[] args) {
		System.out.printlin("Hello, World!");
	}
}
```

> 这里不进行代码的解释，重点是编译的过程。

## 编译

Java 源码只是一个文本文件`Hello.java`，需要使用编译工具`javac`将其编译成字节码 `Hello.class`，然后用`java`命令执行这个字节码文件。

![image-20240716162310062](C:\Users\谌颖\AppData\Roaming\Typora\typora-user-images\image-20240716162310062.png)

> 图片参考[廖雪峰的官网](https://www.liaoxuefeng.com/wiki/1252599548343744/1255878730977024)

![image-20240716162856416](C:\Users\谌颖\AppData\Roaming\Typora\typora-user-images\image-20240716162856416.png)

- 创建 Hello.java 编辑好代码
- 终端中键入 javac Hello.java 
- 执行用 java Hello

或者一种更快的方法是:

`java Hello.java` 可以理解为直接编译运行一条龙服务

![image-20240716163150680](C:\Users\谌颖\AppData\Roaming\Typora\typora-user-images\image-20240716163150680.png)

## 总结

理解 `javac` 是 `Java` 的编译器，可以用 `javac` 这个应用程序来编译 `.java` 源代码，将其编译成 `.class` 字节码，最后用 `java` 执行程序。