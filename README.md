dock0/fidelius
=======

[![Automated Build](http://img.shields.io/badge/automated-build-green.svg)](https://registry.hub.docker.com/u/dock0/fidelius/)
[![MIT Licensed](http://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)

Container to run [committed](https://github.com/akerl/fidelius), a web app that checks for password security.

## Usage

```
docker pull dock0/fidelius
docker run -d -p 80:80 -e "REDIS_URL=redis://user:password@host:port/db" dock0/fidelius
```

Make sure that REDIS_URL is accessible for the container

I'd recommend using [dock0/redis](https://github.com/dock0/redis), but I'll admit to being a bit biased.

## License

This repo is released under the MIT License. See the bundled LICENSE file for details.

