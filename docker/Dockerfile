FROM jupyter/datascience-notebook

RUN pip install --upgrade pip \
    && pip install datapackage \
    && pip install --upgrade seaborn \
    && pip install plotly_express \
    && pip install --upgrade scikit-learn \
    && pip install tensorflow \
    && pip3 install torch torchvision \
    && pip install --user -U nltk 

WORKDIR '/home/jovyan/work/code/'
