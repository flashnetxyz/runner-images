FROM amazonlinux

LABEL git.repository_url="github.com/flashnetxyz/runner-images"
LABEL org.opencontainers.image.source="https://github.com/flashnetxyz/runner-images"
LABEL org.opencontainers.image.path="runners/nitro/Dockerfile"
LABEL org.opencontainers.image.title="nitro"
LABEL org.opencontainers.image.description="A runner image for Nitro"
LABEL org.opencontainers.image.authors="Nejc Drobnic <nejc@flashnet.xyz>"
LABEL org.opencontainers.image.vendor="Polarity Ln, Inc."
LABEL org.opencontainers.image.licenses="Apache-2.0"
LABEL org.opencontainers.image.documentation="https://github.com/flashnetxyz/runner-images/README.md"

RUN yum install -y \
    aws-nitro-enclaves-cli \
    aws-nitro-enclaves-cli-devel \
    tar \
    jq \
    git \
    sudo \
    procps-ng \
    && yum clean all
