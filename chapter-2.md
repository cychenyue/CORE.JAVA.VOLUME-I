CORE.JAVA.VOLUME-I 第二章
==================

java运行时环境jre,它包含虚拟机但不包含编译器. 这不是开发者想要的环境, 而是专门为不需要编译器的用户设计的.


----------

java只有在安装过程和编译命令时候与系统有关. 与系统无关性是java的一个主要的优势
***夸平台***


----------

jdk的安装:
>* 下载安装jdk. 我这里是安装在C:\java 
>* 设置坏境变量 JAVA_HOME 值为 C:\java
>* 设置CLASSPATH 值为 .;%JAVA_HOME%\LIB;
>* 在已经有的环境变量 PATH中添加 %JAVA_HOME%\bin (如果PATH为Path,修改为全部大写)

***如果出现在cmd中输入java可以，但是javac不行的情况：
path变量下面添加java安装路径，到有javac。exe为止
例如
..../java1.6/bin/***

javac 是一个java的编译器。它将java文件编译成class。并发送到虚拟机。虚拟机执行编译器存放在class文件中的字节码


----------


