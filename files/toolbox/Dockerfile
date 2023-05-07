# All credit goes to https://www.cogitri.dev/posts/12-fedora-toolbox/

FROM registry.fedoraproject.org/fedora-toolbox:38

COPY extra-packages /

RUN dnf -y install $(<extra-packages)

RUN rm /extra-packages
