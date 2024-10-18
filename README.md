SYSTEM REQUIREMENTS

Windows Operating system 

Computer with minimum: 
-64 Gt RAM
-CPU with 8 cores or more
- 1 Tb of hard disk space

1: Install R (Version: 4.4.1) 
2: Install RStudio (Version: 2024.04.2+764)

Install the following R packages:
BiocNeighbors	https://www.bioconductor.org/packages/release/bioc/html/BiocNeighbors.html 

CellChat	http://www.cellchat.org/  

ClusterProfiler	https://bioconductor.org/packages/release/bioc/html/clusterProfiler.html 

ComplexHeatmap	https://jokergoo.github.io/ComplexHeatmap-reference/book/index.html 

data.table	https://rdatatable.gitlab.io/data.table/

DoubletFinder	https://github.com/chris-mcginnis-ucsf/DoubletFinder

dplyr		https://dplyr.tidyverse.org/

enrichplot	https://bioconductor.org/packages/enrichplot.

ggalluvial	https://corybrunson.github.io/ggalluvial/

ggplot2		https://ggplot2.tidyverse.org/

glmGamPoi	https://github.com/const-ae/glmGamPoi

heatmaply	https://talgalili.github.io/heatmaply/

htmltools	https://rstudio.github.io/htmltools/

Igraph		https://r.igraph.org/

maftools	https://bioconductor.org/packages/devel/bioc/vignettes/maftools/inst/doc/maftools.html 

magrittr	https://magrittr.tidyverse.org/

nichenetr	https://github.com/saeyslab/nichenetr

Matrix		https://rdrr.io/rforge/Matrix/

NMF		https://renozao.github.io/NMF/devel/index.html 

patchwork	https://patchwork.data-imaginist.com/

pathview	https://pathview.r-forge.r-project.org/ 

plotly		https://plotly.com/r/getting-started/

RColorBrewer	https://r-graph-gallery.com/38-rcolorbrewers-palettes.html

Reticulate	https://rstudio.github.io/reticulate/

scCustomize	https://samuel-marsh.github.io/scCustomize/index.html

rstatix		https://rdrr.io/cran/rstatix/

Seurat		https://satijalab.org/seurat/

SeuratDisk	https://github.com/mojaveazure

tidyverse	https://www.tidyverse.org/

Ucell		https://rdrr.io/github/carmonalab/UCell/

viridis		https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html

INSTALLATION QUIDE

https://posit.co/download/rstudio-desktop/
estimated install time: 30 min - 1 h

See links above for R package installation.

INSTRUCTIONS FOR USE

DATA 1. Mouse melanoma and control lung data

Follow code at: 
https://github.com/nmsantio/Mouse-melanoma-lung-EC-scRNASeq

DATA 3. Human lung EC data from
https://hlca.ds.czbiohub.org/

Download data:

https://www.synapse.org/Synapse:syn21041850/wiki/600865

Follow code at: https://github.com/nmsantio/HLCA_scRNASeq_EC

4. Integrate human data from DATA 3. with mouse data from DATA 1.

Follow code at:

https://github.com/nmsantio/Integration-of-mouse-and-human-scRNASeq-data

Open both datasets created from DATA 3 and DATA 1 in R. 
Step 1. Downsampling - Replace filename with mouse data file name
Step 2. Mouse gene names to human
Step 3. Data integration - Check that the human data file has name hLung, if not, replace hLung with the datafile name

Link summary to github
https://github.com/nmsantio/Mouse-melanoma-lung-EC-scRNASeq
https://github.com/nmsantio/HLCA_scRNASeq_EC
https://github.com/nmsantio/Integration-of-mouse-and-human-scRNASeq-data

Additional visualization instructions can be found from the above mentioned links, mainly at
https://satijalab.org/seurat/
https://samuel-marsh.github.io/scCustomize/index.html
