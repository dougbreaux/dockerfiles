# tiny Linux
FROM alpine

# add docker client
RUN apk add --update curl && rm -rf /var/cache/apk/* && curl -L https://download.docker.com/linux/static/stable/x86_64/docker-18.09.2.tgz > docker.tgz 
RUN tar xzvf docker.tgz docker/docker --strip-components 1 -C /usr/local/bin && rm docker.tgz