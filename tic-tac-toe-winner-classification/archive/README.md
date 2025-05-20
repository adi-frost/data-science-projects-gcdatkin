# Tic-Tac-Toe Endgame Data Set

Abstract: Binary classification task on possible configurations of tic-tac-toe game

- | -
------- | -----
Data Set Characteristics | Multivariate
Number of Instances | 958
Area | Game
Attribute Characteristics | Categorical
Number of Attributes | 9
Associated Tasks | Classification


#### Creator: David W. Aha (aha '@' cs.jhu.edu)
#### Donor: David W. Aha (aha '@' cs.jhu.edu)


### Data Set Information:
This database encodes the complete set of possible board configurations at the end of tic-tac-toe games, where "x" is assumed to have played first. The target concept is "win for x" (i.e., true when "x" has one of 8 possible ways to create a "three-in-a-row").
Interestingly, this raw database gives a stripped-down decision tree algorithm (e.g., ID3) fits. However, the rule-based CN2 algorithm, the simple IB1 instance-based learning algorithm, and the CITRE feature-constructing decision tree algorithm perform well on it.


### Attribute Information:
1. top-left-square: {x,o,b}
2. top-middle-square: {x,o,b}
3. top-right-square: {x,o,b}
4. middle-left-square: {x,o,b}
5. middle-middle-square: {x,o,b}
6. middle-right-square: {x,o,b}
7. bottom-left-square: {x,o,b}
8. bottom-middle-square: {x,o,b}
9. bottom-right-square: {x,o,b}
10. Class: {positive,negative}

