# TaxoBench
This is a container-based framework which will include tools to Benchmark the performance of taxonomic classifier tools.
It will contain "apps" not only to assess performance, but different tools can be brought in as "apps" to be included in the
suite of tools tested. Additionally, apps can serve the purpose of pulling in various synthetic data sets designed to act
as consistent ground truth "control" sets to test against. The build system levarages Github Actions to re-build the container
on git tag push after any additions or updates. It is based on a pattern like [SciducTainer](https://github.com/NSSAC/SciducTainer) (see that for more documentation).
