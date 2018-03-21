FROM debian
MAINTAINER Marc EYMARD <contact@marc-eymard.fr>

ARG INFO_UID
ARG INFO_USER
ARG INFO_GID

RUN groupadd --gid $INFO_GID usergroup
RUN useradd --uid $INFO_UID --gid $INFO_GID $INFO_USER

