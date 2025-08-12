FROM docker.io/python:3.13-bookworm

ENV DEBIAN_FRONTEND=noninteractive \
    PIP_NO_CACHE_DIR=1 \
    PIP_ROOT_USER_ACTION=ignore

RUN python3 -m pip install \
        jupyter \
        jupyterlab \
        nbclassic \
        ipykernel \
        ipympl \
        nglview \
        widgetsnbextension \
        jupyterlab_widgets \
        notebook \
        ipywidgets \
        scipy \
        matplotlib
