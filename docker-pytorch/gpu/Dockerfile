FROM continuumio/miniconda3:latest

LABEL maintainer "Mustang"
RUN apt-get update && apt-get -y install gcc
RUN conda install --yes pytorch -c pytorch
RUN conda install --yes tensorflow-gpu -c anaconda
RUN conda install --yes keras -c conda-forge
RUN conda install --yes scikit-learn
RUN conda install --yes pandas -c anaconda
RUN conda install --yes flask -c anaconda
RUN conda install --yes nltk -c anaconda
RUN pip install transformers
RUN pip install seqeval[gpu]
RUN conda install numba

RUN numba -s

RUN conda clean -afy