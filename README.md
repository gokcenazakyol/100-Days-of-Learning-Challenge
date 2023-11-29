# 100-Days-of-Learning-Challenge

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/b6f6f169-7b08-4491-8fba-c2cf034eb510)

--------------------------------------------------------------------
### Day 9: 29 November Wed
#### Heap
- Complete Binary Tree: If you represent a binary tree with an array, there should be no gaps between elements in array to call this binary tree as a complete binary tree. Height of a binary tree is logn.
- Full Binary Tree: All nodes in levels should be there.
<img width="1206" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/a1ee45b3-4a3d-4e13-979a-60ed5a24dc6c">

#### Max Heap and Min Heap
<img width="1067" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/8195282d-5241-4377-826d-47ed7b642697">

#### Insertion
- Max:O(logn), Min:O(1) time taken.

<img width="1009" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/48c60904-ce05-4f0c-b8ec-972a4d974620">

#### Delete
- You can only delete the root element in a heap.
- Max:O(logn), Min:O(1) time taken.
  
<img width="1093" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/ef9dbe04-92d3-44be-8512-4b16f7288f64">

<img width="1117" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/87bd1435-0d1d-429a-805b-1d2020bdae30">

#### Heap Sort
- If you delete the elements and fill the blank spaces with the deleted elements in array, you will get a sorted array. This is the methodolgy of the heap sort.

- First, with the given elements create a heap by inserting elements one by one. Then, once the heap is created, delete the element in the heap one by one. Then elements will be sorted.

- Time taken for creating a heap is O(nlogn)

<img width="1370" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/0229509c-1bb4-4468-b6f8-dceb1b92d514">

- Time taken for deletion a heap is O(nlogn)

<img width="1432" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/ed73f1cd-96ea-4b07-907e-228642cb2fbd">

- So, The total time is O(nlogn).

#### Heapify

- Heapify is a procedure for creating a heap, but the directions differ. Directions will be top to bottom of the heap.
- The time taken is O(n).

<img width="1349" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/88dc86ff-e12b-4568-bd87-15d2e1f4c2e9">

<img width="1176" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/bbfa6f36-00ba-4e81-a3c1-47da448a4aaa">

<img width="1332" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/bb297e39-483e-4a8b-b644-472086d799a3">

#### Priority Queue

- The time taken for deletion (and also insertion) in a list is O(n). Because after deleting an element, we need to shift rest of the elements in the list.
- So the best way to use a priority queue is using a heap, because insertion and deletion takes O(n).

<img width="1339" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/f12da512-9a29-4035-8ce9-68d62805fc99">


--------------------------------------------------------------------
### Day 8: 27 November Mon
#### Masters Theorem in Algorithms for Dividing Function
<img width="1074" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/c001a4e3-13e6-4d34-ac5a-ada96b2a76a4">

- For examples, video link is [here](https://www.youtube.com/watch?v=OynWkEj0S-s&list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O&index=27).

<img width="975" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/9469ee35-8d75-4406-8621-602f06161898">

<img width="975" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/f89f2f28-31b4-49df-ad8c-e84d471019d8">

<img width="985" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/1aeba935-b017-4984-9ff1-b4aa4cfffa0b">

#### Recurrence Relation on Root Function

<img width="1118" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/593b5a3d-7c44-4b0e-95ed-640344013aa6">

<img width="1047" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/f7223937-2055-48d2-bee0-db04a6b7867e">

#### Binary Search (Iterative Method)

<img width="1271" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/8952561c-b957-453b-b7f6-b9de3c725789">

#### Binaru Search (Recursive Method)

<img width="1399" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/a8fd2241-2de3-420d-9cc4-9b2755a16fda">

<img width="1267" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/585d7f79-ce73-4b5b-872a-6ce397d14225">


--------------------------------------------------------------------
### Day 7: 26 November Sun
#### Zip Syntax in Python
- Python zip() method takes iterable containers and returns a single iterator object, having mapped values from all the containers.
![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/2fdf1a62-d76a-4857-a695-736633816a31)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/64cfd403-2b33-4160-b4cd-c2f4fddca9c0)


--------------------------------------------------------------------
### Day 6: 21 November Tue
#### Monotonic Stack
- A monotonic stack is a stack whose elements are monotonically increasing or decreasing. It contains all qualities that a typical stack has and its elements are all monotonic decreasing or increasing.

--------------------------------------------------------------------
### Day 5: 17 November Fri
#### ord() function in Python

- Python ord() function returns the Unicode code from a given character. This function accepts a string of unit length as an argument and returns the Unicode equivalence of the passed argument. In other words, given a string of length 1, the ord() function returns an integer representing the Unicode code point of the character when an argument is a Unicode object, or the value of the byte when the argument is an 8-bit string.

<img width="742" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/4435e4aa-e660-4e55-acb9-ad263fcb8af6">

