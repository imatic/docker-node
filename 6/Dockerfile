FROM node:6

ENV HOME="/opt/app-root/src"

RUN mkdir -p ${HOME} && \
    chown --recursive 1001:0 ${HOME} && \
    useradd --uid 1001 --system --gid 0 --home-dir ${HOME} --shell /sbin/nologin default

USER default
WORKDIR ${HOME}

