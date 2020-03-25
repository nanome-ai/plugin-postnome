# Nanome - Postgnome

A web request plugin for Nanome

### Preparation

Install the latest version of [Python 3](https://www.python.org/downloads/)

| NOTE for Windows: replace `python3` in the following commands with `python` |
| --------------------------------------------------------------------------- |


Install the latest `nanome` lib:

```sh
$ python3 -m pip install nanome --upgrade
```

### Dependencies

**TODO**: Provide instructions on how to install and link any external dependencies for this plugin.

**TODO**: Update docker/Dockerfile to install any necessary dependencies.

### Installation

To install Postgnome:

```sh
$ python3 -m pip install nanome-postgnome
```

### Usage

To start Postgnome:

```sh
$ nanome-postgnome -a <plugin_server_address> [optional args]
```

#### Optional arguments:

- `-x arg`

  Example argument documentation

**TODO**: Add any optional argument documentation here, or remove section entirely.

### Docker Usage

To run Postgnome in a Docker container:

```sh
$ cd docker
$ ./build.sh
$ ./deploy.sh -a <plugin_server_address> [optional args]
```

### Development

To run Postgnome with autoreload:

```sh
$ python3 run.py -r -a <plugin_server_address> [optional args]
```

### License

MIT
