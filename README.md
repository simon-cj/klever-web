# Klever Web

English | [中文](./README_zh.md)

Klever Web is the front-end interface of [Klever Model Registry](https://github.com/kleveross/klever-model-registry)

## Getting Started

### Clone Repository

```
$ git clone https://github.com/kleveross/klever-web.git
$ cd klever-web
```

### Install dependencies,

```bash
$ yarn
```

### Start the dev server,

```bash
$ yarn start
```

## Publish

### Build Image

```
$ yarn run build
$ docker build -t lever-dev.cargo.io/release/klever-web:v0.0.3 .
```

### Run Image

```
$ docker run -p 8888:8080 -d lever-dev.cargo.io/release/klever-web:v0.0.3
```

## nodePort

The default application port is 8080, and the external port of the docker startup container is 8888

