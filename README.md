# BSTVisualization
It's a Java application with a graphical user interface (GUI).

In this project, the graphical representation of the Binary Search Tree (BST) is updated when adding or deleting nodes through a combination of methods and logic.
However, it's important to note that the code doesn't include explicit balancing logic to ensure that the tree remains perfectly balanced like in a self-balancing BST 
(e.g., AVL tree or Red-Black tree). Instead, it relies on the order of insertion to construct the tree.

- The BST is implemented using the following classes:
     - `Node`: Represents the nodes of the BST.
       - Contains a `JLabel` to display data.
       - Stores references to left and right child nodes.
       - Has a `Points` object for storing coordinates when drawing the tree.
     - `Points`: Represents coordinates for drawing lines connecting nodes.
     - `Height`: Stores height information for the root and its left and right subtrees.
     - `BinarySearchTree`: Manages BST operations like adding, deleting, and searching nodes.
 
Operations:*
   - Key operations include:
     - *Add*: Inserts a new node into the BST.
     - *Delete*: Removes a node from the BST.
     - *Search*: Finds a node and highlights the search path.
    
This project structure combines Java's Swing library for GUI components with custom classes for BST operations and visualization. 
It allows users to interactively visualize and manipulate a Binary Search Tree.



https://github.com/Aqs31/BSTVisualization/assets/88832346/6888445e-b92e-4aee-8bb4-d6414a61defc

