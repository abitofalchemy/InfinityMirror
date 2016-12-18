# InfinityMirror

Infinity Mirror Graph Test

Test how well synthetic graphs from various network graph generators hold. This approach assess how well a synthetic graph
the network's topological structure to stand in for the original.

## Abstract

Graph generators learn a model from a source graph in order to generate a new graph that has many of the same prop- erties. The learned models each have implicit and explicit biases built in, and it is important to understand the as- sumptions that are made when generating a new graph. Of course, the differences between the new graph and the origi- nal graph, as compared by any number of graph properties, are important indicators of the biases inherent in any mod- elling task. But these critical differences are subtle and not immediately apparent using standard performance metrics. Therefore, we introduce the infinity mirror test for the anal- ysis of graph generator performance and robustness. This stress test operates by repeatedly, recursively fitting a model to itself. A perfect graph generator would have no deviation from the original or ideal graph, however the implicit biases and assumptions that are cooked into the various models are exaggerated by the infinity mirror test allowing for new insights that were not available before. We show, via hun- dreds of experiments on 6 real world graphs, that several common graph generators do degenerate in interesting and informative ways. We believe that the observed degenera- tive patterns are clues to future development of better graph models.

This work was presented at the 12th International Workshop on Mining and Learning with Graphs concurrent with SIGKDD 2016. Workshop 
- [MLG2016 accepted papers](http://www.mlgworkshop.org/2016/#papers)
- [Publication](http://www.mlgworkshop.org/2016/paper/MLG2016_paper_17.pdf)


