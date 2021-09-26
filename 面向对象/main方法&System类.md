## Main 方法

main方法也是一个静态的，有 String[]做参数的，没有返回值的方法而已。它的特殊性在于 Java可以把main方法作为程序入口。


```java
// XXX.main(args);

public class LearnMain {
    public static void main(String[] args) {
        System.out.println(args.length);
        for (int i = 0; i < args.length; i++) {
            System.out.println(args[i]);
        }
    }
}

...


public class InvokeMain {
    public static void main(String[] args) {
        System.out.println("进入InvokeMain方法");
        LearnMain.main(args);
        System.out.println("InvokeMain的main方法执行结束");
    }
}


```

## System类

System类中有很多和系统相关的方法。常用的静态属性， in和out 用来读取和输入数据。


最常用，无可替代的方法，取当前时间。