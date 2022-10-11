# python
学习python笔记

1.查看 Python 版本
我们可以在命令窗口(Windows 使用 win+R 调出 cmd 运行框)使用以下命令查看我们使用的 Python 版本：

python -V
或
python --version
以上命令执行结果如下：

Python 3.3.2
你也可以进入Python的交互式编程模式，查看版本：

Python 3.3.2 (v3.3.2:d047928ae3f6, May 16 2013, 00:03:43) [MSC v.1600 32 bit (Intel)] on win32
Type "copyright", "credits" or "license()" for more information.
>>> 
第一个Python3.x程序
对于大多数程序语言，第一个入门编程代码便是 "Hello World！"，以下代码为使用 Python 输出 "Hello World！"：

hello.py 文件代码：
#!/usr/bin/python3
 
print("Hello, World!")

运行实例 »
Python 常用文件扩展名为 .py。

你可以将以上代码保存在 hello.py 文件中并使用 python 命令执行该脚本文件。

$ python3 hello.py
以上命令输出结果为：

Hello, World!