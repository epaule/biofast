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
| Command | Mean [s] | Min [s] | Max [s] | Relative |
|:---|---:|---:|---:|---:|
| `fqcnt_needletail M_abscessus_HiSeq.fq` | 0.500 ± 0.009 | 0.488 | 0.515 | 1.00 |
| `fqcnt_cr1_klib M_abscessus_HiSeq.fq` | 0.826 ± 0.023 | 0.795 | 0.881 | 1.65 ± 0.05 |
| `fqcnt_c1_kseq M_abscessus_HiSeq.fq` | 0.902 ± 0.051 | 0.836 | 0.995 | 1.80 ± 0.11 |
| `fqcnt_nim1_klib M_abscessus_HiSeq.fq` | 1.172 ± 0.005 | 1.165 | 1.182 | 2.35 ± 0.04 |
| `fqcnt_go1 M_abscessus_HiSeq.fq` | 1.505 ± 0.027 | 1.485 | 1.577 | 3.01 ± 0.07 |
| `bin/fqcnt_rustbio M_abscessus_HiSeq.fq` | 1.621 ± 0.018 | 1.603 | 1.664 | 3.24 ± 0.07 |
| `crystal fqcnt_cr1_klib.cr M_abscessus_HiSeq.fq` | 4.433 ± 0.124 | 4.334 | 4.718 | 8.87 ± 0.29 |
| `fqcnt_py1_4l.py M_abscessus_HiSeq.fq` | 8.527 ± 0.353 | 8.250 | 9.489 | 17.06 ± 0.76 |
| `fqcnt_lua1_klib.lua M_abscessus_HiSeq.fq` | 20.243 ± 0.166 | 20.026 | 20.575 | 40.50 ± 0.77 |
