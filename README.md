# 3DRouting

## Table of Contents
* [Introduction](#1)
* [Object](#2)
* [Environment](#3)
* [Core Idea](#4)
* [Result Show](#5)

### <h3 id="1">Introduction</h2>
In recent years, with the advancement of biochip technology, MEDA, a biochip with smaller individual electrodes, has been widely used in biochemistry experiments such as DNA detection, protein analysis, PCR detection, etc. MEDA is one-tenth of the size of DMFB compared to traditional biochips such as DMFB. MEDA also allows for diagonal droplet movement, a feature that makes MEDA more flexible in biochemistry experiments and makes traditional DMFB-based routing algorithms unsuitable. It is for this reason that our lab proposes a 3D routing algorithm based on MEDA.

### <h3 id="2">Object</h3>
In some specific biological experiments, multiple droplets of the same type are required to be routed from different starting positions to a specified location for a series of biochemical reactions. Therefore, this project aims to ***minimize the time of multiple droplet routing*** by our design routing algorithm. Also, due to the property that droplet routing of the same type droplet in MEDA can share the same cell at different times, we propose a 3D routing algorithm.

### <h3 id="3">Environment</h3>
We simulate the form of droplet routing on MEDA by constructing a model. The core code was built in C++, and after determining the completion of the first tests, we reworked the source code using Python/
  - C++
  - Python3

### <h3 id="4">Core Idea</h3>

### <h3 id="5">Result Show</h3>
