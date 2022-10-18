# 8mile

> You only get one chance...

## Build

> Uses [ko](https://github.com/ko-build/ko) to build the application

```sh
ko build ./cmd/app
```

### Local

```sh
docker run -p 4000:4000 $(ko build ./cmd/app)
```
