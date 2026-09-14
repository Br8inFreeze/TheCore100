# The Core 100

**English** | [中文](./ReadMe.md)

This list is distilled from my own job-hunting journey over the past few years. If I had an interview next week, these are the 100 problems I would drill this week. I have also worked through some of the popular online lists such as Hot 100 and Grind 75, and based on their pain points plus my real interview experience, I made the following improvements:

1. Some problems simply aren't hot — at least not in the North American SDE/MLE job market. You can often tell by checking LeetCode's built-in company frequency stats, and they rarely show up in interview reports. So I combined my own interview experience with the interview reports I've read to pick the problems that genuinely come up often in North American interviews.
2. Some problems lack representativeness. They're hard to generalize from, they test something obscure, and repeated practice doesn't pay off much. Of course, if you're preparing for a specific company you may see a few of these in its interview reports and they're worth cramming — but I don't think they belong in a curated list.
3. Some lists cover a skewed range of topics and fall short of "essential." For example, a few contain no DP or graph theory at all, even though those remain hot interview topics; others include hard and obscure topics such as TreeMap or segment trees, which I consider unnecessary. This list covers the most mainstream, most common interview topics.

Here are the 100 problems I picked; the numbers are LeetCode problem numbers. Some are worth solving with multiple approaches, and some have several follow-ups that are best handled together, so one full pass is slightly more than 100 problems in practice. On the other hand, a personal list of 100 is inevitably one-sided and incomplete — suggestions are welcome.

