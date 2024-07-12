# Dockerfile

FROM public.ecr.aws/amazonlinux/amazonlinux:latest

RUN yum install -y unzip

# AWS CLI installation
RUN curl -sOL https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip \
  && unzip awscli-exe-linux-x86_64.zip \
  && ./aws/install

RUN curl -sOL https://fastdl.mongodb.org/tools/db/mongodb-database-tools-amazon2-x86_64-100.6.0.rpm \
  && yum install -y mongodb-database-tools-amazon2-x86_64-100.6.0.rpm
