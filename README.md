# saketlab.r-universe.dev

R packages from [saketlab](https://github.com/saketlab) on [r-universe](https://saketlab.r-universe.dev).

## Packages

<p align="center">
  <a href="https://censusindia.saketlab.org/"><img src="https://raw.githubusercontent.com/saketlab/censusindia/main/man/figures/logo.png" height="120" alt="censusindia"></a>
  <a href="https://saketlab.github.io/anumaan/"><img src="https://raw.githubusercontent.com/saketlab/anumaan/main/man/figures/logo.png" height="120" alt="anumaan"></a>
  <a href="https://seqout.org/cli/R/"><img src="https://raw.githubusercontent.com/saketlab/seqout/main/R/man/figures/logo.svg" height="120" alt="seqout"></a>
  <a href="https://genevintage.saketlab.org/R/"><img src="https://raw.githubusercontent.com/saketlab/genevintage/main/R/man/figures/logo.png" height="120" alt="genevintage"></a>
  <a href="https://lightson.saketlab.org/"><img src="https://raw.githubusercontent.com/saketlab/lightson/main/man/figures/logo.png" height="120" alt="lightson"></a>
  <a href="https://varunayan.saketlab.org/R/"><img src="https://raw.githubusercontent.com/saketlab/varunayan/main/R/man/figures/logo.png" height="120" alt="varunayan"></a>
  <a href="https://vayuayan.saketlab.org/R/"><img src="https://raw.githubusercontent.com/saketlab/vayuayan/main/R/man/figures/logo.png" height="120" alt="vayuayan"></a>
  <a href="https://mospir.saketlab.org/"><img src="https://raw.githubusercontent.com/saketkc/mospiR/main/man/figures/logo.png" height="120" alt="mospiR"></a>
  <a href="https://nesstarr.saketlab.org/"><img src="https://raw.githubusercontent.com/saketkc/nesstarR/main/man/figures/logo.png" height="120" alt="nesstarR"></a>
  <a href="https://alethia.saketlab.org/cli/R/"><img src="https://raw.githubusercontent.com/saketlab/alethia/main/docs/assets/logo.svg" height="120" alt="alethiaR"></a>
  <a href="https://sexseek.saketlab.org/"><img src="https://raw.githubusercontent.com/saketlab/SexSeek/main/man/figures/logo.png" height="120" alt="SexSeek"></a>
</p>

| Package | Description | Repository | Documentation |
|---|---|---|---|
| `censusindia` | Digitised Census of India (1901–2011) | [saketlab/censusindia](https://github.com/saketlab/censusindia) | [censusindia.saketlab.org](https://censusindia.saketlab.org/) |
| `anumaan` | Antimicrobial resistance surveillance preprocessing and burden estimation | [saketlab/anumaan](https://github.com/saketlab/anumaan) | [saketlab.github.io/anumaan](https://saketlab.github.io/anumaan/) |
| `seqout` | R client for the SeqOut genomics metadata search interface (GEO, SRA, ENA, ArrayExpress) | [saketlab/seqout](https://github.com/saketlab/seqout) | [seqout.org/cli/R](https://seqout.org/cli/R/) |
| `genevintage` | Detect the species and Ensembl/GENCODE release of gene IDs, then convert them to gene names | [saketlab/genevintage](https://github.com/saketlab/genevintage) | [genevintage.saketlab.org/R](https://genevintage.saketlab.org/R/) |
| `lightson` | Download and analyse nighttime lights satellite data | [saketlab/lightson](https://github.com/saketlab/lightson) | [lightson.saketlab.org](https://lightson.saketlab.org/) |
| `varunayan` | Download and process climate data from ERA5, IMD, HadEX3, and CRU TS | [saketlab/varunayan](https://github.com/saketlab/varunayan) | [varunayan.saketlab.org/R](https://varunayan.saketlab.org/R/) |
| `vayuayan` | Air quality data from Indian monitoring networks (CPCB, OAQ) and satellites (WUSTL PM2.5) | [saketlab/vayuayan](https://github.com/saketlab/vayuayan) | [vayuayan.saketlab.org/R](https://vayuayan.saketlab.org/R/) |
| `mospiR` | Client for the MoSPI microdata portal | [saketkc/mospiR](https://github.com/saketkc/mospiR) | [mospir.saketlab.org](https://mospir.saketlab.org/) |
| `nesstarR` | Read and export NESSTAR binary containers | [saketkc/nesstarR](https://github.com/saketkc/nesstarR) | [nesstarr.saketlab.org](https://nesstarr.saketlab.org/) |
| `alethiaR` | Match and deduplicate messy entity names against a reference list | [saketlab/alethia](https://github.com/saketlab/alethia) | [alethia.saketlab.org/cli/R](https://alethia.saketlab.org/cli/R/) |
| `SexSeek` | Estimate genetic sex from expression counts | [saketlab/SexSeek](https://github.com/saketlab/SexSeek) | [sexseek.saketlab.org](https://sexseek.saketlab.org/) |

## Install

Individual package (CRAN is listed so dependencies resolve):

```r
install.packages("censusindia", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("anumaan", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("seqout", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("genevintage", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("lightson", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("varunayan", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("vayuayan", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("mospiR", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("nesstarR", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("alethiaR", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
install.packages("SexSeek", repos = c("https://saketlab.r-universe.dev", "https://cloud.r-project.org"))
```

All of them, with CRAN dependencies resolved:

```r
options(repos = c(
  saketlab = "https://saketlab.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))

install.packages(c("censusindia", "anumaan", "seqout", "genevintage", "lightson", "varunayan", "vayuayan", "mospiR", "nesstarR", "alethiaR", "SexSeek"))
```

### System requirements

`censusindia`, `lightson`, `varunayan` and `vayuayan` depend on `sf`/`terra`. Binaries on Windows and macOS need nothing extra; on Linux install GDAL, GEOS and PROJ first (e.g. `sudo apt install libgdal-dev libgeos-dev libproj-dev libudunits2-dev`).

`anumaan` optionally uses CmdStan for Bayesian estimation:

```r
install.packages("cmdstanr", repos = c("https://stan-dev.r-universe.dev", "https://cloud.r-project.org"))
cmdstanr::install_cmdstan()
```

