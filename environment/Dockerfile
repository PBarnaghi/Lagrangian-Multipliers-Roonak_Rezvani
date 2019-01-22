FROM registry.codeocean.com/codeocean/r-base:3.4.4-ubuntu16.04

ARG DEBIAN_FRONTEND=noninteractive

RUN Rscript -e 'devtools::install_version("Rssa", \
      version = "1.0", \
      dependencies = TRUE)'
RUN Rscript -e 'devtools::install_version("caret", \
      version = "6.0-80", \
      dependencies = TRUE)'
RUN Rscript -e 'devtools::install_version("clValid", \
      version = "0.6-6", \
      dependencies = TRUE)'
RUN Rscript -e 'devtools::install_version("cluster", \
      version = "2.0.6", \
      dependencies = TRUE)'
RUN Rscript -e 'devtools::install_version("dtwclust", \
      version = "5.5.1", \
      dependencies = TRUE)'
RUN Rscript -e 'devtools::install_version("lsa", \
      version = "0.73.1", \
      dependencies = TRUE)'
RUN Rscript -e 'devtools::install_version("party", \
      version = "1.3-1", \
      dependencies = TRUE)'
