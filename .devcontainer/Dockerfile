# Use the base image
FROM codercom/enterprise-base:ubuntu
USER root
# Add the CA certificate
COPY ./CACert.crt /usr/local/share/ca-certificates/ca.crt
# Update the CA certificates
RUN update-ca-certificates
