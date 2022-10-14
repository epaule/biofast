### gzipped input

| Command | Mean [s] | Min [s] | Max [s] | Relative |
|:---|---:|---:|---:|---:|
| `fqcnt_cr1_klib M_abscessus_HiSeq.fq.gz ` | 6.133 ± 0.019 | 6.091 | 6.158 | 1.00 |
| `fqcnt_c1_kseq M_abscessus_HiSeq.fq.gz ` | 6.177 ± 0.037 | 6.129 | 6.274 | 1.01 ± 0.01 |
| `fqcnt_needletail M_abscessus_HiSeq.fq.gz ` | 6.206 ± 0.023 | 6.173 | 6.242 | 1.01 ± 0.00 |
| `fqcnt_nim1_klib M_abscessus_HiSeq.fq.gz ` | 6.649 ± 0.133 | 6.521 | 6.898 | 1.08 ± 0.02 |
| `fqcnt_rustbio M_abscessus_HiSeq.fq.gz ` | 7.209 ± 0.037 | 7.129 | 7.252 | 1.18 ± 0.01 |
| `crystal fqcnt_cr1_klib.cr M_abscessus_HiSeq.fq.gz ` | 9.906 ± 0.124 | 9.751 | 10.100 | 1.62 ± 0.02 |
| `fqcnt_go1 M_abscessus_HiSeq.fq.gz ` | 10.680 ± 0.082 | 10.597 | 10.811 | 1.74 ± 0.01 |
| `fqcnt_py1_4l.py M_abscessus_HiSeq.fq.gz ` | 17.875 ± 0.222 | 17.599 | 18.218 | 2.91 ± 0.04 |
| `fqcnt_lua1_klib.lua M_abscessus_HiSeq.fq.gz ` | 20.475 ± 0.771 | 19.912 | 21.993 | 3.34 ± 0.13 |

### raw input
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `bin/fqcnt_needletail biofast-data-v1/M_abscessus_HiSeq.fq` | 531.6 ± 154.2 | 476.6 | 970.4 | 1.00 |
| `./fqcnt_cr1_klib biofast-data-v1/M_abscessus_HiSeq.fq` | 750.9 ± 27.1 | 715.0 | 793.7 | 1.41 ± 0.41 |
| `./fqcnt_c1_kseq biofast-data-v1/M_abscessus_HiSeq.fq` | 840.7 ± 18.8 | 822.8 | 868.7 | 1.58 ± 0.46 |
| `bin/fqcnt_rustbio biofast-data-v1/M_abscessus_HiSeq.fq` | 1626.9 ± 42.7 | 1586.2 | 1741.0 | 3.06 ± 0.89 |
| `crystal fqcnt_cr1_klib.cr biofast-data-v1/M_abscessus_HiSeq.fq` | 4392.6 ± 88.1 | 4300.8 | 4605.8 | 8.26 ± 2.40 |
