This is [Discourse](http://www.discourse.org/) packaged as a docker image.

It is originally based on ``srid/discourse-docker``, but I've stripped out
everytying that is not Discourse itself; no management scripts, no redis
and postgres containers; there is only the Ruby app here.

You are supposed to use an external orchestration tool to hook this up with
Redis and Postres. I am using [docker-deploy](https://github.com/miracle2k/docker-deploy).
