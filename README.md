# java 面试整理

* ## 集合框架

### **Collection接口是集合类的根接口，Java中没有提供这个接口的直接的实现类。但是却让其被继承产生了两个接口，就是Set和List。Set中不能包含重复的元素。List是一个有序的集合，可以包含重复的元素，提供了按索引访问的方式。**

### **Map是Java.util包中的另一个接口，它和Collection接口没有关系，是相互独立的，但是都属于集合类的一部分。Map包含了key-value对。Map不能包含重复的key，但是可以包含相同的value。**

* ## **层次关系**

## ![](/assets/import1.png)

* ## 接口实现类：

| List接口实现类： | Map接口实现类 | **Set接口实现类** | **Queue接口实现** |
| :--- | :--- | :--- | :--- |
| ArrayList | HashMap | HashSet | ArrayDeque |
| LinkedList | Hashtable |  | PriorityQueue |
| Vector | TreeMap | TreeSet |  |
| Stack | LinkedHashMap | LinkedHashSet |  |

参考:[https://www.cnblogs.com/NextNight/p/6972172.html](https://www.cnblogs.com/NextNight/p/6972172.html)

