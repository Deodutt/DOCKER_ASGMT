FROM ubuntu:latest
LABEL description="GIT"

RUN apt-get update -y
RUN apt-get install git -y
RUN apt-get upgrade && DEBIAN_FRONTEND="noninteractive" TZ="America/New_York" apt-get install tzdata ssh -y
