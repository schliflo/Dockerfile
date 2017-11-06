#+++++++++++++++++++++++++++++++++++++++
# Dockerfile for webdevops/ssh:latest
#    -- automatically generated  --
#+++++++++++++++++++++++++++++++++++++++

FROM webdevops/base-app:latest

RUN set -x \
    && /opt/docker/bin/control.sh service.enable ssh \
    && docker-run-bootstrap \
    && docker-image-cleanup

EXPOSE 22
