# Alpine Linux Docker Images

[Alpine](https://www.alpinelinux.org/) linux docker images with some utils.

## Tags

- `3.12-util`
- `3.10-util`
- `3.8-util-2`
- `3.7-util`
- `3.6-util-1`
- `3.5-util-2`

## Usage

run as ssh server:

```bash
docker run -d -p 22:22 helphi/alpine:3.12-util
ssh root@127.0.0.1
#enter password root
```

run git command:

```bash
docker run helphi/alpine:3.12-util git clone https://github.com/helphi/Dockerfile-alpine.git
```

run as ...
