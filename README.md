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
62 Unique Paths 2D matrix dp
63 Unique Paths II 2D matrix dp
494 Target Sum 1D dp
486 Predict the Winner 2D dp dp(i, j) = max(nums[j] - dp(i, j-1), nums[i] - dp(i+1, j))
    dp[i][j] means that the array from i to j, player 1 can get points.
474 Ones and Zeros 2D dp it represent the number of ones and zeros.
472 Concatenated Words dfs use unordered_set to store the words that cannot be composed by the other
467 Unique Substrings in Wraparound String 用一个26长的vector记录以他结尾string的最长长度，然后就是直接加
139 Word Break 1D dp 检查到哪一位可以使正确的
322 Coin Change 1D dp 金额的递推方程
188. Best Time to Buy and Sell Stock IV dp consider release and hold.
