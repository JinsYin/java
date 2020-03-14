# Java 数据类型转换

## 自动类型转换

```graph

                                  +----------+
                                  | char(16) |
                                  +----------+
                                       |
                                       v
+---------+     +-----------+     +---------+     +----------+
| byte(8) | --> | short(16) | --> | int(32) | --> | long(64) | ----+
+---------+     +-----------+     +---------+     +----------+     |
                                      | |                          |
                            +---------+ +---------+                |
                        loss|                     |                |
                            v                     v                |
                      +-----------+         +------------+         |
                      | float(32) |  ---->  | double(64) |         |
                      +-----------+         +------------+         |
                            ^                     ^                |
                        loss|                     |loss            |
                            +--------------------------------------+
```

> loss：可能存在精度损失

```java
1f / 3;   // 0.33333334 （自动转成 float 类型）
10 / 3.5; // 2.857142857142857 （自动转成 double 类型）
10 / 3;   // 3
```

## 强制类型转换

```java
(float) 10 / 3; // 3.3333333
```