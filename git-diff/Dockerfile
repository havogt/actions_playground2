FROM alpine:latest

WORKDIR /workdir

RUN apk update && apk add git

CMD ["git", "diff", "-U0", "--no-color", "master"]

#ENTRYPOINT ["clang-format-diff.py"]
#CMD ["--help"]
