# Set-Cover Problem
The Set Cover Problem involves a universe of elements and a collection of sets, where each set contains some of those elements. The goal is to select the smallest number of these sets such that their union covers all the elements in the universe.

## RESULT 
My solution is based on Tabu search algorithm and the  best results that i obtained are the following: 

| Instance | Universe size | Num sets | Density | Result |
|---------|-----|-----|-----|-----|
| 1 | 100     | 10     | 0.2 | -258.7307216591009 |
| 2 | 1_000   | 100    | 0.2 | -6_023.07723283961  |
| 3 | 10_000  | 1_000  | 0.2 | -886_177.5509467437 |
| 4 | 100_000 | 10_000 | 0.1 | -102_783_314.62948833 | 
| 5 | 100_000 | 10_000 | 0.2 | -221_073_680.58279872 |
| 6 | 100_000 | 10_000 | 0.3 | -254_549_363.31683755 |
