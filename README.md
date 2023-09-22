# Mind

A modern reactive trading system

## Getting Started

This repository assumes that you have [installed nix](https://determinate.systems/posts/determinate-nix-installer)

```shell
./scripts/bootstrap
```

Start a `nix` dev shell

```shell
nix develop -c $SHELL
```

Create a kubernetes cluster, install helm dependencies and apply manifests

```shell
./scripts/setup
```

## Development

Install python dependencies

```shell
pip install -r requirements.txt
```

## Endpoints

| Service          | URI                                                                           |
| -----------------| ------------------------------------------------------------------------------|
| Dagster          | [dagster.127.0.0.1.nip.io](http://dagster.127.0.0.1.nip.io)                   |
| Grafana          | [grafana.127.0.0.1.nip.io](http://grafana.127.0.0.1.nip.io)                   |
| Redpanda Console | [redpanda-console.127.0.0.1.nip.io](http://redpanda-console.127.0.0.1.nip.io) |

## Authors

- Alex Kwiatkowski - alex+git@fremantle.io

## License

`mind` is released under the [MIT license](./LICENSE)
