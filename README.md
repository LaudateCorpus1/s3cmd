# s3cmd

The purpose of this container is to be used as part of a drone build pipeline and pull in an object from s3.

Build:
```
docker build s3cmd:latest .
```

Usage
```
docker run viant/s3cmd:latest s3cmd get s3://example/foo.txt
```
