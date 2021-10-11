## 万类之祖Object

所有的类，都间接或者直接的继承自 Object 类

Object 没有成员变量， 只有方法。

一些方法使用 `native` 关键字，映射本地 c 或 c++语言。


### hashCode 和 equals

```
hashCode 可以翻译为哈希码，或者散列码。应该是一个代表对象的特征值的 int 整数。

equals 方法应该用来判断两个对象从逻辑上是否相等。

```

两者关系:

```

hashCode 和 equals是我们最长覆盖的两个方法。

覆盖的原则是，equals为true, hashCode 就应该相等。这是一种约定俗称的规范。

equals为 true 是 hashCode 相等的充分非必要条件。
 
```

### Class

Class 类代表类的类。 每个Class 类的实例，都代表了一个类。


### 反射

