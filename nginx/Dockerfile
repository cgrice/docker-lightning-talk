FROM nginx:alpine

RUN apk --no-cache add curl

HEALTHCHECK --retries=3 --interval=1s --timeout=1s \
  CMD curl localhost:8080 || exit 1
