# saketlab.r-universe.dev

R packages from [saketlab](https://github.com/saketlab) on [r-universe](https://saketlab.r-universe.dev).

## Packages

| | Package | Description | Source |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/saketlab/censusindia/main/man/figures/logo.png" height="60"> | `censusindia` | Digitised Census of India (1901–2011) | [saketlab/censusindia](https://github.com/saketlab/censusindia) |
|  | `anumaan` | Antimicrobial resistance surveillance preprocessing and burden estimation | [saketlab/anumaan](https://github.com/saketlab/anumaan) |
| <img src="https://raw.githubusercontent.com/saketlab/seqout/main/R/man/figures/logo.svg" height="60"> | `seqout` | R client for the SeqOut genomics metadata search interface (GEO, SRA, ENA, ArrayExpress) | [saketlab/seqout](https://github.com/saketlab/seqout) |
| <img src="https://raw.githubusercontent.com/saketlab/genevintage/main/R/man/figures/logo.png" height="60"> | `genevintage` | Detect the species and Ensembl/GENCODE release of gene IDs, then convert them to gene names | [saketlab/genevintage](https://github.com/saketlab/genevintage) |
|  | `lightson` | Download and analyse nighttime lights satellite data | [saketlab/lightson](https://github.com/saketlab/lightson) |
| <img src="https://raw.githubusercontent.com/saketlab/varunayanR/main/man/figures/logo.png" height="60"> | `varunayan` | Download and process climate data from ERA5, IMD, HadEX3, and CRU TS | [saketlab/varunayanR](https://github.com/saketlab/varunayanR) |
| <img src="https://raw.githubusercontent.com/saketlab/vayuayanR/main/man/figures/logo.png" height="60"> | `vayuayan` | Air quality data from CPCB, OAQ, and WUSTL satellite PM2.5 | [saketlab/vayuayanR](https://github.com/saketlab/vayuayanR) |
| <img src="https://raw.githubusercontent.com/saketkc/mospiR/main/man/figures/logo.png" height="60"> | `mospiR` | Client for the MoSPI microdata portal | [saketkc/mospiR](https://github.com/saketkc/mospiR) |
|  | `nesstarR` | Read and export NESSTAR binary containers | [saketkc/nesstarR](https://github.com/saketkc/nesstarR) |
| <img src="https://raw.githubusercontent.com/saketlab/alethia/main/docs/assets/logo.svg" height="60"> | `alethiaR` | Match and deduplicate messy entity names against a reference list | [saketlab/alethia](https://github.com/saketlab/alethia) |
| <img src="https://raw.githubusercontent.com/saketlab/SexSeek/main/man/figures/logo.png" height="60"> | `SexSeek` | Estimate genetic sex from expression counts | [saketlab/SexSeek](https://github.com/saketlab/SexSeek) |

## Install

Individual package:

```r
install.packages("censusindia", repos = "https://saketlab.r-universe.dev")
install.packages("anumaan", repos = "https://saketlab.r-universe.dev")
install.packages("seqout", repos = "https://saketlab.r-universe.dev")
install.packages("genevintage", repos = "https://saketlab.r-universe.dev")
install.packages("lightson", repos = "https://saketlab.r-universe.dev")
install.packages("varunayan", repos = "https://saketlab.r-universe.dev")
install.packages("vayuayan", repos = "https://saketlab.r-universe.dev")
install.packages("mospiR", repos = "https://saketlab.r-universe.dev")
install.packages("nesstarR", repos = "https://saketlab.r-universe.dev")
install.packages("alethiaR", repos = "https://saketlab.r-universe.dev")
install.packages("SexSeek", repos = "https://saketlab.r-universe.dev")
```

All of them, with CRAN dependencies resolved:

```r
options(repos = c(
  saketlab = "https://saketlab.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))

install.packages(c("censusindia", "anumaan", "seqout", "genevintage", "lightson", "varunayan", "vayuayan", "mospiR", "nesstarR", "alethiaR", "SexSeek"))
```
