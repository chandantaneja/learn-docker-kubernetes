# Use an existing docker image as a base
FROM alpine

# Download and install a dep
RUN apk add --update redis
CMD ["redis-server"]
# Tell the image twhat to do when it starts as a container 