--------------------------------------------------------------------
### Day 4: 16 November Thu
#### Recurrence Relation T(n)=2T(n-1) + 1

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/0703a17c-1aa6-45d9-80a1-beb747ddf203)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/3f34fb6f-56f8-4a1e-8d29-8610432972e1)

- The result is theta(2**n).

#### Masters Theorem Decreasing Function

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/d25b9392-e97e-4ccb-ba1c-01e80658876a)

#### Recurrence Relation Dividing Functions

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/a8aef511-23a1-403a-86cf-66b0cddcb1bd)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/add170eb-6389-4e01-a62b-e37612102389)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/dee72a2f-fa94-49ca-a345-7fef5d3549df)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/888488a6-44c3-4642-b085-b90e974e3be2)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/858ac67a-db62-4f3c-abd2-b8a5fcc16d10)

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/f2a21c98-d8ef-4fce-90fd-390f8fc42753)

--------------------------------------------------------------------
### Day 3: 15 November Wed
#### Divide and Qonquer

<img width="836" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/ec83f336-2d63-4730-a76a-62a406a00ac0">

#### Recurrence Relation
##### Recurrence Relation with nlogn

<img width="1463" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/25091531-c994-4bee-9a1c-67aac8d0cd58">

- Time complexity is O(nlogn) because the upper bound for logn! is logn**n and it is equal to nlogn.

<img width="1445" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/438681c9-2ea8-418e-8130-7ccb28a4aea6">

- So the main rule is whatever the term we have, we multiply it with n.

<img width="1432" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/fd2ed3d7-59d2-4d17-9dee-0fa82928f2fb">


---------------------------------------------------------------------
### Day 2: 14 November Tue
#### Default Dict
- Dictionary in Python is an unordered collection of data values that are used to store data values like a map. Unlike other Data Types that hold only single value as an element, the Dictionary holds key-value pair. In Dictionary, the key must be unique and immutable. This means that a Python Tuple can be a key whereas a Python List can not. A Dictionary can be created by placing a sequence of elements within curly {} braces, separated by ‘comma’.

<img width="714" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/373f1d89-bb58-4d6e-acd2-a0bf85efda9d">

- Sometimes, when the KeyError is raised, it might become a problem. To overcome this Python introduces another dictionary like container known as Defaultdict which is present inside the collections module.
Defaultdict is a container like dictionaries present in the module collections. Defaultdict is a sub-class of the dictionary class that returns a dictionary-like object. The functionality of both dictionaries and defaultdict are almost same except for the fact that defaultdict never raises a KeyError. It provides a default value for the key that does not exists.

<img width="763" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/8cfb90af-0ccf-4960-aaa6-a06822fe6a53">

#### Solving this problem without sorting and using set:

<img width="1458" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/50ffbf85-7f83-43f2-bcbd-49d431125811">

#### Linear Search Computing Average Case

<img width="1107" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/809976f1-36d9-4b82-90e3-bac41c181908">

#### Binary Search
- The time taking for seaching is how many times that I have done. The comparisons I have done is equal to length of the binary seaarch tree. And length of the binary search tree is logn. logn is worst case scenario (for leaf element). Constant time for root element.

<img width="930" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/b5e2c5b9-8091-4e39-86b2-594cc5e39508">

- Min-max worst case depends on the data structures. For binary search tree, it depends on the height of a tree.

#### Disjoint Sets
- Disjoint sets are useful for detecting edges.

<img width="1428" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/fadcd797-2d0d-4376-8150-82bfc3a153cf">

- Minus represent parent itself, and the number after minus represents how many elements are there in this set. Other values represent the parent of its set.

<img width="1041" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/ce135943-7247-47c4-9738-bf5ebe2597ec">

<img width="1021" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/41696c98-72af-49e5-9dc2-7f7a0555b7fb">

<img width="1064" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/5337da59-bf81-4ac0-926e-d11c0afca074">

<img width="965" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/18f2cee1-8d09-4994-b83d-82cef90024bd">

- Collapsing Find: Directly connecting an element to its root parent.

---------------------------------------------------------------------
### Day 1: 13 November Mon
#### Bucket Sort

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/8e03909a-b205-49e9-972b-c6d94363ef9c)

#### Dictionary

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/b4cbbecd-cd52-4897-a288-c9a76ab8781d)

#### Asymptotic Notations

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/68555640-508c-4344-9ede-03b560dffb74)

<img width="710" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/0735b133-9f92-4134-ba9b-c20d7df2072a">

<img width="813" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/d6342362-d210-4a33-bab9-28929a274c6c">

<img width="814" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/fc8ed723-e1d4-46db-b14a-caa5cf8348c8">

<img width="850" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/19b3c55c-4cfc-4070-aa0c-cbdfe400871e">

- We can not found theta bound for this example.

<img width="800" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/2ed3f9f4-9aa9-47fe-afff-297d151fa560">

<img width="886" alt="image" src="https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/51144ca9-5f7d-4f07-8086-637fb37aa910">
