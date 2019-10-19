martinpauly/hugo
==============
Forked from monachus/hugo. Added FTP client.

`monachus/hugo` is a [Docker](https://www.docker.io) base image for static sites generated with [Hugo](http://gohugo.io).  

This image is uses the `extended` release of Hugo, which contains support for Sass/SCSS.

Images derived from this image can either run as a stand-alone server, or function as a volume image for your web server.  You can also use them in a CI/CD system such as Gitlab CI to build your content prior to bundling it into a standalone webserver container such as `httpd:alpine`.

