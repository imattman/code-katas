Tree Nodes
==========

Write a program that reads the contents of a text file that represents the
nodes of a binary tree and then prints out the tree in level order.

- The nodes in the text file are represented as `PARENT : CHILD` pairs separated
  by a `:`, one pair per line
- comment lines starting with `#` and blank lines should be ignored
- The node pairs are not guaranteed to be in any order
- nodes are allowed 0, 1, or 2 children
- the first child encountered in the dataset can be assumed to be the
  left-child, though that distinction is not important in this exercise
- a valid dataset contains one and only one root node

Your program should detect and print an error on invalid tree descriptions.

### Example

Contents of `nodes.txt`:

```
cat : dog
cat : fish
dog : one
dog : two
fish : red
fish : boat
red : yellow
boat : steam
```

The tree modeled:

```
       cat
       / \
    dog   fish
   / \     / \
 one two  red boat
          /    /
      yellow steam
```

Expected output:

(you can ignore indentation spacing of child rows)

```
cat
dog fish
one two red boat
yellow steam
```



            
