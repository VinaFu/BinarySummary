# BinarySummary

1. introduction： https://www.youtube.com/watch?app=desktop&v=fAAZixBzIAI 

         depth- first- values： Stack 竖向排序 
            （stack.pop） dfv 参见144.
         breadth-first-valües： Queue  横向排列
            （queue.shift） bfv

         DFS: Preorder  | Inorder | Postorder (Depth First Search)
             left-right |left-leaf-right |bottom-top, left-right 

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
         
  2. leetcode 144
  3. leetcode 94
  4. leetcode 145
  5. leetcode 107
  6. leetcode 102
  7. leetcode 103
  8. leetcode 637
  9. leetcode 314
  
  
  重看视频。
  把几个题目总结到文档里
  白板弄出过程和演讲方式。
