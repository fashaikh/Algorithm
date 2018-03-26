# Algorithm

What is inside this repo?
Each folder contains a algorithm questions, and some test (if it is written in ruby).

On the top of each question, there is a brief description of the question, input output, difficulty level and related tags.

How to ran it?
Java solution:
1. Open https://codepad.remoteinterview.io/pads in browser.
2. Pause the solution in the editor and hit "run" on the bottom.

Ruby solution:
1. Open the terminal and clone the folder.
2. Direct inside the folder and ran Rspec file.

## Greedy

```
  track everything!
```

#### Easy
- [Stock Price](https://github.com/cogrammers/Algorithm/tree/master/stockPrice)

## Binary Search
```
input: an array of intergers and a target.
output: index position of the first/any/last of the given target.
```
### Template

- [First Position of Target](https://github.com/cogrammers/Algorithm/tree/master/firstPositionOfTarget)
- [Classical Binary Search](https://github.com/cogrammers/Algorithm/tree/master/anyPositionOfTarget)
- [Last Position of Target](https://github.com/cogrammers/Algorithm/tree/master/lasterPositionOfTarget)

### Easy
- [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/description/)
- [Find closest number in array](https://www.geeksforgeeks.org/find-closest-number-array/)

### Med
- [First Bad Version](https://leetcode.com/problems/first-bad-version/description/)
- [Find Peak Element](https://leetcode.com/problems/find-peak-element/description/)

### Hard
- [Smallest Rectangle Enclosing Black Pixels](http://www.lintcode.com/en/problem/smallest-rectangle-enclosing-black-pixels/)

### Pool
- [Recover Rotated Sorted ArrayList](https://github.com/cogrammers/Algorithm/tree/master/recoverRotatedSortedList)

## Binary Tree & Divide Conquer
```java
  public class TreeNode {
    public int value;
    public TreeNode left, right;
    public TreeNode(int) {
      this.value = int;
      this.left = this.right = null;
    }
  }
```

```java

// for codepad
class MyCode {

  public static class TreeNode {
    public int val;
    public TreeNode left, right;
    public TreeNode(int num) {
      this.val = num;
      this.left = this.right = null;
    }

  }

  public static void main (String[] args) {
    TreeNode root = new TreeNode(2);
    root.left = new TreeNode(3);
    root.right = new TreeNode(4);
    System.out.println(root.val);
  }
}
```

```javascript
  class TreeNode {
    constructor(num) {
      this.val = num;
      this.left = this.right = null;
    }
  }

  var root = new TreeNode(3);
  console.log(root.val);

```

```ruby
class TreeNode
  attr_accessor :val, :left, :right
  def initialize(num)
    @val = num
    @left = @right = nil
  end
end

root = TreeNode.new(5)

puts root.val
```

### Template

- [Preorder Traversal](https://github.com/cogrammers/Algorithm/tree/master/preorder)
- [Inorder Traversal](https://github.com/cogrammers/Algorithm/tree/master/inorder)
- [Postorder Traversal](https://github.com/cogrammers/Algorithm/tree/master/postorder)

### Easy

- [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/description/)
- [Minimum Subtree](https://github.com/cogrammers/Algorithm/tree/master/minimumSubtree)
- [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/description/)
- [Subtree with Maximum Average](https://github.com/cogrammers/Algorithm/tree/master/subtreeWithMaximumAverage)

### Med

- [Validate Binary Search Tree](https://github.com/cogrammers/Algorithm/tree/master/validateBinarySearchTree)
- [Lowest common Ancestor](https://github.com/cogrammers/Algorithm/tree/master/lowestCommonAncestor)

## Breath First Search
```java
  public class TreeNode {
    public int value;
    public TreeNode left, right;
    public TreeNode(int) {
      this.value = int;
      this.left = this.right = null;
    }
  }
```

```java

// for codepad
class MyCode {

  public static class TreeNode {
    public int val;
    public TreeNode left, right;
    public TreeNode(int num) {
      this.val = num;
      this.left = this.right = null;
    }

  }

  public static void main (String[] args) {
    TreeNode root = new TreeNode(2);
    root.left = new TreeNode(3);
    root.right = new TreeNode(4);
    System.out.println(root.val);
  }
}
```

```javascript
  class TreeNode {
    constructor(num) {
      this.val = num;
      this.left = this.right = null;
    }
  }

  var root = new TreeNode(3);
  console.log(root.val);

```

```ruby
class TreeNode
  attr_accessor :val, :left, :right
  def initialize(num)
    @val = num
    @left = @right = nil
  end
end

root = TreeNode.new(5)

puts root.val
```

### Template

- [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/description/)
- [Graph Valid Tree](https://github.com/cogrammers/Algorithm/tree/master/graphValidTree)
- [Zombie in Matrix](https://github.com/cogrammers/Algorithm/tree/master/zombieInMatrix)

## Depth First Search

### Template

```
  Recursion:
    - Definition
    - Disassembly
    - Exit
```
### Easy

- [Combination Sum](https://leetcode.com/problems/combination-sum/description/)
- [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/description/)
- [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/description/)
- [Permutations](https://leetcode.com/problems/permutations/description/)

## Linked List & Array

#### Template

```java
public ListNode {
  int val;
  ListNode next;
  ListNode(int val) {
    val = val;
    next = null;
  }
}
```
- [Reverse Order Storage](https://github.com/cogrammers/Algorithm/tree/master/reverseOrderStorage)
- [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/description/)
- [Insert Into A Cyclic Sorted List](https://github.com/cogrammers/Algorithm/tree/master/insertIntoACyclicSortedList)

## Two Pointers

#### Med
- [Find All Anagrams In A String](https://leetcode.com/problems/find-all-anagrams-in-a-string/description/)

## Question Pool
- [K Distinct Character](https://github.com/cogrammers/Algorithm/tree/master/kDistinctChar)
- [Valid Parenthesis](https://github.com/cogrammers/Algorithm/tree/master/validParenthesis)


## Coding Style
[Google Coding Style](https://google.github.io/styleguide/javaguide.html)

# Data Structures

How do we do this one?
1. We can vote the topic for the next meetup and do flash talk(15min?).
2. Have someone talks about it during the meetup.(more like a short class?? it may be really dry!)
