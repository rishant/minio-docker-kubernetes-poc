FROM ubuntu:latest

# Install necessary packages
RUN apt-get update && apt-get install -y \
    s3fs \
    python3 \
    python3-pip

# Install Python packages
COPY requirements.txt /tmp/
RUN pip3 install -r /tmp/requirements.txt

# Copy Python script to container
COPY script.py /script.py
