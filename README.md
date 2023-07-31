# Levenshtein_Distance
The Levenshtein distance is a string metric for measuring difference between two sequences. Informally, the Levenshtein distance between two words is the minimum number of single-character edits (i.e. insertions, deletions or substitutions) required to change one word into the other. It is named after Vladimir Levenshtein, who considered this distance in 1965.

Levenshtein distance may also be referred to as edit distance, although it may also denote a larger family of distance metrics. It is closely related to pairwise string alignments.

For example we want to calculate distance between "intention" and "execution".

Explanation:

step 0: "intention"

step 1: intention -> inention (remove 't')

step 2: inention -> enention (replace 'i' with 'e')

step 3: enention -> exention (replace 'n' with 'x')

step 4: exention -> exection (replace 'n' with 'c')

step 5: exection -> execution (insert 'u')

That means distance between 'intention' and 'execution' is 5
