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

## Source

The files were copied from the local benchmark folder:

`C:\Users\28074\Desktop\MCS\download-master\monotone-classification-problems`

The source README describes the datasets as research data for monotone
classification problems involving preference-ordered criteria and classes. The
original sources include UCI, WEKA, and the DenBosch housing dataset reference.

Before public release, please verify that redistribution is permitted by the
original data sources and add the formal citation or license information required
by the target journal/repository.
