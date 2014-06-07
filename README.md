deegree docker container
========================

deegree version 3.3.9 webservice with docker using tomacat+deegree bundle from the deegree.org website

Usage
-----

```bash
docker run -p 8080:8080 -d martinvi/deegree:3.3.9
```

Build
-----
download the dockerfile into a directory an run:

```bash
docker build -t martinvi/deegree .
```
