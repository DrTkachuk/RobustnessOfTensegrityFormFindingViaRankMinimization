# RobustnessOfTensegrityFormFindingViaRankMinimization
Reimplementing the original Matlab solution from Tkachuk (2022) paper using Python in Google Colab

Implementation relies on cvxpy solver [1] and uses default setting.

List of reimplemented examples
- Example 1: Plane 6-node tensegrity with 9 members: initial submission 2026-02-10
- Example 2: Plane 6-node tensegrity with 9 members + constraint between force densities q(1) and q(2): initial submission 2026-02-10
- Example 3: Plane 6-node tensegrity with 10 members: initial submission on 2026-02-11
- Example 4: Plane 10-node tensegrity with 18 members: initial submission on 2026-02-11
- Example 5: Spatial 12-node tensegrity with 22 members: initial submission on 2026-02-12

Full article reference
Tkachuk, A. (2022). Robustness of rank minimization heuristics for form-finding of tensegrity structures. Computers & Structures, 266, 106786.

External references
1. Diamond, S., & Boyd, S. (2016). CVXPY: A Python-embedded modeling language for convex optimization. Journal of Machine Learning Research, 17(83), 1-5.
