# DFS_game
A small game analysis using depth-first-search (DFS) for algorithms class at NYU.
# ToDo list:
1. Figure out the distribution of Value[s]: at each level, the distribution of Value[v] is the sampling distribution of the maximum/minimum from the distribution of Value[w], w being an adjacency node at the lower level. The pdf of such distribution is found on page 4 and 5 of [these slides](https://www2.stat.duke.edu/courses/Spring12/sta104.1/Lectures/Lec15.pdf). We don't have a closed form/approximation of the top value when ![equation](<img src="http://www.sciweavers.org/tex2img.php?eq=%5Clim_%7Bn%5Crightarrow%20%5Cinfty%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="\lim_{n\rightarrow \infty}" width="36" height="25" />) yet.
2. Implement [alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning) to speed up value computation. 
3. Other creative questions to ask (problem 6).
