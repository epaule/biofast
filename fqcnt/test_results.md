### gzipped input
| Command | Mean [s] | Min [s] | Max [s] | Relative |
|:---|---:|---:|---:|---:|
| `./fqcnt_cr1_klib biofast-data-v1/M_abscessus_HiSeq.fq.gz` | 6.222 ± 0.022 | 6.189 | 6.260 | 1.00 |
| `./fqcnt_c1_kseq biofast-data-v1/M_abscessus_HiSeq.fq.gz` | 6.277 ± 0.057 | 6.236 | 6.395 | 1.01 ± 0.01 |
| `bin/fqcnt_rustbio biofast-data-v1/M_abscessus_HiSeq.fq.gz` | 7.267 ± 0.105 | 7.196 | 7.556 | 1.17 ± 0.02 |
| `crystal fqcnt_cr1_klib.cr biofast-data-v1/M_abscessus_HiSeq.fq.gz` | 10.100 ± 1.007 | 9.740 | 12.964 | 1.62 ± 0.16 |

### raw input
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `bin/fqcnt_needletail biofast-data-v1/M_abscessus_HiSeq.fq` | 531.6 ± 154.2 | 476.6 | 970.4 | 1.00 |
| `./fqcnt_cr1_klib biofast-data-v1/M_abscessus_HiSeq.fq` | 750.9 ± 27.1 | 715.0 | 793.7 | 1.41 ± 0.41 |
| `./fqcnt_c1_kseq biofast-data-v1/M_abscessus_HiSeq.fq` | 840.7 ± 18.8 | 822.8 | 868.7 | 1.58 ± 0.46 |
| `bin/fqcnt_rustbio biofast-data-v1/M_abscessus_HiSeq.fq` | 1626.9 ± 42.7 | 1586.2 | 1741.0 | 3.06 ± 0.89 |
| `crystal fqcnt_cr1_klib.cr biofast-data-v1/M_abscessus_HiSeq.fq` | 4392.6 ± 88.1 | 4300.8 | 4605.8 | 8.26 ± 2.40 |
