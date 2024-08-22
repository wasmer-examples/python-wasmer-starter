This is a simple [Python](https://python.org/) HTTP server.

## Usage

Modify the logic of your simple Python HTTP server in the `src/main.py` file.

You can run the server with Python with:

```bash
$ python src/main.py
```

Or you can also use `wasmer run` to run it locally (check out the [Wasmer install guide](https://docs.wasmer.io/install)):

```bash
$ wasmer run . --env PORT=8080
```

Open [http://localhost:8080](http://localhost:8080) with your browser to see the Python application response.

## Deploy on Wasmer Edge

The easiest way to deploy your Python app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://python-worker-wasmer-starter-worker.wasmer.app/

Run this commmand to deploy to Wasmer Edge:

```bash
wasmer deploy
```
