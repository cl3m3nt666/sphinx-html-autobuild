# sphinx-watcher


[![Docker Automated buil](https://img.shields.io/docker/automated/cl3m3nt/sphinx-autobuild.svg?style=flat-square)](https://hub.docker.com/r/cl3m3nt/sphinx-autobuild/)
[![Docker Build Statu](https://img.shields.io/docker/build/cl3m3nt/sphinx-autobuild.svg?style=flat-square)](https://hub.docker.com/r/cl3m3nt/sphinx-autobuild/)
[![Docker Pulls](https://img.shields.io/docker/pulls/cl3m3nt/sphinx-autobuild.svg?style=flat-square)](https://hub.docker.com/r/cl3m3nt/sphinx-autobuild/)
[![](https://images.microbadger.com/badges/image/cl3m3nt/sphinx-autobuild.svg)](https://microbadger.com/images/cl3m3nt/sphinx-autobuild "Get your own image badge on microbadger.com")



Depend on :

[sphinx-alpine](https://github.com/cl3m3nt666/sphinx-alpine)

## Example

Default port : `8000`

Default path for source : `/root/docs/source`

Default path for build : `/root/docs/build`



```
docker run -it -p8000:8000 -v ${PWD}/my-sphinx-docs:/root/docs cl3m3nt/sphinx-autobuild /root/docs/source /root/docs/build
```



```
docker run -it -p8000:8000 -v ${PWD}/my-sphinx-docs:/root/docs cl3m3nt/sphinx-autobuild
```
