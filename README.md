# Apache HTTP with SSI

This Apache HTTP image is intended for development of the buildroot.org website.

## Build

    docker build -t angelocompagnucci/httpd-ssi .

## Run

    docker run --rm --name httpd-ssi -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ angelocompagnucci/httpd-ssi
