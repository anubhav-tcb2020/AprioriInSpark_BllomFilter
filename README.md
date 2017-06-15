# AprioriInSpark_BllomFilter

The "Apriori" algorithm along with its set of improved variants, which were one of the earliest proposed frequent pattern generation algorithms still
remain a preferred choice due to their ease of implementation and natural tendency to be parallelized.

In the implementation of Apriori, the most computationally expensive task is the generation of candidate sets having all possible pairs for singleton frequent items and
comparing each pair with every transaction record. By using a new data structure (new in this context), Bloom Filter, we tottaly eliminate the
candidate generation part making this particular implementation extremely fast for using with really really large datasets.

