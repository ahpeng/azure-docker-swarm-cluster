# This is a minimal Apline image that preinstalls requirements upon Docker build
FROM rcarmo/alpine-python:3.5-onbuild

ADD . /app
WORKDIR /app
USER nobody
EXPOSE 8000
ENV PORT=8000
CMD python app.py