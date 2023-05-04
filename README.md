Download Link: https://assignmentchef.com/product/solved-csds455-homework-21-tree-decomposition-for-graph
<br>
<strong>Problem 1: </strong>Assume that you have a tree decomposition for graph <em>G </em>and a second graph <em>H </em>without a decomposition. Assume the decomposition is adjusted so that every bag has size exactly <em>k </em>+ 1 and every bag has 0 or 2 children.

Write a dynamic programming solution to: <em>Graph Isomorphism</em>: Given two graphs <em>G </em>and <em>H</em>, determine if <em>G </em><sup>∼</sup>= <em>H</em>.

Assume you have a tree decomposition for <em>G </em>but not for <em>H</em>. As a hint, first spend <em>O</em>(<em>n<sup>k</sup></em><sup>+1</sup>) time to find all separators of size <em>k </em>+ 1 in <em>H</em>. A dynamic programming solution uses a table of at most 2<em>n<sup>k</sup></em><sup>+1</sup>(<em>k </em>+ 1)! booleans for each bag of the decomposition.

<strong>Problem 2: </strong>Assume that you have a tree decomposition for graph <em>G</em>. Assume the decomposition is adjusted so that every bag has size exactly <em>k </em>+ 1 and every bag has 0 or 2 children.

Write a dynamic programming solution to: <em>Hamiltonian Circuit</em>: Given a graph <em>G</em>, does there exist a cycle that visits each vertex of <em>G </em>exactly once?

A dynamic programming solution uses a table of at mostbooleans for each bag of the decomposition. <em>S</em>(<em>a,b</em>) is the Stirling number that counts the number of ways to partition <em>a </em>labelled elements into <em>b </em>non-empty, unlabelled subsets.