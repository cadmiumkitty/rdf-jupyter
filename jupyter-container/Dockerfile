FROM jupyter/scipy-notebook
MAINTAINER Eugene Morozov <emorozov@gmail.com>

RUN pip install sparqlkernel
RUN jupyter sparqlkernel install --user
RUN pip install rdfpandas
RUN pip install gastrodon
RUN pip install ipython-sparql
