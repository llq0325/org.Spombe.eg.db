# org.Spombe.eg.db  
Title: Genome wide annotation for Schizosaccharomyces pombe  
Description: Genome wide annotation for Schizosaccharomyces pombe, primarily based on mapping using Entrez Gene identifiers.  
Version: 0.1  
Author: Langqing Liu
Maintainer: Langqing Liu
Depends: R (>= 2.7.0), methods, AnnotationDbi (>= 1.52.0)  
Suggests: DBI, annotate, RUnit  
Imports: methods, AnnotationDbi  
License: Artistic-2.0  
organism: Schizosaccharomyces pombe  
species: Schizosaccharomyces pombe  
biocViews: OrgDb, annotation  

```Rscript
library(AnnotationForge)
makeOrgPackageFromNCBI(version = "0.1",
                        author = "your name <your.name@email.com>",
                        maintainer = "your name <your.name@email.com",
                        outputDir = ".",
                        tax_id = "4896",
                        genus = "Schizosaccharomyces",
                        species = "pombe")


install('org.Spombe.eg.db')
library('org.Spombe.eg.db')
```
