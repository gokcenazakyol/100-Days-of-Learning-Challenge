# 100-Days-of-Learning-Challenge

![image](https://github.com/gokcenazakyol/100-Days-of-Learning-Challenge/assets/74296174/b6f6f169-7b08-4491-8fba-c2cf034eb510)

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
