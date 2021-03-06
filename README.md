# docker-wrapper-py [![Build status](https://ci.frigg.io/badges/frigg/docker-wrapper-py/)](https://ci.frigg.io/frigg/docker-wrapper-py/last/) [![Coverage status](https://ci.frigg.io/badges/coverage/frigg/docker-wrapper-py/)](https://ci.frigg.io/frigg/docker-wrapper-py/last/)

## Install

    pip install docker-wrapper

## Usage

Use it in a with statement:
```python
with Docker() as docker:
    docker.run('command')
```

or as a decorator:
```python
    @Docker.wrap()
    def run_command_in_container(command, docker)
        docker.run(command)
```

Read the documentation on [docker-wrapper-py.readthedocs.org](http://docker-wrapper-py.readthedocs.org)
for more information about how to use this.

--------------

MIT © frigg.io

