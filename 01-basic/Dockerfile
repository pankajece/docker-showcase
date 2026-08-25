FROM ubuntu:24.04 AS builder

RUN printf 'Built in the builder stage\n' > /hello.txt

FROM ubuntu:24.04

COPY --from=builder /hello.txt /hello.txt

CMD ["cat", "/hello.txt"]
