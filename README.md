单向循环链表是指在单链表的基础上，表的最后一个元素指向链表头结点，不再是为空。
![image](https://github.com/user-attachments/assets/d89986a5-36f5-4cd9-a0ac-41ea59c6c2b6)
由图可知，单向循环链表的判断条件不再是表为空了，而变成了是否到表头。

操作

is_empty() 判断链表是否为空
length() 返回链表的长度
travel() 遍历
add(item) 在头部添加一个节点
append(item) 在尾部添加一个节点
insert(pos, item) 在指定位置pos添加节点
remove(item) 删除一个节点
search(item) 查找节点是否存在

具体代码：


运行结果：

