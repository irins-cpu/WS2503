## Instruction on how to use the superset buildand howw to build custom images on existing superset imae. Adding new database support.

``` bash
docker build -t superset-build .
docker run -d -p 8088:8088 --name superset superset-build
```

