Tree Nodes
==========

Write a program that reads the contents of a text file that represents the
nodes of a binary tree and then prints out the tree in level order.

- The nodes in the text file are represented as `PARENT : CHILD` pairs, one pair
  per line
- The node pairs are not guaranteed to be in any order.

Your program should detect and print an error on invalid tree descriptions.

### Example

Contents of `nodes.txt`:

```
cat : dog
cat : fish
dog : one
dog : two
red : yellow
fish : red
fish : boat
boat : steam
```

The tree modeled:

```
       cat
       / \
    dog   fish
   / \     / \
 one two  red boat
               /
             steam
```

Expected output:

(note you can ignore indentation spacing of child rows)

```
cat
dog fish
one two red boat
steam
```



            
