# Java 安装

## OpenJDK 与 Oracla Java

Java 有两种不同的实现：OpenJDK 和 Oracle Java 。两者都基于相同的代码，但 OpenJDK 是 Java 的参考实现，且是完全开源的，而 Oracle Java 包含一些专有代码（proprietary code）。

## JDK 与 JRE

| 对比项                          | 描述                                                                         |
| ------------------------------- | ---------------------------------------------------------------------------- |
| JRE（Java Runtime Environment） | JVM（Java Virtual Machine）的一种实现，运行编译完成的 Java 应用程序和 Applet |
| JDK（Java Development Kit）     | 包含 JRE，以及开发、编译 Java 应用程序和 Applet 的其他软件                   |

## 平台

* [Linux](java-for-linux.md)
* [macOS](java-for-macOS.md)
* [Windows](java-for-windows.md)

## 环境变量

| 变量名      | 变量值含义                             |
| ----------- | -------------------------------------- |
| `JAVA_HOME` | Java 安装路径                          |
| `CLASSPATH` | Java 字节码文件（`*.class`）的执行路径 |
