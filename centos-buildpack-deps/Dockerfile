# "ported" from https://registry.hub.docker.com/_/buildpack-deps/
FROM centos:centos8

RUN dnf -y update && dnf clean all
RUN dnf -y install epel-release dnf-plugins-core \
    && dnf clean all \
    && dnf config-manager --set-enabled PowerTools

RUN dnf -y install cvs \
                   git \
                   mercurial \
                   subversion \
                   curl \
                   wget \
                   tar \
                   autoconf \
                   automake \
                   gcc \
                   gcc-c++ \
                   make \
                   file \
                   unzip \
                   ImageMagick \
                   bzip2-devel \
                   libcurl-devel \
                   libevent-devel \
                   libffi-devel \
                   glib2-devel \
                   glibc-devel \
                   libjpeg-devel \
                   ImageMagick-devel \
                   mysql-devel \
                   ncurses-devel \
                   postgresql-devel \
                   readline-devel \
                   sqlite-devel \
                   openssl-devel \
                   libxml2-devel \
                   libxslt-devel \
                   libyaml-devel \
		   libpq-devel \
                   libwebp-devel \
                   libpng-devel \
                   libjpeg-devel \
                   gdbm-devel \
                   zlib-devel \
                   && dnf clean all
