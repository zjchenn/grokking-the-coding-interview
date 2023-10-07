# Grokking the Coding Interview

秋招时整理的 [Grokking the Coding Interview: Patterns for Coding Questions](https://www.educative.io/courses/grokking-the-coding-interview) 上对应的大部分 LeetCode 中文区的题目，归档自用。

## Pattern: Sliding Window

|  id  | title                                                      | leetcode-cn                                                  |     comment      |
| :--: | :--------------------------------------------------------- | :----------------------------------------------------------- | :--------------: |
|  1   | Maximum Sum Subarray of Size K                             | [53. 最大子数组和](https://leetcode.cn/problems/maximum-subarray/) | similar question |
|  2   | Smallest Subarray with a given sum                         | [209. 长度最小的子数组](https://leetcode.cn/problems/minimum-size-subarray-sum/) |                  |
|  3   | Longest Substring with K Distinct Characters               | [340. 至多包含 K 个不同字符的最长子串](https://leetcode.cn/problems/longest-substring-with-at-most-k-distinct-characters/) |     plus会员     |
|  4   | Fruits into Baskets                                        | [904. 水果成篮](https://leetcode.cn/problems/fruit-into-baskets/) |                  |
|  5   | No-repeat Substring                                        | [3. 无重复字符的最长子串](https://leetcode.cn/problems/longest-substring-without-repeating-characters/) |                  |
|  6   | Longest Substring with Same Letters after Replacement      | [424. 替换后的最长重复字符](https://leetcode.cn/problems/longest-repeating-character-replacement/) |                  |
|  7   | Longest Subarray with Ones after Replacement               | [1004. 最大连续1的个数 III](https://leetcode.cn/problems/max-consecutive-ones-iii/) |                  |
|  8   | Problem Challenge 1 - Permutation in a String              | [567. 字符串的排列](https://leetcode.cn/problems/permutation-in-string/) |                  |
|  9   | Problem Challenge 2 - String Anagrams                      | [438. 找到字符串中所有字母异位词](https://leetcode.cn/problems/find-all-anagrams-in-a-string/) |                  |
|  10  | Problem Challenge 3 - Smallest Window containing Substring | [76. 最小覆盖子串](https://leetcode.cn/problems/minimum-window-substring/) |                  |
|  11  | Problem Challenge 4 - Words Concatenation                  | [30. 串联所有单词的子串](https://leetcode.cn/problems/substring-with-concatenation-of-all-words/) |                  |

## Pattern: Two Pointers

|  id  | title                                                        | leetcode-cn                                                  | comment  |
| :--: | :----------------------------------------------------------- | :----------------------------------------------------------- | :------: |
|  1   | Pair with Target Sum                                         | [167. 两数之和 II - 输入有序数组](https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/) |          |
|  2   | Remove Duplicates                                            | [26. 删除有序数组中的重复项](https://leetcode.cn/problems/remove-duplicates-from-sorted-array/) |          |
|  3   | Squaring a Sorted Array                                      | [977. 有序数组的平方](https://leetcode.cn/problems/squares-of-a-sorted-array/) |          |
|  4   | Triplet Sum to Zero                                          | [15. 三数之和](https://leetcode.cn/problems/3sum/)           |          |
|  5   | Triplet Sum Close to Target                                  | [16. 最接近的三数之和](https://leetcode.cn/problems/3sum-closest/) |          |
|  6   | Triplets with Smaller Sum                                    | [259. 较小的三数之和](https://leetcode.cn/problems/3sum-smaller) | plus会员 |
|  7   | Subarrays with Product Less than a Target                    | [713. 乘积小于K的子数组](https://leetcode.cn/problems/subarray-product-less-than-k/) |          |
|  8   | Dutch National Flag Problem                                  | [75. 颜色分类](https://leetcode.cn/problems/sort-colors/)    |          |
|  9   | Problem Challenge 1 - Quadruple Sum to Target                | [18. 四数之和](https://leetcode.cn/problems/4sum/)           |          |
|  10  | Problem Challenge 2 - Comparing Strings containing Backspaces | [844. 比较含退格的字符串](https://leetcode.cn/problems/backspace-string-compare/) |          |
|  11  | Problem Challenge 3 - Minimum Window Sort                    | [581. 最短无序连续子数组](https://leetcode.cn/problems/shortest-unsorted-continuous-subarray/) |          |

## Pattern: Fast & Slow pointers

|  id  | title                                           | leetcode-cn                                                  | comment |
| :--: | :---------------------------------------------- | :----------------------------------------------------------- | :-----: |
|  1   | LinkedList Cycle                                | [141. 环形链表](https://leetcode.cn/problems/linked-list-cycle/) |         |
|  2   | Middle of the LinkedList                        | [142. 环形链表 II](https://leetcode.cn/problems/linked-list-cycle-ii/) |         |
|  3   | Start of LinkedList Cycle                       | [202. 快乐数](https://leetcode.cn/problems/happy-number/)    |         |
|  4   | Happy Number                                    | [876. 链表的中间结点](https://leetcode.cn/problems/middle-of-the-linked-list/) |         |
|  5   | Problem Challenge 1 - Palindrome LinkedList     | [234. 回文链表](https://leetcode.cn/problems/palindrome-linked-list/) |         |
|  6   | Problem Challenge 2 - Rearrange a LinkedList    | [143. 重排链表](https://leetcode.cn/problems/reorder-list/)  |         |
|  7   | Problem Challenge 3 - Cycle in a Circular Array | [457. 环形数组是否存在循环](https://leetcode.cn/problems/circular-array-loop/) |         |

## Pattern: Merge Intervals

|  id  | title                                       | leetcode-cn                                                  | comment  |
| :--: | :------------------------------------------ | :----------------------------------------------------------- | :------: |
|  1   | Merge Intervals                             | [56. 合并区间](https://leetcode.cn/problems/merge-intervals/) |          |
|  2   | Insert Interval                             | [57. 插入区间](https://leetcode.cn/problems/insert-interval/) |          |
|  3   | Intervals Intersection                      | [986. 区间列表的交集](https://leetcode.cn/problems/interval-list-intersections/) |          |
|  4   | Conflicting Appointments                    | 应该是 [252. 会议室](https://leetcode.cn/problems/meeting-rooms) | plus会员 |
|  5   | Problem Challenge 1 - Minimum Meeting Rooms | [253. 会议室 II](https://leetcode.cn/problems/meeting-rooms-ii) | plus会员 |
|  6   | Problem Challenge 2 - Maximum CPU Load      |                                                              |          |
|  7   | Problem Challenge 3 - Employee Free Time    | [759. 员工空闲时间](https://leetcode.cn/problems/employee-free-time) | plus会员 |

- Problem Challenge 2: Could not find equivalent. Given a list of intervals with values, find the peak sum (i.e. if intervals are overlapping, sum their values)

## Pattern: Cyclic Sort

|  id  | title                                                        | leetcode-cn                                                  |     comment      |
| :--: | :----------------------------------------------------------- | :----------------------------------------------------------- | :--------------: |
|  1   | Cyclic Sort                                                  |                                                              |                  |
|  2   | Find the Missing Number                                      | [268. 丢失的数字](https://leetcode.cn/problems/missing-number/) |                  |
|  3   | Find all Missing Numbers                                     | [448. 找到所有数组中消失的数字](https://leetcode.cn/problems/find-all-numbers-disappeared-in-an-array/) |                  |
|  4   | Find the Duplicate Number                                    |                                                              | 是下一题的简化版 |
|  5   | Find all Duplicate Numbers                                   | [442. 数组中重复的数据](https://leetcode.cn/problems/find-all-duplicates-in-an-array/) |                  |
|  6   | Problem Challenge 1 - Find the Corrupt Pair                  |                                                              |                  |
|  7   | Problem Challenge 2 - Find the Smallest Missing Positive Number | [41. 缺失的第一个正数](https://leetcode.cn/problems/first-missing-positive/) |                  |
|  8   | Problem Challenge 3 - Find the First K Missing Positive Numbers | [1539. 第 k 个缺失的正整数](https://leetcode.cn/problems/kth-missing-positive-number/) |                  |

- Cyclic Sort: Couldn't find equivalent for the first question. The second question below encompasses the first one though. See <https://leetcode.com/problems/missing-number/discuss/859510/C%2B%2B-O(N)-O(1)-using-Cyclic-Sort> for how grokking the coding interview approached these problems. It uses the fact that we can sort the array in O(n) without comparison operators
- Problem Challenge 1: combine <https://leetcode.cn/problems/find-the-duplicate-number/> and <https://leetcode.cn/problems/missing-number/>

## Pattern: In-place Reversal of a LinkedList

|  id  | title                                                        | leetcode-cn                                                  | comment |
| :--: | :----------------------------------------------------------- | :----------------------------------------------------------- | :-----: |
|  1   | Reverse a LinkedList                                         | [206. 反转链表](https://leetcode.cn/problems/reverse-linked-list/) |         |
|  2   | Reverse a Sub-list                                           | [92. 反转链表 II](https://leetcode.cn/problems/reverse-linked-list-ii/) |         |
|  3   | Reverse every K-element Sub-list                             | [25. K 个一组翻转链表](https://leetcode.cn/problems/reverse-nodes-in-k-group/) |         |
|  4   | Problem Challenge 1 - Reverse alternating K-element Sub-list | Next question is the same, but alternate each subgroup       |         |
|  5   | Problem Challenge 2 - Rotate a LinkedList                    | [61. 旋转链表](https://leetcode.cn/problems/rotate-list/)    |         |

## Pattern: Tree Breadth First Search

|  id  | title                                                  | leetcode-cn                                                  |     comment      |
| :--: | :----------------------------------------------------- | :----------------------------------------------------------- | :--------------: |
|  1   | Binary Tree Level Order Traversal                      | [102. 二叉树的层序遍历](https://leetcode.cn/problems/binary-tree-level-order-traversal/) |                  |
|  2   | Reverse Level Order Traversal                          | [107. 二叉树的层序遍历 II](https://leetcode.cn/problems/binary-tree-level-order-traversal-ii/) |                  |
|  3   | Zigzag Traversal                                       | [103. 二叉树的锯齿形层序遍历](https://leetcode.cn/problems/binary-tree-zigzag-level-order-traversal/) |                  |
|  4   | Level Averages in a Binary Tree                        | [637. 二叉树的层平均值](https://leetcode.cn/problems/average-of-levels-in-binary-tree/) |                  |
|  5   | Minimum Depth of a Binary Tree                         | [111. 二叉树的最小深度](https://leetcode.cn/problems/minimum-depth-of-binary-tree/) |                  |
|  6   | Level Order Successor                                  | [285. 二叉搜索树中的中序后继](https://leetcode.cn/problems/inorder-successor-in-bst) | similar question |
|  7   | Connect Level Order Siblings                           | [116. 填充每个节点的下一个右侧节点指针](https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/) | similar question |
|  8   | Problem Challenge 1 - Connect All Level Order Siblings | Next question is the same, but connect end nodes to the next level instead of null |                  |
|  9   | Problem Challenge 2 - Right View of a Binary Tree      | [199. 二叉树的右视图](https://leetcode.cn/problems/binary-tree-right-side-view/) |                  |

## Pattern: Tree Depth First Search

|  id  | title                                       | leetcode-cn                                                  | comment  |
| :--: | :------------------------------------------ | :----------------------------------------------------------- | :------: |
|  1   | Binary Tree Path Sum                        | [112. 路径总和](https://leetcode.cn/problems/path-sum/)      |          |
|  2   | All Paths for a Sum                         | [113. 路径总和 II](https://leetcode.cn/problems/path-sum-ii/) |          |
|  3   | Sum of Path Numbers                         | [129. 求根节点到叶节点数字之和](https://leetcode.cn/problems/sum-root-to-leaf-numbers/) |          |
|  4   | Path With Given Sequence                    | [1430. 判断给定的序列是否是二叉树从根到叶的路径](https://leetcode.cn/problems/check-if-a-string-is-a-valid-sequence-from-root-to-leaves-path-in-a-binary-tree/) | plus会员 |
|  5   | Count Paths for a Sum                       | [437. 路径总和 III](https://leetcode.cn/problems/path-sum-iii/) |          |
|  6   | Problem Challenge 1 - Tree Diameter         | [543. 二叉树的直径](https://leetcode.cn/problems/diameter-of-binary-tree/) |          |
|  7   | Problem Challenge 2 - Path with Maximum Sum | [124. 二叉树中的最大路径和](https://leetcode.cn/problems/binary-tree-maximum-path-sum/) |          |

## Pattern: Two Heaps

|  id  | title                               | leetcode-cn                                                  | comment |
| :--: | :---------------------------------- | :----------------------------------------------------------- | :-----: |
|  1   | Find the Median of a Number Stream  | [295. 数据流的中位数](https://leetcode.cn/problems/find-median-from-data-stream/) |         |
|  2   | Sliding Window Median               | [480. 滑动窗口中位数](https://leetcode.cn/problems/sliding-window-median/) |         |
|  3   | Maximize Capital                    | [502. IPO](https://leetcode.cn/problems/ipo/)                |         |
|  4   | Problem Challenge 1 - Next Interval | [436. 寻找右区间](https://leetcode.cn/problems/find-right-interval/) |         |

## Pattern: Subsets

|  id  | title                                                        | leetcode-cn                                                  | comment  |
| :--: | :----------------------------------------------------------- | :----------------------------------------------------------- | :------: |
|  1   | Subsets                                                      | [78. 子集](https://leetcode.cn/problems/subsets/)            |          |
|  2   | Subsets With Duplicates                                      | [90. 子集 II](https://leetcode.cn/problems/subsets-ii/)      |          |
|  3   | Permutations                                                 | [46. 全排列](https://leetcode.cn/problems/permutations/)     |          |
|  4   | String Permutations by changing case                         | [784. 字母大小写全排列](https://leetcode.cn/problems/letter-case-permutation/) |          |
|  5   | Balanced Parentheses                                         | [22. 括号生成](https://leetcode.cn/problems/generate-parentheses/) |          |
|  6   | Unique Generalized Abbreviations                             | [320. 列举单词的全部缩写](https://leetcode.cn/problems/generalized-abbreviation) | plus会员 |
|  7   | Problem Challenge 1 - Evaluate Expression                    | [241. 为运算表达式设计优先级](https://leetcode.cn/problems/different-ways-to-add-parentheses/) |          |
|  8   | Problem Challenge 2 - Structurally Unique Binary Search Trees | [95. 不同的二叉搜索树 II](https://leetcode.cn/problems/unique-binary-search-trees-ii/) |          |
|  9   | Problem Challenge 3 - Count of Structurally Unique Binary Search Trees | [96. 不同的二叉搜索树](https://leetcode.cn/problems/unique-binary-search-trees/) |          |

## Pattern: Modified Binary Search

|  id  | title                                         | leetcode-cn                                                  |     comment      |
| :--: | :-------------------------------------------- | :----------------------------------------------------------- | :--------------: |
|  1   | Order-agnostic Binary Search                  | [704. 二分查找](https://leetcode.cn/problems/binary-search/) | similar question |
|  2   | Ceiling of a Number                           | Did not find. Problem is find index of smallest element greater or equal to input value |                  |
|  3   | Next Letter                                   | [744. 寻找比目标字母大的最小字母](https://leetcode.cn/problems/find-smallest-letter-greater-than-target/) |                  |
|  4   | Number Range                                  | [34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/) |                  |
|  5   | Search in a Sorted Infinite Array             | [702. 搜索长度未知的有序数组](https://leetcode.cn/problems/search-in-a-sorted-array-of-unknown-size) |     plus会员     |
|  6   | Minimum Difference Element                    | [658. 找到 K 个最接近的元素](https://leetcode.cn/problems/find-k-closest-elements/) |      当K=1       |
|  7   | Bitonic Array Maximum                         | [852. 山脉数组的峰顶索引](https://leetcode.cn/problems/peak-index-in-a-mountain-array/) |                  |
|  8   | Problem Challenge 1 - Search Bitonic Array    | [1095. 山脉数组中查找目标值](https://leetcode.cn/problems/find-in-mountain-array/) |                  |
|  9   | Problem Challenge 2 - Search in Rotated Array | [33. 搜索旋转排序数组](https://leetcode.cn/problems/search-in-rotated-sorted-array/) |                  |
|  10  | Problem Challenge 3 - Rotation Count          | Similar to previous, but find the number of rotations of the array. |                  |

## Pattern: Bitwise XOR

|  id  | title                        | leetcode-cn                                                  | comment |
| :--: | :--------------------------- | :----------------------------------------------------------- | :-----: |
|  1   | Single Number                | [136. 只出现一次的数字](https://leetcode.cn/problems/single-number/) |         |
|  2   | Two Single Numbers           | [260. 只出现一次的数字 III](https://leetcode.cn/problems/single-number-iii/) |         |
|  3   | Complement of Base 10 Number | [1009. 十进制整数的反码](https://leetcode.cn/problems/complement-of-base-10-integer/) |         |
|  4   | Problem Challenge 1          | [832. 翻转图像](https://leetcode.cn/problems/flipping-an-image/) |         |

## Pattern: Top 'K' Elements

|  id  | title                                                   | leetcode-cn                                                  | comment  |
| :--: | :------------------------------------------------------ | :----------------------------------------------------------- | :------: |
|  1   | Top 'K' Numbers                                         | [215. 数组中的第K个最大元素](https://leetcode.cn/problems/kth-largest-element-in-an-array/) |          |
|  2   | Kth Smallest Number                                     | [215. 数组中的第K个最大元素](https://leetcode.cn/problems/kth-largest-element-in-an-array/) |   同上   |
|  3   | 'K' Closest Points to the title                         | [973. 最接近原点的 K 个点](https://leetcode.cn/problems/k-closest-points-to-origin/) |          |
|  4   | Connect Ropes                                           | [1167. 连接棒材的最低费用](https://leetcode.cn/problems/minimum-cost-to-connect-sticks) | plus会员 |
|  5   | Top 'K' Frequent Numbers                                | [347. 前 K 个高频元素](https://leetcode.cn/problems/top-k-frequent-elements/) |          |
|  6   | Frequency Sort                                          | [451. 根据字符出现频率排序](https://leetcode.cn/problems/sort-characters-by-frequency/) |          |
|  7   | Kth Largest Number in a Stream                          | [703. 数据流中的第 K 大元素](https://leetcode.cn/problems/kth-largest-element-in-a-stream/) |          |
|  8   | 'K' Closest Numbers                                     | [658. 找到 K 个最接近的元素](https://leetcode.cn/problems/find-k-closest-elements/) |          |
|  9   | Maximum Distinct Elements                               | [1481. 不同整数的最少数目](https://leetcode.cn/problems/least-number-of-unique-integers-after-k-removals/) | similar  |
|  10  | Sum of Elements                                         |                                                              |          |
|  11  | Rearrange String                                        | [767. 重构字符串](https://leetcode.cn/problems/reorganize-string/) |          |
|  12  | Problem Challenge 1 - Rearrange String K Distance Apart | [358. K 距离间隔重排字符串](https://leetcode.cn/problems/rearrange-string-k-distance-apart) | plus会员 |
|  13  | Problem Challenge 2 - Scheduling Tasks                  | [621. 任务调度器](https://leetcode.cn/problems/task-scheduler/) |          |
|  14  | Problem Challenge 3 - Frequency Stack                   | [895. 最大频率栈](https://leetcode.cn/problems/maximum-frequency-stack/) |          |

- Maximum Distinct Elements:  [Maximum distinct elements after removing k elements](https://www.geeksforgeeks.org/maximum-distinct-elements-removing-k-elements/) exactly
- Sum of Elements: [Sum of all elements between k1’th and k2’th smallest elements](https://www.geeksforgeeks.org/sum-elements-k1th-k2th-smallest-elements/)

## Pattern: K-way merge

|  id  | title                                           | leetcode-cn                                                  | comment |
| :--: | :---------------------------------------------- | :----------------------------------------------------------- | :-----: |
|  1   | Merge K Sorted Lists                            | [23. 合并K个升序链表](https://leetcode.cn/problems/merge-k-sorted-lists/) |         |
|  2   | Kth Smallest Number in M Sorted Lists           | [23. 合并K个升序链表](https://leetcode.cn/problems/merge-k-sorted-lists/) |  同上   |
|  3   | Kth Smallest Number in a Sorted Matrix          | [378. 有序矩阵中第 K 小的元素](https://leetcode.cn/problems/kth-smallest-element-in-a-sorted-matrix/) |         |
|  4   | Smallest Number Range                           | [632. 最小区间](https://leetcode.cn/problems/smallest-range-covering-elements-from-k-lists/) |         |
|  5   | Problem Challenge 1 - K Pairs with Largest Sums | [373. 查找和最小的 K 对数字](https://leetcode.cn/problems/find-k-pairs-with-smallest-sums/) | similar |

## Pattern : 0/1 Knapsack (Dynamic Programming)

|  id  | title                                     | leetcode-cn                                                  |  comment   |
| :--: | :---------------------------------------- | :----------------------------------------------------------- | :--------: |
|  1   | 0/1 Knapsack                              |                                                              | 01背包问题 |
|  2   | Equal Subset Sum Partition                | [416. 分割等和子集](https://leetcode.cn/problems/partition-equal-subset-sum/) |            |
|  3   | Subset Sum                                |                                                              |            |
|  4   | Minimum Subset Sum Difference             | [1049. 最后一块石头的重量 II](https://leetcode.cn/problems/last-stone-weight-ii/) |  similar   |
|  5   | Problem Challenge 1 - Count of Subset Sum | [40. 组合总和 II](https://leetcode.cn/problems/combination-sum-ii/) |  similar   |
|  6   | Problem Challenge 2 - Target Sum          | [494. 目标和](https://leetcode.cn/problems/target-sum/)      |            |

- 0/1 Knapsack: [educative](https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/RM1BDv71V60)
- Subset Sum: [educative](https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/3j64vRY6JnR)
- 补充题： [474. 一和零](https://leetcode.cn/problems/ones-and-zeroes/)

## Pattern: Topological Sort (Graph)

|  id  | title                                           | leetcode-cn                                                  |    comment    |
| :--: | :---------------------------------------------- | :----------------------------------------------------------- | :-----------: |
|  1   | Topological Sort                                |                                                              | 与下面3题类似 |
|  2   | Tasks Scheduling                                | [207. 课程表](https://leetcode.cn/problems/course-schedule/) |               |
|  3   | Tasks Scheduling Order                          | [210. 课程表 II](https://leetcode.cn/problems/course-schedule-ii/) |               |
|  4   | All Tasks Scheduling Orders                     |                                                              |  与上题类似   |
|  5   | Alien Dictionary                                | [269. 火星词典](https://leetcode.cn/problems/alien-dictionary) |   plus会员    |
|  6   | Problem Challenge 1 - Reconstructing a Sequence | [444. 序列重建](https://leetcode.cn/problems/sequence-reconstruction) |   plus会员    |
|  7   | Problem Challenge 2 - Minimum Height Trees      | [310. 最小高度树](https://leetcode.cn/problems/minimum-height-trees/) |               |

## Miscellaneous

|  id  | title               | leetcode-cn                                                  | comment |
| :--: | :------------------ | :----------------------------------------------------------- | :-----: |
|  1   | Kth Smallest Number | [215. 数组中的第K个最大元素](https://leetcode.cn/problems/kth-largest-element-in-an-array/) |         |

---

# Reference

1. [穷码农的知乎回答](https://www.zhihu.com/question/36738189/answer/908664455)
2. <https://github.com/cl2333/Grokking-the-Coding-Interview-Patterns-for-Coding-Questions>
3. <https://gist.github.com/tykurtz/3548a31f673588c05c89f9ca42067bc4>
4. <https://github.com/dipjul/Grokking-the-Coding-Interview-Patterns-for-Coding-Questions>
