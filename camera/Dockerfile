FROM aler9/rtsp-simple-server AS rtsp
FROM alpine:3.18

RUN apk add --no-cache bash
RUN apk add --no-cache ffmpeg

WORKDIR /

COPY --from=rtsp /mediamtx /