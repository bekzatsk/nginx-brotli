# What is this?
This project is based on Alpine Linux, the official nginx image and an nginx module that provides static and dynamic brotli compression. [Brotli](https://github.com/google/brotli) and the [nginx brotli module ](https://github.com/google/ngx_brotli) are built by Google.

# How to use this image
As this project is based on the official [nginx image](https://hub.docker.com/_/nginx/) look for instructions there. In addition to the standard configuration directives, you'll be able to use the brotli module specific ones, see [here for official documentation](https://github.com/google/ngx_brotli#configuration-directives)


https://github.com/google/ngx_brotli/commits/master/
get last commit hash


docker build -t innlabkz/nginx-brotli:latest . --platform linux/x86_64
docker tag innlabkz/nginx-brotli:latest innlabkz/nginx-brotli:latest & docker push innlabkz/nginx-brotli:latest
