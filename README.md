# saketlab.r-universe.dev

R packages from [saketlab](https://github.com/saketlab) on [r-universe](https://saketlab.r-universe.dev).

## Packages

| Package | Description | Source |
|---|---|---|
| `censusindia` | Digitised Census of India (1901–2011) | [saketlab/censusindia](https://github.com/saketlab/censusindia) |
| `anumaan` | Antimicrobial resistance surveillance preprocessing and burden estimation | [saketlab/anumaan](https://github.com/saketlab/anumaan) |
| `seqout` | R client for the SeqOut genomics metadata search interface (GEO, SRA, ENA, ArrayExpress) | [saketlab/seqout](https://github.com/saketlab/seqout) |

## Install

Individual package:

```r
install.packages("censusindia", repos = "https://saketlab.r-universe.dev")
install.packages("anumaan", repos = "https://saketlab.r-universe.dev")
install.packages("seqout", repos = "https://saketlab.r-universe.dev")
```

All of them, with CRAN dependencies resolved:

```r
options(repos = c(
  saketlab = "https://saketlab.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))

install.packages(c("censusindia", "anumaan", "seqout"))
```
