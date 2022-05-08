
## Introduction

This is an example how to use apache-webdav file server from https://github.com/BytemarkHosting/docker-webdav
with http methods.


## API

- Create folder 'files': curl -X MKCOL 'http://localhost:8080/files'
- Upload file: curl -T 'docker-compose.yaml' 'http://localhost:8080/files/'
- Download file: curl 'https://example.com/files/docker-compose.yaml'

There is an webdav.postman_collection that illustrates the rest-http calls.

#Reference
https://www.qed42.com/insights/coe/drupal/using-curl-commands-webdav

