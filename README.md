# Comprehensive evaluation of lossless compression algorithms in a real use case for smart grid applications

This repository contains the original dataset used in the following pubblication. 

## Abstract
The so-called “energy digitalization” is pervading the power and energy industry by providing many state-of-the-art digital technologies to collect, store, and analyze the very heterogeneous information managed in modern power systems. Requirements in terms of sampling frequency, temporal and user aggregation, measured quantities, measurement aggregations, involved players, and applications can be very different. Compression strategies, removing redundancy and over-specification in collected samples, can play a relevant role in efficiently move and store such heterogeneous data. In this work, a reference dataset from a real-world use case has been collected for comparing the performance of 62 lossless compression algorithms derived from the LZ77/LZSS/LZMA strategies. Compression of the six-day long acquisition, including active power measurements of a prosumer’s system equipped with a Photovoltaic (PV) and a Battery Energy Storage System, highlights the different obtainable performance when the aggregation interval is changed from 15 min to 24 h. In particular, once the top performing algorithms have been selected, it has been possible to stress the impact of night-day cycle, mainly due to the different sparsity of PV-related data. The obtained results demonstrate that, globally, the compression ratio increases by increasing the aggregation interval, by reaching values close to 9.7. In particular, when offline operation is tolerated, optimal compression schemes can be easily applied, leading to consistent improvement of the compression ratio (up to 24%, depending on the actual algorithm and aggregation interval), which can be very significant when large number of data sources is considered.

## Nomenclature

- PV: PhtoVoltaic
- U: Utility
- BESS: Battery Energy Storage System

## Data Description

- Timestamp: the timestamp of the measurement, reported by adopting the ISO 8601 standard;
- P_PV: the active power of the PV system by assuming the convention of generators, reported in W;
- P_U: the active power exchanged by the systems with the utility, by assuming the convention of loads, reported in W. Positive values represent that active energy is taken from the grid, while negative values represent that active energy is injected back into the grid;
- P_BESS: the active power of the BESS, by assuming the convention of loads, reported in W. Positive values represent that active energy is charged into the BESS, while negative values represent that active energy is discharged from the BESS;

## Processing details

All details are available in the following paper:

* M. Pasetti, E. Sisinni, P. Ferrari, P. Bellagente, and D. Zaninelli, “Comprehensive evaluation of lossless compression algorithms in a real use case for smart grid applications” Sustainable Energy, Grids and Networks, p. 101238, Nov. 2023, doi: [10.1016/j.segan.2023.101238](https://doi.org/10.1016/j.segan.2023.101238).

