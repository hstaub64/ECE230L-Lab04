# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.

We learned more about utilizing and creating K-Maps from standard truth tables, as well as proper SOP/POS grouping to simplify boolean equations.
We also learned more/got more practice writing verilog and utilizing vivado to demonstrate equations on Basys3 boards.  

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?



### Why are the names Sum of Products and Products of Sums?


### Open the test.v file – how are we able to check that the signals match using XOR?

We are able to check because the underlying nature of XOR. XOR only evaluates to true when the elements differ, therefore, when we compare outputs from naive min and max, if their outputs are not 0 (i.e. they are different), then we output a message to the console saying they do not match.
