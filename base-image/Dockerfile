FROM ubuntu:14.04.2
RUN locale-gen en_US.UTF-8
ENV LANG en_US.UTF-8
COPY ./scripts/bootstrap /scripts/
RUN ./scripts/bootstrap
COPY ./scripts/ /source/scripts/
COPY ./config/ /source/config/
