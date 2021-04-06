# cpsc481-pacman

A Pacman maze solving project for CS 481

## Submission 2

Date: 2021-04-05

- Chris Nutter
- Estrella Meija

*Submission 1 code was used for this project with members no longer in this group*

### Tasks Completed

- A\* Search (3/3)
- Finding All the Corners (0/3)

Due to the nature of the project. We were able to implement A\* Search but we weren't able
to implement heuristics until the end of the project's deadline however once we implemented it,
we got correct cases for many of the questions however it causes all tests to fail because of
overly expanded states.

How we implemented searching was through creating a Priority Queue from util.py. This
allowed us to check whether the current node was empty, what our next step should be,
pushing and popping, as well as getting the final solution. The part where we struggled was
dealing with the heuristics checking the problem and how it would be implemented in code as well
as dealing
