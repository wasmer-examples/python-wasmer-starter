This is a simple [Python](https://python.org/) HTTP server.

## Usage

Modify the logic of your simple Python HTTP server in the `src/main.py` file.

You can run the server with Python with:

```bash
$ python src/main.py
```

or you can also use `wasmer run` to run things locally.

```bash
$ wasmer run . --net --env PORT=8080
```

> [!NOTE]
> You will need to have Wasmer installed (check out [the docs to install the Wasmer CLI](https://docs.wasmer.io/install)!). 
> The `--net` flag is required to enable networking support in Wasmer.

You will see the output from the Python application in the console. The above command will run the Python worker locally on port `8080`.

## Deploy on Wasmer Edge

The easiest way to deploy your Python app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: http://python-worker-wasmer-starter-worker.wasmer.app/

Run this commmand to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
