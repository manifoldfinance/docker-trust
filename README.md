# docker trust signer

> Docker Signing

## Usage

```bash
docker trust key generate NAME
```

```bash
docker trust sign IMAGE:TAG
```

```bash
docker trust inspect --pretty example/trust-demo
```


> docker trust signer: Manage entities who can sign Docker images

| Command | Description |
| --- | --- |
| [docker trust inspect](https://docs.docker.com/engine/reference/commandline/trust_inspect/) | Return low-level information about keys and signatures |
| [docker trust key](https://docs.docker.com/engine/reference/commandline/trust_key/) | Manage keys for signing Docker images |
| [docker trust revoke](https://docs.docker.com/engine/reference/commandline/trust_revoke/) | Remove trust for an image |
| [docker trust sign](https://docs.docker.com/engine/reference/commandline/trust_sign/) | Sign an image |
| [docker trust signer](https://docs.docker.com/engine/reference/commandline/trust_signer/) | Manage entities who can sign Docker images |
