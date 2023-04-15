FROM alpine
RUN apk update && \
    apk upgrade && \
    apk add bash

WORKDIR /alpine
 
COPY . .

CMD ["bash"]