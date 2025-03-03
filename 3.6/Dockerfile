# Deprecated image. Won't build anymore.
#This Dockerfile is used only to patch the cert issue.
FROM govpf/python:3.6-lastbuild

COPY 3.6/install_certs /tmp/install_certs
RUN rm /usr/local/share/ca-certificates/* && bash -xe /tmp/install_certs
