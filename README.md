# BinarySummary

1. 介绍视频： introduction： https://www.youtube.com/watch?app=desktop&v=fAAZixBzIAI 
         常考排序，会问怎么修改？变换要求？big O怎么看？


         depth-first-values： Stack 竖向排序 
         breadth-first-valües： Queue  横向排列
         

         DFS: Preorder  | Inorder | Postorder (Depth First Search)
     root-left-right |left- root-right |bottom-top, left-right 
     N字形
     
         https://www.geeksforgeeks.org/tree-traversals-inorder-preorder-and-postorder/
   
         BFS： level

        用法：
          1）查items - tree includes
          2）查总和 - tree sum
          3）查最小值   - tree min value
          4）Max root to Leaf path summ
        查target是否在binary里面 1） 暴力 2） 看它的子集是否有，否定这个。 ｜｜ or 然后 false or false = false true or false = true
        2. total += current.val
          or
          sum root.left； sum root.right

        3. 用stack来一遍；queue来一遍；root.left+root.right来一遍

         4. 
         选子集最大， 然后和上面相加
         recursion
         maxChildPathSum = Math.max(maxPathSum(root.left), maxPathSum(root.right))
         root.val + maxChildPathSum
         
  2. leetcode 144 （preorder）
  3. leetcode 94 （inorder） 字形上下，先stack全左，再一个个判断右
  4. leetcode 145 （post）倒着的preorder + recursion
  
  5. leetcode 107 非常好! 都记得，但：每层level跟queue的长度走。有for i in range（len（queue））
  6. leetcode 102 顺序
  7. leetcode 103 Z形。完美子！亲爱的崽
  8. leetcode 637 本来就没问题
  9. leetcode 314
  
  
  重看视频。
  把几个题目总结到文档里
  白板弄出过程和演讲方式。
