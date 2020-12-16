FROM miniconda3

LABEL maintainer=@and92reas

RUN conda update conda && \
    conda install pip &&\
    pip install backports.functools_lru_cache &&\
    conda install --quiet --yes ipython && \
    conda clean -tipsy


CMD ["ipython"]
