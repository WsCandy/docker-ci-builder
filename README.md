# Docker CI Base

This docker image contains the bare minimum required to build projects on CircleCI. This image should be used as a base image for anything done on CircleCI. 

The image is based off of Alpine Linux and is only 11mb in size, keeping your CI builds fast.

If you want to use the Docker client on CircleCI use this [image](https://github.com/WsCandy/ci-docker) instead.

## Usage

In your `.circleci/config.yml` simply add the following:

    docker:
      - image: wscandy/ci-base

Happy building..!