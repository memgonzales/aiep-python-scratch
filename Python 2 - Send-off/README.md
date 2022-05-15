# AIEP Python 2 Send-off Program
The AIEP Python 2 send-off program was launched in 2022 with the goal of preparing students to represent the country in global and international informatics, computational thinking, and programming competitions. The trainees were selected based on their performance in the AIEP Python 2 (Python for Competitive Programming) qualifying program.

## Curriculum Design
For the AIEP Python 2 send-off, I designed the curriculum for the last five sessions with the following rationale:
- Sessions 6 to 7 are dedicated to deepening the trainees' understanding of two algorithmic paradigms that were preliminarily introduced during the qualifying program: binary search and dynamic programming. Bisection method (an extension of binary search to continuous search spaces) is also discussed.
- Sessions 8 to 9 introduce two new efficient data structures: priority queues and disjoint-set data structures.
- Session 10 aims to send the trainees off with a real-world application of informatics: unearthing patterns across items in large datasets via association rule mining.

Session | Topic
-- | --
6 | Binary Search and Bisection Method
7 | Dynamic Programming
8 | Priroity Queue
9 | Disjoint-Set Data Structure
10 | Association Rule Mining

## Contributed Materials
Each handout starts with a motivating problem and a theoretical exploration of the topic before proceeding to a walkthrough of classical and competitive programming tasks. Exercises and questions for class discussion/self-driven learning are also provided to supplement the discussion.

### Session 6
This session serves to give a deeper discussion of binary search (including getting the upper and lower bounds). Bisection method, an extension of binary search to continuous search spaces, is also introduced. Walkthroughs are provided for the following problems: [Where is the Marble?](https://onlinejudge.org/external/104/10474.pdf), [Expanding Rods](https://open.kattis.com/problems/expandingrods), and [Careful Ascent](https://open.kattis.com/problems/carefulascent).

### Session 7
This session serves to give a deeper discussion of dynamic programming (DP), with an emphasis on the top-down approach (memoization) for pedagogy. Three categories of DP problems are explored:
- _One-dimensional DP:_ [Problem 25 from the 2010 American Mathematics Competition 8](https://artofproblemsolving.com/wiki/index.php/2010_AMC_8_Problems/Problem_25)
- _Two-dimensional DP:_ [Tetrahedron](https://codeforces.com/problemset/problem/166/E), [Problem 11 from the 2008 American Invitational Mathematics Examination I](https://artofproblemsolving.com/wiki/index.php/2008_AIME_I_Problems/Problem_11), and Levenshtein distance
- _Knapsack-style DP:_ 0-1 knapsack problem and subset sum problem
- _Forward vs. backward recursion:_ 0-1 knapsack problem (revisited) and [Nikola](https://open.kattis.com/problems/nikola)

### Session 8
This session serves to introduce the priority queue as an efficient data structure for implementing greedy algorithms. Walkthroughs are provided for the following problems: getting the *k*th-highest element, Huffman coding, and [Assigning Workstations](https://open.kattis.com/problems/workstations).

### Session 9
This session serves to introduce the disjoint-set data structure as an efficient data structure for union and merge operations. Known optimization techniques, namely union by rank and path compression, are also discussed. Walkthroughs are provided for the following problems: [Virtual Friends](https://open.kattis.com/problems/virtualfriends), [Skolavslutningen](https://open.kattis.com/problems/skolavslutningen), and [Swap to Sort](https://open.kattis.com/problems/swaptosort).

### Sessions 10
This session serves to introduce association rule mining as a data mining technique for unearthing patterns across items in large datasets. In particular, the apriori algorithm is discussed.
