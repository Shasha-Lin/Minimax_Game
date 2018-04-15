# DFS_game
A small game analysis using depth-first-search (DFS) for algorithms class at NYU.
# ToDo list:
1. Figure out the distribution of Value[s]: at each level, the distribution of Value[v] is the sampling distribution of the maximum/minimum from the distribution of Value[w], w being an adjacency node at the lower level. The pdf of such distribution is found on page 4 and 5 of [these slides](https://www2.stat.duke.edu/courses/Spring12/sta104.1/Lectures/Lec15.pdf). We don't have a closed form/approximation of the top value when $lim_{n\rightarrow \infty}$ yet.
2. Implement [alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning) to speed up value computation. 
3. Other creative questions to ask (problem 6).
