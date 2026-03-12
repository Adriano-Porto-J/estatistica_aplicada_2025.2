# Instalar bibliotecas do R

Abra o R ou RStudio e execute:

```r
install.packages(c(
  "dplyr",
  "ggplot2",
  "readxl",
  "corrplot",
  "rlang",
  "skimr"
))
```
Para instalar as bibliotecas do projeto

# Suporte de geração de pdf

```bash
quarto install tinytex
```

# Gerar o relatório
Para gerar o html e pdf execute:

```bash
quarto render report.qmd
```