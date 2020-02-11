FROM cyversevice/rstudio-verse:latest

RUN apt-get update && apt-get install -y zlib1g-dev libxml2-dev

RUN Rscript -e 'source("http://bioconductor.org/biocLite.R"); biocLite("devtools"); biocLite("pachterlab/sleuth");'
RUN Rscript -e 'source("http://bioconductor.org/biocLite.R"); biocLite("edgeR");'
RUN Rscript -e 'source("http://bioconductor.org/biocLite.R"); biocLite("annotate"); biocLite("genefilter");'
RUN Rscript -e 'source("http://bioconductor.org/biocLite.R"); biocLite("DESeq2");'
RUN Rscript -e 'source("http://bioconductor.org/biocLite.R"); biocLite("ballgown");'
© 2020 GitHub, Inc.
