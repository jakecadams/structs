*Note: this is a personal project and is very incomplete. If you really want a great data structures library, You should checkout (mori)[http://swannodette.github.io/mori/]

#Structs - WIP

##JavaScript Data Structure Library

###Includes

- Bag
- Binary Search Tree
- Graph
- Heap
- LinkedList
- LinkedMap
- Map
- Matrix
- Pool
- RedBlackTree
- Set
- Stack
- Trie
- Tree
- QuadTree
- Queue

###Install

```
npm install --save structs
```

###Example

```
var queue = new structs.Queue();
queue.enqueue(1);
queue.enqueue(2);
queue.enqueue(3);
queue.dequeue(); // 1
queue.size(); // 2
```

###Dependencies
- [Lodash](https://github.com/lodash/lodash)

###Note
All data structures uses the Pseudo-classical pattern
