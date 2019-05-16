FROM mongo
EXPOSE 27017
COPY ./tmp /tmp
WORKDIR /tmp/
ENTRYPOINT mongod --config mongodb.yml && mongoimport -h 127.0.0.1:27017 -d youtube_db -c col col.dat