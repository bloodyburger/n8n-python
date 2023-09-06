# n8n - docker image with Python 3.11

![n8n.io - Workflow Automation](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-logo.png)

This [image](https://hub.docker.com/r/naskio/n8n-python) includes Python 3.11 by default. It can be used to run python
scripts inside n8n using the [Execute Command](https://docs.n8n.io/nodes/n8n-nodes-base.executeCommand/) node .

> Run python 3.11 code on n8n.

[Docker Hub](https://hub.docker.com/r/bloodyburger/n8n-python)

[GitHub repository](https://www.github.com/bloodyburger/n8n-python)

## Image Setup

Using docker compose
[docker-compose.yml](./docker-compose.yml)

## Usage

### Run mounted Python scripts using the ExecuteCommand node

You can run `*.py`files that has been mounted to the container using
the [ExecuteCommand](https://docs.n8n.io/nodes/n8n-nodes-base.executeCommand/) node.

Create a folder "py_scripts" and place your scripts in there.
On Execute Command node ```python3 /data/py_scripts/script.py```


## Documentation

The official n8n documentation can be found under: [https://docs.n8n.io](https://docs.n8n.io)

Additional information and example workflows on the n8n.io website: [https://n8n.io](https://n8n.io)

Learn [how to run n8n in **Docker**](https://github.com/n8n-io/n8n/tree/master/docker/images/n8n/README.md)
