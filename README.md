
<!-- README.md is generated from README.Rmd. Please edit that file -->

# About scDrugHunter

<!-- badges: start -->
<!-- badges: end -->

**scDrugHunter** evaluates potential gene-drug interactions associated
with candidate genes by single-cell gene expression specificity level in
each cell type, correlation between single-cell gene expression and
phenotypes, significance of eQTL-phenotype associations and the
drug-gene interaction score provided by DGIdb database

## Installation

You can install the released version of scPagwas from
[github](https://github.com/x-burner-ux/scDrugHunter) with:

``` r
#install some dependence packages
install.packages("circlize")
devtools::install_github("ricardo-bion/ggradar", dependencies = TRUE)

#install scDrugHunter
devtools::install_github("x-burner-ux/scDrugHunter")
```

## Tutorials

scDrugHunter provides a tutorial
[Quik\_start\_for\_scDrugHunter](http://htmlpreview.github.io/?https://github.com/x-burner-ux/x-burner-ux.github.io/blob/main/scDrugHunter/article/Quik_start_for_scDrugHunter.html)
with quick example. Please also visit the documentation.

## Related analysis codes
See the application of scDrugHunter on revealing the cell type-specific drugs for severe COVID-19, [link](https://github.com/mayunlong89/scHuman_organoids_COVID19/tree/main). 

## Citation
Ma et al. Integration of human organoids single-cell transcriptomic profiles and human genetics repurposes critical cell type-specific drug targets for severe COVID-19, [Cell Proliferation, 2023,e13558](https://onlinelibrary.wiley.com/doi/full/10.1111/cpr.13558)

# All COVID-19-related projects in our group:
1) Meta-analysis of large-scale GWAS data to uncover novel loci for COVID-19. see [Ma et al. Human Molecular Genetics, 2021](https://academic.oup.com/hmg/article/30/13/1247/6265026), and see related [Github codes](https://github.com/mayunlong89/Host_genetics_for_COVID-19).
2) Identification of genetics-influenced immune cell sub-populations relevant to severe COVID-19. see [Ma et al. Genome Medicine, 2022](https://link.springer.com/article/10.1186/s13073-022-01021-1), and see related [Github codes](https://github.com/mayunlong89/COVID19_scRNA).
3) Repurposing cell type-specific durg targets for severe COVID-19 based on human organoids scRNA-seq atlas. see [Ma et al. Cell Proliferation, 2023](https://onlinelibrary.wiley.com/doi/full/10.1111/cpr.13558), and see related [Github codes](https://github.com/mayunlong89/scHuman_organoids_COVID19)
4) Development of novel polygenic regression method scPagwas for integrating scRNA-seq data with GWAS on complex diseases. see [Ma et al. Cell Genomics, 2023](https://www.cell.com/cell-genomics/fulltext/S2666-979X(23)00180-5), and see related [Github codes](https://github.com/mayunlong89/scPagwas_main)
