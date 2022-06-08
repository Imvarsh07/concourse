FROM redis
RUN mkdir -p opt/aqfer
COPY addition.sh /opt/aqfer/
CMD echo "This is a test." | wc -
#CMD [ "redis-server", "opt/aqfer/addition.sh" ]
#ENTRYPOINT ["/bin/bash", "/addition.sh"]
