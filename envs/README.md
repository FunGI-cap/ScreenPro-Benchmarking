# Setup environments

### `crisprVerse`

```bash
mamba env create -f envs/crisprVerse.yml
```

```R
BiocManager::install("crisprVerse")
```

```R
install.packages("devtools")
devtools::install_github("crisprVerse/crisprDesignData")
```