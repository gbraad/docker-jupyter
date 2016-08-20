FROM registry.gitlab.com/gbraad/fedora:24
MAINTAINER Gerard Braad <me@gbraad.nl>

RUN pip3 install --upgrade pip; \
    pip3 install jupyter; \

    mkdir -p /workspace; \
    mkdir -p /etc/jupyter

VOLUME ["/workspace"]
WORKDIR /workspace

EXPOSE 8888

COPY jupyter_notebook_config.py /etc/jupyter

CMD ["jupyter", "notebook"]
