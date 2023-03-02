0x1D. C - Binary trees

C Group Project Algorithm Data structure

A binary tree is a rooted tree that is also an ordered tree in which every node has at most two children. A rooted tree naturally imparts a notion of levels (distance from the root), thus for every node a notion of children may be defined as the nodes connected to it a level below.


GENERAL
What is a binary tree
What is the difference between a binary tree and a Binary Search Tree
What is the possible gain in terms of time complexity compared to linked lists
What are the depth, the height, the size of a binary tree
What are the different traversal methods to go through a binary tree
What is a complete, a full, a perfect, a balanced binary tree



DATA STRUCTURES

Basic Binary Tree
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;




Binary Search Tree
typedef struct binary_tree_s bst_t;


AVL Tree
typedef struct binary_tree_s avl_t;


Max Binary Heap
typedef struct binary_tree_s heap_t;


NOTE: For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.



