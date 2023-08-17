# 1041C

Recently Monocarp got a job. His working day lasts exactly m
 minutes. During work, Monocarp wants to drink coffee at certain moments: there are n
 minutes a1,a2,…,an
, when he is able and willing to take a coffee break (for the sake of simplicity let's consider that each coffee break lasts exactly one minute).

However, Monocarp's boss doesn't like when Monocarp takes his coffee breaks too often. So for the given coffee break that is going to be on minute ai
, Monocarp must choose the day in which he will drink coffee during the said minute, so that every day at least d
 minutes pass between any two coffee breaks. Monocarp also wants to take these n
 coffee breaks in a minimum possible number of working days (he doesn't count days when he is not at work, and he doesn't take coffee breaks on such days). Take into account that more than d
 minutes pass between the end of any working day and the start of the following working day.

For each of the n
 given minutes determine the day, during which Monocarp should take a coffee break in this minute. You have to minimize the number of days spent.

Input
The first line contains three integers n
, m
, d
 (1≤n≤2⋅105,n≤m≤109,1≤d≤m)
 — the number of coffee breaks Monocarp wants to have, the length of each working day, and the minimum number of minutes between any two consecutive coffee breaks.

The second line contains n
 distinct integers a1,a2,…,an
 (1≤ai≤m)
, where ai
 is some minute when Monocarp wants to have a coffee break.

Output
In the first line, write the minimum number of days required to make a coffee break in each of the n
 given minutes.

In the second line, print n
 space separated integers. The i
-th of integers should be the index of the day during which Monocarp should have a coffee break at minute ai
. Days are numbered from 1
. If there are multiple optimal solutions, you may print any of them.