## Binary Search
- [Classic binary search - 704](https://leetcode.com/problems/binary-search/description/)
- [Leftmost / rightmost bound (aggressive binary search) - 34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/description/)
- [Transformed array - 33](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)
- [Find peak element - 162](https://leetcode.com/problems/find-peak-element/description/)
- [Median of two arrays - 4](https://leetcode.com/problems/median-of-two-sorted-arrays/description/)
- [Binary search on the answer - 875](https://leetcode.com/problems/koko-eating-bananas/description/)

## Two Pointers
- [Two Sum - 1](https://leetcode.com/problems/two-sum/description/)
- [Three Sum - 15](https://leetcode.com/problems/3sum/description/)
- [Expand from the center - 5](https://leetcode.com/problems/longest-palindromic-substring/description/)
- [Palindrome check - 125](https://leetcode.com/problems/valid-palindrome/description/)
- [Trapping rain water (multiple approaches) - 42](https://leetcode.com/problems/trapping-rain-water/description/)
- [In-place merge of arrays - 88](https://leetcode.com/problems/merge-sorted-array/description/)

## Sliding Window
- [Fixed-size window (basics) - 643](https://leetcode.com/problems/maximum-average-subarray-i/description/)
- [Longest window - 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/description/)
- [Shortest window - 76](https://leetcode.com/problems/minimum-window-substring/description/)
- [Count valid subarrays - 713](https://leetcode.com/problems/subarray-product-less-than-k/description/)

## Sorting
- [Basics — practice different sorting algorithms - 912](https://leetcode.com/problems/sort-an-array/description/)
- [Merge sort - 493](https://leetcode.com/problems/reverse-pairs/description/)
- [Quick sort - 215](https://leetcode.com/problems/kth-largest-element-in-an-array/description/)
- [Bucket sort - 347](https://leetcode.com/problems/top-k-frequent-elements/description/)
- [Rainbow sort - 75](https://leetcode.com/problems/sort-colors/description/)

## String
- [Longest common prefix - 14](https://leetcode.com/problems/longest-common-prefix/description/)
- [Palindrome - 680](https://leetcode.com/problems/valid-palindrome-ii/description/)
- [Abbreviation - 408](https://leetcode.com/problems/valid-word-abbreviation/description/)
- [KMP - 28](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/description/)
- [Manacher - 5](https://leetcode.com/problems/longest-palindromic-substring/description/)

## Hash Table
- [Grouping - 49](https://leetcode.com/problems/group-anagrams/description/)

## Stack
- [Parentheses - 20](https://leetcode.com/problems/valid-parentheses/description/)
- [Remove invalid parentheses - 1249](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/description/)
- [Simplify path - 71](https://leetcode.com/problems/simplify-path/description/)
- [Min stack - 155](https://leetcode.com/problems/min-stack/description/)
- [Arithmetic expressions - 227](https://leetcode.com/problems/basic-calculator-ii/description/)
- [String parsing - 394](https://leetcode.com/problems/decode-string/description/)

## Monotonic Stack
- [Daily temperatures - 739](https://leetcode.com/problems/daily-temperatures/description/)
- [Next greater element - 496](https://leetcode.com/problems/next-greater-element-i/description/)
- [Largest rectangle - 84](https://leetcode.com/problems/largest-rectangle-in-histogram/description/)
- [People in a queue - 1944](https://leetcode.com/problems/number-of-visible-people-in-a-queue/description/)
- [Monotonic queue - 239](https://leetcode.com/problems/sliding-window-maximum/description/)

## Heap / Priority Queue
- [Kth largest - 703](https://leetcode.com/problems/kth-largest-element-in-a-stream/description/)
- [Merge multiple arrays - 23](https://leetcode.com/problems/merge-k-sorted-lists/description/)
- [Ugly number - 264](https://leetcode.com/problems/ugly-number-ii/description/)
- [Find median - 295](https://leetcode.com/problems/find-median-from-data-stream/description/)

## Prefix Sum
- [Range query (1D) - 303](https://leetcode.com/problems/range-sum-query-immutable/description/)
- [Range query (2D) - 304](https://leetcode.com/problems/range-sum-query-2d-immutable/description/)
- [Maximum subarray - 53](https://leetcode.com/problems/maximum-subarray/description/)
- [Prefix sum + sliding window - 209](https://leetcode.com/problems/minimum-size-subarray-sum/description/)
- [Prefix sum + binary search - 528](https://leetcode.com/problems/random-pick-with-weight/description/)
- [Subarray with target sum - 560](https://leetcode.com/problems/subarray-sum-equals-k/description/)
- [Prefix product - 238](https://leetcode.com/problems/product-of-array-except-self/description/)

## Difference Array / Sweep Line
- [Meeting Rooms II - 253](https://leetcode.com/problems/meeting-rooms-ii/description/)
- [Merge intervals - 56](https://leetcode.com/problems/merge-intervals/description/)

## Linked List
- [Reverse linked list - 206](https://leetcode.com/problems/reverse-linked-list/description/)
- [Fast and slow pointers - 876](https://leetcode.com/problems/middle-of-the-linked-list/description/)
- [Two techniques combined - 143](https://leetcode.com/problems/reorder-list/description/)
- [Merge linked lists - 21](https://leetcode.com/problems/merge-two-sorted-lists/description/)
- [Remove the nth node - 19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/description/)
- [Copy a linked list - 138](https://leetcode.com/problems/copy-list-with-random-pointer/description/)
- [Add two numbers - 2](https://leetcode.com/problems/add-two-numbers/description/)
- [LRU - 146](https://leetcode.com/problems/lru-cache/description/)

## Binary Tree
- [Maximum depth - 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/description/)
- [Maximum path sum - 124](https://leetcode.com/problems/binary-tree-maximum-path-sum/description/)
- [Diameter of a tree - 543](https://leetcode.com/problems/diameter-of-binary-tree/description/)
- [LCA - 236](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/description/)
- [Validate BST - 98](https://leetcode.com/problems/validate-binary-search-tree/description/)
- [Right side view - 199](https://leetcode.com/problems/binary-tree-right-side-view/description/)
- [Level order traversal - 102](https://leetcode.com/problems/binary-tree-level-order-traversal/description/)
- [Zigzag traversal - 103](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/description/)
- [Vertical order traversal (Premium) - 314](https://leetcode.com/problems/binary-tree-vertical-order-traversal/description/)
- [Vertical order traversal (Standard) - 987](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/description/)

## Backtracking
- [Pick or skip - 78](https://leetcode.com/problems/subsets/description/)
- [Partitioning - 131](https://leetcode.com/problems/palindrome-partitioning/description/)
- [Word break with a dictionary - 140](https://leetcode.com/problems/word-break-ii/description/)
- [Permutations - 46](https://leetcode.com/problems/permutations/description/)
- [Combinations - 39](https://leetcode.com/problems/combination-sum/description/)
- [N-Queens - 51](https://leetcode.com/problems/n-queens/description/)

## Grid Graph
- [Number of islands - 200](https://leetcode.com/problems/number-of-islands/description/)
- [Max area of island - 695](https://leetcode.com/problems/max-area-of-island/description/)
- [Making a large island - 827](https://leetcode.com/problems/making-a-large-island/description/)
- [Shortest path - 1091](https://leetcode.com/problems/shortest-path-in-binary-matrix/description/)
- [Word search - 79](https://leetcode.com/problems/word-search/description/)
- [Rotting oranges - 994](https://leetcode.com/problems/rotting-oranges/description/)

## Graph Theory
- [Connected components via DFS - 547](https://leetcode.com/problems/number-of-provinces/description/)
- [Shortest path via BFS - 127](https://leetcode.com/problems/word-ladder/description/)
- [Course schedule (classic topological sort) - 207](https://leetcode.com/problems/course-schedule/description/)
- [Alien dictionary (advanced topological sort) - 269](https://leetcode.com/problems/alien-dictionary/description/)
- [Shortest path via Dijkstra - 787](https://leetcode.com/problems/cheapest-flights-within-k-stops/description/)

## Dynamic Programming
- [Jump game - 55](https://leetcode.com/problems/jump-game/description/)
- [Climbing stairs - 70](https://leetcode.com/problems/climbing-stairs/description/)
- [House robber - 198](https://leetcode.com/problems/house-robber/description/)
- [Minimum path sum - 64](https://leetcode.com/problems/minimum-path-sum/description/)
- [Coin change - 322](https://leetcode.com/problems/coin-change/description/)
- [Edit distance - 72](https://leetcode.com/problems/edit-distance/description/)
- [Longest common subsequence (LCS) - 1143](https://leetcode.com/problems/longest-common-subsequence/description/)
- [Longest increasing subsequence (LIS) - 300](https://leetcode.com/problems/longest-increasing-subsequence/description/)
- [Best time to buy and sell stock series - 188](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/description/)

## Greedy
- [Task scheduler - 621](https://leetcode.com/problems/task-scheduler/description/)
- [Move the smaller side - 11](https://leetcode.com/problems/container-with-most-water/description/)
- [Candy - 135](https://leetcode.com/problems/candy/description/)
- [Gas station - 134](https://leetcode.com/problems/gas-station/description/)

## Trie
- [Classic problem - 208](https://leetcode.com/problems/implement-trie-prefix-tree/description/)
- [Word search in a grid - 212](https://leetcode.com/problems/word-search-ii/description/)

## Math
- [Reverse integer - 7](https://leetcode.com/problems/reverse-integer/description/)
- [Next permutation - 31](https://leetcode.com/problems/next-permutation/description/)
- [Spiral matrix - 54](https://leetcode.com/problems/spiral-matrix/description/)
- [Add binary - 67](https://leetcode.com/problems/add-binary/description/)
