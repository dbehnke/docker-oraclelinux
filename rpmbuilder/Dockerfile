FROM dbehnke/ol6:latest

RUN yum update -y && \
    yum install -y rpm-build && \
    yum clean all && \
    rm -r -f /var/cache/* && \
    rm -r -f /tmp
