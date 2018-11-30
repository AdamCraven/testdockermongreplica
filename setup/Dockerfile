FROM mongo
WORKDIR /usr/src/configs

COPY replicaSet.js .
COPY setup.sh .
CMD ["chmod", "+x", "./setup.sh"]
CMD ["./setup.sh"]