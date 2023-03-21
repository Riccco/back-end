# 方法

```JAVA

public int xxx(){
    return xxx;
}

```

## 静态方法

```JAVA

public static void main(String[] args){

}

```

  这是一个初始化方法

  ## 静态方法与方法

  * 静态方法只能访问静态变量，用于不需要实例化对象就可以执行的操作。

  * 方法可以访问静态方法和静态变量，用于需要访问类的实例变量和方法的操作。

  # 静态成员变量

  类似于前端全局变量，可以被所有对象共享,关键字为`static` 

  # private

  * 声明后只能在内部访问

  `private static int a`

  # final

  等于JavaScript中的`const`