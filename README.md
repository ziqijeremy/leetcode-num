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
188 Best Time to Buy and Sell Stock IV dp consider release and hold.
638 Shopping Offers dfs with normal methods
689 Maximum Sum of 3 Non-Overlapping Subarrays
    1.first sum up the total into a array
    2.get the left position of the k number of sum.
    3.get the right position of the k number of sum.
    4.random made it up through a for
2 Add Two Numbers new a linkedlist
7 Reverse Integer consider the number larger than the INT_MAX. so if(new_num > (INT_MAX - x) / 10) return 0;
8 String to Integer (atoi) remember use double to store it
9 Palindrome Number consider negative number
12 Integer to Roman list it out and the sum them up to a string
13 Roman to Integer we need to calculate every position indivisually, and then if(pre < cur) sum+=cur - 2*pre else sum+= cur
123 Best Time to Buy and Sell Stock III smae idea with the 188,use tow vectors and dp them.
120 Triangle dp, add up from bottom to top
312 Burst Balloons 2D dp it means start points and end points. len = 1-n, left = 1-n - len + 1 k = left - right
    dp[left][right] = max(dp[left][right], nums[left - 1] * nums[k] * nums[right + 1] + dp[left][k - 1] + dp[k + 1][right])
303 Range Sum Query - Immutable sum to a array, return with minus.
304 Range Sum Query 2D - Immutable sum to a matrix, return with minus
516 Longest Palindromic Subsequence 2D dp dp[i][i] = 1; ifs[i] == s[j] dp[i][j] = max(dp[i + 1][j], dp[i][j - 1], dp[i - 1][j - 1] + 2)
    else dp[i][j] = max(dp[i + 1][j], dp[i][j - 1], dp[i - 1][j - 1])
24. Swap Nodes in Pairs 注意指针的变换
