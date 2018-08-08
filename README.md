# lsst.ap.verify

`ap_verify` is a package to be added to the [LSST Science Pipelines](https://pipelines.lsst.io/).

This package manages end-to-end testing and metric generation for the [LSST DM Alert Production pipeline](https://github.com/lsst-dm/ap_pipe/).
Metrics are tested against both project- and lower-level requirements, and will be deliverable to the SQuaSH metrics service.

`ap_verify` is designed to work on downloadable Git LFS datasets, which must be installed separately.
Unlike the Alert Production pipeline itself, it cannot be run on generic data repositories.

For more details, including user instructions and information about supported datasets, consult the [package documentation](https://github.com/lsst-dm/ap_verify/tree/master/doc/lsst.ap.verify).
When `ap_verify` is formally added to the LSST Stack this documentation will be available through the [Science Pipelines](https://pipelines.lsst.io/) documentation.
