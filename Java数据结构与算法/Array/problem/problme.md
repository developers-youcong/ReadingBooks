## 问题列表如下:

### 1.向一个无序数组中插入一个数据项(c)

a.费时与数组的大小成正比

b.需要多次比较

c.需要移动其他数组项来提供空间

d.不管已有多少数据项都花费同样的时间


### 2.判断题:当从无序数组中删除数据项时，大多数情况下需要移动其他数据项来填充
是的。
代码示例如下:
```
import java.util.HashSet;
import java.util.Iterator;
import java.util.Set;

public class TestJunit {

	public static void main(String[] args) {
		
		Set set = new HashSet();
		set.add("2");
		set.add("1");
		set.add("3");
		set.remove("1");
		Iterator ite = set.iterator();
		
		while(ite.hasNext()) {
			Object obj = ite.next();
			
			System.out.println(obj);
		}
	}

}


```

最后输出的是2,3

### 3.在无序数组中，允许重复会导致(b)

a.所有操作时间都会增加

b.在某些情况下查找时间的增加

c.总会增加插入时间

d.有时会减少插入时间



#### 4.判断题:在无序数组中，查找一个不在数组中的数据项通常要比找到一个数据项快
错误，无序意味着没有顺序，不能像有序数组那样根据索引进行查询。

#### 5.Java中创建一个数组需要使用关键字?
和创建对象一样，使用new关键字。
示例如下:
```
public class TestJunit {

	public static void main(String[] args) {
		
		int [] num = new int[3];
		num[0] = 0;
		num[1] = 1;
		num[2] = 2;
		for (int i = 0; i < num.length; i++) {
			System.out.println(num[i]);
		}
	}

}

```

#### 6.如果类A要使用类B，那么

a.类A中的方法应该很好理解

b.如果类B与程序用户交互是更加可取的

c.比较复杂的操作都应放在类A中

d.类B能做的操作越多越好

### 7.当类A使用类B时，可以被类A访问的类B中的方法和字段被称作是类B的什么?


### 8.与无序数组相比，有序数组(d)

a.删除更快

b.插入更快

c.创建更快

d.查找更快


### 9.对数是什么的反函数
指数函数

### 10.以10为底1000的对数是什么
等于3(10的3次方等于1000)


### 11.在一个含有200个数据项的数组中完成二分查找所需检查的最大数据项个数是 d

a.200

b.8

c.1

d.13

### 12.以2为底64的对数是什么
6(2的6次方等于64)

### 13.判断题:以2为底100的对数是2  
错，应该是10

### 14.大O表示法表示了(a)

a.算法的速度是如何与数据项的个数相关的

b.含有给定大小的数据结构的算法运行时间

c.含有给定数据项数据的算法的运行时间

d.数据结构的大小是如何与数据项的个数相关的

### 15.O(1)意味着一个操作执行什么的时间?
线性时间(对应O(n))，简单查找就是最好的体现。

### 16.简单类型变量和什么都可以存入数组中?
以Java为例，int、short、long、byte、char、float、double、boolean等八大基本数组类型都可以存入数组，非基本数组类型如String和Object也可以存入数组。