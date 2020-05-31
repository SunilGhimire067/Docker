#Use existing docker image as a file

FROM alpine

#Download and Install all dependencies

RUN apk add --update redis

#tell the contaner what to do when it starts as a container

CMD ["redis-server"]