# mmtsne

## An R Package for Multiple Maps t-SNE

Benjamin J. Radford


An implementation of multiple maps t-distributed stochastic neighbor embedding (t-SNE) in R. Multiple maps t-SNE is a method for projecting high-dimensional data into several low-dimensional maps such that metric space properties are better preserved than they would be by a single map. Multiple maps t-SNE with only one map is equivalent to standard t-SNE. When projecting onto more than one map, multiple maps t-SNE estimates a set of latent weights that allow each point to contribute to one or more maps depending on similarity relationships in the original data. This implementation is a port of the original Matlab library by Laurens van der Maaten.

License: FreeBSD | file LICENSE

-----

This material is based upon work supported by the United States Air Force and Defense Advanced Research Project Agency (DARPA) under Contract No. FA8750-17-C-0020.

Any opinions, findings and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the United States Air Force and Defense Advanced Research Projects Agency.

Distribution Statement A: Approved for Public Release; Distribution Unlimited.
