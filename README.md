# Genome-Sequencing

First, implementing a version of the naive exact matching algorithm that is strand-aware. That is, instead of looking only for occurrences of Pattern(P) in Text(T), additionally look for occurrences of thereverse complement of P in the T. If P is GGC, the function should find occurrences of both GGC and its reverse complement GCC in T.
