A linked list is a data structure in which the object are arranged in a linear order.
The order in the array is determined by the array indices where as the order in the linked list is determined by the pointer in each object.
Each objecy in the list is usually (doubly linked list) is represented by the current node key, prev and next.
Let us consider x is the current node or the current element in the list, x.prev represents the previous element for the node in the linked list where as x.next represents the next element to the corresponding node.
If x.next=Nil that means there is no next element to the current node that represents that node is the last node similarly if x.prev=Nill that represents there is no previous element to the current node that represents that current node is the first node.
If L.head=Nil that represents the list is empty.
![image](https://user-images.githubusercontent.com/44836993/169692414-40456cd4-0b32-454d-bc11-93260cd73b21.png)



**Searching an element in the linked list**:
we do follow procedure called List-Search(L,k) where L is the list which we are usually searching and k is the key in the list.

![image](https://user-images.githubusercontent.com/44836993/169692433-3f30bb35-a3c5-4786-be25-6048ee2b776f.png)


The Worst case to search in an linked list is O(n) coz for the worst need to search n elements in the linked list with size of n.



**Inserting an element in the linked list**
![image](https://user-images.githubusercontent.com/44836993/169693023-fbc0bb88-db13-44db-86c6-9e3dd91a432e.png)
![image](https://user-images.githubusercontent.com/44836993/169693032-1f342c65-13f2-43e8-8329-62bc38e5d42d.png)

![image](https://user-images.githubusercontent.com/44836993/169693126-594f01d0-eb70-4a7b-bfdf-51a5ffe7a185.png)


![image](https://user-images.githubusercontent.com/44836993/169693464-64036767-156e-4037-8a9a-d9a71097ba47.png)


**Comparision of arrays to linked lists:**
Arrays can be used to store linear data of similar types the limitations of arrays over linked lists are:
1. The size of the arrays is fixed so we have to know the upper limit of the array in advance.
2. Inserting and deletion of an element is expensive in an array because to insert or delete an element we need to move all the remaining elements in that array.
3. So Dynamic Size and Ease of insertion and deletion are the advantages over arrays.
**Disadvantages of linked lists**
1. random access of the elements is not allowed.we have to access elements sequentially starting from the first node.
2. Extra memory space is required for the pointer.



The First node of the linked list is called the Head of the linked list.
Each node in the inked list is represented by the two values i.e, Data and the pointer.

![image](https://user-images.githubusercontent.com/44836993/169747950-c1e472d4-abf5-4b74-8e5b-1601d62289e1.png)


![image](https://user-images.githubusercontent.com/44836993/169748051-77a174a7-adcf-4524-979d-70372ba23727.png)




![image](https://user-images.githubusercontent.com/44836993/169748796-b15fe6d7-0611-499b-a2dd-a5f26ddbf0a1.png)

![image](https://user-images.githubusercontent.com/44836993/169748846-46faa348-0e34-4d7d-95fd-edb3a4214a09.png)

![image](https://user-images.githubusercontent.com/44836993/169748873-f6d62297-c01e-472c-8a6b-17d70fc9447d.png)



![image](https://user-images.githubusercontent.com/44836993/169749029-d5c6456e-cfc9-427c-8411-29cd336a0535.png)







**Traversing over the linked list**



![image](https://user-images.githubusercontent.com/44836993/169752103-fb673e4e-9175-405e-a281-8671175278b4.png)


