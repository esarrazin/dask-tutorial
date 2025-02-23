# Dask Tutorial

**This is a forked from https://github.com/dask/dask-tutorial**

Dask is a parallel and distributed computing library that scales the existing Python and PyData ecosystem. Dask can scale up to your full laptop capacity and out to a cloud cluster.

## Prepare

#### 1. You should clone this repository

    git clone http://github.com/esarrazin/dask-tutorial

and then install necessary packages.
There are three different ways to achieve this, pick the one that best suits you, and ***only pick one option***.
They are, in order of preference:

#### 2. Install via pixi

Install [pixi](https://pixi.sh/latest/)

In the main repo directory

    pixi install 
    pixi shell

### Launch Jupyter

From the repo directory

    jupyter lab

You are welcome to use Jupyter notebook if you prefer, but we'll be using lab in the live tutorial.

## Links

*  Reference
    *  [Docs](https://dask.org/)
    *  [Examples](https://examples.dask.org/)
    *  [Code](https://github.com/dask/dask/)
    *  [Blog](https://blog.dask.org/)
*  Ask for help
    *   [`dask`](http://stackoverflow.com/questions/tagged/dask) tag on Stack Overflow, for usage questions
    *   [github issues](https://github.com/dask/dask/issues/new) for bug reports and feature requests
    *   [discourse forum](https://dask.discourse.group/) for general, non-bug, questions and discussion
    *   Attend a live tutorial

## Outline

0. [Overview](00_overview.ipynb) - dask's place in the universe.

1. [Dataframe](01_dataframe.ipynb) - parallelized operations on many pandas dataframes spread across your cluster.

2. [Array](02_array.ipynb) - blocked numpy-like functionality with a collection of numpy arrays spread across your cluster.

3. [Delayed](03_dask.delayed.ipynb) - the single-function way to parallelize general python code.

4. [Deployment/Distributed](04_distributed.ipynb) - Dask's scheduler for clusters, with details of how to view the UI.

5. [Distributed Futures](05_futures.ipynb) - non-blocking results that compute asynchronously.

6. [Machine learning](06_machine_learning.ipynb) - use dask for machine learning.
