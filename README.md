# python-worker-wasmer-starter

Python worker template for Wasmer Edge. This is a template project for creating a Python worker that can be deployed to Wasmer Edge.

## Usage

### 1. Install the `wasmer` CLI

```bash
curl https://get.wasmer.io -sSfL | sh
```

### 2. Clone this repository

```bash
git clone https://github.com/wasmer-examples/python-worker-wasmer-starter.git
```

### 3. Add your Python worker

Add your Python worker to the `src/main.py` file.

### 4. Run the Python worker

```bash
wasmer run . --net --env PORT=8080
```

You will get the output from the Python worker. The above command will run the Python worker locally on port 8080.

### 5. Deploy the Python worker

```bash
wasmer deploy
```

> You will need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
