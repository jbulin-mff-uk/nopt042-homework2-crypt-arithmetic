# Homework 1 - leaves

Write a program that receives a binary tree encoded using the structure `$node(Value,LeftChild,RightChild)` and outputs the list of its leaves (childless nodes) in prefix order (e.g., as in DFS). See the assignment on GitHub Classroom. For example:
```
picat leaves.pi "node(42,nil,nil)"
picat leaves.pi "node(1,node(2,nil,nil),node(3,nil,nil))"
picat leaves.pi "node(1,node(2,node(3,node(4,nil,nil),node(5,nil,nil)),nil),node(6,node(7,nil,nil),node(8,nil,nil)))"
```
should output:
```
[42]
[2,3]
[4,5,7,8]
```

Push to your Github classroom repository and see if it passes the test.