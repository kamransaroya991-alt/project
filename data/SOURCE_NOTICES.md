# Data sources and archival credits

Four graph distributions are bundled with NetworkX 3.6.1. The NetworkX documentation credits the following original sources:

* Karate club: W. W. Zachary (1977), “An information flow model for conflict and fission in small groups”, Journal of Anthropological Research, 33, pp. 452–473. The packaged edge weights count interaction contexts.
* Les Misérables: D. E. Knuth (1993), The Stanford GraphBase: A Platform for Combinatorial Computing. The graph represents fictional character co-appearances.
* Southern women: A. Davis, B. B. Gardner and M. R. Gardner (1941), Deep South. The graph has separate woman and event vertex types.
* Florentine families: R. L. Breiger and P. E. Pattison (1986), “Cumulated social roles: The duality of persons and their algebras”, Social Networks, 8(3), pp. 215–256. The retained graph concerns marriage ties.

The compressed Caenorhabditis elegans neural graph is retained from:
https://github.com/cran/igraph/blob/master/tests/testthat/celegansneural.gml.gz

Its Git blob SHA-1 is `9f2b2e18aca6f5136d97276d794370684c8bdcec`. The GML export header is dated 31 August 2006 and names Mark Newman as creator. This archival network is associated with the earlier neural-network compilation distributed through Newman's network-data collection. It is not presented as a newly measured or complete contemporary connectome.

The compressed source bytes are unchanged. Multigraph parsing is enabled only in memory to retain repeated ordered records before documented simplification. All source links are retained in `datasets.json`. Consult original distribution terms before further redistribution; this package does not claim ownership of the original data.
