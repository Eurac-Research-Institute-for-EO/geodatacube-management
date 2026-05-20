# geodatacube-management

## Introduction

Making the world a better place one GeoDataCube at a time

## How to compile

The recommended way is to run the following, which will generate the output files:

```sh
docker run --rm \
   -v "$(pwd)":/metanorma -w /metanorma \
   metanorma/metanorma metanorma compile --agree-to-terms -t ogc -x html,pdf document.adoc
```

or if you have installed the tool locally:

```sh
metanorma compile --agree-to-terms -t ogc -x html,pdf document.adoc
```
