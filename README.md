# What is docker-ubuntu-xrdp?
Docker-ubuntu-xrdp is a base image of Ubuntu Yakkety with xrdp installed. It is meant as a base image for docker-based desktop environments, like Mate, running over RDP.

# How to use this image
You generally don't want to run this image on it's own. You would use it as the "FROM" in your Dockerfile.

For example:

```
FROM rigormortiz/ubuntu-xrdp:yakkety

...
```
