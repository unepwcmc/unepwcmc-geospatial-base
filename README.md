# unepwcmc-geospatial-base

Geospatial base image for dockerised Rails apps at UNEP-WCMC. Includes GDAL, Postgres, Node, npm, GEOS, RVM and Ruby 2.6.3; with bundler, rake and so forth.

## Building the image
Here we use the example of `20190809` as the date to tag the image.

```
docker build . -t unepwcmc/unepwcmc-geospatial-base:20190809
```

## Pushing the image

Please first get the correct permissions on Docker Hub to push to the repo.

```
docker push unepwcmc/unepwcmc-geospatial-base:20190809
```
