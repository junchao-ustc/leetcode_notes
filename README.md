# tleetcode_notes

**当前总题数：132(不包含重复题目)**

## 树

[递归&前中后层遍历](https://github.com/junchao-ustc/leetcode_notes/blob/main/tree/%E9%80%92%E5%BD%92%26%E5%89%8D%E4%B8%AD%E5%90%8E%E5%B1%82%E9%81%8D%E5%8E%86.md)

[BST&Trie](https://github.com/junchao-ustc/leetcode_notes/blob/main/tree/BST%26Trie.md)

[构建树](https://github.com/junchao-ustc/leetcode_notes/blob/main/tree/%E6%9E%84%E5%BB%BA%E6%A0%91.md)

### 刷题统计

**刷题进度：**  67

**刷题表格：**

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 备注                                                 |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | ---------------------------------------------------- |
| 94. 二叉树的中序遍历                                         | √      | esay | √    |      | 栈、莫里斯遍历可以重做                               |
| 95. 不同的二叉搜索树 II                                      | √      | mid  | √    | √    | 递归、动态规划                                       |
| 96. 不同的二叉搜索树                                         | √      | mid  |      | √    | 卡特兰数                                             |
| 98. 验证二叉搜索树                                           | √      | mid  |      |      |                                                      |
| 99. 恢复二叉搜索树                                           | √      | mid  |      | √    | 其实再思考一下能想出来                               |
| 100. 相同的树                                                | √      | easy |      |      |                                                      |
| 101. 对称二叉树<br>剑指 Offer 28. 对称的二叉树               | √      | easy |      |      |                                                      |
| 102. 二叉树的层序遍历<br>剑指 Offer 32 - II. 从上到下打印二叉树 II | √      | mid  |      |      | 模板                                                 |
| 103. 二叉树的锯齿形层序遍历<br>剑指 Offer 32 - I. 从上到下打印二叉树<br>剑指 Offer 32 - III. 从上到下打印二叉树 III | √      | mid  |      |      |                                                      |
| 104. 二叉树的最大深度<br>剑指 Offer 55 - I. 二叉树的深度     | √      | easy |      |      |                                                      |
| 105. 从前序与中序遍历序列构造二叉树<br>剑指 Offer 07. 重建二叉树 | √      | mid  |      |      |                                                      |
| 106. 从中序与后序遍历序列构造二叉树                          | √      | mid  | √    |      |                                                      |
| 107. 二叉树的层序遍历 II                                     | √      | mid  |      |      |                                                      |
| 108. 将有序数组转换为二叉搜索树                              | √      | esay |      |      | 好好分析，能做出来                                   |
| 109. 有序链表转换二叉搜索树                                  | √      | mid  | √    |      | 快慢指针、中序遍历                                   |
| 110. 平衡二叉树<br>剑指 Offer 55 - II. 平衡二叉树            | √      | easy |      |      | 阻断可以看下                                         |
| 111. 二叉树的最小深度                                        | √      | esay |      |      |                                                      |
| 112. 路径总和                                                | √      | easy |      |      | 代码优化                                             |
| 113. 路径总和 II<br>剑指 Offer 34. 二叉树中和为某一值的路径  | √      | mid  |      |      |                                                      |
| 114. 二叉树展开为链表                                        | √      | mid  |      | √    | Morris遍历、递归、迭代                               |
| 116. 填充每个节点的下一个右侧节点指针                        | √      | mid  | √    |      | 常量辅助空间迭代和递归                               |
| 117. 填充每个节点的下一个右侧节点指针 II                     | √      | mid  |      | √    | 运用链表思维                                         |
| 124. 二叉树中的最大路径和                                    | √      | hard |      |      |                                                      |
| 129. 求根节点到叶节点数字之和                                | √      | mid  |      |      |                                                      |
| 144. 二叉树的前序遍历                                        | √      | esay |      |      |                                                      |
| 145. 二叉树的后序遍历                                        | √      | esay |      | √    | 中右左->左右中                                       |
| 199. 二叉树的右视图                                          | √      | mid  |      |      |                                                      |
| 208. 实现 Trie (前缀树)                                      | √      | mid  |      | √    | 关键在于构造TrieNode                                 |
| 222. 完全二叉树的节点个数                                    | √      | mid  | √    |      | 计算方式没弄好                                       |
| 226. 翻转二叉树                                              | √      | esay |      |      |                                                      |
| 230. 二叉搜索树中第K小的元素<br>剑指 Offer 54. 二叉搜索树的第k大节点 | √      | mid  |      |      |                                                      |
| 235. 二叉搜索树的最近公共祖先<br>剑指 Offer 68 - I. 二叉搜索树的最近公共祖先 | √      | esay |      |      |                                                      |
| 236. 二叉树的最近公共祖先<br>剑指 Offer 68 - II. 二叉树的最近公共祖先 | √      | mid  |      |      |                                                      |
| 257. 二叉树的所有路径                                        | √      | esay |      |      |                                                      |
| 297. 二叉树的序列化与反序列化<br>剑指 Offer 37. 序列化二叉树 | √      | hard |      | √    | 反序列化，可以利用先序跟队列                         |
| 337. 打家劫舍 III                                            | √      | mid  |      | √    | 大致上能写递归、记忆化，<br />动态规划不熟，没写出来 |
| 404. 左叶子之和                                              | √      | easy |      |      | 代码优化                                             |
| 429. N 叉树的层序遍历                                        | √      | mid  |      |      |                                                      |
| 437. 路径总和 III                                            | √      | mid  | √    |      | 前缀和没写出来                                       |
| 450. 删除二叉搜索树中的节点                                  | √      | mid  |      | √    | 没有分清情况。没有利用好搜索树特性                   |
| 501. 二叉搜索树中的众数                                      | √      | esay |      | √    | 思路想到了，但是代码没写好                           |
| 513. 找树左下角的值                                          | √      | mid  |      |      |                                                      |
| 515. 在每个树行中找最大值                                    | √      | mid  |      |      |                                                      |
| 530. 二叉搜索树的最小绝对差                                  | √      | easy |      |      |                                                      |
| 538. 把二叉搜索树转换为累加树                                | √      | mid  |      |      |                                                      |
| 543. 二叉树的直径                                            | √      | esay |      |      |                                                      |
| 572. 另一棵树的子树                                          | √      | esay |      |      |                                                      |
| 617. 合并二叉树                                              | √      | easy |      |      |                                                      |
| 637. 二叉树的层平均值                                        | √      | esay |      |      |                                                      |
| 652. 寻找重复的子树                                          | √      | mid  |      | √    | 序列化                                               |
| 653. 两数之和 IV - 输入 BST                                  | √      | easy |      |      |                                                      |
| 654. 最大二叉树                                              | √      | mid  |      |      |                                                      |
| 669. 修剪二叉搜索树                                          | √      | mid  |      | √    | 怎么将下层符合节点传给上层                           |
| 671. 二叉树中第二小的节点                                    | √      | easy |      | √    | 没有读懂题目，想到最优解                             |
| 677. 键值映射                                                | √      | mid  |      | √    | 前缀树基础上增加递归。                               |
| 687. 最长同值路径                                            | √      | mid  |      | √    | 其实可以类比路径之和                                 |
| 700. 二叉搜索树中的搜索                                      | √      | esay |      |      |                                                      |
| 701. 二叉搜索树中的插入操作                                  | √      | mid  |      | √    | 不熟悉                                               |
| 872. 叶子相似的树                                            | √      | esay |      | √    | 有思路，但代码不优雅                                 |
| 938. 二叉搜索树的范围和                                      | √      | esay |      |      |                                                      |
| 993. 二叉树的堂兄弟节点                                      | √      | easy |      | √    | 看似简单题实则那么不简单，深搜广搜均可               |
| 1038. 把二叉搜索树转换为累加树                               | √      | mid  |      |      |                                                      |
| 1373. 二叉搜索子树的最大键值和                               | √      | hard |      | √    | 思路正确，代码有误，时间复杂度高                     |
| 剑指 Offer 26. 树的子结构                                    | √      | mid  |      |      |                                                      |
| 剑指 Offer 27. 二叉树的镜像                                  | √      | esay |      |      |                                                      |
| 剑指 Offer 33. 二叉搜索树的后序遍历序列                      | √      | mid  |      | √    | 看了答案的思路分治自己写出来，单调栈没写出来         |
| 剑指 Offer 36. 二叉搜索树与双向链表                          | √      | mid  |      | √    | 思路大致正确，但没有考虑周全空节点跟收尾连接问题     |

## 动态规划

### 刷题统计

刷题数量：57

刷题表格：

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 分类                                  | 备注                                 |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | ------------------------------------- | ------------------------------------ |
| 5. 最长回文子串                                              | ✔      | mid  |      |      | [回文串.md](dp\回文串.md)             | 中心扩散                             |
| [32. 最长有效括号](https://leetcode-cn.com/problems/longest-valid-parentheses/) | ✔      | hard | ✔    | ✔    | [匹配问题.md](dp\匹配问题.md)         | 动态规划、栈、双指针                 |
| 53. 最大子数组和                                             | ✔      | esay |      |      | [子序列.md](dp\子序列.md)             |                                      |
| 62. 不同路径                                                 | ✔      | mid  |      |      | [矩阵路径.md](dp\矩阵路径.md)         |                                      |
| [63. 不同路径 II](https://leetcode-cn.com/problems/unique-paths-ii/) | ✔      | mid  | ✔    |      | [矩阵路径.md](dp\矩阵路径.md)         | 初始化没处理好，解答太慢了           |
| 64. 最小路径和                                               | ✔      | mid  |      |      | [矩阵路径.md](dp\矩阵路径.md)         |                                      |
| 70. 爬楼梯<br>[509. 斐波那契数](https://leetcode-cn.com/problems/fibonacci-number/) | ✔      | esay |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |
| 72. 编辑距离                                                 | ✔      | hard |      |      | [编辑距离.md](dp\编辑距离.md)         |                                      |
| 91. 解码方法                                                 | ✔      | mid  |      |      | [分割整数.md](dp\分割整数.md)         | 做出，但不熟练                       |
| 115. 不同的子序列                                            | ✔      | hard |      | ✔    | [编辑距离.md](dp\编辑距离.md)         | 当匹配的时候，有两种策略             |
| [118. 杨辉三角](https://leetcode-cn.com/problems/pascals-triangle/) | ✔      | easy |      |      | [数学.md](dp\数学.md)                 | 构建pre、cur列表                     |
| 119. 杨辉三角 II                                             | ✔      | esay |      |      | [数学.md](dp\数学.md)                 |                                      |
| [120. 三角形最小路径和](https://leetcode-cn.com/problems/triangle/) | ✔      | mid  | ✔    | ✔    | [矩阵路径.md](dp\矩阵路径.md)         | 回溯超时，动态规划应自底向上比较简单 |
| 121. 买卖股票的最佳时机<br>[剑指 Offer 63. 股票的最大利润](https://leetcode-cn.com/problems/gu-piao-de-zui-da-li-run-lcof/) | ✔      | esay |      |      | [股票问题.md](dp\股票问题.md)         |                                      |
| 122. 买卖股票的最佳时机 II                                   | ✔      | mid  |      |      | [股票问题.md](dp\股票问题.md)         |                                      |
| 123. 买卖股票的最佳时机 III                                  | ✔      | hard |      | ✔    | [股票问题.md](dp\股票问题.md)         | 三维，也可以穷举                     |
| 139. 单词拆分                                                | ✔      | mid  | ✔    | ✔    | [背包问题.md](dp\背包问题.md)         | 分阶段，从后往前匹配                 |
| [152. 乘积最大子数组](https://leetcode-cn.com/problems/maximum-product-subarray/) | ✔      | mid  | ✔    | ✔    | [连续子数组.md](dp\连续子数组.md)     | 当前最大值、最小值和全局最大值       |
| [188. 买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/) | ✔      | hard |      |      | [股票问题.md](dp\股票问题.md)         | 根据123题可以举一反三                |
| 198. 打家劫舍<br>[面试题 17.16. 按摩师](https://leetcode-cn.com/problems/the-masseuse-lcci/) | ✔      | mid  |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |
| 213. 打家劫舍 II                                             | ✔      | mid  |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |
| [221. 最大正方形](https://leetcode-cn.com/problems/maximal-square/) | ✔      | mid  |      |      | [数学.md](dp\数学.md)                 |                                      |
| 279. 完全平方数                                              | ✔      | mid  |      |      | [分割整数.md](dp\分割整数.md)         |                                      |
| 300. 最长递增子序列                                          | ✔      | mid  |      |      | [子序列.md](dp\子序列.md)             |                                      |
| 303. 区域和检索 - 数组不可变                                 | ✔      | esay |      |      | [数组区间.md](dp\数组区间.md)         |                                      |
| 309. 最佳买卖股票时机含冷冻期                                | ✔      | mid  |      | ✔    | [股票问题.md](dp\股票问题.md)         |                                      |
| 322. 零钱兑换                                                | ✔      | mid  |      |      | [背包问题.md](dp\背包问题.md)         |                                      |
| [338. 比特位计数](https://leetcode-cn.com/problems/counting-bits/) | ✔      | esay |      | ✔    | [数学.md](dp\数学.md)                 | 思路不清晰，耗时太久了               |
| 343. 整数拆分<br>[剑指 Offer 14- I. 剪绳子](https://leetcode-cn.com/problems/jian-sheng-zi-lcof/) | ✔      | mid  |      |      | [分割整数.md](dp\分割整数.md)         | 分类讨论                             |
| 377. 组合总和 Ⅳ                                              | ✔      | mid  | ✔    | ✔    | [背包问题.md](dp\背包问题.md)         | 组合问题，应该从子问题中得归纳出来   |
| 392. 判断子序列                                              | ✔      | esay |      |      | [编辑距离.md](dp\编辑距离.md)         |                                      |
| 413. 等差数列划分                                            | ✔      | mid  | ✔    |      | [数组区间.md](dp\数组区间.md)         | 动态规划比滑动窗口更简便             |
| 416. 分割等和子集                                            | ✔      | mid  |      |      | [背包问题.md](dp\背包问题.md)         |                                      |
| 435. 无重叠区间                                              | ✔      | mid  |      |      | [子序列.md](dp\子序列.md)             | 跟646类似                            |
| 452. 用最少数量的箭引爆气球                                  | ✔      | mid  |      |      | [子序列.md](dp\子序列.md)             | 有坑                                 |
| 474. 一和零                                                  | ✔      | mid  | ✔    | ✔    | [背包问题.md](dp\背包问题.md)         | 二维0-1背包                          |
| 494. 目标和                                                  | ✔      | mid  |      |      | [背包问题.md](dp\背包问题.md)         |                                      |
| [516. 最长回文子序列](https://leetcode-cn.com/problems/longest-palindromic-subsequence/) | ✔      | mid  | ✔    | ✔    | [回文串.md](dp\回文串.md)             | 没有独立思考出状态方程               |
| 518. 零钱兑换 II                                             | ✔      | mid  | ✔    | ✔    | [背包问题.md](dp\背包问题.md)         | 没有充分理解，类似爬楼梯             |
| 583. 两个字符串的删除操作                                    | ✔      | mid  |      |      | [编辑距离.md](dp\编辑距离.md)         |                                      |
| 646. 最长数对链                                              | ✔      | mid  | ✔    |      | [子序列.md](dp\子序列.md)             | 画图讨论、贪心                       |
| [647. 回文子串](https://leetcode-cn.com/problems/palindromic-substrings/) | ✔      | mid  |      | ✔    | [回文串.md](dp\回文串.md)             | 动态规划或中心扩展                   |
| 650. 只有两个键的键盘                                        | ✔      | mid  |      | ✔    | [编辑距离.md](dp\编辑距离.md)         | 解题耗时长                           |
| 674. 最长连续递增序列                                        | ✔      | esay |      |      | [子序列.md](dp\子序列.md)             |                                      |
| 714. 买卖股票的最佳时机含手续费                              | ✔      | mid  |      |      | [股票问题.md](dp\股票问题.md)         | 参考状态机                           |
| 718. 最长重复子数组                                          | ✔      | mid  |      |      | [子序列.md](dp\子序列.md)             |                                      |
| [746. 使用最小花费爬楼梯](https://leetcode-cn.com/problems/min-cost-climbing-stairs/) | ✔      | easy |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |
| 1035. 不相交的线                                             | ✔      | mid  |      |      | [子序列.md](dp\子序列.md)             |                                      |
| [1137. 第 N 个泰波那契数](https://leetcode-cn.com/problems/n-th-tribonacci-number/) | ✔      | esay |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |
| 1143. 最长公共子序列                                         | ✔      | mid  |      |      | [子序列.md](dp\子序列.md)             |                                      |
| [1049. 最后一块石头的重量 II](https://leetcode-cn.com/problems/last-stone-weight-ii/) | ✔      | mid  |      | ✔    | [背包问题.md](dp\背包问题.md)         | 0-1背包                              |
| [剑指 Offer 10- I. 斐波那契数列](https://leetcode-cn.com/problems/fei-bo-na-qi-shu-lie-lcof/)<br>[剑指 Offer 10- II. 青蛙跳台阶问题](https://leetcode-cn.com/problems/qing-wa-tiao-tai-jie-wen-ti-lcof/) | ✔      | esay |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |
| [剑指 Offer 42. 连续子数组的最大和](https://leetcode-cn.com/problems/lian-xu-zi-shu-zu-de-zui-da-he-lcof/) | ✔      | esay |      |      | [连续子数组.md](dp\连续子数组.md)     |                                      |
| [剑指 Offer 46. 把数字翻译成字符串](https://leetcode-cn.com/problems/ba-shu-zi-fan-yi-cheng-zi-fu-chuan-lcof/) | ✔      | mid  |      | ✔    | [分割整数.md](dp\分割整数.md)         | 没处理好无法多翻译子串细节           |
| [剑指 Offer 47. 礼物的最大价值](https://leetcode-cn.com/problems/li-wu-de-zui-da-jie-zhi-lcof/) | ✔      | mid  |      |      | [矩阵路径.md](dp\矩阵路径.md)         |                                      |
| 原创题：信件错排                                             | ✔      | mid  | ✔    | ✔    | [斐波那契数列.md](dp\斐波那契数列.md) | 花了很长时间理解答案                 |
| 原创题：母牛生产                                             | ✔      | mid  |      |      | [斐波那契数列.md](dp\斐波那契数列.md) |                                      |

## 回溯

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 备注           |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | -------------- |
| [22. 括号生成](https://leetcode-cn.com/problems/generate-parentheses/) | ✔      | mid  |      |      | 找好三个if条件 |

## 贪心

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 备注 |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | ---- |
| [45. 跳跃游戏 II](https://leetcode-cn.com/problems/jump-game-ii/) | ✔      | mid  |      |      |      |
| [55. 跳跃游戏](https://leetcode-cn.com/problems/jump-game/)  | ✔      | mid  |      |      |      |
| 376. 摆动序列                                                | ✔      | mid  | ✔    |      |      |

## 双指针

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 备注 |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | ---- |
| [42. 接雨水](https://leetcode-cn.com/problems/trapping-rain-water/) | ✔      | hard |      |      |      |

## 搜索

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 分类                           | 备注    |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | ------------------------------ | ------- |
| [剑指 Offer 13. 机器人的运动范围](https://leetcode-cn.com/problems/ji-qi-ren-de-yun-dong-fan-wei-lcof/) | ✔      | mid  |      |      | [dfs.md](search\dfs.md)        |         |
| [542. 01 矩阵](https://leetcode-cn.com/problems/01-matrix/)  | ✔      | mid  |      | ✔    | [bfs.md](search\bfs.md) <br>dp |         |
| [1162. 地图分析](https://leetcode-cn.com/problems/as-far-from-land-as-possible/) | ✔      | mid  |      |      | [bfs.md](search\bfs.md) <br>dp | 同542题 |

## 栈、队列与堆

| 题目                                                         | 已完成 | 难度 | 好题 | 错题 | 分类                                    | 备注           |
| ------------------------------------------------------------ | ------ | ---- | ---- | ---- | --------------------------------------- | -------------- |
| [84. 柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/) | ✔      | hard |      | ✔    | [单调栈.md](stack&queue&heap\单调栈.md) | 对单调栈不熟悉 |
| [85. 最大矩形](https://leetcode-cn.com/problems/maximal-rectangle/) | ✔      | hard |      |      | [单调栈.md](stack&queue&heap\单调栈.md) | 参考上题       |

