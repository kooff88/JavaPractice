## String 

```
String 对象最重要的特点： 不可变( immutable ). String 用来存储字符的数据是private的，而且不提供可修改的方法。
所以String 对象一旦生成，其内容就是完全不可能被修改的。

```

### String类的好兄弟

`StringBuilder` 是一个非常方便的用来拼接和处理字符串的类。和 String不同的是，它是可变的。

对它进行操作的方法，都会返回this自引用。这样我们就可以一直点下去，对 String 进行构造。