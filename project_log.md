Apr 21

I notice that the way I loop through index is not consistent in my NFA execution (exclusion and inclusion problem).

Apr 22

I realized that the spec asks me to match greedily and only print out the longest match.

Apr 23

My prefix extraction algorithm from parsing tree is not robust. An alternative is to retrieve the prefix from the NFA instead of the parsing tree.

Apr 24

Yalov suggests me using vector instead of hashmap. It turned out that using vector is slower than using hashmap.

Apr 25

I tried to change vector in my NFA class into hashmap, but it also slowed down the program.

Apr 28

I finally noticed that my past code didn't handle the edge case where the last character alone matches to the regular expression.
