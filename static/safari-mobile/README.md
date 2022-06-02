#Safari 15.0

This folder contains files to build browser image with Webkit 613.1.6.1 (Safari 15.0) using a mobile user agent:

```shell
User-agent: Mozilla/5.0 (iPhone; CPU iPhone OS 15_0_2 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/15.0 Mobile/15E148 Safari/604.1
```

## Building the image

```shell

> cd <safari-mobile-folder-path>
> docker build . -t browsers/safari-mobile:14.0 [--build-arg WEBKIT_VERSION=613.1.6.1]
```