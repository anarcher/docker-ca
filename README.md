# docker-ca

A simple certificate generator for docker TLS

`https://registry.hub.docker.com/u/anarcher/docker-ca/`

## Usage

`docker run --rm -it -v $PWD/.docker:/root/.docker anarcher/docker-ca example.com`

```
Digest::Digest is deprecated; use Digest
Digest::Digest is deprecated; use Digest
CA certificates are in /root/.docker/ca
Client certificates are in /root/.docker
Server certificates are in /root/.docker/example.com
```

