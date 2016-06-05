[![Build Status](https://travis-ci.org/mesoscloud/ubuntu.svg?branch=master)](https://travis-ci.org/mesoscloud/ubuntu) [![Docker Stars](https://img.shields.io/docker/stars/mesoscloud/ubuntu.svg)](https://hub.docker.com/r/mesoscloud/ubuntu/) [![Docker Pulls](https://img.shields.io/docker/pulls/mesoscloud/ubuntu.svg)](https://hub.docker.com/r/mesoscloud/ubuntu/)

# ubuntu

[![Join the chat at https://gitter.im/mesoscloud/mesoscloud](https://badges.gitter.im/mesoscloud/mesoscloud.svg)](https://gitter.im/mesoscloud/mesoscloud?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Ubuntu

http://www.ubuntu.com/

### What is the purpose of this repository?

To create a set of images that are ready to be consumed by mesoscloud.

**Here's an example**

Ubuntu 16.04:

```text
MAJOR=16.04
```

GitHub release:

```text
GITHUB_RELEASE=20160605
```

The following images are produced when the GitHub release is created:

```text
mesoscloud/ubuntu:$MAJOR-$GITHUB_RELEASE  # This image is created
mesoscloud/ubuntu:$MAJOR                  # This image is updated
```
