FROM python:3.11-alpine
ARG VERSION=v1
ENV VERSION=$VERSION
WORKDIR /app
RUN pip install --no-cache-dir flask
COPY main.py .
EXPOSE 8888
CMD ["python", "main.py"]
