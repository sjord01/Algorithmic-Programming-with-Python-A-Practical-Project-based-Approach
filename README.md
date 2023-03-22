# Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach
The project is a series of liveProjects that teaches you how to use specific algorithms to solve important programming problems. It covers topics such as recursion, linked data structures, trees, network algorithms, and more. You'll gain practical experience with various algorithmic topics, data structures, and programming techniques in this series of projects. Overall, this project aims to provide a comprehensive understanding of algorithms and their practical applications in programming.

## Trees
This series of project steps involve using Python and various algorithms to manipulate binary and N-ary trees. Binary trees have at most two child nodes, while n-ary trees can have any number of child nodes. Throughout the portfolio, agile programming technique of frequent builds and thorough debugging are applied, with each unit covering incremental changes to the code. By adding version numbers to each program, different iterations can be tracked referencing previous milestones. The focus will be on sorting data, as well as storing, finding, and removing data in sorted trees. Additionally, it explores different layout approaches for organizing charts. By the end of the project, a base for a production-ready project on manipulating trees in Python and creating effective organizational charts will be scripted.

![binarynode](https://user-images.githubusercontent.com/104819501/226405840-0d9ee68a-d800-4d4b-9c86-beab32b2df2f.png) ![narynode](https://user-images.githubusercontent.com/104819501/226405963-d0abcfb4-40e4-42fd-a458-c3ca7967d172.png)



### Node Classes
The classes BinaryNode and NaryNode have variables that refer to other objects of the same class. For instance, a BinaryNode can have a maximum of two BinaryNode "children". The recursive structure of a tree is made possible by the fact that nodes can have children that are also node objects.

See: [binary_node1](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/binary_node1.ipynb),
See: [nary_node1](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/nary_node1.ipynb)
### Outline Views
This milestone showcases recursion, which is a crucial concept in trees. Additionally, it highlights the advantage of working with n-ary trees over binary ones, as an n-ary tree enables looping through a node's children, rather than dealing with each child individually. In fact, in certain scenarios, it might be more convenient to use an n-ary node class to represent a binary tree. However, some adjustments may be necessary to ensure that no node has more than two children in its children collection.

See: [binary_node2](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/binary_node2.ipynb),
See: [nary_node2](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/nary_node2.ipynb)
### Exhaustive Search
If you compare the str method (from the previous milestone) and the find_node method (from this milestone), you will notice that both methods use recursive traversal to perform some action throughout the tree. While the str method prints information about each visited node, the find_node method compares the value of the current node with a target value.

One notable difference between the two methods is that the find_node method can terminate the search as soon as it finds the target value, whereas str method always visits every node in the tree. Thus, while the find_node method is considered an exhaustive search since it may potentially visit every node in the tree, the str method is even more exhaustive as it always visits every node.

See: [binary_node3](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/binary_node3.ipynb),
See: [nary_node3](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/nary_node3.ipynb)
### Traversals
This project phase explores the traversal methods in a tree data structure, which involve recursively traversing the tree in different orders to visit its nodes. The methods covered in this context are preorder, inorder, postorder, and breadth-first traversals. The difference between these methods lies in the order in which they visit a node's children. While preorder, inorder, and postorder traverse to the bottom of the tree and work their way back up, breadth-first traversal uses a queue to visit nodes in a different order. All these methods build a list of visited nodes that can be iterated over to perform some action or execute a given method for each node.

See: [binary_node4](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/binary_node4.ipynb),
See: [nary_node4](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/nary_node4.ipynb)
### Drawing
This milestone is challengine in which separate recursive traversals of a tree are used to perform layout, draw links, and draw nodes. While each individual task is relatively simple, performing them in separate methods makes them easier to implement. However, it is possible to perform all the tasks in one recursive traversal, though it requires determination. The key is to perform each task after a recursive call returns, as each node's position depends on the positions of its children. The recommended approach follows the basic pattern of the "arrange_subtree" method: after arranging child subtrees and positioning the current node, links between the node and its children can be drawn followed by drawing the child nodes.

![Image 2023-03-21 at 12 16 PM](https://user-images.githubusercontent.com/104819501/226789277-d239eb62-a899-4620-beaf-970dc99f1277.jpeg)
![Image 2023-03-21 at 12 34 PM](https://user-images.githubusercontent.com/104819501/226789349-505e8b4c-b10f-453f-9049-c3c6e4de2bf5.jpeg)

See: [binary_node5](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/binary_node5.ipynb),
See: [nary_node5](https://github.com/sjord01/Algorithmic-Programming-with-Python-A-Practical-Project-based-Approach/blob/main/nary_node5.ipynb)
### Org Charts
### Updating Sorted Trees

## Shortest Paths

## Scheduling

## Image Processing

## Work Assignment

## Fractals
