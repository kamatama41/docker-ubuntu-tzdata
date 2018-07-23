# docker-ubuntu-tzdata

Ubuntu 18.04 with tzdata

## Usage

```sh
$ docker run -it --rm kamatama41/ubuntu-tzdata date                                                                                                                                                                                      [docker-ubuntu-tzdata](master)
Mon Jul 23 07:28:30 UTC 2018
```

With specific timezone
```sh
$ docker run -it -e TZ=Asia/Tokyo --rm kamatama41/ubuntu-tzdata date                                                                                                                                                                     [docker-ubuntu-tzdata](master)
Mon Jul 23 16:28:34 JST 2018
```
