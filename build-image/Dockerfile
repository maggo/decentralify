FROM netlify/build:xenial

USER root
ADD build.sh /usr/local/bin/build-decentralized
RUN chmod u+x /usr/local/bin/build-decentralized

ENTRYPOINT ["build-decentralized"]