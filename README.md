# Experimental datasets

This directory contains the nine monotone multicriteria sorting datasets used in
the experiments.

## Files

Raw CSV files are stored in `raw/`:

| Dataset | Alternatives | Columns | File |
| --- | ---: | ---: | --- |
| BCC | 278 | 9 | `raw/BCC.csv` |
| CEV | 1728 | 8 | `raw/CEV.csv` |
| CPU | 209 | 8 | `raw/CPU.csv` |
| DBS | 120 | 10 | `raw/DBS.csv` |
| ERA | 1000 | 6 | `raw/ERA.csv` |
| ESL | 488 | 6 | `raw/ESL.csv` |
| LEV | 1000 | 6 | `raw/LEV.csv` |
| MMG | 830 | 7 | `raw/MMG.csv` |
| MPG | 392 | 9 | `raw/MPG.csv` |

## Format

Each CSV file contains:

- `Alternative`: alternative identifier;
- `g1`, `g2`, ...: normalized criterion performances;
- `Class`: ordered assignment class, where a greater class index indicates a
  more preferred class.

All criteria are gain-type criteria and their performances are normalized in the
`[0, 1]` interval.

## Sources and references

These datasets are benchmark data for monotone multicriteria
classification/sorting problems. The data files follow the public dataset
released with Liu et al. (2021). The original sources include the UCI Machine
Learning Repository, WEKA example datasets, and the DenBosch housing dataset.

Please cite the original data sources when using these files:

1. Liu, J., Kadzinski, M., Liao, X., and Mao, X. (2021). Data-driven preference
   learning methods for value-driven multiple criteria sorting with interacting
   criteria. INFORMS Journal on Computing, 33(2), 586-606.
   Dataset repository:
   https://github.com/ijoc-data/download/tree/master/monotone-classification-problems

2. Dua, D., and Graff, C. (2019). UCI Machine Learning Repository. University of
   California, Irvine, School of Information and Computer Sciences.
   https://archive.ics.uci.edu/

3. Frank, E., Hall, M. A., and Witten, I. H. (2016). The WEKA Workbench. Online
   Appendix for Data Mining: Practical Machine Learning Tools and Techniques
   (4th ed.). Morgan Kaufmann.
   https://www.cs.waikato.ac.nz/ml/weka/

4. Daniels, H., and Kamp, B. (1999). Applications of MLP networks to bond rating
   and house pricing. Neural Computing & Applications, 8(3), 226-234.

Before public release, please verify that redistribution is permitted by the
original data sources and add any license information required by the target
journal or repository.
