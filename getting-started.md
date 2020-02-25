# Java 入门

## 三步曲

* 编写（`Hello.java`）

```java
// 文件名必须和 public class 类名相同，且一个文件只能有一个 public class 类
public class Hello {
    public static void main(String args[]) {
        System.out.println("Hello, world");
    }
}
```

* 编译

```sh
$ javac Hello.java
```

```sh
$ ls
Hello.class  Hello.java
```

* 运行（由 JVM 解释执行 + JIT 即是编译高频字节码为机器码）

```sh
$ java Hello # 只有 class 文件的文件名，没有扩展名
Hello, world
```
