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
