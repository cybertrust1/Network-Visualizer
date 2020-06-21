# Network Visualizer

> :warning: Work in progress !

:relaxed:

## Summary

1. [Overview](#overview)

2. [Installation](#installation)

3. [Features](#features)

## Overview

So I needed something to help me during CTF and stuff to visualize nmap scans. I decided to create one ^.^

![Overview of the app](overview.png)

This is a dockerized Flask app which uses [amcharts](https://www.amcharts.com/) (a JavaScript library) to render the graph.

## Installation

### Clone the repo

* With SSH :

    ```bash
    git clone git@github.com:OxNinja/Network-Visualizer.git
    ```

* With HTTPS :

    ```bash
    git clone https://github.com/OxNinja/Network-Visualizer.git
    ```

### Build and launch the docker container

Go to the cloned repo folder : `cd Network-Visualizer`

```bash
docker-compose up --build
```

You should be able to go to `http://172.16.0.2:5000` and see the app.

## Features

- [x] Render a graph from a JSON file
- [x] File upload on the container
- [ ] Auto load the uploaded file to render
- [x] Parsing XML to JSON

See the [project's kanban](https://github.com/OxNinja/Network-Visualizer/projects/1) for more details.

