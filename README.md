Dockerized phpDocumentor
========================

This Docker image contains a working [phpDocumentor](http://www.phpdoc.org/) installation.

Usage
-----

Use as follows:

    docker run --rm -v $PWD:/work -u $(id -u) martinhelmich/phpdoc [phpdoc-options]
