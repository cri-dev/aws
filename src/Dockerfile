FROM python
MAINTAINER michael.ottoson@cri.com

RUN pip install --no-cache-dir awscli
RUN apt-get update && apt-get install -y \
    groff \
    nano \
    && rm -rf /var/lib/apt/lists/*

CMD ["bash"]