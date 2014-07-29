Docker Sentinel Image
=====================
A Docker base image which includes [Sentinel][1].

Building
--------
To do the thing:

    git clone https://github.com/BlueDragonX/docker-sentinel.git
    docker build --rm -t bluedragonx/sentinel docker-sentinel

Configuration
-------------
The Sentinel image is meant to be used as a base image. The image expects
Sentinel's config file to be located at `/etc/sentinel/config.yml`. The
directory already exists. It is the inheriting image's job to place a file
there so that Sentinel runs accordingly.

License
-------
Copyright (c) 2014 Ryan Bourgeois. Licensed under BSD-Modified. See the LICENSE

[1]: https://github.com/BlueDragonX/sentinel "Sentinel"
