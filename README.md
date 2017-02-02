[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/catfriend.svg)](https://hub.docker.com/r/rubygem/catfriend/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/catfriend.svg)](https://hub.docker.com/r/rubygem/catfriend/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/catfriend.svg)](https://hub.docker.com/r/rubygem/catfriend/)
[![Gem Downloads](https://img.shields.io/gem/dt/catfriend.svg)](https://rubygems.org/gems/catfriend/)
# catfriend

Auto-Generated Docker image for catfriend to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/catfriend`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/catfriend`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/catfriend`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/catfriend/)
