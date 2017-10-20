# leetcode-num
leetcode
698 dfs
673 dp consider len and cnt
688 knight Probability in Chessboard 用一个三维的dp
650 整除的方法
647 Palindromic Substrings 中心向两边扩散
646 Maximin Length of Pair Chain 先sort一下，再做其他的查找
32 Longest Valid Parentheses 用stack来做
44 Wildcard Matching 递推公式：
    P[i][j] = P[i - 1][j - 1] && (s[i - 1] == p[j - 1] || p[j - 1] == '?'), if p[j - 1] != '*';
    P[i][j] = P[i][j - 1] || P[i - 1][j], if p[j - 1] == '*'.
96 Uniqeu Binary Search Trees 递推得到
