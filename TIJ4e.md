# 第十一章:持有对象

Java容器类类库划分为两个不同的概念:
### Collection: List, Set, Queue
### Map

Collection: This interface is typically used to pass collections around and manipulate them where maximum generality is desired.    
List接口:在`Collection`接口上增加了:
### E get(int index);
### E set(int index, E element);
### void add(int index, E element);
### E remove(int index);
### int indexOf(Object o);
### int lastIndexOf(Object o);
等方法
