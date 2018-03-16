FROM kalilinux/kali-linux-docker:latest

MAINTAINER "Jeremy CURNY" <jeremy.curny.pro@gmail.com>

ARG DEBIAN_FRONTEND=noninteractive

RUN  \
    apt-get update \
    && apt-get install -y metasploit-framework \
    && apt-get clean autoclean \
    && apt-get autoremove
