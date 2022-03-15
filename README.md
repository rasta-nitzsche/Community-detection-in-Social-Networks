# community-detection

In this section we will discover and implement 4 methods for comunity detection in social networks:
  * Louvain: an algorithm that optimizes the modularity function.
  * Leiden: an amelioration of Louvain as it solves the problem of disconnected communities. 
  * Ga-Net: a genetic algorithm for community detection.
  * CMN: a greedy optimization by exploiting some shortcuts and using more sophisticated data structures.

We will also compare the score and computation time on each algorithm through a benchmark composed of real world networks (Football, karate, dolphin) and some synthetic networks.

Papers of the algos:
  * Louvain: https://iopscience.iop.org/article/10.1088/1742-5468/2008/10/P10008
  * Leiden: https://www.nature.com/articles/s41598-019-41695-z
  * Ga-Net: https://www.researchgate.net/publication/220701568_GA-Net_A_Genetic_Algorithm_for_Community_Detection_in_Social_Networks
  * CMN: https://arxiv.org/abs/cond-mat/0408187
