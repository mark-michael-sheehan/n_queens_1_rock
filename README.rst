==============
N Queens 1 Rock
==============

Mark Sheehan 05-03-2023

This project attempts to solve an interesting problem that my friend Dave posed which he called the 'N Queens 1 Rock' problem.

The regular n-queens problem involves a chess board with n spaces on a side.  The goal of the problem is to find all the valid
configurations for placing n queens on the board such that no queen threatens another.  In this case, the problem is
naturally constrained such that only one queen can be placed on each row.  This problem is typically posed as an example
for how tree-based pruning strategies can be used to explore a solution space and efficiently (relative to a brute-force 
search) find the solutions.

The n queens 1 rock problem changes this by introducing at least one 'rock' on the board which obstructs the attacking capability
of the queens and therefore changes the nature of viable solutions.  For example, the typical constraint for the 
n-queens problem of only having 1 queen per row is now invalid since a rock between two queens in the same row blocks
the attack of both.

This solution aims to explore the new set of solutions which arise from the modification to the problem.


Features
--------

* TODO

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
