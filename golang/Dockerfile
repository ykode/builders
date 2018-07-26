FROM golang:alpine

RUN apk --update --no-cache add upx file clang build-base curl git bzr mercurial \ 
      && curl https://raw.githubusercontent.com/golang/dep/master/install.sh | sh \
      && curl https://glide.sh/get | sh


