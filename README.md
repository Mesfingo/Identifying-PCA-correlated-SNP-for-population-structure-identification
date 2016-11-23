## R-code-for-identifying-gnetic-markers-SNP-with-strong-contribution-to-population-structure.-
The R code is an implementation of a method described by Paschou et al in a serious of articles (Paschou et al 2007; Paschou et al 2008; Paschou et al 2010; Lewis et al 2011).  Singular value decomposition is performed on genotype data, and SNP are ordered based on the squared sum of corresponding right singular vectors. The number of rows the right singular vectors are summed over depends on the number of significant principal components identified, which has to be determined beforehand (Tracy-Widom distribution and Broken-stick method come to mind).

**Refference**

Lewis, J. et al., 2011. Tracing Cattle Breeds with Principal Components Analysis Ancestry Informative SNPs. , 6(4).

Paschou, P. et al., 2010. Ancestry informative markers for fine-scale individual assignment to worldwide populations. Journal of Medical 

Genetics, 47(12), pp.835–847.

Paschou, P. et al., 2007. PCA-Correlated SNPs for Structure Identification in Worldwide Human Populations. PLoS Genetics, 3(9).

Paschou, P. et al., 2008. Tracing Sub-Structure in the European American Population with PCA-Informative Markers. PLoS Genetics, 4(7).

