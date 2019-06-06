# Sorting: Comparator
Input Format:
The first line contains an integer, n, the number of players. 
Each of the next n lines contains a player's respective name and score, a string and an integer.

## Constraints:
1. 0<=score<=100
2. Two or more players can have the same name.
3. Player names consist of lowercase English alphabetic letters.


### Sample Input:
5

amy 100

david 100

heraldo 50

aakansha 75

aleksa 150

### Sample Output:

aleksa 150

amy 100

david 100

aakansha 75

heraldo 50

### Explanation:
As you can see, the players are first sorted by decreasing score and then sorted alphabetically by name.
