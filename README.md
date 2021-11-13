# leetcode_notes

## 树

[递归&前中后层遍历](https://github.com/junchao-ustc/leetcode_notes/blob/main/tree/%E9%80%92%E5%BD%92%26%E5%89%8D%E4%B8%AD%E5%90%8E%E5%B1%82%E9%81%8D%E5%8E%86.md)

[BST&Trie](https://github.com/junchao-ustc/leetcode_notes/blob/main/tree/BST%26Trie.md)

[构建树](https://github.com/junchao-ustc/leetcode_notes/blob/main/tree/%E6%9E%84%E5%BB%BA%E6%A0%91.md)

### 刷题统计

**刷题进度：**  54

**刷题表格：**

| 题目                                     | 已完成 | 难度 | 好题 | 错题 | 备注                                                 |
| ---------------------------------------- | ------ | ---- | ---- | ---- | ---------------------------------------------------- |
| 94. 二叉树的中序遍历                     | √      | esay | √    |      | 栈、莫里斯遍历可以重做                               |
| 95. 不同的二叉搜索树 II                  | √      | mid  | √    | √    | 递归、动态规划                                       |
| 96. 不同的二叉搜索树                     | √      | mid  |      | √    | 卡特兰数                                             |
| 98. 验证二叉搜索树                       | √      | mid  |      |      |                                                      |
| 99. 恢复二叉搜索树                       | √      | mid  |      | √    | 其实再思考一下能想出来                               |
| 100. 相同的树                            | √      | easy |      |      |                                                      |
| 101. 对称二叉树                          | √      | easy |      |      |                                                      |
| 102. 二叉树的层序遍历                    | √      | mid  |      |      | 模板                                                 |
| 104. 二叉树的最大深度                    | √      | easy |      |      |                                                      |
| 105. 从前序与中序遍历序列构造二叉树      | √      | mid  |      |      |                                                      |
| 106. 从中序与后序遍历序列构造二叉树      | √      | mid  | √    |      |                                                      |
| 107. 二叉树的层序遍历 II                 | √      | mid  |      |      |                                                      |
| 108. 将有序数组转换为二叉搜索树          | √      | esay |      |      | 好好分析，能做出来                                   |
| 109. 有序链表转换二叉搜索树              | √      | mid  | √    |      | 快慢指针、中序遍历                                   |
| 110. 平衡二叉树                          | √      | easy |      |      | 阻断可以看下                                         |
| 111. 二叉树的最小深度                    | √      | esay |      |      |                                                      |
| 112. 路径总和                            | √      | easy |      |      | 代码优化                                             |
| 114. 二叉树展开为链表                    | √      | mid  |      | √    | Morris遍历、递归、迭代                               |
| 116. 填充每个节点的下一个右侧节点指针    | √      | mid  | √    |      | 常量辅助空间迭代和递归                               |
| 117. 填充每个节点的下一个右侧节点指针 II | √      | mid  |      | √    | 运用链表思维                                         |
| 124. 二叉树中的最大路径和                | √      | hard |      |      |                                                      |
| 144. 二叉树的前序遍历                    | √      | esay |      |      |                                                      |
| 145. 二叉树的后序遍历                    | √      | esay |      | √    | 中右左->左右中                                       |
| 199. 二叉树的右视图                      | √      | mid  |      |      |                                                      |
| 208. 实现 Trie (前缀树)                  | √      | mid  |      | √    | 关键在于构造TrieNode                                 |
| 226. 翻转二叉树                          | √      | esay |      |      |                                                      |
| 230. 二叉搜索树中第K小的元素             | √      | mid  |      |      |                                                      |
| 235. 二叉搜索树的最近公共祖先            | √      | esay |      |      |                                                      |
| 236. 二叉树的最近公共祖先                | √      | mid  |      |      |                                                      |
| 297. 二叉树的序列化与反序列化            | √      | hard |      | √    | 反序列化，可以利用先序跟队列                         |
| 337. 打家劫舍 III                        | √      | mid  |      | √    | 大致上能写递归、记忆化，<br />动态规划不熟，没写出来 |
| 404. 左叶子之和                          | √      | easy |      |      | 代码优化                                             |
| 429. N 叉树的层序遍历                    | √      | mid  |      |      |                                                      |
| 437. 路径总和 III                        | √      | mid  | √    |      | 前缀和没写出来                                       |
| 450. 删除二叉搜索树中的节点              | √      | mid  |      | √    | 没有分清情况。没有利用好搜索树特性                   |
| 501. 二叉搜索树中的众数                  | √      | esay |      | √    | 思路想到了，但是代码没写好                           |
| 513. 找树左下角的值                      | √      | mid  |      |      |                                                      |
| 515. 在每个树行中找最大值                | √      | mid  |      |      |                                                      |
| 530. 二叉搜索树的最小绝对差              | √      | easy |      |      |                                                      |
| 538. 把二叉搜索树转换为累加树            | √      | mid  |      |      |                                                      |
| 543. 二叉树的直径                        | √      | esay |      |      |                                                      |
| 572. 另一棵树的子树                      | √      | esay |      |      |                                                      |
| 617. 合并二叉树                          | √      | easy |      |      |                                                      |
| 652. 寻找重复的子树                      | √      | mid  |      | √    | 序列化                                               |
| 653. 两数之和 IV - 输入 BST              | √      | easy |      |      |                                                      |
| 654. 最大二叉树                          | √      | mid  |      |      |                                                      |
| 669. 修剪二叉搜索树                      | √      | mid  |      | √    | 怎么将下层符合节点传给上层                           |
| 671. 二叉树中第二小的节点                | √      | easy |      | √    | 没有读懂题目，想到最优解                             |
| 677. 键值映射                            | √      | mid  |      | √    | 前缀树基础上增加递归。                               |
| 687. 最长同值路径                        | √      | mid  |      | √    | 其实可以类比路径之和                                 |
| 700. 二叉搜索树中的搜索                  | √      | esay |      |      |                                                      |
| 701. 二叉搜索树中的插入操作              | √      | mid  |      | √    | 不熟悉                                               |
| 1038. 把二叉搜索树转换为累加树           | √      | mid  |      |      |                                                      |

