# PHP_CodeSniffer Docker image

## Supported tags

* latest

## What is PHP Mess Detector?

PHPMD takes a given PHP source code base and look for several potential problems within that source.

> https://github.com/phpmd/phpmd

## How to use this image

```console
docker run --volume </local/path>:/project hlacos/phpmd[:tag] [<options>]
```

Example:
```console
docker run --volume /project/path:/project hlacos/phpmd phpmd /project text cleancode,codesize,controversial,design,naming,unusedcode
```
