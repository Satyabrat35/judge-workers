FROM alpine:3.7

RUN apk add --no-cache nodejs=8.9.3-r0  bash
COPY ./compile.sh /bin/compile.sh
COPY ./run.sh /bin/run.sh
RUN chmod 777 /bin/compile.sh; \
    chmod 777 /bin/run.sh