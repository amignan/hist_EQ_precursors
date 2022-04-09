# hist_EQ_precursors

## json databases for earthquake prediction meta-analyses

**DB_EQpred_ForeshockMinM_v1**: Corpus of 37 short-term foreshock studies (1982-2013). The main attributes are data_mmin and target_mmin relating sampling size (amount of small earthquakes with magnitude greater or equal to data_mmin) to mainshock target size (i.e. minimum magnitude target_min). Ref: [Mignan, Scientific Reports, 2014](https://www.nature.com/articles/srep04099)

**DB_EQpred_ASRtheories_v1**: Corpus of 101 precursory accelerating seismicity studies (1988-2018). Two labellings defined, binary: {1 = critical process, 0 = other}, and multi-class: {0 = non-criticality, 1 = agnostic, 2 = criticality assumed, 3 = criticality demonstrated}. This DB consists of all features (incl. article abstracts) used for text classification. Refs: [Mignan, Tectonophysics, 2011](https://www.sciencedirect.com/science/article/pii/S0040195111001284); [Mignan, Journal of Seismology, 2019](https://link.springer.com/article/10.1007/s10950-019-09833-2)

**DB_EQpred_NeuralNets_v1**: Corpus of 77 publications on artificial neural networks for earthquake prediction (1994-2019). Includes network type, network architecture, result score and other extracted meta-data. Ref: [Mignan & Broccardo, Seismological Research Letters, 2020](https://pubs.geoscienceworld.org/ssa/srl/article-abstract/91/4/2330/586519/Neural-Network-Applications-in-Earthquake)

*Disclaimer*: Despite every effort to make these corpora as complete and correct as possible, some studies may still be missing and some attributes may have been misinterpreted by the reviewer. Please contact Arnaud Mignan if you spot any omission or error, or fork hist_eq_pred to directly update the DBs. Version v1 is published/used in a peer-reviewed journal. Subversions v1.x are updated DBs (modififed attributes, new entries) which are not published and still subject to changes.
