FROM ubuntu
WORKDIR /opt
RUN mkdir aqfer/ 
COPY test-binary aqfer/ 
RUN chmod +x aqfer/test-binary
CMD ["/bin/bash", "aqfer/test-binary"]
