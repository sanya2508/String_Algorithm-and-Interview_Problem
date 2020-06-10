# String Matching Algorithm

## <a href="https://github.com/sanya2508/String_Algorithm-and-Interview_Problem/blob/master/naive%20algorithm.cpp">Naive Algorithm</a>
 * Naive pattern searching is the simplest method among other pattern searching algorithms. It checks for all character of the main string to the pattern. This algorithm is helpful for smaller texts. It does not need any pre-processing phases. We can find substring by checking once for the string. It also does not occupy extra space to perform the operation.

 * The time complexity of Naive Pattern Search method is O(m*n) in the worst case and O(n) in the best  case. The m is the size of pattern and n is the size of the main string.

<hr/>

## <a href="https://github.com/sanya2508/String_Algorithm-and-Interview_Problem/blob/master/rabin%20carp%20algorithm.cpp">Rabin Karp Algorithm</a>
 * Rabin-Karp is another pattern searching algorithm to find the pattern in a more efficient way. It also checks the pattern by moving window one by one, but without checking all characters for all cases, it finds the hash value. When the hash value is matched, then only it tries to check each character. This procedure makes the algorithm more efficient.

 * The time complexity is O(m+n), but for the worst case, it is O(mn).

<hr/>

## <a href="https://github.com/sanya2508/String_Algorithm-and-Interview_Problem/blob/master/knuth%20morris%20pratt%20algorithm.cpp">Knuth Morris Pratt</a>
 * Knuth Morris Pratt (KMP) is an algorithm, which checks the characters from left to right. When a pattern has a sub-pattern appears more than one in the sub-pattern, it uses that property to improve the time complexity, also for in the worst case.

 * The time complexity of KMP is O(n).
