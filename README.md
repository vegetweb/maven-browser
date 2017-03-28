# maven-browser
Docker image containing maven and webbrowsers for testing.

This image is based on the `maven:3-jdk-8` docker image. It contains these addional features:
  * xfvb on DISPLAY:99
  * iceweasel
  * google chrome
 
The scripts for setting up `xvfb` and `google-chrome` are taken from https://github.com/kfatehi/docker-chrome-xvfb
