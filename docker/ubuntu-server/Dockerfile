# Start with Ubuntu 22.04 as the base image
FROM ubuntu:22.04

# Set the maintainer label (optional)
LABEL maintainer="werner.damboeck@htlstp.ac.at"

# Update the package list and install nano
RUN apt-get -y update && \
    apt-get install -y nano && \
    apt-get -y clean

# Set the default command to run bash
CMD ["bash"]
