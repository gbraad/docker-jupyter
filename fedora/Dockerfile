FROM registry.gitlab.com/gbraad/fedora:24
MAINTAINER Gerard Braad <me@gbraad.nl>

RUN dnf install -y python3-devel redhat-rpm-config gcc-c++ @'Development Tools'; \

    pip3 install jupyter; \

    dnf remove -y python3-devel redhat-rpm-config gcc-c++ @'Development Tools'; \

    mkdir -p /workspace

VOLUME ["/workspace"]
WORKDIR /workspace

EXPOSE 8888

CMD ["jupyter"]
