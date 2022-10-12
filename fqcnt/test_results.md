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
| `./fqcnt_cr1_klib biofast-data-v1/M_abscessus_HiSeq.fq` | 713.3 ± 9.6 | 704.4 | 739.1 | 1.00 |
| `./fqcnt_c1_kseq biofast-data-v1/M_abscessus_HiSeq.fq` | 819.7 ± 10.9 | 810.5 | 846.1 | 1.15 ± 0.02 |
| `bin/fqcnt_rustbio biofast-data-v1/M_abscessus_HiSeq.fq` | 1589.5 ± 14.2 | 1565.3 | 1609.8 | 2.23 ± 0.04 |
| `crystal fqcnt_cr1_klib.cr biofast-data-v1/M_abscessus_HiSeq.fq` | 4385.2 ± 162.2 | 4288.5 | 4825.5 | 6.15 ± 0.24 |
