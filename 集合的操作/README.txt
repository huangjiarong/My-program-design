集合运算 
问题描述：
设有两个用单链表表示的集合A、B，其元素类型是int且以非递减方式存储，其头结点分别为ha、hb。要求下面各问题中的结果集合同样以非递减方式存储，结果集合不影响原集合。
实现要求：
⑴  编写集合元素测试函数IN_SET，如果元素已经在集合中返回0，否则返回1；
⑵  编写集合元素输入并插入到单链表中的函数INSERT_SET，保证所输入的集合中的元素是唯一且以非递减方式存储在单链表中；
⑶  编写求集合A、B的交C=A∩B的函数，并输出集合C的元素；
⑷  编写求集合A、B的并D=A∪B的函数，并输出集合D的元素；
⑸  求集合A与B的对称差E=(A-B)∪(B-A) 的函数，并输出集合D的元素；
⑹  设计一个菜单，具有输入集合元素、求集合A、B的交C、求集合A、B的并D、求集合A与B的对称差E、退出等基本的功能。
测试数据：由同学们自定，但集合A、B的元素个数不得少于16个。