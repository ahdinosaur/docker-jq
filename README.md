# docker-jq

an alpine docker image with `jq`

## how to

### install

install `docker`, then

```shell
git clone https://github.com/ahdinosaur/docker-jq
```

### build

```shell
docker build -t ahdinosaur/jq .
```

### run

```shell
cat package.json | docker run -i ahdinosaur/jq '.version'
```

### publish

```shell
docker push ahdinosaur/jq
```
