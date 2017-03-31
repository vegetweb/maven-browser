# maven-browser
Docker image containing maven and webbrowsers for testing.

This image is based on the `ubuntu:i16.10` docker image. It contains these addional features:
  * xfvb on DISPLAY:99
  * firefox 52
  * google chrome 57
  * openjdk 8
  * maven
 
The scripts for setting up `xvfb` and `google-chrome` are taken from https://github.com/kfatehi/docker-chrome-xvfb
