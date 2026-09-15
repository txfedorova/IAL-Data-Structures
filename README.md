# IAL / Algorithms and Data Structures in C

Collection of C coursework exercises from the Algorithms (IAL) course at Brno University of Technology. The repository focuses on implementing and working with fundamental data structures using pointers, dynamic memory and explicit data-structure operations.

## Repository overview

The coursework is split into two groups of exercises.

### `du_1` — linear data structures

- `c201` — singly linked list
- `c203` — queue implemented with a circular array
- `c206` — doubly linked list

Each exercise contains the C source and header files together with the original test utilities and Makefile used for the assignment.

### `du_2` — trees and hashing

- `hashtable` — hash table with separate chaining
- `btree/rec` — recursive binary search tree exercise
- `btree/iter` — iterative binary search tree exercise using explicit stacks

The binary-tree exercises cover operations such as initialization, search, insertion, deletion, disposal and tree traversal. The iterative variant uses auxiliary stack structures instead of recursion.

## Topics covered

- pointers and dynamic memory management in C
- abstract data types
- singly and doubly linked lists
- circular queue implementation
- hash tables and collision handling with chaining
- binary search trees
- recursive and iterative tree processing
- preorder, inorder and postorder traversal
- Makefile-based compilation and assignment test programs

## Repository structure

```text
.
├── README.md
├── du_1/
│   ├── c201/          # singly linked list
│   ├── c203/          # circular queue
│   └── c206/          # doubly linked list
└── du_2/
    ├── hashtable/     # chained hash table exercise
    └── btree/
        ├── iter/      # iterative BST variant
        └── rec/       # recursive BST variant
```

## Building the exercises

Individual exercises contain their own Makefiles. For example:

```bash
cd du_1/c201
make
```

The same pattern can be used for the other exercise directories that contain a Makefile.

## Notes

This repository preserves the original coursework state. Some directories contain assignment scaffolding, test programs or partially completed exercise code in addition to the implemented parts. The source files have not been rewritten for portfolio presentation; this top-level README was added later to make the repository structure and subject matter easier to understand from GitHub.
