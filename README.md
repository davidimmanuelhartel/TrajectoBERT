# Location Bert - Building Bert from scratch with PyTorch

This repository contains code mainly from

[Building BERT with PyTorch from scratch](https://coaxsoft.com/blog/building-bert-with-pytorch-from-scratch)

The goal is build a BERT model for next location prediction of human mobility trajectory data.

## Installation

After you clone the repository and setup virtual environment,
install dependencies

```shell
pip install -r requirements.txt
```

### Installation on Mac M1

You may experience difficulties installing `tensorboard`.
Tensorboard requires `grpcio` that should be installed with extra environment
variables. Read more in [StackOverflow](https://stackoverflow.com/questions/66640705/how-can-i-install-grpcio-on-an-apple-m1-silicon-laptop).

So, your installation line for Mac M1 should look like

```shell
export GRPC_PYTHON_BUILD_SYSTEM_OPENSSL=1
export GRPC_PYTHON_BUILD_SYSTEM_ZLIB=1

pip install -r requirements.txt
```
