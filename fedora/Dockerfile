FROM registry.gitlab.com/gbraad/fedora:24
MAINTAINER Gerard Braad <me@gbraad.nl>

RUN pip3 install --upgrade pip; \
    pip3 install jupyter; \

    mkdir -p /workspace

VOLUME ["/workspace"]
WORKDIR /workspace

EXPOSE 8888

CMD ["jupyter", "notebook", "--no-browser", "--allow-root"]
