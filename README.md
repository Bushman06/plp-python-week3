# Week 3 Assignment: Conditions and Loops

`grade_reporter.py` - Uses loops and conditions to calculate grades, pass/fail counts, and the average score.

`bug_hunt.py` - Finds and fixes three bugs in a while loop program that calculates the sum from 1 to 5.

The hardest bug to find was the loop condition because the program ran without showing an error message, but it printed 10 instead of the expected 15. I knew something was wrong because the program was supposed to add 1, 2, 3, 4, and 5, so I checked the loop condition and found that `count < 5` stopped the loop before 5 was added.